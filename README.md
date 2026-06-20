# Red, Blue, & Purple Team Operator's Bookshelf

A skill-first reading roadmap for three paths into cybersecurity: **Red Team Pentester**, **Blue Team Security Expert**, and **Purple Team Cybersecurity Expert** — including a dedicated track for AI security.

This isn't a certification reading list. Every book is chosen for what it teaches you to *do*, not what it helps you pass. Exam crams, "for dummies" titles, and duplicate cert guides are deliberately left out.

**[→ View the live roadmap](#)**
*(replace this link once GitHub Pages is enabled — see below)*

---

## What this is

A single self-contained HTML page with three switchable tracks:

- **Red Team** — offense, exploitation, and adversary emulation. Foundations → scripting → core hacking → API exploitation → advanced red teaming → OSINT/social engineering → AI red teaming.
- **Blue Team** — detection, response, and forensics. Foundations → scripting & automation → detection/SOC → incident response → digital forensics → AI security.
- **Purple Team** — the fusion role that validates red findings against blue detections. Shared foundation → threat-informed defense → adversary emulation → application-layer fusion → AI security from both sides.

Each track is organized into numbered, collapsible phases. Each phase is a skill, not just a topic — and every book entry includes a one-line note on *why* it's there, plus a badge:

- 🟥 **core** — read this, no substitute
- 🟪 **AI security** — securing or attacking AI/ML systems specifically
- ⬜ **optional** — valuable, but skippable if you're short on time

## Why this exists

Most "best cybersecurity books" lists are either:
1. Built around certification syllabuses, or
2. A wall of 80+ titles with no order, no reasoning, and no sense of what's actually load-bearing.

This roadmap strips both problems out. It's built from a real personal library, filtered down to the books that build a transferable skill, and sequenced in the order you'd actually want to read them.

## Using it

Just open `index.html` in a browser — no build step, no dependencies beyond two Google Fonts (which degrade gracefully to system fonts if blocked).

To host it for free on GitHub Pages:

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — your roadmap will be live at `https://<your-username>.github.io/operators-bookshelf/` within a minute or two.

## Contributing

Found a better book, a broken link, or a phase that's missing a skill? Open an issue or a pull request. Suggested edits should include:

- the book title and edition,
- which track and phase it belongs in,
- and a one-line reason it earns a spot (what skill it builds, not just "it's good").

## Disclaimer

This list is curated by a learner, for learners. It reflects one opinionated path through the material, not an industry standard. Pair every book with a lab, a CTF, or a home range — reading alone won't make you an operator.

## License

This roadmap (content and code) is shared under the [MIT License](LICENSE). Book titles and authors remain the property of their respective publishers; this repo only links to and discusses them.
