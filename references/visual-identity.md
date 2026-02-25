# Labotech Visual Identity — Full Reference

Source: Manual de Identidad Visual (official brand manual PDF).

## Table of Contents

- [Logo Construction](#logo-construction)
- [Logo Components](#logo-components)
- [Logo Variations & Restrictions](#logo-variations--restrictions)
- [Color System](#color-system)
- [Typography System](#typography-system)
- [Photography & Imagery](#photography--imagery)

---

## Logo Construction

The logo elements are built on a modular grid called "cuadricula". Each module is called **X** (a perfect square).

### Proportions
- **Full imagotipo:** 25X wide x 6X tall
- **Isotipo (icon):** square proportion (can be used independently)
- **Separation** between isotipo and typography: 2X units
- **Clear space:** minimum 1X on all sides (applies to both full mark and standalone isotipo)

### Grid Detail

The PDF shows dimensional annotations on the logo construction grid:
- Values visible: 11x, 8x, 1x, 3x, 2.5x
- These annotate the isotipo and typography proportions within the grid
- **Note:** Exact dimension-to-element mapping requires visual inspection of the original PDF (page 3). Refer to the manual PDF directly for precise grid interpretation.

### Minimum Sizes
- **Print:** 3.5cm minimum width for full imagotipo
- **Digital:** 100px minimum width for full imagotipo
- **Below minimum:** use isotipo alone (both digital and print)

---

## Logo Components

The brand identity is an **imagotipo**: a unified mark combining:
1. **Isotipo** (icon) — the geometric mark on the left
2. **Custom typography** — "LABOTECH" set in a bespoke typeface

These complement each other and form a single visual unit. The isotipo can be used independently when space is limited.

---

## Logo Variations & Restrictions

### Allowed Usage (Correct)
- **Horizontal layout** — standard arrangement (isotipo left, text right)
- On white/light backgrounds with brand colors
- On dark backgrounds in negative/white version
- Single-color (monochrome) versions

### Prohibited Usage (Incorrect)
- **Stretching** (altering width independently)
- **Squishing** (altering height independently)
- **Rotating** the logo
- **Rearranging** component disposition (e.g., stacking isotipo on top of text)
- Applying **gradients or color blending** to the logo
- Using on **incorrect background colors** that reduce contrast
- Any modification to **morphological characteristics or reading direction**

---

## Color System

### Primary Palette

#### Green
| Property | Value |
|----------|-------|
| **Hex** | `#52B247` |
| **Pantone** | 361 CP |
| **CMYK** | C: 68.3% / M: 5.53% / Y: 81.68% / K: 0% |
| **RGB** | R: 82 / G: 178 / B: 71 |
| **HSB** | H: 113 / S: 60.11% / B: 69.8% |

#### Blue
| Property | Value |
|----------|-------|
| **Hex** | `#0072B1` |
| **Pantone** | 2196 CP / P 173-14 C |
| **CMYK** | C: 93% / M: 30% / Y: 5.23% / K: 0.65% |
| **RGB** | R: 0 / G: 114 / B: 177 |
| **HSB** | H: 201 / S: 100% / B: 69.41% |

#### Dark Gray
| Property | Value |
|----------|-------|
| **Hex** | `#595959` |
| **CMYK** | C: 0% / M: 0% / Y: 0% / K: 65% |
| **RGB** | R: 89 / G: 89 / B: 89 |
| **HSB** | H: 0 / S: 0 / B: 34.9% |

### Color Usage Rules

**Correct usage:**
- Flat/solid colors only
- Logo on color backgrounds (maintaining proper contrast)
- Single-color (monochrome) applications
- Negative (white) on dark backgrounds

**Incorrect usage:**
- Color combinations not in the palette
- Non-standard background pairings
- Dark-on-dark or low-contrast applications
- Gradient or color degradation on brand elements

Colors must be reproduced with fidelity. Variations that contribute to visual confusion or dispersion are not allowed.

### Extended Web Palette

Derived from the 3 official brand colors for web UI use:

#### Green Scale (from #52B247)
| Token | Hex | Usage |
|-------|-----|-------|
| green-50 | `#EDF7EC` | Success backgrounds, badges |
| green-100 | `#D4EDD2` | Hover backgrounds |
| green-200 | `#A9DBA5` | Success borders |
| green-400 | `#52B247` | **Brand base** — primary CTAs, accents |
| green-600 | `#3D8A35` | Hover on green base, active states |
| green-800 | `#214C1D` | Text on light green backgrounds |

#### Blue Scale (from #0072B1)
| Token | Hex | Usage |
|-------|-----|-------|
| blue-50 | `#E5F2FA` | Info backgrounds, cards |
| blue-100 | `#B3D9EF` | Hover backgrounds |
| blue-200 | `#80BFE4` | Borders, visited links |
| blue-400 | `#0072B1` | **Brand base** — links, headers, trust elements |
| blue-600 | `#005B8E` | Hover on blue base, active states |
| blue-800 | `#002D47` | Text on light blue backgrounds |

#### Neutral Scale (from #595959)
| Token | Hex | Usage |
|-------|-----|-------|
| neutral-50 | `#F8F9FA` | Page background, surface |
| neutral-100 | `#E8E8E8` | Borders, dividers |
| neutral-200 | `#BDBDBD` | Disabled text, placeholders |
| neutral-400 | `#595959` | **Brand base** — body text |
| neutral-600 | `#333333` | Headings, primary text |
| neutral-800 | `#1A1A1A` | Maximum contrast text |

#### Semantic Colors
| Token | Hex | Source |
|-------|-----|--------|
| success | `#52B247` | = brand green |
| info | `#0072B1` | = brand blue |
| warning | `#F59E0B` | Amber (proposed) |
| error | `#DC2626` | Red (proposed) |
| background | `#FFFFFF` | White |
| surface | `#F8F9FA` | = neutral-50 |

---

### Official Brand Typeface: Aller

The logotype uses a **custom typeface designed exclusively for the brand** (not available as a font file — it is built into the logo).

**Aller** is the official companion typeface for all brand communications (advertising, digital, print). The full family includes:

| Weight/Style | Original Usage |
|-------------|----------------|
| **Aller Regular** | Body text, general content |
| **Aller Light Italic** | Captions, subtle emphasis |
| **Aller Italic** | Inline emphasis |
| **Aller Bold** | Headings, strong emphasis |
| **Aller Bold Italic** | Strong inline emphasis |
| **Aller Display** | Hero text, display headings |

### Web Implementation: Nunito Sans

Since Aller is not widely available as a web font, **Nunito Sans** (Google Fonts, open source) is the approved web alternative. It matches Aller's humanist, rounded character.

| Nunito Sans Weight | CSS | Maps to Aller |
|-------------------|-----|---------------|
| Light (300) | `font-weight: 300` | Aller Light |
| Regular (400) | `font-weight: 400` | Aller Regular |
| SemiBold (600) | `font-weight: 600` | (no direct equivalent) |
| Bold (700) | `font-weight: 700` | Aller Bold |

**Font stack:** `'Nunito Sans', 'Aller', system-ui, sans-serif`

**Google Fonts import:**
```
https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,wght@0,300;0,400;0,600;0,700;1,400&display=swap
```

### Typography Rules
- Nunito Sans (or Aller if available) is the primary typeface for ALL brand communications
- May combine with other typefaces ONLY if visual harmony is maintained
- The logotype custom typeface must NOT be replicated or approximated in content — it is logo-only

---

## Iconography

The brand manual includes guidelines for iconographic style. When creating or selecting icons for the website:

- Maintain consistency with the clinical/scientific visual language
- Use simple, clean line icons that match the "minimal, clinical-tech" visual tone
- Prefer structured content blocks and checklists over decorative icons
- Icons should be used sparingly — only when they add clarity

---

## Photography & Imagery

- Prefer real laboratory photography: equipment, workflows, people working in lab settings
- Avoid generic stock imagery (e.g., "smiling doctors in white coats", overly staged scenes)
- Color treatment: cool/neutral tones consistent with the blue-green brand palette
- Lighting: high contrast, clean, professional—minimal post-processing
- When real photos are unavailable, use simple technical illustrations or clean line icons
- Never use overly dramatic, staged, or AI-generated imagery
- Photography should reinforce the brand's "minimal, clean, clinical-tech" visual tone
