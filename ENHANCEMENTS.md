# Enhancements — Standalone Edition Changelog

Upstream: https://github.com/public-apis/public-apis
Maintainer of this edition: Syed Mujtaba Abbas (@mujtbabbas)

## v1.1.0 — Enhancement release (2026-10-20)
- Added "About This Standalone Edition" section to README.md with upstream link, base version provenance, and credit.
- Added this changelog (ENHANCEMENTS.md).
- Added .github/dependabot.yml (weekly GitHub Actions updates, plus pip for scripts/, whose requirements.txt the upstream validation workflows install).
- Added .markdownlint.json and .github/workflows/markdown-check.yml (markdown linting automation for the API list; upstream test_of_push_and_pull.yml, test_of_validate_package.yml and validate_links.yml workflows kept as-is — they already run the repo's real Python validation tooling, so no duplicate CI was added).
- Added .editorconfig (standard editor settings: UTF-8, LF, 2-space indent).

## v1.0.0 — Baseline (2026-10-20)
- Clean standalone baseline of public-apis/public-apis at upstream commit 93086df88fbce354dd612373ab755f941f53a473 (upstream HEAD dated 2026-10-19).
- Fork history severed; all files and the MIT licence (LICENSE) preserved as-is, including the four PNG sponsor/banner images under .github/.
