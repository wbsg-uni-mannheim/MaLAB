# Quellen- und Webrecherche-Audit

**Fall:** `de/strafrecht/materielles-strafrecht/fortgeschrittenenklausur-geldabheben-mit-hindernissen`

## Zählung

- Suchanfragen: **36**
- Als verwendet belegte URLs: **10**
- Explizit als Open/Fetch protokollierte URLs: **1**
- In der Lösung zitierte URLs: **0**
- Eindeutige verwendete Quellen-URLs: **10**
- Eindeutige verwendete Domains: **3**
- Alle im Audit beobachteten URLs: **11**
- Verstöße gegen die Domain-Sperre: **0**
- Verstöße gegen den Webzugriffsmodus: **0**
- Informativ markierte Suchanfragen: **40**

## Domain-Sperre

- Gesperrte Domains: `dskrpt.de`, `forum-iuridicum.com`, `moodle.ruhr-uni-bochum.de`, `openrewi.org`, `pure.mpg.de`, `wikibooks.org`, `zjs-online.com`
- Status: **bestanden**
- Webzugriffsmodus: erlaubt
- Webzugriffs-Audit: **bestanden**
- Such-Leakage-Audit: **nur Hinweis; keine Verwerfung**

## Quellen

| Quelle | Domain | verwendet | Open/Fetch protokolliert | in Lösung zitiert | Zweck/Nachweis |
|---|---|:---:|:---:|:---:|---|
| [Link](https://juris.bundesgerichtshof.de/cgi-bin/rechtsprechung/document.py?Art=en&Blank=1.pdf&Datum=2018-10&Gericht=bgh&anz=276&nr=92916&pos=1) | `juris.bundesgerichtshof.de` | ja | nein | nein | Ausschluss der Ersatzhehlerei und Schutzzweck des § 259 StGB |
| [Link](https://juris.bundesgerichtshof.de/cgi-bin/rechtsprechung/document.py?Art=en&Blank=1.pdf&Datum=2019-3-21&Gericht=bgh&anz=24&nr=98461&pos=2) | `juris.bundesgerichtshof.de` | ja | nein | nein | Gewahrsam der Bank und personelle Beschränkung des Einverständnisses bei der Geldautomatenausgabe |
| [Link](https://juris.bundesgerichtshof.de/cgi-bin/rechtsprechung/document.py?Art=en&Blank=1.pdf&Datum=2021-3-3&Gericht=bgh&anz=24&client=12&nr=117052&pos=8) | `juris.bundesgerichtshof.de` | ja | nein | nein | Gewahrsam des legitimierten Bankkunden bei Ablenkungsfällen am Geldautomaten |
| [Link](https://juris.bundesgerichtshof.de/cgi-bin/rechtsprechung/document.py?Art=en&Blank=1.pdf&Datum=2024-11-12&Gericht=bgh&anz=37&nr=140047&pos=9) | `juris.bundesgerichtshof.de` | ja | nein | nein | Aktuelle Bestätigung der Diebstahlslösung bei Geldentnahme nach Karten- und PIN-Eingabe des Berechtigten |
| [Link](https://juris.bundesgerichtshof.de/cgi-bin/rechtsprechung/document.py?Art=en&Blank=1.pdf&Datum=Aktuell&Gericht=bgh&Sort=12288&anz=750&nr=131578&pos=8) | `juris.bundesgerichtshof.de` | ja | nein | nein | Funktionsbeeinträchtigung als Sachbeschädigung bei unmittelbarer Einwirkung |
| [Link](https://recht.nulegal.eu/rechtsprechung/bgh/2013-10-22/3-str-69-13) | `recht.nulegal.eu` | ja | nein | nein | Erfordernis eines Absatzerfolgs bei Absetzen und Absatzhilfe |
| [Link](https://recht.nulegal.eu/rechtsprechung/olg-koeln/2020-05-18/2-ws-161-20) | `recht.nulegal.eu` | ja | nein | nein | Versuchsbeginn beim Cash Trapping |
| [Link](https://www.gesetze-im-internet.de/bgb/__929.html) | `www.gesetze-im-internet.de` | nein | ja | nein | web_search open |
| [Link](https://www.gesetze-im-internet.de/bgb/__932.html) | `www.gesetze-im-internet.de` | ja | nein | nein | Eigentumserwerb des gutgläubigen Restaurantinhabers |
| [Link](https://www.gesetze-im-internet.de/bgb/__935.html) | `www.gesetze-im-internet.de` | ja | nein | nein | Geld-Ausnahme nach § 935 Abs. 2 BGB |
| [Link](https://www.gesetze-im-internet.de/stgb/BJNR001270871.html?level=1) | `www.gesetze-im-internet.de` | ja | nein | nein | Verifikation der einschlägigen Strafnormen und Strafantragserfordernisse |

### Informative Such-Leakage-Flags

Diese Treffer sind Review-Hinweise. Sie kontaminieren oder verwerfen den Fall nicht.

- `task-identifier` (`zjs`): "4 StR 338/20" "263a" -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): "Bankkarte" "PIN" "Prospekt" "Computerbetrug" Geldautomat -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `quoted-task-fragment` (`Prospekt`): "Bankkarte" "PIN" "Prospekt" "Computerbetrug" Geldautomat -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): "Cash Trapping" "Sachbeschädigung" Geldautomat -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): "Cash Trapping" "unmittelbar ansetzt" Diebstahl Versuch -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): "Cash-Trapping" Versuchsbeginn § 22 Diebstahl Geldautomat -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): "Dann gönne ich mir" Seezunge Frascati StGB -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `quoted-task-fragment` (`Dann gönne ich mir`): "Dann gönne ich mir" Seezunge Frascati StGB -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): "Eingabe der Höhe" "Computerbetrug" Geldautomat Ablenkung Prospekt -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): "Geldbetrag eingeben" "Computerbetrug" Geldautomat Ablenkung Kunde -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): "Prospekt" "Auszahlungsbetrag" "§ 263a" Geldautomat -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `quoted-task-fragment` (`Prospekt`): "Prospekt" "Auszahlungsbetrag" "§ 263a" Geldautomat -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `quoted-task-fragment` (`Auszahlungsbetrag`): "Prospekt" "Auszahlungsbetrag" "§ 263a" Geldautomat -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): "Seezunge" "Frascati" Hehlerei -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `quoted-task-fragment` (`Seezunge`): "Seezunge" "Frascati" Hehlerei -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `quoted-task-fragment` (`Frascati`): "Seezunge" "Frascati" Hehlerei -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): 3 StR 333/18 Computerbetrug § 263a Eingabe Auszahlungsbetrag -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): BGH 12 November 2024 Geldautomat Berechtigter Bankkarte PIN Gewahrsam Aktenzeichen -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): BGH 3 StR 333/18 21. März 2019 Geldautomat Prospekt Ablenkung Volltext -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): BGH Absatzhilfe Bezahlung mit gestohlenem Geld § 259 -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): BGH Begünstigung § 257 Tatvorteil Ersatzgegenstand Wechselgeld Beute verwerten -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): BGH Sachbeschädigung Funktionsbeeinträchtigung körperliche Einwirkung vorübergehend § 303 -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): Geldautomat Opfer Karte PIN Täter Auszahlungsbetrag eingibt § 263a -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): Hehlerei Absatzhilfe gestohlenes Geld bezahlen Essen Restaurant -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): OLG Cash Trapping Sachbeschädigung Geldautomat § 303 Metallleiste -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): gestohlener Geldschein Restaurant Wechselgeld Absatzhilfe Hehlerei § 259 -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:bundesgerichtshof.de "Absetzen hilft" "Vortäter" § 259 Absatzhilfe selbständig unselbständig -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:bundesgerichtshof.de "Cash Trapping" -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:bundesgerichtshof.de Cash Trapping Geldautomat Versuch Diebstahl Blende Klebeband -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:bundesgerichtshof.de Geldautomat abgelenkt PIN Auszahlungsbetrag eingegeben Diebstahl Computerbetrug -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:bundesgerichtshof.de Hehlerei Ersatzsache Wechselgeld § 259 BGH -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:bundesgerichtshof.de Wechselgeld Hehlerei Ersatzhehlerei Geld -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:bundesgerichtshof.de § 257 Begünstigung Beute verbrauchen Vorteil sichern eigenes Interesse Absicht -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:bundesgerichtshof.de § 259 Absatzhilfe Vortäter wirtschaftliche Verwertung Sache Erfolg -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:bundesgerichtshof.de § 303 Funktionsfähigkeit nicht unerhebliche Beeinträchtigung Sache -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:gesetze-im-internet.de StGB § 242 § 263a § 259 § 257 § 303a -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:gesetze-im-internet.de/stgb __257 __259 __242 __263a -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): site:rechtsprechung-im-internet.de Cash Trapping Diebstahl -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): § 257 Beute ausgeben Restaurant Begünstigung Vortäter Vorteil sichern -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- `task-identifier` (`zjs`): § 259 Wechselgeld gestohlener Geldschein Hehlerei Ersatzhehlerei BGH -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com

## Suchanfragen

- "4 StR 338/20" "263a" -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- "Bankkarte" "PIN" "Prospekt" "Computerbetrug" Geldautomat -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- "Cash Trapping" "Sachbeschädigung" Geldautomat -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- "Cash Trapping" "unmittelbar ansetzt" Diebstahl Versuch -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- "Cash-Trapping" Versuchsbeginn § 22 Diebstahl Geldautomat -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- "Dann gönne ich mir" Seezunge Frascati StGB -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- "Eingabe der Höhe" "Computerbetrug" Geldautomat Ablenkung Prospekt -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- "Geldbetrag eingeben" "Computerbetrug" Geldautomat Ablenkung Kunde -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- "Prospekt" "Auszahlungsbetrag" "§ 263a" Geldautomat -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- "Seezunge" "Frascati" Hehlerei -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- '§ 303 Sachbeschädigung'
- 3 StR 333/18 Computerbetrug § 263a Eingabe Auszahlungsbetrag -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- BGH 12 November 2024 Geldautomat Berechtigter Bankkarte PIN Gewahrsam Aktenzeichen -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- BGH 3 StR 333/18 21. März 2019 Geldautomat Prospekt Ablenkung Volltext -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- BGH Absatzhilfe Bezahlung mit gestohlenem Geld § 259 -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- BGH Begünstigung § 257 Tatvorteil Ersatzgegenstand Wechselgeld Beute verwerten -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- BGH Sachbeschädigung Funktionsbeeinträchtigung körperliche Einwirkung vorübergehend § 303 -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- Geldautomat Opfer Karte PIN Täter Auszahlungsbetrag eingibt § 263a -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- Hehlerei Absatzhilfe gestohlenes Geld bezahlen Essen Restaurant -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- OLG Cash Trapping Sachbeschädigung Geldautomat § 303 Metallleiste -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- gestohlener Geldschein Restaurant Wechselgeld Absatzhilfe Hehlerei § 259 -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- https://www.gesetze-im-internet.de/bgb/__929.html
- site:bundesgerichtshof.de "Absetzen hilft" "Vortäter" § 259 Absatzhilfe selbständig unselbständig -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- site:bundesgerichtshof.de "Cash Trapping" -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- site:bundesgerichtshof.de Cash Trapping Geldautomat Versuch Diebstahl Blende Klebeband -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- site:bundesgerichtshof.de Geldautomat abgelenkt PIN Auszahlungsbetrag eingegeben Diebstahl Computerbetrug -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- site:bundesgerichtshof.de Hehlerei Ersatzsache Wechselgeld § 259 BGH -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- site:bundesgerichtshof.de Wechselgeld Hehlerei Ersatzhehlerei Geld -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- site:bundesgerichtshof.de § 257 Begünstigung Beute verbrauchen Vorteil sichern eigenes Interesse Absicht -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- site:bundesgerichtshof.de § 259 Absatzhilfe Vortäter wirtschaftliche Verwertung Sache Erfolg -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- site:bundesgerichtshof.de § 303 Funktionsfähigkeit nicht unerhebliche Beeinträchtigung Sache -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- site:gesetze-im-internet.de StGB § 242 § 263a § 259 § 257 § 303a -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- site:gesetze-im-internet.de/stgb __257 __259 __242 __263a -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- site:rechtsprechung-im-internet.de Cash Trapping Diebstahl -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- § 257 Beute ausgeben Restaurant Begünstigung Vortäter Vorteil sichern -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com
- § 259 Wechselgeld gestohlener Geldschein Hehlerei Ersatzhehlerei BGH -site:dskrpt.de -site:forum-iuridicum.com -site:moodle.ruhr-uni-bochum.de -site:openrewi.org -site:pure.mpg.de -site:wikibooks.org -site:zjs-online.com

## Methodische Grenze

Used means the URL appears in the selected deliverable or in Codex's required .codex-used-sources.json sidecar. Open/Fetch means Codex additionally recorded an explicit page-open action or HTTP fetch command. Search-result URLs are not invented from snippets and are not counted unless one of those records exists.
