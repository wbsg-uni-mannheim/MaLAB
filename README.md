# MaLAB: Mannheim Legal Agent Benchmark

Website: https://wbsg-uni-mannheim.github.io/MaLAB/

MaLAB evaluates how LLM agents solve German legal cases. Each case has its own
pass/fail criteria for the individual legal requirements, derived from reference solutions. 
A committee of LLM judges applies these criteria (rubrics) without seeing the reference solution.

This repository contains the public part of MaLAB: 45 cases of the German First 
State Examination in Law (Erstes Juristisches Staatsexamen) together with their rubrics, 
the answers of ten LLMs and LLM-based agents, the scores given to these answers by LLM judges, the pipeline code, and the project website. 
MaLAB also uses a private test set consisting of 45 German Second State Examination (Zweites Juristisches Staatsexamen) cases which is not part of this repository.

## Layout

```text
tasks/de/<area>/<field>/<case>/   45 cases: task.json, documents/, evals/ (reference solution, rubric)
studies/de-core-45/               taskset, revisions and the judge validation (JUDGE_VALIDATION.md)
results/first-exam/<system>/      answers and scores of ten systems on all 45 cases
website/                          project website (static HTML)
scripts/, evaluation/, prompts/   rubric generation, solver harnesses, judging
configs/                          judge committee configurations
tests/                            unit tests
```

## Results

`results/first-exam/` has one folder per system:

| Folder | Harness | Model |
|---|---|---|
| `single-call-gpt-5.6-sol` | Single call | gpt-5.6-sol |
| `single-call-gpt-5.6-terra` | Single call | gpt-5.6-terra |
| `single-call-deepseek-v4-pro` | Single call | deepseek-v4-pro |
| `opencode-gpt-5.6-sol` | OpenCode | gpt-5.6-sol |
| `opencode-gpt-5.6-terra` | OpenCode | gpt-5.6-terra |
| `opencode-deepseek-v4-pro` | OpenCode | deepseek-v4-pro |
| `codex-cli-gpt-5.6-sol` | Codex CLI | gpt-5.6-sol |
| `codex-cli-gpt-5.6-sol-web` | Codex CLI | gpt-5.6-sol with web search |
| `codex-cli-gpt-6-astra` | Codex CLI | GPT-6 Astra |
| `claude-code-opus-5.5` | Claude Code | Claude Opus 5.5 |

Each case folder contains the submitted answer (`submission/`), the prompt the
system received (`prompt.md`), run metadata (`metadata.json`) and the
per-criterion verdicts of the frozen judge (`scores-v4-frozen.json`). Web runs
also contain the sources the agent opened (`sources.json`, `sources.md`).
`results/first-exam/scores.csv` lists the content and style score of every
system on every case. `SOURCE.json` in each system folder records the run in
the LAB-EU working repository the answers come from. For
`opencode-deepseek-v4-pro`, one run produced no answer, so this system has 44
cases.

## Judging an answer

```bash
python -m venv env && env/bin/pip install -r requirements.txt
env/bin/python -m evaluation.run <task-dir> <answer-file> \
  --judge-committee configs/judge-committee-luna6-deepseek41-gemini38-tiebreaker.json \
  --committee-tiebreaker --style-evaluation --judge-prompt-version v4
```

The command needs API keys for the judge models (OpenAI, DeepSeek and Google).
See [scripts/README.md](scripts/README.md) for the solver harnesses and
[docs/rubric-generation.md](docs/rubric-generation.md) for rubric generation.

## Sources and licences

43 cases originate from the Zeitschrift für das Juristische Studium (ZJS) via the
[BenGER](https://github.com/SebastianNagl/benger-platform) dataset
(CC BY 4.0), two originate from the [OpenRewi](https://openrewi.org/) casebook on administrative law
(CC BY-SA 4.0). Source, authors and licence of each case are recorded in its
`task.json`. The ZJS source map and citation are in `tasks/de/provenance/zjs/`. 
We thank the BenGER and the OpenRewi projects a lot for providing the cases and solution under open licenses!

## Authors

Aaron Steiner, Benedikt Asal, Nico Halkenhäuser, Ralf Müller-Terpitz,
Friedemann Kainer, Svenja Behrendt, Christian Bizer.
University of Mannheim.
