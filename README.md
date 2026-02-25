## Toolkit PM IA

This repository contains a set of **product‑management AI agents** packaged as a Claude / Cursor plugin.

- **Marketplace config**: defined in `.claude-plugin/marketplace.json` under the `toolkit-pm-ia` plugin entry.
- **Agents definitions**: located in the `agents/` directory (e.g. `agents/bob.md`, `agents/zoe.md`, `agents/neo.md`, `agents/joe.md`).

### Prerequisites

- **Git installé** sur votre machine.
- **Configuration HTTPS recommandée** pour GitHub afin de contourner les restrictions SSH :

```bash
git config --global url."https://github.com/".insteadOf "git@github.com:"
```

#### Installer Git depuis le terminal (macOS)

- **Option 1 – via les outils de ligne de commande Xcode (simple)** :

```bash
xcode-select --install
```

- **Option 2 – via Homebrew (si Homebrew est déjà installé)** :

```bash
brew install git
```

Pour vérifier que Git est bien installé :

```bash
git --version
```

### Usage

1. Run `/plugin marketplace add antoinethiga/thiga-marketplace` in your terminal
2. Run `/plugin install thiga-marketplace@toolkit-pm-ia`

### Agents

- **Bob**: CPO / expert data & product marketing. Il transforme une idée de fonctionnalité brute en **dossier de production complet** : user stories INVEST, critères d’acceptation Gherkin, KPIs business, plan de tracking analytics, release notes et tickets Jira prêts à l’emploi.
- **Joe**: Lead user researcher & data analyst. Il prend des **volumes de feedbacks clients** (avis, tickets, interviews) et les transforme en **data quantifiée**, tableaux de thèmes, priorisation et plans d’action stratégiques pour CPO, Head of Product et PM.
- **ZOE**: Lead UX researcher zéro biais. Elle part d’une **hypothèse produit ou d’un doute** et construit un **protocole de recherche scientifique** (méthode, recrutement, guide d’entretien / survey / test, grille d’Atomic Research) entièrement purgé de biais cognitifs.
- **NEO**: Gardien stratégique de la discovery. Il empêche de tomber dans la **feature factory** en challengeant les idées, en vérifiant la preuve produit / marché et en protégeant le budget tech contre les développements non validés.

### Development

- Edit agent prompts and configuration in the `agents/` directory.
- Update `.claude-plugin/marketplace.json` when adding, renaming, or changing plugins exposed in the marketplace.
