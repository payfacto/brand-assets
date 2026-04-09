---
name: payfacto-brand-guidelines
description: "Use when creating any PayFacto-branded material, or when asked about PayFacto colors, fonts, logos, icons, photography, email signatures, or brand compliance."
license: CC-BY-4.0
---

# PayFacto Brand Guidelines

Official brand standards for PayFacto — North America's leading provider of payment solutions and technology to the hospitality industry. Recognized for expertise, flexibility, and quality of execution.

---

## Logo Assets (Always Available)

The BLACK-GOLD and WHITE-GOLD logos are **embedded in this skill as base64 PNG and inline SVG** — use them in any output without network access or filesystem paths. See the **Embedded Logo Assets** section near the bottom for the actual data.

- **HTML `<img>` tag:** `<img src="data:image/png;base64,[BASE64 BLOCK]" alt="PayFacto">`
- **Inline SVG:** paste the SVG block directly into HTML markup
- **Python (docx/pptx):** `io.BytesIO(base64.b64decode("[BASE64 BLOCK]"))` → pass to `add_picture()`

For icons or other logo variants, see **Asset Locations Reference**.

---

## Identity & Brand Voice

- **Tagline:** Expertise · Agility · Execution
- **Brand personality:** Elegant, powerful, trustworthy, modern — black signals elegance, gold represents luxury and power
- **Logo concept:** Straight lines with softly condensed curves — strength and flexibility; chip symbol represents electronic payment expertise and is formed from the capital letters P and F

---

## Colors

### Main Colors (authoritative from official PDF)

| Name           | Hex       | RGB           | CMYK                     | Usage                                                     |
| -------------- | --------- | ------------- | ------------------------ | --------------------------------------------------------- |
| **Black**      | `#000000` | 0, 0, 0       | 0-0-0-100                | Primary background, dark panels, typography on light      |
| **Gold**       | `#bc955c` | 188, 148, 91  | Pantone 465 / 9-29-66-24 | Primary brand accent — CTAs, headers, highlights, accents |
| **White**      | `#ffffff` | 255, 255, 255 | 0-0-0-0                  | Light backgrounds, text on dark                           |
| **Dark Grey**  | `#535353` | 83, 83, 83    | 0-0-0-70                 | Secondary text, supporting elements                       |
| **Beige**      | `#e4d2bb` | 228, 210, 187 | 9-15-27-5                | Subtle backgrounds, group headers                         |
| **Light Grey** | `#e6e6e6` | 230, 230, 230 | 25-20-20-2               | Light neutral backgrounds                                 |

**Key rule: PayFacto's dark is pure black `#000000` — never use navy blue as a substitute.**

### Complementary Colors

| Name       | Hex       | RGB          | CMYK      | Usage                |
| ---------- | --------- | ------------ | --------- | -------------------- |
| **Blue**   | `#5c83bc` | 92, 131, 188 | 69-44-5-0 | Complementary accent |
| **Green**  | `#5cbc95` | 92, 188, 149 | 64-0-52-0 | Complementary accent |
| **Purple** | `#955cbc` | 149, 92, 188 | 56-71-0-0 | Complementary accent |

> Note: `#bc955c` is the official web hex from the PDF. Some internal files may show `#bc945b` — the PDF value takes precedence.

---

## Typography

### Primary Typefaces (print / design)

Available on Adobe Typekit / Creative Cloud.

| Font                    | Weight  | Use                                        |
| ----------------------- | ------- | ------------------------------------------ |
| **Facto Bold**          | Bold    | Headings / H1 — titles and section headers |
| **Montserrat Regular**  | Regular | Body text / paragraphs                     |
| **Montserrat** (family) | Various | Full type system for designed materials    |

### Replacement Typefaces (email, Office, Outlook, signatures)

| Font                | Weight         | Use                                                   |
| ------------------- | -------------- | ----------------------------------------------------- |
| **Franklin Gothic** | Demi / Regular | Text, email signatures, Outlook — primary replacement |
| **Cambria Regular** | Regular        | Titles in email / Office contexts                     |

### Email Signature Specs (Franklin Gothic)

| Element | Style                                               |
| ------- | --------------------------------------------------- |
| Name    | Franklin Gothic Demi, 12pt, Bold, Gold (188/148/91) |
| Title   | 10pt, Regular, Black                                |
| Phone   | 10pt, Bold, Black                                   |
| Email   | 10pt, Regular, Black                                |

In Outlook: File → Options → Mail → Signatures

---

## Logo Usage

**Asset priority:**
1. **Embedded assets** (in this skill) — always works, no network or filesystem needed
2. **GitHub URLs** — when you need SVG or icon files not embedded here
3. **Local skill files** — only when offline

See **Asset Locations Reference** for GitHub URLs and local paths.

### Logo Rules

**Always:**

- Use chip + wordmark together — never the wordmark alone without the chip
- Use two-color version (BLACK-GOLD or WHITE-GOLD) as first preference on both light and dark backgrounds
- Surround logo with clear space equal to the upper-left dimension of the chip icon (minimum 0.25 inches / ~24px on all sides)
- Keep minimum logo size: 0.80" × 0.15" (77px × 14.5px)

**Never:**

- Remove the chip from the logo
- Distort or stretch the logo
- Place on a background that reduces readability
- Add shadows, glows, or any visual effects around or behind the logo
- Use only the text without the chip symbol

---

## Icons

Asset location: obtain the `PayFacto-Icon-Library/` folder from your brand admin — too large to bundle in the skill (640 files).

Available color variants: BLACK, BLACK-GOLD, WHITE, WHITE-GOLD

### Icon Rules

- Maximum size: **72px × 72px**
- Minimum clear space on all four sides: **0.25 inches**
- The chip symbol may be used standalone as a decorative graphic element
- The chip must never exceed the height of the letter "P" in the PayFacto wordmark
- Must follow brand color rules (use approved palette only)

### Icon Stroke Thickness

| Icon size     | Stroke |
| ------------- | ------ |
| 16px × 16px   | 0.45px |
| 32px × 32px   | 0.90px |
| 48px × 48px   | 1.42px |
| 72px × 72px   | 2.88px |
| 256px × 256px | 6.75px |

---

## Brand Lines & Textures (Decorative Motion Lines)

Diagonal lines are a core brand graphic element. Rules:

- **Angle:** Always 135 degrees
- **Pattern:** Three lines — center/medium line, then large line, then small line (left to right)

### Line Colors by Background

| Background | Line 1 (center/medium) | Line 2 (large) | Line 3 (small) |
| ---------- | ---------------------- | -------------- | -------------- |
| **Black**  | `#ffffff`              | `#bc955c`      | `#535353`      |
| **White**  | `#000000`              | `#bc955c`      | `#535353`      |
| **Gold**   | `#000000`              | `#ffffff`      | `#535353`      |

---

## Photography

### Style Direction

- Atmosphere, Interaction, Dynamic, Human
- Contemporary images with desaturated colors and reduced vibrance
- Chic and casual look
- Centered and close-up framing preferred

### Avoid

- Staged studio photo setups
- Photo montages with technology/techno-style illustrations

### Photo Treatment (when overlaying text or brand elements)

- **Color photo:** Apply black `#000000` overlay at **65% opacity**
- **Black & white photo:** Apply black `#000000` overlay at **75% opacity**

---

## Business Card Specs

| Property   | Value                                                             |
| ---------- | ----------------------------------------------------------------- |
| Dimensions | 3.5" × 2"                                                         |
| Material   | Matte black cardboard, 24pt                                       |
| Finish     | Metal matte gold + glossy white stamping + matt gold painted edge |
| Bleed      | 0.125 inches                                                      |

---

## Quick Reference Checklist

When creating any PayFacto-branded asset, verify:

- [ ] Gold used: `#bc955c` (not orange, not yellow, not a different gold)
- [ ] Dark background uses pure black `#000000` (not navy, not charcoal substitutes)
- [ ] Logo includes chip symbol — not wordmark-only
- [ ] Logo has 0.25" clear space on all sides
- [ ] Typography uses Facto Bold (H1) + Montserrat (body), or Franklin Gothic for digital/email
- [ ] Brand lines at 135° following the three-line pattern with correct colors per background
- [ ] Photos desaturated with black overlay (65% color / 75% B&W)
- [ ] Icons use brand colors and stay within 72×72px max

---

## Asset Locations Reference

### GitHub Repository (Public)

**Repository:** https://github.com/payfacto/brand-assets

#### Direct Raw Asset URLs

**Logo - BLACK-GOLD** (recommended for light backgrounds)

- PNG: https://github.com/payfacto/brand-assets/raw/main/PayFacto-Logo/PayFacto%20-%20Logo/PayFacto%20-%20Logo%20BLACK-GOLD/PayFacto%20-%20Logo%20BLACK-GOLD.png
- SVG: https://github.com/payfacto/brand-assets/raw/main/PayFacto-Logo/PayFacto%20-%20Logo/PayFacto%20-%20Logo%20BLACK-GOLD/PayFacto%20-%20Logo%20BLACK-GOLD.svg

**Logo - WHITE-GOLD** (recommended for dark backgrounds)

- PNG: https://github.com/payfacto/brand-assets/raw/main/PayFacto-Logo/PayFacto%20-%20Logo/PayFacto%20-%20Logo%20WHITE-GOLD/PayFacto%20-%20Logo%20WHITE-GOLD.png
- SVG: https://github.com/payfacto/brand-assets/raw/main/PayFacto-Logo/PayFacto%20-%20Logo/PayFacto%20-%20Logo%20WHITE-GOLD/PayFacto%20-%20Logo%20WHITE-GOLD.svg

**Chip - GOLD** (preferred standalone accent icon) 

- SVG: https://github.com/payfacto/brand-assets/raw/main/PayFacto-Chip/PayFacto%20-%20Chip%20GOLD/PayFacto%20-%20Chip%20GOLD.svg
- PNG: https://github.com/payfacto/brand-assets/raw/main/PayFacto-Chip/PayFacto%20-%20Chip%20GOLD/PayFacto%20-%20Chip%20GOLD.png

**Chip - BLACK** (standalone accent on light backgrounds)

- SVG: https://github.com/payfacto/brand-assets/raw/main/PayFacto-Chip/PayFacto%20-%20Chip%20BLACK/PayFacto%20-%20Chip%20BLACK.svg
- PNG: https://github.com/payfacto/brand-assets/raw/main/PayFacto-Chip/PayFacto%20-%20Chip%20BLACK/PayFacto%20-%20Chip%20BLACK.png

**Chip - WHITE** (standalone accent on dark backgrounds)

- SVG: https://github.com/payfacto/brand-assets/raw/main/PayFacto-Chip/PayFacto%20-%20Chip%20WHITE/PayFacto%20-%20Chip%20WHITE.svg
- PNG: https://github.com/payfacto/brand-assets/raw/main/PayFacto-Chip/PayFacto%20-%20Chip%20WHITE/PayFacto%20-%20Chip%20WHITE.png

#### Icons

##### BLACK-GOLD (light backgrounds, two-color)

**Agility** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Agility%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Agility%20BLACK-GOLD.svg)  
**All Users** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_All%20Users%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_All%20Users%20BLACK-GOLD.svg)  
**Ambition** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Ambition%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Ambition%20BLACK-GOLD.svg)  
**Android** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Android%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Android%20BLACK-GOLD.svg)  
**Apply Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Apply%20Settings%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Apply%20Settings%20BLACK-GOLD.svg)  
**Automation** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Automation%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Automation%20BLACK-GOLD.svg)  
**Batch File** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Batch%20File%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Batch%20File%20BLACK-GOLD.svg)  
**Battery** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Battery%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Battery%20BLACK-GOLD.svg)  
**Camera** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Camera%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Camera%20BLACK-GOLD.svg)  
**Care** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Care%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Care%20BLACK-GOLD.svg)  
**Career** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Career%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Career%20BLACK-GOLD.svg)  
**Cash Register** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Cash%20Register%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Cash%20Register%20BLACK-GOLD.svg)  
**Check** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Check%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Check%20BLACK-GOLD.svg)  
**Checklist** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Checklist%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Checklist%20BLACK-GOLD.svg)  
**Cloud Configuration** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Cloud%20Configuration%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Cloud%20Configuration%20BLACK-GOLD.svg)  
**Cloud POS Workstation** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Cloud%20POS%20Workstation%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Cloud%20POS%20Workstation%20BLACK-GOLD.svg)  
**Cloud Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Cloud%20Settings%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Cloud%20Settings%20BLACK-GOLD.svg)  
**Configurations** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Configurations%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Configurations%20BLACK-GOLD.svg)  
**Connectivity** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Connectivity%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Connectivity%20BLACK-GOLD.svg)  
**Connector** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Connector%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Connector%20BLACK-GOLD.svg)  
**Costumer Support** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Costumer%20Support%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Costumer%20Support%20BLACK-GOLD.svg)  
**Courage** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Courage%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Courage%20BLACK-GOLD.svg)  
**Dashboard** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Dashboard%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Dashboard%20BLACK-GOLD.svg)  
**Data Management** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Data%20Management%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Data%20Management%20BLACK-GOLD.svg)  
**Delivery Itinerary** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Delivery%20Itinerary%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Delivery%20Itinerary%20BLACK-GOLD.svg)  
**Devices** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Devices%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Devices%20BLACK-GOLD.svg)  
**Discount Tag** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Discount%20Tag%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Discount%20Tag%20BLACK-GOLD.svg)  
**FAQ** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_FAQ%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_FAQ%20BLACK-GOLD.svg)  
**Freebees** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Freebees%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Freebees%20BLACK-GOLD.svg)  
**Functions** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Functions%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Functions%20BLACK-GOLD.svg)  
**Gateway Solution** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Gateway%20Solution%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Gateway%20Solution%20BLACK-GOLD.svg)  
**Hosted Solution** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Hosted%20Solution%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Hosted%20Solution%20BLACK-GOLD.svg)  
**Laptop Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Laptop%20Settings%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Laptop%20Settings%20BLACK-GOLD.svg)  
**Launch** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Launch%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Launch%20BLACK-GOLD.svg)  
**Layers** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Layers%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Layers%20BLACK-GOLD.svg)  
**List Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_List%20Settings%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_List%20Settings%20BLACK-GOLD.svg)  
**Log In** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Log%20In%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Log%20In%20BLACK-GOLD.svg)  
**Maintenance** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Maintenance%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Maintenance%20BLACK-GOLD.svg)  
**Medal** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Medal%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Medal%20BLACK-GOLD.svg)  
**Merchant Form** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Merchant%20Form%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Merchant%20Form%20BLACK-GOLD.svg)  
**MEV Web** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_MEV%20Web%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_MEV%20Web%20BLACK-GOLD.svg)  
**Modern Workstation** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Modern%20Workstation%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Modern%20Workstation%20BLACK-GOLD.svg)  
**Money** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Money%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Money%20BLACK-GOLD.svg)  
**Network Security** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Network%20Security%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Network%20Security%20BLACK-GOLD.svg)  
**New Idea** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_New%20Idea%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_New%20Idea%20BLACK-GOLD.svg)  
**Online Payment** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Online%20Payment%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Online%20Payment%20BLACK-GOLD.svg)  
**Optimization** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Optimization%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Optimization%20BLACK-GOLD.svg)  
**Payment** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Payment%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Payment%20BLACK-GOLD.svg)  
**Picture** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Picture%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Picture%20BLACK-GOLD.svg)  
**POS Workstation** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_POS%20Workstation%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_POS%20Workstation%20BLACK-GOLD.svg)  
**Power User** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Power%20User%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Power%20User%20BLACK-GOLD.svg)  
**Printer** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Printer%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Printer%20BLACK-GOLD.svg)  
**Promotion Coupon** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Promotion%20Coupon%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Promotion%20Coupon%20BLACK-GOLD.svg)  
**QR Scan** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_QR%20Scan%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_QR%20Scan%20BLACK-GOLD.svg)  
**Quick Launch** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Quick%20Launch%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Quick%20Launch%20BLACK-GOLD.svg)  
**Risk Management** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Risk%20Management%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Risk%20Management%20BLACK-GOLD.svg)  
**Satisfaction** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Satisfaction%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Satisfaction%20BLACK-GOLD.svg)  
**Scalable** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Scalable%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Scalable%20BLACK-GOLD.svg)  
**Seamless payment** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Seamless%20payment%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Seamless%20payment%20BLACK-GOLD.svg)  
**Semi-Integreated Solution** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Semi-Integreated%20Solution%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Semi-Integreated%20Solution%20BLACK-GOLD.svg)  
**Send Check** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Send%20Check%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Send%20Check%20BLACK-GOLD.svg)  
**Server Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Server%20Settings%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Server%20Settings%20BLACK-GOLD.svg)  
**Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Settings%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Settings%20BLACK-GOLD.svg)  
**Shop** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Shop%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Shop%20BLACK-GOLD.svg)  
**Shopping bags** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Shopping%20bags%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Shopping%20bags%20BLACK-GOLD.svg)  
**SMS Smartphone** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_SMS%20Smartphone%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_SMS%20Smartphone%20BLACK-GOLD.svg)  
**Software Security** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Software%20Security%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Software%20Security%20BLACK-GOLD.svg)  
**Support** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Support%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Support%20BLACK-GOLD.svg)  
**Tasklist** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Tasklist%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Tasklist%20BLACK-GOLD.svg)  
**Terminal Payment** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Terminal%20Payment%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Terminal%20Payment%20BLACK-GOLD.svg)  
**Terminal Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Terminal%20Settings%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Terminal%20Settings%20BLACK-GOLD.svg)  
**Touch Screen** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Touch%20Screen%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Touch%20Screen%20BLACK-GOLD.svg)  
**Transfer Configuration** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Transfer%20Configuration%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Transfer%20Configuration%20BLACK-GOLD.svg)  
**Trust** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Trust%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Trust%20BLACK-GOLD.svg)  
**User Input** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_User%20Input%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_User%20Input%20BLACK-GOLD.svg)  
**User Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_User%20Settings%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_User%20Settings%20BLACK-GOLD.svg)  
**Users Management** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Users%20Management%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Users%20Management%20BLACK-GOLD.svg)  
**Virtual terminal** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Virtual%20terminal%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Virtual%20terminal%20BLACK-GOLD.svg)  
**Well-Being** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Well-Being%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Well-Being%20BLACK-GOLD.svg)  
**Workplace** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Workplace%20BLACK-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20BLACK-GOLD/ICON_Workplace%20BLACK-GOLD.svg)  


##### WHITE-GOLD (dark backgrounds, two-color)

**Agility** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Agility%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Agility%20WHITE-GOLD.svg)  
**All Users** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_All%20Users%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_All%20Users%20WHITE-GOLD.svg)  
**Ambition** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Ambition%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Ambition%20WHITE-GOLD.svg)  
**Android** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Android%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Android%20WHITE-GOLD.svg)  
**Apply Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Apply%20Settings%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Apply%20Settings%20WHITE-GOLD.svg)  
**Automation** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Automation%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Automation%20WHITE-GOLD.svg)  
**Batch File** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Batch%20File%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Batch%20File%20WHITE-GOLD.svg)  
**Battery** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Battery%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Battery%20WHITE-GOLD.svg)  
**Camera** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Camera%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Camera%20WHITE-GOLD.svg)  
**Care** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Care%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Care%20WHITE-GOLD.svg)  
**Career** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Career%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Career%20WHITE-GOLD.svg)  
**Cash Register** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Cash%20Register%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Cash%20Register%20WHITE-GOLD.svg)  
**Check** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Check%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Check%20WHITE-GOLD.svg)  
**Checklist** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Checklist%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Checklist%20WHITE-GOLD.svg)  
**Cloud Configuration** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Cloud%20Configuration%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Cloud%20Configuration%20WHITE-GOLD.svg)  
**Cloud POS Workstation** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Cloud%20POS%20Workstation%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Cloud%20POS%20Workstation%20WHITE-GOLD.svg)  
**Cloud Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Cloud%20Settings%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Cloud%20Settings%20WHITE-GOLD.svg)  
**Configurations** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Configurations%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Configurations%20WHITE-GOLD.svg)  
**Connectivity** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Connectivity%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Connectivity%20WHITE-GOLD.svg)  
**Connector** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Connector%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Connector%20WHITE-GOLD.svg)  
**Costumer Support** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Costumer%20Support%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Costumer%20Support%20WHITE-GOLD.svg)  
**Courage** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Courage%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Courage%20WHITE-GOLD.svg)  
**Dashboard** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Dashboard%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Dashboard%20WHITE-GOLD.svg)  
**Data Management** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Data%20Management%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Data%20Management%20WHITE-GOLD.svg)  
**Delivery Itinerary** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Delivery%20Itinerary%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Delivery%20Itinerary%20WHITE-GOLD.svg)  
**Devices** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Devices%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Devices%20WHITE-GOLD.svg)  
**Discount Tag** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Discount%20Tag%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Discount%20Tag%20WHITE-GOLD.svg)  
**FAQ** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_FAQ%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_FAQ%20WHITE-GOLD.svg)  
**Freebees** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Freebees%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Freebees%20WHITE-GOLD.svg)  
**Functions** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Functions%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Functions%20WHITE-GOLD.svg)  
**Gateway Solution** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Gateway%20Solution%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Gateway%20Solution%20WHITE-GOLD.svg)  
**Hosted Solution** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Hosted%20Solution%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Hosted%20Solution%20WHITE-GOLD.svg)  
**Laptop Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Laptop%20Settings%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Laptop%20Settings%20WHITE-GOLD.svg)  
**Launch** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Launch%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Launch%20WHITE-GOLD.svg)  
**Layers** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Layers%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Layers%20WHITE-GOLD.svg)  
**List Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_List%20Settings%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_List%20Settings%20WHITE-GOLD.svg)  
**Log In** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Log%20In%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Log%20In%20WHITE-GOLD.svg)  
**Maintenance** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Maintenance%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Maintenance%20WHITE-GOLD.svg)  
**Medal** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Medal%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Medal%20WHITE-GOLD.svg)  
**Merchant Form** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Merchant%20Form%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Merchant%20Form%20WHITE-GOLD.svg)  
**MEV Web** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_MEV%20Web%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_MEV%20Web%20WHITE-GOLD.svg)  
**Modern Workstation** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Modern%20Workstation%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Modern%20Workstation%20WHITE-GOLD.svg)  
**Money** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Money%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Money%20WHITE-GOLD.svg)  
**Network Security** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Network%20Security%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Network%20Security%20WHITE-GOLD.svg)  
**New Idea** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_New%20Idea%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_New%20Idea%20WHITE-GOLD.svg)  
**Online Payment** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Online%20Payment%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Online%20Payment%20WHITE-GOLD.svg)  
**Optimization** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Optimization%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Optimization%20WHITE-GOLD.svg)  
**Payment** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Payment%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Payment%20WHITE-GOLD.svg)  
**Picture** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Picture%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Picture%20WHITE-GOLD.svg)  
**POS Workstation** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_POS%20Workstation%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_POS%20Workstation%20WHITE-GOLD.svg)  
**Power User** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Power%20User%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Power%20User%20WHITE-GOLD.svg)  
**Printer** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Printer%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Printer%20WHITE-GOLD.svg)  
**Promotion Coupon** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Promotion%20Coupon%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Promotion%20Coupon%20WHITE-GOLD.svg)  
**QR Scan** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_QR%20Scan%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_QR%20Scan%20WHITE-GOLD.svg)  
**Quick Launch** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Quick%20Launch%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Quick%20Launch%20WHITE-GOLD.svg)  
**Risk Management** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Risk%20Management%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Risk%20Management%20WHITE-GOLD.svg)  
**Satisfaction** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Satisfaction%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Satisfaction%20WHITE-GOLD.svg)  
**Scalable** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Scalable%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Scalable%20WHITE-GOLD.svg)  
**Seamless payment** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Seamless%20payment%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Seamless%20payment%20WHITE-GOLD.svg)  
**Semi-Integreated Solution** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Semi-Integreated%20Solution%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Semi-Integreated%20Solution%20WHITE-GOLD.svg)  
**Send Check** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Send%20Check%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Send%20Check%20WHITE-GOLD.svg)  
**Server Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Server%20Settings%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Server%20Settings%20WHITE-GOLD.svg)  
**Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Settings%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Settings%20WHITE-GOLD.svg)  
**Shop** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Shop%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Shop%20WHITE-GOLD.svg)  
**Shopping bags** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Shopping%20bags%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Shopping%20bags%20WHITE-GOLD.svg)  
**SMS Smartphone** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_SMS%20Smartphone%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_SMS%20Smartphone%20WHITE-GOLD.svg)  
**Software Security** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Software%20Security%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Software%20Security%20WHITE-GOLD.svg)  
**Support** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Support%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Support%20WHITE-GOLD.svg)  
**Tasklist** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Tasklist%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Tasklist%20WHITE-GOLD.svg)  
**Terminal Payment** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Terminal%20Payment%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Terminal%20Payment%20WHITE-GOLD.svg)  
**Terminal Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Terminal%20Settings%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Terminal%20Settings%20WHITE-GOLD.svg)  
**Touch Screen** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Touch%20Screen%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Touch%20Screen%20WHITE-GOLD.svg)  
**Transfer Configuration** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Transfer%20Configuration%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Transfer%20Configuration%20WHITE-GOLD.svg)  
**Trust** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Trust%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Trust%20WHITE-GOLD.svg)  
**User Input** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_User%20Input%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_User%20Input%20WHITE-GOLD.svg)  
**User Settings** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_User%20Settings%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_User%20Settings%20WHITE-GOLD.svg)  
**Users Management** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Users%20Management%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Users%20Management%20WHITE-GOLD.svg)  
**Virtual terminal** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Virtual%20terminal%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Virtual%20terminal%20WHITE-GOLD.svg)  
**Well-Being** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Well-Being%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Well-Being%20WHITE-GOLD.svg)  
**Workplace** — [PNG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Workplace%20WHITE-GOLD.png) · [SVG](https://github.com/payfacto/brand-assets/raw/main/PayFacto-Icon-Library/PayFacto%20-%20Icon%20Library%20WHITE-GOLD/ICON_Workplace%20WHITE-GOLD.svg)  


### Local Assets

Assets are bundled inside this skill folder. The skill system exposes the base directory at runtime — resolve paths relative to it.

#### Versions Available

| Variant                | File location                                 | Use on                                 |
| ---------------------- | --------------------------------------------- | -------------------------------------- |
| BLACK-GOLD (two-color) | `PayFacto - Logo/PayFacto - Logo BLACK-GOLD/` | White or light backgrounds             |
| WHITE-GOLD (two-color) | `PayFacto - Logo/PayFacto - Logo WHITE-GOLD/` | Dark/black backgrounds                 |
| BLACK (single)         | `PayFacto - Logo/PayFacto - Logo BLACK/`      | Light neutral backgrounds              |
| WHITE (single)         | `PayFacto - Logo/PayFacto - Logo WHITE/`      | Dark backgrounds when gold unavailable |
| Chip BLACK             | `PayFacto - Chip/PayFacto - Chip BLACK/`      | Standalone chip graphic on light       |
| Chip GOLD              | `PayFacto - Chip/PayFacto - Chip GOLD/`       | Standalone chip graphic accent         |
| Chip WHITE             | `PayFacto - Chip/PayFacto - Chip WHITE/`      | Standalone chip graphic on dark        |

Formats available per variant: `.eps`, `.jpg`, `.png`, `.svg`

```
[skill folder]/assets/
├── logos/
│   ├── PayFacto - Logo/
│   │   ├── PayFacto - Logo BLACK-GOLD/     ← use on light bg (.eps .jpg .png .svg)
│   │   ├── PayFacto - Logo WHITE-GOLD/     ← use on dark bg  (.eps .jpg .png .svg)
│   │   ├── PayFacto - Logo BLACK/
│   │   └── PayFacto - Logo WHITE/
│   └── PayFacto - Chip/
│       ├── PayFacto - Chip BLACK/
│       ├── PayFacto - Chip GOLD/
│       └── PayFacto - Chip WHITE/
└── icons/   ← NOT bundled (640 files); request from brand admin
    ├── PayFacto - Icon Library BLACK/
    ├── PayFacto - Icon Library BLACK-GOLD/
    ├── PayFacto - Icon Library WHITE/
    └── PayFacto - Icon Library WHITE-GOLD/
```

## Slide Deck / Powerpoint PPTX Layout Conventions

### Dark slides (title, section dividers, thank you)
- Background: Black `#000000`
- Left vertical stripe: Gold `#bc955c`, ~0.22" wide
- Right decorative panel: Dark Grey `#535353`
- Right inset panel: Dark Grey `#535353`
- Bottom bar: Gold `#bc955c`, ~0.14" tall
- Logo: White+gold version, top-left or top-right

### Light slides (roadmap tables, pipeline, Gantt)
- Background: Light Grey `#e6e6e6`
- Header bar: Black `#000000`, ~0.80" tall
- Left stripe: Gold `#bc955c`, ~0.14" wide
- Footer bar: Gold `#bc955c`, ~0.10" tall
- Logo: White+gold version in header, top-right
- Alternating rows: White `#ffffff` / Beige `#e4d2bb`
- Table column headers: Black background, Gold text

### Progress bars
- Track: Light Grey `#e6e6e6`
- In-progress fill: Gold `#bc955c`
- Complete fill: Green `#5cbc95`

### Status badges
| Status | Text color | Background |
|--------|-----------|------------|
| In Progress | `#bc955c` (Gold) | `#e4d2bb` |
| Done / Complete | `#5cbc95` (Green) | `#e4d2bb` |
| Pending | `#535353` (Dark Grey) | `#e6e6e6` |
| On Hold | `#535353` (Dark Grey) | `#e6e6e6` |
| Discovery | `#535353` (Dark Grey) | `#e6e6e6` |

### Confidentiality Footer
Add to title slides: **"STRICTLY PRIVATE AND CONFIDENTIAL"**
Style: 8.5pt, color `#e6e6e6` (Light Grey)

---

## Embedded Logo Assets

These assets are embedded directly so you can use them in any output without filesystem access.

**Usage rules:**
- Use BLACK-GOLD on light/white backgrounds
- Use WHITE-GOLD on dark/colored backgrounds
- For inline HTML: use the raw SVG block (scales perfectly, no external request)
- For HTML `<img>` tags: `<img src="data:image/png;base64,[BASE64 BLOCK]" alt="PayFacto">`
- For Office docs via Python (python-docx, python-pptx, openpyxl):
  ```python
  import base64, io
  img_bytes = io.BytesIO(base64.b64decode("[BASE64 BLOCK]"))
  # pass img_bytes to document.add_picture() / slide.shapes.add_picture()
  ```
- When in doubt: use the PNG base64 — it works everywhere.

---

### BLACK-GOLD Logo — SVG (inline HTML, light backgrounds)

Paste directly into HTML markup between your content. Scalable, no external request.

```svg
<?xml version="1.0" encoding="UTF-8"?><svg id="Calque_1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 150"><defs><style>.cls-1{fill:#bc955c;}.cls-1,.cls-2{stroke-width:0px;}</style></defs><path class="cls-2" d="m246.23,47.55c0,24.34-13.57,32.75-39.13,32.79h-13.68v37.95h-22.34V14.7h36.02c25.46,0,39.13,8.5,39.13,32.85Zm-22.58.09c0-12.09-4.91-15.25-18.64-15.25h-11.57v30.22h11.57c13.83-.01,18.64-3.08,18.64-14.97Z"/><path class="cls-2" d="m325.61,65.15v53.15h-19.25l-.55-6.44c-8.86,5.25-16.97,8.21-25.89,8.21-12.72,0-23.81-5.92-23.81-25.21,0-20.6,12.56-25.12,31.56-25.51,6.92-.09,9.87-.05,17.55-.03v-3.66c-.04-8.46-5.22-10.33-13.83-10.33-8.11,0-19.05,1.43-28.64,3.24v-17.23c9.62-1.78,19.64-3.27,28.89-3.27,18.34,0,33.96,5.78,33.96,27.06Zm-38.38,38.18c5.77,0,11.3-1.73,18-5.17v-15.79h-15.06c-9.73.03-13.3,1.75-13.29,10.33,0,8.14,3.32,10.63,10.35,10.63Z"/><path class="cls-2" d="m414.34,39.86l-33.13,91.32c-3.66,10.1-12.38,16.27-23.16,16.27h-10.19v-15.78h6.33c5.41,0,9.12-3.16,10.63-7.79l3.37-10.03-33.18-74h21.71l20.4,47.42,15.93-47.42h21.28Z"/><path class="cls-1" d="m450.73,33.39v24.2h38.68v18.7h-38.68s0,42.01,0,42.01h-22.34V14.7h63.39v18.7h-41.05Z"/><path class="cls-1" d="m571.38,65.15v53.15h-19.25l-.55-6.44c-8.86,5.25-16.97,8.21-25.89,8.21-12.72,0-23.8-5.92-23.8-25.21,0-20.6,12.56-25.12,31.55-25.51,6.92-.09,9.88-.05,17.55-.03v-3.66c-.04-8.46-5.22-10.33-13.83-10.33-8.11,0-19.04,1.43-28.64,3.24v-17.23c9.62-1.78,19.64-3.27,28.89-3.27,18.34,0,33.96,5.78,33.96,27.06Zm-38.37,38.18c5.77,0,11.29-1.73,17.99-5.17v-15.79h-15.06c-9.72.03-13.29,1.75-13.29,10.33,0,8.14,3.32,10.63,10.36,10.63Z"/><path class="cls-1" d="m649.12,40.83l.07,17.51c-7.35-1.65-13.94-2.56-20.11-2.56-15.72,0-20.34,6.34-20.34,23.31s4.56,23.31,20.34,23.31c6.16,0,12.73-.92,20.36-2.64l.07,17.5c-7.57,1.65-15.42,2.82-23.25,2.82-28.87,0-38.45-15.05-38.45-40.99s9.65-40.99,38.25-40.99c7.18,0,14.54,1.05,23.06,2.73Z"/><path class="cls-1" d="m707.86,103v16.44c-3.81.37-7.85.64-11.07.64-14.23,0-24.46-4.93-24.46-20.58v-44.14h-11.49v-15.49h11.49v-18.51h20.41v18.52h15.11v15.48h-15.11s0,39.3,0,39.3c0,5.77,2.65,8.64,9.44,8.66,1.91,0,3.27-.16,5.69-.3Z"/><path class="cls-1" d="m798,79.09c0,26.04-9.16,40.99-38.18,40.99s-38.17-14.96-38.17-40.99,9.16-40.99,38.17-40.99,38.18,14.96,38.18,40.99Zm-55.48,0c0,16.72,3.96,23.23,17.3,23.23s17.3-6.51,17.3-23.23-3.96-23.31-17.3-23.31-17.3,6.52-17.3,23.31Z"/><path class="cls-1" d="m126.06,2.55H20.48C10.29,2.55,2,10.84,2,21.03v87.78c0,10.19,8.29,18.48,18.48,18.48h105.58c10.19,0,18.48-8.29,18.48-18.48V21.03c0-10.19-8.29-18.48-18.48-18.48Zm0,11.1c4.07,0,7.38,3.31,7.38,7.38v19.4h-32.72v-.09h-.42c-1.45-10.67-6.88-19.98-14.06-26.7h39.82Zm-25.34,37.88h32.72v26.79h-32.72v-26.79ZM20.48,13.65h40.62c12.93,0,28.53,14.42,28.53,32.33s-15.61,32.34-28.53,32.34H13.1V21.03c0-4.07,3.31-7.38,7.38-7.38Zm-7.38,95.16v-19.4h48c9.93,0,20.71-5.6,28.53-14.61v41.39H20.48c-4.07,0-7.38-3.31-7.38-7.38Zm112.97,7.38h-25.34v-26.78h32.72v19.4c0,4.07-3.31,7.38-7.38,7.38Z"/></svg>
```

---

### BLACK-GOLD Logo — PNG Base64 (Office docs & img tags, light backgrounds)

Use as `<img src="data:image/png;base64,[below]">` or decode to bytes for python-docx/python-pptx.

```
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
```

---

### WHITE-GOLD Logo — SVG (inline HTML, dark backgrounds)

Paste directly into HTML markup. Use on dark/colored backgrounds.

```svg
<?xml version="1.0" encoding="UTF-8"?><svg id="Calque_1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 150"><defs><style>.cls-1{fill:#bc955c;}.cls-1,.cls-2{stroke-width:0px;}.cls-2{fill:#fff;}</style></defs><path class="cls-2" d="m246.23,47.55c0,24.34-13.57,32.75-39.13,32.79h-13.68v37.95h-22.34V14.7h36.02c25.46,0,39.13,8.5,39.13,32.85Zm-22.58.09c0-12.09-4.91-15.25-18.64-15.25h-11.57v30.22h11.57c13.83-.01,18.64-3.08,18.64-14.97Z"/><path class="cls-2" d="m325.61,65.15v53.15h-19.25l-.55-6.44c-8.86,5.25-16.97,8.21-25.89,8.21-12.72,0-23.81-5.92-23.81-25.21,0-20.6,12.56-25.12,31.56-25.51,6.92-.09,9.87-.05,17.55-.03v-3.66c-.04-8.46-5.22-10.33-13.83-10.33-8.11,0-19.05,1.43-28.64,3.24v-17.23c9.62-1.78,19.64-3.27,28.89-3.27,18.34,0,33.96,5.78,33.96,27.06Zm-38.38,38.18c5.77,0,11.3-1.73,18-5.17v-15.79h-15.06c-9.73.03-13.3,1.75-13.29,10.33,0,8.14,3.32,10.63,10.35,10.63Z"/><path class="cls-2" d="m414.34,39.86l-33.13,91.32c-3.66,10.1-12.38,16.27-23.16,16.27h-10.19v-15.78h6.33c5.41,0,9.12-3.16,10.63-7.79l3.37-10.03-33.18-74h21.71l20.4,47.42,15.93-47.42h21.28Z"/><path class="cls-1" d="m450.73,33.39v24.2h38.68v18.7h-38.68s0,42.01,0,42.01h-22.34V14.7h63.39v18.7h-41.05Z"/><path class="cls-1" d="m571.38,65.15v53.15h-19.25l-.55-6.44c-8.86,5.25-16.97,8.21-25.89,8.21-12.72,0-23.8-5.92-23.8-25.21,0-20.6,12.56-25.12,31.55-25.51,6.92-.09,9.88-.05,17.55-.03v-3.66c-.04-8.46-5.22-10.33-13.83-10.33-8.11,0-19.04,1.43-28.64,3.24v-17.23c9.62-1.78,19.64-3.27,28.89-3.27,18.34,0,33.96,5.78,33.96,27.06Zm-38.37,38.18c5.77,0,11.29-1.73,17.99-5.17v-15.79h-15.06c-9.72.03-13.29,1.75-13.29,10.33,0,8.14,3.32,10.63,10.36,10.63Z"/><path class="cls-1" d="m649.12,40.83l.07,17.51c-7.35-1.65-13.94-2.56-20.11-2.56-15.72,0-20.34,6.34-20.34,23.31s4.56,23.31,20.34,23.31c6.16,0,12.73-.92,20.36-2.64l.07,17.5c-7.57,1.65-15.42,2.82-23.25,2.82-28.87,0-38.45-15.05-38.45-40.99s9.65-40.99,38.25-40.99c7.18,0,14.54,1.05,23.06,2.73Z"/><path class="cls-1" d="m707.86,103v16.44c-3.81.37-7.85.64-11.07.64-14.23,0-24.46-4.93-24.46-20.58v-44.14h-11.49v-15.49h11.49v-18.51h20.41v18.52h15.11v15.48h-15.11s0,39.3,0,39.3c0,5.77,2.65,8.64,9.44,8.66,1.91,0,3.27-.16,5.69-.3Z"/><path class="cls-1" d="m798,79.09c0,26.04-9.16,40.99-38.18,40.99s-38.17-14.96-38.17-40.99,9.16-40.99,38.17-40.99,38.18,14.96,38.18,40.99Zm-55.48,0c0,16.72,3.96,23.23,17.3,23.23s17.3-6.51,17.3-23.23-3.96-23.31-17.3-23.31-17.3,6.52-17.3,23.31Z"/><path class="cls-1" d="m126.06,2.55H20.48C10.29,2.55,2,10.84,2,21.03v87.78c0,10.19,8.29,18.48,18.48,18.48h105.58c10.19,0,18.48-8.29,18.48-18.48V21.03c0-10.19-8.29-18.48-18.48-18.48Zm0,11.1c4.07,0,7.38,3.31,7.38,7.38v19.4h-32.72v-.09h-.42c-1.45-10.67-6.88-19.98-14.06-26.7h39.82Zm-25.34,37.88h32.72v26.79h-32.72v-26.79ZM20.48,13.65h40.62c12.93,0,28.53,14.42,28.53,32.33s-15.61,32.34-28.53,32.34H13.1V21.03c0-4.07,3.31-7.38,7.38-7.38Zm-7.38,95.16v-19.4h48c9.93,0,20.71-5.6,28.53-14.61v41.39H20.48c-4.07,0-7.38-3.31-7.38-7.38Zm112.97,7.38h-25.34v-26.78h32.72v19.4c0,4.07-3.31,7.38-7.38,7.38Z"/></svg>
```

---

### WHITE-GOLD Logo — PNG Base64 (Office docs & img tags, dark backgrounds)

Use as `<img src="data:image/png;base64,[below]">` or decode to bytes for python-docx/python-pptx.

```
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
```

