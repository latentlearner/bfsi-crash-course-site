# BFSI Crash Course

A self-paced crash course on **Banking, Financial Services & Insurance**, with a focus on the **UAE and Dubai** market — the business, operations, technology, and regulatory landscape of banking.

**▶ Live site: https://latentlearner.github.io/bfsi-crash-course-site/**

This repository hosts the **published static site** — a single self-contained `index.html` served via GitHub Pages. It is a generated artifact; the course content and build tooling live in a separate source repository.

## What's inside

- **11 modules · ~98 sub-modules** covering banking foundations through implementation pitfalls
- **Module quizzes** with single / multi / boolean questions and a 70% pass threshold; revisiting a quiz shows your best/last/attempts with a retake option
- **Final assessment** gated behind passing all 11 module quizzes
- **Flashcard review** of vocabulary terms, with a selectable card count
- **Client-side search** across all content (`/` or `Ctrl/Cmd-K`)
- **Light / dark** editorial reading theme
- **Progress export / import** as a JSON file

## Using it

Just open the live site — no install, no sign-up. Your progress (completed lessons, quiz scores, theme) is saved **locally in your browser** via `localStorage`. Clearing site data resets it.

- **No accounts, no backend, no tracking.** Everything runs in your browser.
- Works offline after the first load. Web fonts load from the Google Fonts CDN with system fallbacks, so it stays legible even if those are blocked.

## How this site is updated

The site is built from source (markdown content + a Node build that produces a single inlined `index.html`) and the resulting `index.html` is copied into this repository's root. GitHub Pages serves it from there.

## Tech

Vanilla JavaScript + a small reactive state layer, Tailwind CSS (compiled and inlined), Newsreader / Geist / JetBrains Mono typography. The entire app ships as one HTML file.

## License & disclaimer

Dedicated to the public domain under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). No rights reserved — anyone may use, copy, modify, and redistribute this material for any purpose, **no attribution required**.

Provided **as is**, with **no guarantee of accuracy or completeness** and **no liability** for any loss arising from its use. This is **educational content, not professional financial, legal, or investment advice** — banking rules and market details (especially for the UAE and Dubai) change over time, so verify against authoritative sources.
