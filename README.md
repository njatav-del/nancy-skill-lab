# nancy-skill-lab

Personal practice marketplace for learning the GitHub -> Claude skill pipeline.

## Structure

- `.claude-plugin/marketplace.json` — the marketplace catalog (lists plugins in this repo)
- `plugins/practice/.claude-plugin/plugin.json` — the practice plugin's info card (name, version)
- `plugins/practice/skills/hello-nancy/SKILL.md` — the wiring-test skill

## Release discipline

Whenever a skill changes, bump the `version` in `plugins/practice/.claude-plugin/plugin.json` (e.g. 1.0.0 -> 1.0.1) so installed copies of the plugin know there's an update.
