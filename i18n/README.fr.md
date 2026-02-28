[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)



# EventHolography

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](./LICENSE)
![Status](https://img.shields.io/badge/Status-Documentation--First-orange)
![Repository](https://img.shields.io/badge/Repository-Early--Stage-lightgrey)
![i18n](https://img.shields.io/badge/i18n-Directory%20Present-success)

Le dépôt des ressources du projet **Event-assisted Holographic Imaging**.

> Description originale du projet conservée (base canonique) :
> `The repo for the paper Event-assited Holographic Imaging`

## Vue d’ensemble 🔍

`EventHolography` est actuellement un dépôt orienté documentation, centré sur le thème de l’article/projet **Event-assisted Holographic Imaging**.

Au moment de la rédaction, le dépôt contient principalement :

- Un README minimal à la racine (développé ici pour plus de clarté)
- Une licence Apache 2.0
- Un `.gitignore` au niveau du projet
- Un répertoire `i18n/` pour les variantes multilingues du README

Aucun code source, manifeste de dépendances ou pipeline exécutable n’est actuellement versionné.

## Fonctionnalités ✨

- Identité et périmètre du projet clairement définis pour la recherche en holographie assistée par événements
- Licence Apache 2.0 pour un usage ouvert et les contributions
- Organisation documentaire prête pour le multilingue via `i18n/`
- Structure de README enrichie pour de futures intégrations de code/données

## Structure du projet 🗂️

```text
EventHolography/
├── README.md
├── LICENSE
├── .gitignore
└── i18n/
```

| Chemin | Rôle | État actuel |
|---|---|---|
| `README.md` | Documentation principale du projet | Présent et activement maintenu |
| `LICENSE` | Conditions légales | Apache License 2.0 |
| `.gitignore` | Règles d’exclusion pour artefacts locaux/de build | Présent |
| `i18n/` | Fichiers README spécifiques à chaque langue | Le dossier existe ; des fichiers peuvent être ajoutés au fil du temps |

Remarques :

- `i18n/` existe et est réservé aux fichiers README spécifiques à chaque langue.
- `.auto-readme-work/` existe comme contexte de travail généré par pipeline et ne fait pas actuellement partie de la surface publique du projet.

## Prérequis ✅

L’état actuel du dépôt ne nécessite que des outils de base :

- `git` (pour cloner et suivre les modifications)
- Un lecteur Markdown (interface GitHub ou éditeur local)

Optionnel (hypothèse orientée futur basée sur les motifs de `.gitignore`) :

- Un outillage Python pourra être introduit plus tard, mais aucun runtime/dépendance Python n’est actuellement requis par les fichiers versionnés du projet.

## Installation 🛠️

Clonez le dépôt :

```bash
git clone <your-repo-url> EventHolography
cd EventHolography
```

Si vous avez déjà le dépôt en local, vérifiez que vous êtes sur la branche cible avant de modifier la documentation ou d’ajouter des ressources projet.

## Utilisation ▶️

Il n’existe pas encore de point d’entrée exécutable. L’utilisation actuelle est orientée documentation :

```bash
# Inspect repository contents
ls -la

# Read project overview
cat README.md
```

Au fur et à mesure de l’ajout de code, de jeux de données ou de notebooks, cette section devra être enrichie avec des commandes d’exécution exactes.

## Configuration ⚙️

Aucune configuration d’exécution n’est actuellement définie.

Exemples de configuration future planifiée (à ajouter une fois l’implémentation disponible) :

- Chemins des données
- Chemins des modèles/checkpoints
- Paramètres caméra/capteur événementiel
- Paramètres d’expériences de reconstruction/holographie

## Exemples 📌

Les exemples pratiques actuels sont des tâches d’inspection du dépôt :

```bash
# Confirm license
head -n 5 LICENSE

# Check language folder status
ls -la i18n
```

Si vous attendiez des exemples d’entraînement/d’inférence/de démo, ils ne sont pas encore disponibles dans cet instantané du dépôt.

## Notes de développement 🧪

- Il s’agit d’un squelette de dépôt en phase précoce.
- Appuyez les nouvelles affirmations techniques sur des fichiers versionnés (code, configurations, scripts, jeux de données, notebooks ou artefacts de l’article).
- Privilégiez des mises à jour incrémentales de ce README plutôt que le remplacement de sections entières, afin de préserver le contexte historique.

## Dépannage 🩺

### « Il n’y a encore rien à exécuter »

C’est attendu dans l’état actuel. Aucun workflow exécutable n’a été versionné.

### « Je m’attendais à des READMEs traduits »

`i18n/` existe mais peut ne pas encore contenir de fichiers de langue. Ajoutez-y des README spécifiques à chaque langue au fur et à mesure de leur rédaction.

### « L’orthographe du titre du projet diffère selon les endroits »

La description originale inclut `Event-assited` (conservé tel quel). L’orthographe privilégiée dans les nouveaux textes est `Event-assisted`.

## Feuille de route 🗺️

Évolutions prévues de la documentation et du dépôt :

- Ajouter les métadonnées de citation de l’article (BibTeX et lien de publication dès disponibilité)
- Ajouter le code d’implémentation et des instructions d’expériences reproductibles
- Ajouter la documentation des jeux de données/prétraitement
- Ajouter des README multilingues dans `i18n/`
- Ajouter des templates d’issues/PR et les détails du workflow de contribution

## Contribution 🤝

Les contributions sont les bienvenues.

En attendant l’ajout de templates de contribution dédiés, utilisez le workflow GitHub standard :

1. Forkez le dépôt
2. Créez une branche de fonctionnalité/documentation
3. Commitez des changements ciblés avec des messages clairs
4. Ouvrez une pull request décrivant la motivation, les changements et la validation

Si vous ajoutez de nouvelles instructions techniques, incluez des commandes exécutables et les sorties attendues lorsque c’est possible.

## Citation 📚

Les détails de citation ne sont pas encore fournis dans ce dépôt.

Si ce dépôt correspond à un article publié, ajoutez une entrée `BibTeX` et le lien officiel de publication dans cette section.

## Remerciements 🙏

Aucun remerciement n’est actuellement défini dans les fichiers du dépôt.

Si vous avez un soutien institutionnel, des collaborateurs ou des sources de financement à créditer, ajoutez-les ici lors d’une prochaine mise à jour.

## Licence 📄

Ce projet est distribué sous licence Apache License 2.0. Voir [LICENSE](./LICENSE).
