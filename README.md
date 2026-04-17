# Dytomic.github.io

[![Live Site](https://img.shields.io/badge/live-dytomic.github.io-ef9d17?style=flat-square)](https://dytomic.github.io/)
[![Studio](https://img.shields.io/badge/studio-archived-244585?style=flat-square)](https://dytomic.github.io/)

**Source for the Dytomic organisation's archived public site.** A single-page technical record of [Dytomic](https://github.com/Dytomic) &mdash; an independent Montreal game development studio behind [Pirate Raids Online](https://github.com/Dytomic/pro-web), an old-school inspired PC MMORPG. The studio operated from 2021 through early 2024; everything here is preserved as open reference.

Live at **[dytomic.github.io](https://dytomic.github.io/)**.

---

## What the site covers

| Section | Content |
|---------|---------|
| **Studio** | About Dytomic. Montreal-based independent game studio (2021&ndash;2024). |
| **Team** | Founding team contributions: Tommy Roumanas (Co-Founder, CEO), Mourad Elsheraey (Co-Founder, CTO). |
| **Game** | Pirate Raids Online &mdash; pre-production PC MMORPG set in Ascaron. Classless combat, naval gameplay, four Demigod tribes. |
| **Public Code** | The open-sourced subset of the studio's engineering work: pro-web, pro-splash, ariel, ball-simulation. |
| **Research Archive** | Preserved research on the Tales of Pirates / PKO engine family. Links to [pkodev-V3ct0r1024](https://github.com/Dytomic/pkodev-V3ct0r1024), [pkodev-Perseus](https://github.com/Dytomic/pkodev-Perseus), and [top-forums-archive](https://github.com/Dytomic/top-forums-archive). |

---

## Build

No build step. Single static `index.html` with inlined CSS, Google Fonts, and structured data (`Organization`, `VideoGame` JSON-LD). Hosted by GitHub Pages directly from the `main` branch root.

- [index.html](index.html) &mdash; the page
- [sitemap.xml](sitemap.xml) &mdash; for crawler discovery
- [robots.txt](robots.txt) &mdash; allows all
- `team-photo.jpg` &mdash; team call photo used in the Team section

---

## Design

The visual language mirrors [pro-web](https://github.com/Dytomic/pro-web), the studio's marketing site for Pirate Raids Online:

- **Palette:** dark teal `#1d2424`, gold `#ef9d17`, off-white `#edeef0`
- **Typography:** Cormorant Garamond (serif headings) and Raleway (body)
- **Components:** section separators with diamond accents, semi-transparent ShadowBox panels, gold CTAs

---

## SEO &amp; metadata

The page is built as a single static document with full crawlability:

- Semantic HTML5 (`<nav>`, `<header>`, `<main>`, `<section>`, `<footer>`, `<article>`)
- Structured data (`Organization` + `VideoGame` JSON-LD)
- Open Graph and Twitter Card metadata
- Canonical URL, meta keywords and description
- `sitemap.xml` and `robots.txt` at root
- Lazy-loaded image with descriptive alt text

---

## Related repositories

All public Dytomic repositories, archived:

| Repository | About |
|---|---|
| [pro-web](https://github.com/Dytomic/pro-web) | Official marketing site for Pirate Raids Online. Next.js 12, React 18, React Bootstrap. |
| [pro-splash](https://github.com/Dytomic/pro-splash) | Pre-launch splash page (discontinued). React 17. |
| [ariel](https://github.com/Dytomic/ariel) | Facebook Messenger chatbot. Python, Flask. |
| [ball-simulation](https://github.com/Dytomic/ball-simulation) | Live-interview starter for game-dev candidates. Vanilla JS physics sandbox. |
| [pkodev-V3ct0r1024](https://github.com/Dytomic/pkodev-V3ct0r1024) | 42 Tales of Pirates community mods and tools mirrored as git subtrees. |
| [pkodev-Perseus](https://github.com/Dytomic/pkodev-Perseus) | 6 TOP/PKO server and CMS projects mirrored as git subtrees. |
| [top-forums-archive](https://github.com/Dytomic/top-forums-archive) | Preserved snapshots of three TOP/PKO community forums (1,683 threads). |

---

## Status

Archived. The studio ceased operations in early 2024. This page and all linked repositories remain public as a preserved technical record.

---

<sub>**Keywords:** Dytomic &middot; Pirate Raids Online &middot; PRO MMORPG &middot; Montreal game studio &middot; Tales of Pirates &middot; Pirate King Online &middot; PKO research &middot; MMORPG engine &middot; indie game development</sub>
