# Hugel Aesthetics — Design Tokens

Source of truth: `colors_and_type.css` in Hugel's design system (this is a portable reference for use here). Apply these whenever producing an actual slide file, not just a chat outline.

## Brand colors

| Token | Value | Use |
| --- | --- | --- |
| hugel-black | #151515 | Primary text |
| hugel-blue | #0946CE | Primary — logo arc, CTA, links |
| hugel-cyan | #3CC0FF | Accent — logo circles, highlights |
| hugel-white | #FFFFFF | Base surface |

## Neutrals

| Token | Value |
| --- | --- |
| hugel-gray-50 | #F8F9FA |
| hugel-gray-100 | #F0F2F5 |
| hugel-gray-200 | #E4E7EC |
| hugel-gray-300 | #D0D5DD |
| hugel-gray-400 | #98A2B3 |
| hugel-gray-500 | #667085 |
| hugel-gray-600 | #475467 |
| hugel-gray-700 | #344054 |
| hugel-gray-900 | #1D2939 |

## Tints

| Token | Value | Use |
| --- | --- | --- |
| hugel-blue-light | #E8EEFB | Badge bg, info callout |
| hugel-cyan-light | #E6F7FF | — |
| hugel-blue-dark | #062F8C | Hover for primary |

## Semantic status

| Token | Value | Light bg |
| --- | --- | --- |
| hugel-green | #12B76A | #ECFDF3 |
| hugel-amber | #F79009 | #FFFAEB |
| hugel-red | #F04438 | #FEF3F2 |

## Foreground / background

| Token | Maps to |
| --- | --- |
| fg-1 (primary text) | hugel-black |
| fg-2 (body/secondary) | hugel-gray-600 |
| fg-3 (captions/metadata) | hugel-gray-400 |
| fg-inverse | hugel-white |
| fg-link | hugel-blue |
| fg-link-hover | hugel-blue-dark |
| bg-1 (primary surface) | hugel-white |
| bg-2 (alt section) | hugel-gray-50 |
| bg-3 (table head, subtle) | hugel-gray-100 |
| bg-dark (footer, contrast) | hugel-gray-900 |
| border-1 | hugel-gray-200 |
| border-2 | hugel-gray-300 |
| border-strong | hugel-gray-400 |

## Typography

**Families**
- Heading: Noto Sans, Inter, system-ui, sans-serif
- Body: Inter, Noto Sans, system-ui, sans-serif
- Mono: JetBrains Mono, Fira Code, monospace

**Scale**

| Token | Size |
| --- | --- |
| text-display | 56px |
| text-h1 | 40px (32px in dense surfaces) |
| text-h2 | 28px |
| text-h3 | 20px |
| text-h4 | 18px |
| text-body-lg | 17px |
| text-body | 15px |
| text-small | 13px |
| text-micro | 12px |

Line height: tight 1.15 / snug 1.35 / normal 1.55. Weight: regular 400 / medium 500 / semi 600 / bold 700. Tracking: tight -0.02em (display/h1) / snug -0.01em (h2/h3) / normal 0 / wide 0.04em (eyebrows, all-caps labels).

## Spacing (8pt grid + 4px sub-step)

| Token | Value |
| --- | --- |
| space-2xs | 2px |
| space-xs | 4px |
| space-sm | 8px |
| space-md | 16px |
| space-lg | 24px |
| space-xl | 32px |
| space-2xl | 48px |
| space-3xl | 64px |
| space-4xl | 96px |

## Radii

| Token | Value | Use |
| --- | --- | --- |
| radius-xs | 4px | — |
| radius-sm | 6px | Buttons, badges |
| radius-md | 10px | Cards, inputs |
| radius-lg | 16px | Large cards, modals |
| radius-xl | 24px | — |
| radius-pill | 999px | Status badges |

## Elevation

| Token | Value |
| --- | --- |
| shadow-xs | 0 1px 2px rgba(21,21,21,0.04) |
| shadow-sm | 0 1px 2px rgba(21,21,21,0.05), 0 1px 3px rgba(21,21,21,0.04) |
| shadow-md | 0 4px 12px rgba(21,21,21,0.08) |
| shadow-lg | 0 12px 32px rgba(21,21,21,0.12) |
| shadow-xl | 0 24px 56px rgba(21,21,21,0.16) |
| shadow-focus | 0 0 0 4px rgba(9,70,206,0.18) |

## Layout

| Token | Value |
| --- | --- |
| container-narrow | 720px |
| container-default | 1120px |
| container-wide | 1280px |

Grid: 12-column, 24px gutters desktop / 16px tablet / 16px stack mobile.

## Motion

| Token | Value |
| --- | --- |
| ease-out | cubic-bezier(0.22, 1, 0.36, 1) |
| ease-in-out | cubic-bezier(0.65, 0, 0.35, 1) |
| dur-fast | 120ms |
| dur-base | 220ms |
| dur-slow | 380ms |

Subtle only: fades + 8–16px translateY on scroll-in. No bounces, springs, or parallax. (Motion tokens are for interactive/web deliverables — not applicable to static slide decks or documents, note if asked.)
