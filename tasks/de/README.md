# Deutsche Fälle

Die 45 Fälle des Ersten Staatsexamens sind nach Rechtsgebieten geordnet,
15 je Gebiet:

```text
tasks/de/
├── oeffentliches-recht/
│   ├── europarecht/
│   ├── staatshaftungsrecht/
│   ├── staatsrecht/
│   └── verwaltungsrecht/
├── strafrecht/
│   └── materielles-strafrecht/
├── zivilrecht/
│   ├── handels-und-gesellschaftsrecht/
│   ├── sachenrecht/
│   └── schuldrecht/
└── provenance/
    └── zjs/
```

Jeder Fall enthält `task.json` (Aufgabe, Abgabedatei, Quelle und Lizenz),
`documents/` (Sachverhalt) und `evals/` (Musterlösung und Rubrik).

- Lizenz- und Quellenangaben stehen im jeweiligen `task.json`.
- Der Importnachweis der ZJS-Fälle liegt in
  [`provenance/zjs/source-map.json`](provenance/zjs/source-map.json), die
  Zitationsdatei in [`provenance/zjs/CITATION.cff`](provenance/zjs/CITATION.cff).
