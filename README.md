# Sela · صلة

The connective layer for pharmacy in Iraq.

**Status:** pre-launch. Everything in this repository is a prototype. No live data, no users, no product.

## Contents

| Path | What it is | Live at |
|---|---|---|
| `index.html` | Interface prototype | `/Sela/` |
| `design/index.html` | Design system v1.0 | `/Sela/design/` |
| `design/tokens.css` | Design tokens, drop-in CSS | `/Sela/design/tokens.css` |

## Design system

Open `design/index.html` in a browser. It covers logo, color, typography, spacing, components, RTL rules, motion and voice.

To use the tokens in any new page:

```html
<link rel="stylesheet" href="/Sela/design/tokens.css">
```

## Build rules

- **RTL first.** Arabic is the primary language. Use `margin-inline-start`, never `margin-left`.
- **Drug names in Latin script**, always. Wrap them in `<bdi>` inside Arabic text.
- **Western numerals** everywhere, including inside Arabic.
- **One primary button per screen.**
- **No gradients, no glow, no emoji in the interface.**

## Fonts

Tajawal (Arabic) and Plus Jakarta Sans (Latin) from Google Fonts. IBM Plex Mono for prices, batch numbers and codes. All open license.

## Note on prototype content

Numbers, logos and product images inside the prototypes are placeholders. They are not real figures and must not be presented as such.
