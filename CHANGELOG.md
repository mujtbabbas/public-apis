# Changelog

All notable changes to this standalone edition of public-apis are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions updates, plus pip updates for `scripts/` (whose `requirements.txt` the upstream validation workflows install).
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow) for the API list; the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content. Upstream's `test_of_push_and_pull.yml`, `test_of_validate_package.yml` and `validate_links.yml` workflows were kept as-is — they already run the repo's real Python validation tooling, so no duplicate CI was added.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [public-apis/public-apis](https://github.com/public-apis/public-apis) at upstream commit `93086df88fbce354dd612373ab755f941f53a473` (upstream HEAD dated 2026-10-19).
- Fork history severed; all files and the MIT licence (`LICENSE`) preserved as-is, including the four PNG sponsor/banner images under `.github/`.
