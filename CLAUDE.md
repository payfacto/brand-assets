# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is the **PayFacto Brand Assets** repository — a static asset store containing official logos, icons, and brand reference materials for PayFacto (North America's payment solutions provider for the hospitality industry).

There are no build steps, tests, or code to run. This repo is a source of truth for brand assets and guidelines.

## Structure

- `PayFacto-Logo/` — Full logo and chip symbol in four color variants (BLACK, BLACK-GOLD, WHITE, WHITE-GOLD), each available as `.eps`, `.jpg`, `.png`, `.svg`
- `PayFacto-Icon-Library/` — 80 icons × 2 color variants (BLACK-GOLD, WHITE-GOLD) as `.png` and `.svg`
- `SKILL.md` — Machine-readable brand guidelines skill (used by Claude Code's skill system as `payfacto-brand-guidelines`)
- `README.md` — Human-readable overview with color palette, typography, and logo rules
- `official brand-guideline-2021-v2_compressed.pdf` — Authoritative source (May 2021 PDF)

## Brand Rules (Critical)

When generating any PayFacto-branded output, apply these non-negotiable rules:

**Colors**
- Black: `#000000` — never substitute navy blue
- Gold: `#bc955c` (PDF-authoritative; some files show `#bc945b` — use `#bc955c`)
- White: `#ffffff`
- Dark Grey: `#535353`, Beige: `#e4d2bb`, Light Grey: `#e6e6e6`

**Logo**
- Always chip + wordmark together — never wordmark alone
- Prefer two-color (BLACK-GOLD on light, WHITE-GOLD on dark)
- Minimum clear space: 0.25" / ~24px on all sides
- Minimum size: 0.80" × 0.15" (77px × 14.5px)
- Never distort, recolor, add effects, or remove the chip

**Icons**
- Maximum display size: 72px × 72px
- Use approved palette only (BLACK-GOLD or WHITE-GOLD variants)

**Typography**
- Design/print: Facto Bold (headings), Montserrat Regular (body)
- Email/Office: Cambria Regular (titles), Franklin Gothic Demi/Regular (body)

**Decorative lines:** Always 135° angle; pattern is center/medium → large → small

## Skill Integration

The `SKILL.md` file is registered as the `payfacto-brand-guidelines` skill. When creating branded materials, invoke this skill — it contains the complete authoritative ruleset including photo treatment, business card specs, and email signature specs.

## Asset Embedding

To embed logos in HTML/email: base64-encode the PNG and use a data URI. Prefer local files over remote URLs.
