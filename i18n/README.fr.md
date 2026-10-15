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

Dépôt des ressources du projet **Event-assisted Holographic Imaging**.

> Description originale du projet conservée (base canonique) :
> `The repo for the paper Event-assited Holographic Imaging`

## 🧭 Navigation rapide

| Domaine | Lien |
|---|---|
| 🎯 Aperçu | [Aperçu](#overview-) |
| 🗂️ Portée | [Structure du projet](#project-structure-) |
| ✅ Prérequis | [Prérequis](#prerequisites-) |
| ▶️ Utilisation | [Utilisation](#usage-) |
| 🧪 Contributions | [Contributions](#contributing-) |
| ❤️ Support | [❤️ Support](#-support) |
| 📜 Licence | [Licence](#license-) |

<a id="overview-"></a>
## Aperçu 🔍

`EventHolography` est un dépôt centré sur la documentation, dédié au thème du papier/projet **Event-assisted Holographic Imaging**.

À la date de cet instantané, il a pour but principal d'être un point d'entrée de prise en main et de communication, plutôt qu'un package exécutable.

- Statut canonique : socle documentaire de recherche à un stade précoce
- Focus public : contexte de l'article, hypothèses de configuration et guide multilingue
- Portée : structure du dépôt, processus de contribution, et préparation à la prise en charge future du code/des données

## Instantané du dépôt 📈

| Élément | Détails | Statut |
|---|---|---|
| `README.md` | Documentation principale du projet | Présent et maintenu activement |
| `LICENSE` | Conditions légales et politique de réutilisation | Apache License 2.0 |
| `.gitignore` | Règles d'exclusion pour les artefacts locaux/du build | Présent |
| `i18n/` | Fichiers README par langue | Présent |
| `.auto-readme-work/` | Métadonnées de pipeline pour la génération des README | Généré pendant la rédaction |

## Fonctionnalités ✨

- Identité claire pour les supports du projet **Event-assisted Holographic Imaging**
- Licence Apache 2.0 pour une réutilisation ouverte et permissive
- Disposition du README prête pour l'internationalisation (`i18n/`)
- Statut « documentation-first » explicite pour les utilisateurs et contributeurs
- Structure évolutive pour ajouter ultérieurement jeux de données, scripts, checkpoints et guides de reproductibilité

<a id="project-structure-"></a>
## Structure du projet 🗂️

```text
EventHolography/
├── README.md
├── LICENSE
├── .gitignore
├── i18n/
└── .auto-readme-work/
```

Notes :

- `i18n/` contient les versions traduites du README, notamment en arabe, en russe et dans plusieurs autres langues.
- `.auto-readme-work/` est généré au cours de ce flux de travail de documentation et n'est pas l'interface publique canonique du projet.

<a id="prerequisites-"></a>
## Prérequis ✅

L'état actuel du dépôt ne nécessite que :

- `git` pour le clonage et le travail sur l'historique/les branches local
- Un éditeur Markdown-aware ou un visualiseur GitHub

Hypothèse :

- Aucune dépendance Python/Node/Rust et aucun runtime de modèle n'est requis aujourd'hui, car aucun pipeline exécutable n'est engagé.

## Installation 🛠️

Clonez et entrez dans le dépôt :

```bash
git clone <your-repo-url> EventHolography
cd EventHolography
```

Environnement optionnel pour la maintenance documentaire :

```bash
git checkout -b docs/improve-onboarding
```

Si votre objectif est de mettre à jour des traductions, modifiez à la fois `README.md` et le fichier `i18n/README.xx.md` correspondant.

<a id="usage-"></a>
## Utilisation ▶️

Aucun point d'entrée exécutable n'est encore disponible, l'utilisation actuelle est donc centrée sur la documentation :

```bash
# Inspecter le contenu du dépôt
ls -la

# Lire la vue d'ensemble du projet
cat README.md
```

Quand des actifs d'implémentation arriveront, cette section passera à des instructions au niveau de l'exécution (datasets, modèles, commandes train/infer).

## Configuration ⚙️

Il n'existe actuellement aucune surface de configuration au runtime.

Domaines de configuration prévus (une fois le code disponible) :

- Racines des datasets
- Répertoires de checkpoint et de sortie
- Paramètres de reconstruction holographique
- Métadonnées du capteur d'événements et options de calibration
- Préréglages de reproductibilité (seed, splits, augmentations)

## Exemples 📌

Les exemples pratiques dans cet instantané se limitent à des commandes d'exploration du dépôt :

```bash
# Vérifier l'en-tête de licence
head -n 5 LICENSE

# Vérifier la couverture de documentation linguistique
ls -la i18n

# Lire le contexte auto-généré (optionnel)
ls -la .auto-readme-work
```

Si vous attendiez des exemples d'entraînement/inférence, ce dépôt ne les inclut pas encore.

## Notes de développement 🧪

- Il s'agit d'un socle de dépôt à un stade précoce, avec des priorités orientées documentation.
- Conservez les affirmations techniques strictement liées aux actifs engagés (fichiers présents dans l'arbre du dépôt).
- Maintenez des mises à jour incrémentales du README, en préservant le contexte historique et la parité des traductions.
- Si vous ajoutez du code, placez les détails d'implémentation, les résultats attendus et les étapes de reproductibilité à côté de cette documentation.

## Dépannage 🩺

### « Il n'y a rien à exécuter pour l'instant »

C'est normal dans l'état actuel. Aucun script exécutable, config, notebook ou dataset n'est actuellement engagé.

### « Où se trouvent les README traduits ? »

Consultez le dossier `i18n/`. Si une langue cible manque, ajoutez `i18n/README.<lang>.md` et synchronisez les liens de navigation multilingue.

### « Pourquoi l'orthographe du titre diffère ? »

L'expression d'origine dans les notes amont est `Event-assited` (avec un seul « s »), conservée dans la ligne legacy citée. Ce README utilise l'orthographe corrigée `Event-assisted` dans les textes nouvellement rédigés.

### « Dois-je utiliser le dossier `.auto-readme-work/` ? »

Considérez-le comme des métadonnées générées pour la rédaction des README. Il n'est en général pas nécessaire pour les contributeurs standards, sauf lors de travaux sur l'automatisation de la documentation.

## Feuille de route 🗺️

- Ajouter des métadonnées de l'article (lien de publication, DOI et bloc de citation BibTeX)
- Ajouter des points d'entrée d'implémentation et des instructions d'utilisation reproductibles dès que disponibles
- Ajouter la documentation sur les datasets, le prétraitement et la configuration des expériences
- Ajouter des modèles d'issue/PR et des documents d'automatisation de contribution
- Garder les README multilingues synchronisés avec la source anglaise

<a id="contributing-"></a>
## Contributions 🤝

Les contributions sont les bienvenues.

En attendant l'ajout de templates dédiés, utilisez ce workflow standard :

1. Forker le dépôt
2. Créer une branche ciblée (`docs/<topic>`)
3. Commiter de petits changements révisables avec des messages clairs
4. Ouvrir une PR avec la motivation, les changements précis de fichiers et des commandes de vérification si disponible

Si vous ajoutez des instructions techniques, incluez des exemples au niveau des commandes et les sorties attendues.

## Citation 📚

Les détails de citation ne sont pas encore disponibles dans le dépôt.

Quand la publication correspondante sera disponible, ajoutez un bloc `BibTeX` et le lien de publication dans cette section.

## Remerciements 🙏

Aucun remerciement n'est actuellement défini dans les fichiers du dépôt.

Si du soutien, des institutions ou des collaborateurs doivent être crédités, ajoutez-les ici lors d'une mise à jour ultérieure.

## Licence 📄

Ce projet est sous licence Apache 2.0. Voir [LICENSE](./LICENSE).


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |
