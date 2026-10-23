# Reader's Guide — public-apis

## What this project is

**public-apis** is the collective list of **free APIs for use in software and
web development** — one of the most-starred reference lists on GitHub. When
you are building something and need data or a service (weather, geocoding,
finance, cat pictures…), this is the catalogue you search before writing a
scraper. Each entry tells you, in a fixed format, what the API does and what
it takes to call it.

## How the content is organised

Everything lives in [`README.md`](README.md) (this guide was written from its
section outline and the repository tree; the README is very large):

- An **Index** of **51 categories**, each a section of the same-shaped table —
  `API | Description | Auth | HTTPS | CORS` — so you can judge an API at a
  glance: what authentication it needs (`No`, `apiKey`, `OAuth`), whether it
  supports HTTPS, and whether browser calls are allowed (CORS).
  Categories include Animals, Anime, Anti-Malware, Art & Design,
  Authentication & Authorization, Blockchain, Books, Business, Calendar,
  Cloud Storage & File Sharing, Cryptocurrency, Currency Exchange,
  Development, Dictionaries, Email, Entertainment, Environment, Finance,
  Food & Drink, Games & Comics, Geocoding, Government, Health, Jobs,
  Machine Learning, Music, News, Open Data, Photography, Programming,
  Science & Math, Security, Shopping, Social, Sports & Fitness, Test Data,
  Text Analysis, Tracking, Transportation, URL Shorteners, Vehicle, Video
  and Weather.
- Near the top, short sponsored sections (**APILayer APIs**, **MCP Servers**)
  sit above the community list proper.
- `CONTRIBUTING.md` — the strict entry format and quality rules every
  addition must follow.
- `scripts/` — the validation machinery (`validate/`, `tests/`,
  `github_pull_request.sh`) that automatically checks new entries' format
  and links.

## How to use it

1. Find your need in the **Index** and jump to that category's table.
2. Filter by the columns: most readers want `Auth: No` or `apiKey`,
   `HTTPS: Yes`, and `CORS: Yes` for browser apps.
3. Follow the API's link to its own documentation to sign up and get keys.

## About this standalone edition

This repository is a standalone edition of
[public-apis/public-apis](https://github.com/public-apis/public-apis),
converted from a fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to the upstream
contributors; licence MIT (see `LICENSE`).
