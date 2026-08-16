# AFRP Platform — Design Prototypes

Clickable design prototypes for the American Federation of Ramallah, Palestine
member platform. Everything here is a **design artefact**: the by-law citations
are real (2009/2012 AFRP Constitution & By-Laws, 2013 ARFECF By-Laws, 2015
Scholarship Fund policy, 2009 Convention Contract); the people, clubs' counts
and money figures are fictional demo data.

## Start here

**[docs/index.html](docs/index.html)** — the delivery hub. **[docs/prototype.html](docs/prototype.html)** — the integrated prototype: 61 screens across four
lenses (Member · Club · Program · Federation), with live demonstrations of the
rules-as-data design: bylaw toggles, the weighted-delegation calculator, the
electronic ballot flow, versioned dues schedules, and the abstention flip.

Open it on any phone or laptop browser. It is one self-contained file — no
build, no server, no network calls.

## The full set

| File | What it is |
|---|---|
|  `prototype.html` | **Integrated clickable prototype** — the current design, all modules |
| `AFRP-Unified-Member.html` | Member experience, 21 static screens following one member for one day |
| `AFRP-Unified-Operations.html` | Staff operations, 21 static screens grouped by lens |
| `AFRP-Ruleset-Workbench.html` | The bylaw drafting workbench — divergence reports against real history |
| `AFRP-Governance-Finance-Desktop.html` | Earlier governance & finance mockup |
| `AFRP-Governance-Mobile.html` | Earlier governance mockup, mobile |
| `AFRP-Alumni-Desktop.html` / `-Mobile.html` | Scholarship alumni & recruiting |
| `AFRP-Desktop-v2.html` / `AFRP-Mobile-v2.html` | Earlier full-platform mockups |
| `AFRP-Portal-Screens.html` / `AFRP-Portal-Build-Spec.html` | First-generation portal screens |
| `AFRP-Design-System-v2.css` | The design system every mockup inlines byte-for-byte |

The specifications and working backend prototype live in the companion
repository (`afrp-platform`).

## Publishing
GitHub Pages: Settings → Pages → Branch `main`, Folder `/docs`.
Live at: https://davidsaah.github.io/afrp-mockups/

**On the public bylaws question:** the prototypes quote real by-law text from
the 2009/2012 Constitution & By-Laws, the 2013 ARFECF By-Laws, and the 2015
Scholarship Fund policy, and this repo is public — stated plainly on the hub
page. Internal planning documents (bylaws reconciliation, electronic voting
deliberation, and the rest) are deliberately NOT in this repo; they live in the
private afrp-platform repository.
