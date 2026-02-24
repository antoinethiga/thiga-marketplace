## Toolkit PM IA

This repository contains a set of **product‑management AI skills** packaged as a Claude / Cursor plugin.

- **Marketplace config**: defined in `.claude-plugin/marketplace.json` under the `toolkit-pm-ia` plugin entry.
- **Skills**: located in the `skills/` directory (e.g. `skills/bob`, `skills/zoe`, `skills/neo`, `skills/joe`).

### Usage

1. Run `/plugin marketplace add antoinethiga/thiga-marketplace` in your terminal
2. Run `/plugin install thiga-marketplace@toolkit-pm-ia`

### Development

- Edit skills in the `skills/` subdirectories.
- Update `.claude-plugin/marketplace.json` when adding or renaming plugins.

