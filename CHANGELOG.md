# Changelog

All notable changes to this standalone edition of agency-agents are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions dependency updates.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow) for the agent definitions and docs; the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content. Upstream's check-divisions, lint-agents, test-install and other workflows were kept as-is.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) at upstream commit `4e3ac3ca6604c75113f52c695dbddcc7af928b46` (upstream HEAD dated 2026-10-19).
- Fork history severed; all files and the MIT licence (`LICENSE`) preserved as-is.
