# Pora Technologies design system

Brand tokens of poratechnologies.com. Source of truth: `index.html` in this repo. When the site changes, update these files too.

## Colors

| Token | Hex | Use |
|---|---|---|
| abyss | #081F38 | Deep navy. Dark sections, headings on light |
| abyss-soft | #0C2848 | Raised surface on navy |
| abyss-deep | #051426 | Footer |
| blue | #295D88 | Main brand blue. Links, accents |
| hydride | #6EAED7 | Light blue. Primary button on navy (text: abyss), highlights |
| slate | #445F79 | Body text on white |
| mist | #5E748B | Secondary text |
| fog | #6C7982 | Muted text, captions |
| ice | #FAFCFE | Light section background |
| frost | #F1F6FA | Light tint, text on navy |
| white | #FFFFFF | Cards, page |

Lines: `rgba(8,31,56,.10)` on light, `rgba(110,174,215,.18)` on navy.

## Type

- Headings: **Space Grotesk** 500, 600, 700
- Text: **IBM Plex Sans** 400, 500, 600 (17px, line height 1.65)
- Labels and technical text: **IBM Plex Mono** 400, 500

All three are Google Fonts.

## Shape

- Radius 14px
- Content width 1140px

## Files

- `tokens.css`: CSS variables
- `tokens.json`: the same values as JSON, with a `mitlus` block for the Mitlus look
- `logo.png`: the Pora icon (64 x 64)

## Use in Mitlus

Settings, Look: upload this folder as a zip, or enter `poratechnologies.com`. Or ask Claude with the Mitlus connector to set the look from this README.
