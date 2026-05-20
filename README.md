# Filtrona — Lunch & Discussion for AI (v2)

**Session:** 19 May 2026 · Singapore · 40 minutes
**Owner:** Manfei Qi · IT Business Analyst

This is the full delivery pack for Filtrona's first internal **Lunch & Discussion for AI** session: deck, speaker script, audience handout, Mentimeter setup, Microsoft Forms questions, presenter checklist, and resource page.

---

## What's in the pack

```
filtrona-ai-lunch-v2/
├── index.html                          ← The slide deck (open in any modern browser)
├── README.md                           ← This file
├── assets/
│   └── filtrona-logo-placeholder.svg   ← Replace with the official Filtrona logo
└── docs/
    ├── speaker_script.md               ← Slide-by-slide 40-minute script
    ├── audience_handout.md             ← Take-home reference for attendees
    ├── mentimeter_setup.md             ← The 4 Menti slides to publish
    ├── use_case_form_questions.md      ← NEW — Microsoft Forms for "Share your use case"
    ├── ai_resources_page.md            ← Long-form resource page for AI@Filtrona hub
    ├── presenter_checklist.md          ← Pre-, during-, post-session checklist
    └── github_deployment_guide.md      ← How to publish the deck on GitHub Pages
```

---

## What's new vs v1

| Area | v1 | v2 |
|---|---|---|
| Prompt framework | CRAFT (5 elements but listed 6) | **CRAFT-V** — 6 elements, spells out correctly, **V = Verify** as a built-in habit |
| Run-of-show | Misaligned with slide assignments | Realigned slide-by-slide |
| Approved-vs-personal | One mixed table | **Two separate tables, two headers, security principle banner across** |
| Data quiz | Weak explanation | Now anchored to "classification follows content, not metadata" |
| Manufacturing context | Light | Operations, HSE, Supply chain expanded; new Code & Data slide for MES / scripts / DAX users |
| Power Automate | Generic | Concrete **standard-connector** templates, no premium connector recommendations |
| Workflow examples | Vague | General reusable workflow patterns across reporting, approvals, visitor logs and AI@Filtrona hub tiles |
| Copilot tiers | Conflated free and paid | **Simplified three-level spectrum**: safe default, work context, governed scale. Details stay in resources. |
| AI@Filtrona | Mentioned | Slide 14 dedicated; Slide 21 connects to the new **Share your use case** Form |
| Visuals | Some screenshots reused from SharePoint | **Custom dynamic SVG icon library** — ~25 abstract icons, no screenshot reuse |
| Typography | Calibri / system sans | Fraunces (display serif) + DM Sans (body) — retained, enlarged for big-room readability |
| Spacing & dynamics | Tight | Lighter spacing, larger type, stronger but still modern background color, and subtle slide-entry motion |
| Facts | Some claims unverified | Every Copilot / license / connector statement sourced to Microsoft Learn (May 2026) |

---

## The deck — controls

| Key | Action |
|---|---|
| **→** / **Space** / **PgDn** | Next slide |
| **←** / **PgUp** | Previous slide |
| **Home** / **End** | First / last slide |
| **N** | Show / hide speaker notes |
| **F** | Toggle browser fullscreen |
| **T** | Start / pause the 40-minute countdown |
| **M** | Toggle subtle background drone (off by default — careful in hybrid calls) |

A small button row in the bottom-right exposes Notes / Timer / Sound / Fullscreen for mouse use.

---

## Design notes

- **Type pair:** Fraunces (variable display serif, soft optical size) for headlines; DM Sans for body; JetBrains Mono for code and numbers. Loaded from Google Fonts; falls back to system fonts if Google is blocked.
- **Filtrona palette:** red `#d70a26`, blue `#068fd3`, green `#8abd25`, gold `#fab70c`, ice `#eaf3fb`. Used as tints and accents, not solid backgrounds, to keep the deck feeling light.
- **Atmosphere:** richer soft radial gradients, subtle mesh texture, and light object-entry animations. Still bright and projector-safe; no dark cyberpunk background.
- **Icons:** custom SVG symbol library defined once in `<defs>` and referenced via `<use>`. ~25 icons covering Chat, Mail, Doc, Grid, Slides, Team, Bolt, Video, Shield, Lock, Spark, Factory, Gear, Chart, Check, Alert, Arrow, Search, Work, Code, Form, Approve, Bell, Music, etc. None of them reproduce Microsoft product logos verbatim — they're abstract concept icons paired with text labels.
- **Print:** controls and notes are hidden in print CSS; each slide breaks to a new page.

---

## Fact-verification

Detailed Microsoft tool, licensing, connector and entitlement notes were cross-checked against Microsoft Learn or `microsoft.com` product pages in May 2026. The relevant pages:

- `learn.microsoft.com/en-us/copilot/microsoft-365/microsoft-365-copilot-licensing`
- `learn.microsoft.com/en-us/microsoft-copilot-studio/billing-licensing`
- `learn.microsoft.com/en-us/microsoft-copilot-studio/requirements-licensing-subscriptions`
- `learn.microsoft.com/en-us/power-platform/admin/power-automate-licensing/faqs`
- `learn.microsoft.com/en-us/connectors/connector-reference/connector-reference-standard-connectors`
- `learn.microsoft.com/en-us/ai-builder/credit-management`
- `microsoft.com/en-us/microsoft-365-copilot/pricing`

Where Microsoft updates a feature, **update this pack** rather than letting drift accumulate.

---

## Before the session — 5-minute version of the checklist

1. Edit `CONFIG` at the bottom of `index.html` — replace placeholder URLs (Menti, Forms, SharePoint, Teams, logo)
2. Replace `assets/filtrona-logo-placeholder.svg` with the official Filtrona logo
3. Publish the four Mentimeter slides per `docs/mentimeter_setup.md`
4. Publish the Microsoft Form per `docs/use_case_form_questions.md` and replace the **"Coming Soon"** tile on AI@Filtrona
5. Test the URL from a phone on a non-corporate network
6. Keep a local copy as Plan B in case the venue blocks GitHub Pages

Full pre-session, day-of, and post-session checklists are in `docs/presenter_checklist.md`.

---

## License / use

Internal Filtrona use only. Replace the placeholder logo with the official asset before sharing externally.

---

*Built for Manfei Qi · 19 May 2026.*
