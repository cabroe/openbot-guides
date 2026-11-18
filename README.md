# OpenBot Guides und Docs (Deutsch)

Deutschsprachige Sammlung zu [OpenBot](https://openbot.run). Alle Seiten sind eigenständige HTML-Dateien, lassen sich direkt im Browser öffnen und verlinken untereinander.

Die Sammlung ist in zwei Arten geteilt:

- **Guides** (`guides/`) sind Anleitungen: Sie erklären, *wie* du etwas einrichtest oder machst, Schritt für Schritt und mit Empfehlungen.
- **Docs** (`docs/`) sind zum Nachschlagen: Sie beschreiben, *was es gibt* und wie es funktioniert, also Technik, Oberfläche, Team-Funktionen, Kataloge und Versionen.

## Guides

| Datei | Inhalt |
| --- | --- |
| [OpenBot_Komplett_Setup_mehrere_Firmen.html](guides/OpenBot_Komplett_Setup_mehrere_Firmen.html) | Eigener Gesamt-Guide: Agenten, AGENTS.md, Ordner, Kanäle, Bibliothek, Gedächtnis, Skills, Apps, Routinen, Workflows, Projekte, mehrere Firmen, Sicherheit |
| [OpenBot_Firmen_und_Projekte.html](guides/OpenBot_Firmen_und_Projekte.html) | Mehrere Firmen und Team-Projekte mit eigenen Agents pro Firma |
| [OpenBot_Guides_14_offizielle_Guides_DE.html](guides/OpenBot_Guides_14_offizielle_Guides_DE.html) | Die 14 offiziellen Guides von openbot.run, ins Deutsche übersetzt |

## Docs

| Datei | Inhalt |
| --- | --- |
| [OpenBot_Dokumentation.html](docs/OpenBot_Dokumentation.html) | Technische Dokumentation: Installation, Konfiguration, Architektur, Daten, Entwicklung |
| [OpenBot_Teams.html](docs/OpenBot_Teams.html) | OpenBot für Teams: Setup-Optionen, Team-Features, Rollen und Rechte |
| [OpenBot_Bots.html](docs/OpenBot_Bots.html) | Bots im Chat: Unterschied zu Agents, das + Menü und seine fünf Optionen |
| [OpenBot_Apps.html](docs/OpenBot_Apps.html) | App-Katalog im Marketplace: Kategorien, wichtige Apps, Zapier und Composio |
| [OpenBot_Changelog.html](docs/OpenBot_Changelog.html) | Release-Übersicht 0.50.0 bis 0.72.0 (Okt.–Nov. 2026) |

## Design

Alle Seiten folgen dem Design von [Firmen & Projekte](guides/OpenBot_Firmen_und_Projekte.html): gleiches Layout, gleiche Schriften, gleiche Bausteine (Kopfleiste mit Inhaltsverzeichnis, Teil-Trenner, Hinweis-Boxen, Tabellen, Schritte, Karten), Hell- und Dunkelmodus. Jede Seite hat nur eine eigene Akzentfarbe. Oben links steht „OpenBot Guide“ oder „OpenBot Docs“; ein Klick darauf springt zum Seitenanfang.

## Mehrere Firmen: zwei Ansätze

Die Guides empfehlen für die Arbeit mit mehreren Firmen zwei unterschiedliche Modelle:

| | Gemeinsames Kernteam | Eigene Agents pro Firma |
| --- | --- | --- |
| Guide | [Komplett-Setup](guides/OpenBot_Komplett_Setup_mehrere_Firmen.html#firmen) | [Firmen & Projekte](guides/OpenBot_Firmen_und_Projekte.html) |
| Agents | Ein Kernteam arbeitet für alle Firmen | Jede Firma hat eigene Agents, nie firmenübergreifend geteilt |
| Trennung des Wissens | Eigener Seitenleisten-Ordner und eigene Kanäle pro Firma; Wissen bleibt über Kanal-Erinnerungen getrennt | Eigene Agents, Ordner und Routinen pro Firma |
| Vorteil | Weniger Agents, weniger Pflegeaufwand | Strengste Trennung, kein Kontext kann zwischen Firmen wandern |
| Risiko | Trennung hängt an sauber geführten Kanälen und Erinnerungen | Mehr Agents, mehr Einrichtung und Pflege |

Der Komplett-Setup-Guide beschreibt das eigene Setup und ist damit der Standard. Das Modell aus „Firmen & Projekte“ passt, wenn eine Firma strikte Datentrennung verlangt, etwa bei vertraulichen Kundendaten. Der Abschnitt [Mehrere Firmen](guides/OpenBot_Komplett_Setup_mehrere_Firmen.html#firmen) im Komplett-Setup zeigt, wo die Trennung beim Kernteam endet.

Stand: November 2026.
