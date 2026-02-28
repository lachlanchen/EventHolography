[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)



# EventHolography

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](../LICENSE)
![Status](https://img.shields.io/badge/Status-Documentation--First-orange)
![Repository](https://img.shields.io/badge/Repository-Early--Stage-lightgrey)
![i18n](https://img.shields.io/badge/i18n-Directory%20Present-success)

Das Repository für Projektmaterialien zu **Event-assisted Holographic Imaging**.

> Beibehaltene ursprüngliche Projektbeschreibung (kanonische Basis):
> `The repo for the paper Event-assited Holographic Imaging`

## Überblick 🔍

`EventHolography` ist derzeit ein dokumentationsorientiertes Repository rund um das Paper-/Projektthema **Event-assisted Holographic Imaging**.

Zum Zeitpunkt der Erstellung enthält das Repository hauptsächlich:

- Ein minimales README im Root-Verzeichnis (hier zur besseren Verständlichkeit erweitert)
- Eine Apache-2.0-Lizenz
- Eine projektweite `.gitignore`
- Ein Verzeichnis `i18n/` für mehrsprachige README-Varianten

Aktuell sind kein Quellcode, kein Abhängigkeits-Manifest und keine ausführbare Pipeline eingecheckt.

## Funktionen ✨

- Klare Projektidentität und -abgrenzung für Forschung zu Event-assisted holographischer Bildgebung
- Apache-2.0-Lizenz für offene Nutzung und Beiträge
- Mehrsprachig vorbereitete Dokumentationsstruktur über `i18n/`
- Erweiterte README-Struktur für künftiges Onboarding von Code und Daten

## Projektstruktur 🗂️

```text
EventHolography/
├── README.md
├── LICENSE
├── .gitignore
└── i18n/
```

| Pfad | Zweck | Aktueller Stand |
|---|---|---|
| `README.md` | Hauptdokumentation des Projekts | Vorhanden und aktiv gepflegt |
| `LICENSE` | Rechtliche Bedingungen | Apache License 2.0 |
| `.gitignore` | Ignore-Regeln für lokale/Build-Artefakte | Vorhanden |
| `i18n/` | Sprachspezifische README-Dateien | Verzeichnis existiert; Dateien können mit der Zeit ergänzt werden |

Hinweise:

- `i18n/` existiert und ist für sprachspezifische README-Dateien vorgesehen.
- `.auto-readme-work/` existiert als pipeline-generierter Arbeitskontext und gehört derzeit nicht zur öffentlichen Projektoberfläche.

## Voraussetzungen ✅

Der aktuelle Zustand des Repositories erfordert nur grundlegende Werkzeuge:

- `git` (zum Klonen und Nachverfolgen von Änderungen)
- Einen Markdown-Viewer (GitHub UI oder lokaler Editor)

Optional (zukunftsgerichtete Annahme basierend auf `.gitignore`-Mustern):

- Python-Tooling könnte später hinzukommen, derzeit sind jedoch keine Python-Laufzeit/Abhängigkeiten durch eingecheckte Projektdateien erforderlich.

## Installation 🛠️

Repository klonen:

```bash
git clone <your-repo-url> EventHolography
cd EventHolography
```

Wenn du das Repository bereits lokal hast, stelle vor dem Bearbeiten der Dokumentation oder dem Hinzufügen von Projektartefakten sicher, dass du auf deinem Ziel-Branch bist.

## Nutzung ▶️

Es gibt noch keinen ausführbaren Einstiegspunkt. Die aktuelle Nutzung ist dokumentationsorientiert:

```bash
# Inspect repository contents
ls -la

# Read project overview
cat README.md
```

Sobald Code, Datensätze oder Notebooks hinzugefügt werden, sollte dieser Abschnitt um exakte Ausführungsbefehle erweitert werden.

## Konfiguration ⚙️

Derzeit ist keine Laufzeitkonfiguration definiert.

Geplante zukünftige Konfigurationsbeispiele (werden hinzugefügt, sobald eine Implementierung existiert):

- Datenpfade
- Modell-/Checkpoint-Pfade
- Kamera-/Event-Sensor-Parameter
- Rekonstruktions-/Holographie-Experiment-Einstellungen

## Beispiele 📌

Aktuelle praktische Beispiele sind Aufgaben zur Repository-Inspektion:

```bash
# Confirm license
head -n 5 LICENSE

# Check language folder status
ls -la i18n
```

Falls du Trainings-/Inference-/Demo-Beispiele erwartet hast: Diese sind in dieser Repository-Momentaufnahme noch nicht verfügbar.

## Entwicklungshinweise 🧪

- Dies ist ein Repository-Gerüst in einer frühen Phase.
- Neue technische Aussagen sollten an eingecheckte Dateien gebunden sein (Code, Konfigurationen, Skripte, Datensätze, Notebooks oder Paper-Artefakte).
- Bevorzuge inkrementelle Aktualisierungen dieses READMEs statt kompletter Ersetzungen von Abschnitten, damit historischer Kontext erhalten bleibt.

## Fehlerbehebung 🩺

### „Es gibt noch nichts auszuführen“

Das ist im aktuellen Zustand erwartbar. Es wurde noch kein ausführbarer Workflow eingecheckt.

### „Ich habe übersetzte READMEs erwartet“

`i18n/` existiert, enthält aber möglicherweise noch keine Sprachdateien. Füge dort sprachspezifische README-Dateien hinzu, sobald sie erstellt wurden.

### „Der Projekttitel ist unterschiedlich geschrieben“

Die ursprüngliche Beschreibung enthält `Event-assited` (wörtlich beibehalten). Die bevorzugte Schreibweise in neuem Text ist `Event-assisted`.

## Roadmap 🗺️

Geplantes Wachstum von Dokumentation und Repository:

- Hinzufügen von Zitiermetadaten zum Paper (BibTeX und Publikationslink, sobald verfügbar)
- Hinzufügen von Implementierungscode und reproduzierbaren Experimentanleitungen
- Hinzufügen von Datensatz-/Preprocessing-Dokumentation
- Hinzufügen mehrsprachiger README-Dateien unter `i18n/`
- Hinzufügen von Issue-/PR-Templates und Details zum Contribution-Workflow

## Mitwirken 🤝

Beiträge sind willkommen.

Bis dedizierte Contribution-Templates hinzugefügt sind, nutze den Standard-GitHub-Workflow:

1. Forke das Repository
2. Erstelle einen Feature-/Dokumentations-Branch
3. Committe fokussierte Änderungen mit klaren Nachrichten
4. Öffne einen Pull Request, der Motivation, Änderungen und Validierung beschreibt

Wenn du neue technische Anleitungen einführst, füge nach Möglichkeit ausführbare Befehle und erwartete Ausgaben hinzu.

## Zitation 📚

In diesem Repository sind derzeit keine Zitierdetails hinterlegt.

Falls dieses Repository einem veröffentlichten Paper entspricht, füge in diesem Abschnitt einen `BibTeX`-Eintrag und den offiziellen Publikationslink hinzu.

## Danksagung 🙏

In den Repository-Dateien sind derzeit keine Danksagungen definiert.

Wenn institutionelle Unterstützung, Mitwirkende oder Förderquellen genannt werden sollen, ergänze sie hier in einem Folge-Update.

## Lizenz 📄

Dieses Projekt ist unter der Apache License 2.0 lizenziert. Siehe [LICENSE](../LICENSE).
