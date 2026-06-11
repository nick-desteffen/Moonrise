# Risk 2210 A.D. — Moonrise Theme

A port of [risk2210.net](https://risk2210.net) built on the [Moonrise](https://github.com/TolgaTatli/Moonrise) Jekyll theme.

## Setup

1. **Fork the [Moonrise repo](https://github.com/TolgaTatli/Moonrise/fork)** into your GitHub account.
2. **Copy this repo's files** over the forked Moonrise files:
   - `_config.yml` — replaces the default config
   - `_data/navigation.yml` — sets the nav links
   - `pages/` — all content pages (expansions, resources)
3. **Rename** your forked repo to `YourUsername.github.io` (for GitHub Pages) or keep it as-is and set the `baseurl` in `_config.yml`.
4. **Update `_config.yml`** with your own URL and any customizations (logo, background image, etc.).

## Running Locally

```bash
bundle install
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000).

## Site Structure

```
_config.yml          ← Site settings (title, URL, bio, etc.)
_data/
  navigation.yml     ← Top nav links
pages/
  expansions/
    index.md         ← Expansions landing page
    mars.md
    antarctica.md
    factions.md
    galaxy-commander.md
    capitals.md
    invasion-of-the-giant-amoebas.md
    arctic.md
    asteroid-colonies.md
    dark-side-of-the-moon.md
    europa.md
    io.md
    pluto.md
    titan.md
    majors-promo-cards.md
    resistance-commander.md
    tech-commander.md
    galactic-risk.md
  resources.md       ← Files, links, and blogs
```

## Adding Content

Each page uses standard Jekyll front matter:

```yaml
---
layout: page
title: "Page Title"
permalink: /your/path/
---
```

Body content is plain Markdown.

## Notes on Stub Pages

Several expansion pages (`arctic`, `asteroid-colonies`, `dark-side-of-the-moon`, `europa`, `io`, `pluto`, `titan`, `majors-promo-cards`, `resistance-commander`, `tech-commander`, `galactic-risk`) are stubs that link back to the original site. Expand them by copying the rules and card lists from [risk2210.net](https://risk2210.net).

## Theme Credit

[Moonrise](https://github.com/TolgaTatli/Moonrise) by [TolgaTatli](https://github.com/TolgaTatli), MIT License.
