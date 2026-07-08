---
name: image-post
description: Turn an idea into a complete, ready-to-run image-generation prompt for a single on-brand social image post (LinkedIn or Instagram), to paste into an image model like gpt-image, Midjourney, or DALL-E. Use when the user wants an image post, a single social graphic, a branded image for LinkedIn or Instagram, "make me an image for X", or "image post about Y".
---

# Purely Personal — Image Post

You turn a concept into ONE complete image-model prompt for a single social image. You do not render the image, you output a prompt the user pastes into an image model.

## Read the ledger first (VOICE-DNA.md)

Before asking anything, look for `VOICE-DNA.md` in the working folder. If it exists, take the brand from section 8 (accent color, background, name, tagline, face preference) and shape any on-image words with their vocabulary and banned list, then skip those questions. You then only need the concept.

If it does not exist, suggest once that extract-voice sets the voice and brand permanently, then proceed with the brief below.

## Gather the brief (one message)
Ask for whatever is missing:
1. **The concept** — what the image should say or show, and any text that must appear verbatim (a headline, a stat, a quote).
2. **Platform / shape** — LinkedIn (portrait 4:5, 1088x1360) or Instagram (square 1:1, 1088x1088).
3. **Brand** — the single accent color (hex), background (light or dark), fonts if any, and whether to feature the founder's face. If no brand, pick one cohesive premium palette and say so.

## Write the image prompt
Produce a single, self-contained, copyable prompt that specifies:
- The exact size and aspect (1088x1360 for LinkedIn portrait, 1088x1088 for Instagram square). Modern, clean, premium, editorial.
- The main subject or scene, described concretely and realistically. Prefer a REAL, specific visual (a labeled infographic, a chart, a device mockup, a clear scene, or a strong typographic layout), never abstract blobs, generic 3D shapes, or random robots.
- Any TEXT rendered verbatim, with the key word(s) in the accent color and a clear hierarchy (a bold headline, an optional subline). Keep on-image text short.
- BRAND PALETTE, exact colors only: the given background, the ONE accent color for emphasis and highlights, and high-contrast text (near-white on dark, near-black on light). Do not introduce other accent hues.
- Typography direction: a bold modern sans for headlines, a clean sans for body. Use the brand fonts if given.
- If a founder's face is provided, describe how they appear (for example a background-removed cutout to one side) and to keep the likeness consistent with the reference photo.
- Composition notes: generous whitespace, clear focal point, balanced margins, premium feel.
- End with: no em dash or en dash in any rendered text; use commas or periods.

Present the final prompt in a copyable code block. Tell the user the exact size to generate at, and that they can regenerate with small wording tweaks to steer the result.

Offer to write variations (a different headline, layout, or a matching set), or to turn it into a multi-slide carousel.
