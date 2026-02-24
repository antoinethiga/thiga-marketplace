## Toolkit PM IA

This repository contains a set of **product‑management AI skills** packaged as a Claude / Cursor plugin.

- **Marketplace config**: defined in `.claude-plugin/marketplace.json` under the `toolkit-pm-ia` plugin entry.
- **Skills**: located in the `skills/` directory (e.g. `skills/bob`, `skills/zoe`, `skills/neo`, `skills/joe`).

### Usage

1. Install / link this repository as a plugin in Claude / Cursor.
2. Ensure the `marketplace.json` `source.repo` field points to the GitHub repo for this project.
3. Reload the plugin in your IDE / assistant to pick up any changes.

### Development

- Edit skills in the `skills/` subdirectories.
- Update `.claude-plugin/marketplace.json` when adding or renaming plugins.

