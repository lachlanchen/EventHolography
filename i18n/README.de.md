[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner — apps and four buddies](https://lazying.art/media/brand/lazyingart-intro.gif)](https://lazying.art)

# EventHolography

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-3776ab?style=for-the-badge&logo=apache&logoColor=white)](./LICENSE)
![Focus: Documentation-First](https://img.shields.io/badge/Focus-Documentation--First-FCA121?style=for-the-badge)
![Repository Stage](https://img.shields.io/badge/Stage-Early--Stage-lightgrey?style=for-the-badge)
![i18n](https://img.shields.io/badge/i18n-Directory%20Present-2ea44f?style=for-the-badge)
![Status](https://img.shields.io/badge/Repository-Documentation%20First-0f766e?style=for-the-badge&logo=markdown&logoColor=white)
![Audience](https://img.shields.io/badge/Audience-Researchers%20%26%20Contributors-22c55e?style=for-the-badge&logo=google-translate&logoColor=white)

---

Repository für die Projektmaterialien zur **Event-assisted Holographic Imaging**.

> Beibehaltene ursprüngliche Projektbeschreibung (kanonische Basis):
> `The repo for the paper Event-assited Holographic Imaging`

## 🧭 Schnelle Navigation

| Bereich | Link |
|---|---|
| 🎯 Überblick | [Überblick](#overview-) |
| 🗂️ Umfang | [Projektstruktur](#project-structure-) |
| ✅ Voraussetzungen | [Voraussetzungen](#prerequisites-) |
| ▶️ Nutzung | [Nutzung](#usage-) |
| 🧪 Mitwirken | [Mitwirken](#contributing-) |
| ❤️ Support | [❤️ Support](#-support) |
| 📜 Lizenz | [Lizenz](#license-) |

<a id="overview-"></a>
## Überblick 🔍

`EventHolography` ist ein **dokumentationsorientiertes** Repository zum Projekt/Thema **Event-assisted Holographic Imaging**.

Zum Zeitpunkt dieses Repository-Schnappschusses dient es als Onboarding- und Kommunikations-Hub statt als ausführbares Paket.

- Kanonischer Status: frühes Dokumentations-Scaffold für Forschungsarbeit
- Öffentliches Fokusfeld: Paper-Kontext, Setup-Annahmen und mehrsprachige Anleitung
- Umfang: Repository-Struktur, Beitragspfad und Vorbereitungsgrad für zukünftige Code-/Daten-Arbeit

## Repository-Snapshot 📈

| Element | Details | Status |
|---|---|---|
| `README.md` | Dokumentation des Hauptprojekts | Vorhanden und aktiv gepflegt |
| `LICENSE` | Rechtliche Bedingungen und Nutzungsregeln | Apache License 2.0 |
| `.gitignore` | Regeln zum Ausschluss lokaler/build-bezogener Artefakte | Vorhanden |
| `i18n/` | Sprachspezifische README-Dateien | Vorhanden |
| `.auto-readme-work/` | Pipeline-Metadaten für README-Generierung | Wird nur während der Erstellung erzeugt |

## Funktionen ✨

- Klare Identität für Projektmaterialien rund um **Event-assisted Holographic Imaging**
- Apache-2.0-Lizenz für offene und permissive Wiederverwendung
- Internationalisierungstaugliches README-Layout (`i18n/`)
- Explizite Dokumentations-first-Ausrichtung für Nutzer:innen und Mitwirkende
- Zukunftsfähige Struktur zum späteren Hinzufügen von Datensätzen, Skripten, Checkpoints und Reproduzierbarkeitsanleitungen

<a id="project-structure-"></a>
## Projektstruktur 🗂️

```text
EventHolography/
├── README.md
├── LICENSE
├── .gitignore
├── i18n/
└── .auto-readme-work/
```

Hinweise:

- `i18n/` enthält die übersetzten Versionen der README-Dateien, darunter bereits Arabisch, Russisch und weitere Sprachen.
- `.auto-readme-work/` wird während dieses Dokumentations-Workflows erzeugt und ist nicht die kanonische öffentliche Oberfläche.

<a id="prerequisites-"></a>
## Voraussetzungen ✅

Der aktuelle Zustand des Repositories benötigt nur:

- `git` für das Klonen und die lokale Versionsverwaltung
- Ein Markdown-fähiges Editor- oder GitHub-Interface zum Lesen

Annahmen:

- Da derzeit keine ausführbare Pipeline vorhanden ist, werden keine Python-/Node-/Rust-Toolchain oder Laufzeitabhängigkeiten benötigt.

<a id="usage-"></a>
## Nutzung ▶️

Es gibt noch keinen ausführbaren Entry Point, daher ist die aktuelle Nutzung dokumentationszentriert:

```bash
# Inspect repository contents
ls -la

# Read project overview
cat README.md
```

Sobald Implementierungsartefakte verfügbar sind, sollte dieser Abschnitt auf ausführbare Anweisungen erweitert werden (Datensätze, Modelle, Trainings-/Inferenz-Befehle).

## Konfiguration ⚙️

Es gibt aktuell keine Laufzeitkonfiguration.

Geplante Konfigurationsbereiche (nach Bereitstellung von Code):

- Wurzelpfade zu Datensätzen
- Checkpoint- und Ausgabeverzeichnisse
- Holographische Rekonstruktionsparameter
- Metadaten und Kalibrierung des Event-Sensors
- Reproduzierbarkeits-Presets (Seed, Splits, Augmentationen)

## Beispiele 📌

Praktische Beispiele in diesem Repository-Schnappschuss sind Befehle zur Repo-Erkundung:

```bash
# Confirm license header
head -n 5 LICENSE

# Verify language documentation coverage
ls -la i18n

# Read auto-generated context (optional)
ls -la .auto-readme-work
```

Wenn du Trainings-/Inferenzbeispiele erwartest, sind diese im aktuellen Stand noch nicht enthalten.

## Entwicklungsnotizen 🧪

- Dies ist ein frühes Repository-Scaffold mit dokumentationszentrierten Prioritäten.
- Technische Aussagen sollten ausschließlich auf tatsächlich vorhandene Artefakte im Repository verweisen.
- README-Änderungen sollten inkrementell erfolgen und historischen Kontext sowie Übersetzungskonsistenz bewahren.
- Wenn Code hinzugefügt wird, sollten Implementierungsdetails, erwartete Ausgaben und Reproduzierbarkeitsschritte zusammen mit der Dokumentation ergänzt werden.

## Fehlerbehebung 🩺

### „Es gibt noch nichts auszuführen"

Das ist im aktuellen Stand zu erwarten. Es sind keine ausführbaren Skripte, Konfigurationen, Notebooks oder Datensätze eingecheckt.

### „Wo sind die übersetzten README-Dateien?"

Schau in das Verzeichnis `i18n/`. Falls eine Zielsprache fehlt, lege `i18n/README.<lang>.md` an und synchronisiere die Sprach-Navigation.

### „Warum ist die Titel-Rechtschreibung unterschiedlich?"

Der ursprüngliche Begriff in den Upstream-Notizen lautet `Event-assited` (mit einem „s“). Diese Schreibweise wird im wörtlich übernommenen Legacy-Zitat belassen. In neu verfasstem Fließtext verwendet diese README die korrigierte Form `Event-assisted`.

### „Sollte ich den `.auto-readme-work/`-Ordner verwenden?"

Behandle ihn als generierte Metadaten für die README-Erstellung. Für reguläre Beiträge ist er in der Regel nicht nötig, außer bei Arbeit an Dokumentationsautomatisierung.

## Roadmap 🗺️

- Paper-Metadaten ergänzen (Publikationslink, DOI, BibTeX-Zitationsblock)
- Umsetzungseintrittspunkte und reproduzierbare Nutzungshinweise ergänzen, sobald verfügbar
- Dokumentation zu Datensatz, Preprocessing und Experimentkonfiguration hinzufügen
- Issue/PR-Templates und Beiträge-Automatisierung dokumentieren
- Mehrsprachige README-Dateien mit dem Englischen synchron halten

<a id="contributing-"></a>
## Mitwirken 🤝

Beiträge sind willkommen.

Bis dedizierte Templates vorliegen, nutze bitte diesen Standard-Workflow:

1. Repository forken
2. Einen fokussierten Branch erstellen (`docs/<thema>`)
3. Kleine, prüfbare Änderungen mit klaren Commit-Meldungen committen
4. Eine PR mit Motivation, exakten Dateichanges und möglichen Verifikationsbefehlen öffnen

Wenn du technische Anleitungen ergänzt, bitte konkrete Befehle auf Kommandoebene und erwartete Ausgaben aufnehmen.

## Zitation 📚

Zitationsangaben sind im Repository noch nicht verfügbar.

Wenn die zugehörige Publikation vorliegt, füge in diesem Abschnitt einen `BibTeX`-Block und den Publikationslink hinzu.

## Danksagung 🙏

Es sind derzeit keine Danksagungen in den Repository-Dateien definiert.

Falls Unterstützer, Institutionen oder Kooperationspartner genannt werden sollen, ergänze diese in einem Folge-Update.

## Lizenz 📄

Dieses Projekt ist unter der Apache License 2.0 lizenziert. Siehe [LICENSE](./LICENSE).


## ❤️ Support

<!-- support:start -->
[![GitHub Sponsors](https://img.shields.io/badge/GitHub-Sponsors-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/lachlanchen)
[![LazyingArt Support](https://img.shields.io/badge/LazyingArt-Support-0EA5E9?style=for-the-badge)](https://chat.lazying.art/donate)
[![PayPal Support](https://img.shields.io/badge/PayPal-Support-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/RongzhouChen)
[![Stripe Support](https://img.shields.io/badge/Stripe-Support-635BFF?style=for-the-badge&logo=stripe&logoColor=white)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400)
<!-- support:end -->
