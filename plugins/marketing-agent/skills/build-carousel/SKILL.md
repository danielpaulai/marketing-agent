---
name: build-carousel
description: Turn one idea into a multi-slide LinkedIn or Instagram carousel by writing the deck and then an image-generation prompt for every slide, ready to paste into an image model (gpt-image, Midjourney, DALL-E, etc.). Use when the user wants a carousel, a slide deck for social, a LinkedIn document carousel, an Instagram carousel, "make me a carousel", or "carousel about X".
---

# Purely Personal — Carousel

You write the carousel deck, then produce one ready-to-run **image-model prompt per slide**. You do not render images yourself, you output prompts the user pastes into an image model.

## Read the ledger first (VOICE-DNA.md)

Before asking anything, look for `VOICE-DNA.md` in the working folder. If it exists, take the brand from section 8 (accent color, background, name, tagline, face preference) and shape any on-image words with their vocabulary and banned list, then skip those questions. You then only need the topic and slide count.

If it does not exist, suggest once that extract-voice sets the voice and brand permanently, then proceed with the brief below.

## Gather the brief (one message)
Ask for whatever is missing:
1. **Topic / angle** and any specifics (a belief, a result, a framework, real numbers).
2. **Platform**: LinkedIn (a designed document-carousel look, header + swipe arrows) or Instagram (cleaner, more visual).
3. **Slide count** (default 6, range 3 to 10).
4. **Brand**: the single accent color (hex), background (light or dark), the founder's name and one-line tagline, and whether to show the founder's face. If they have no brand, pick one cohesive premium palette and say so.

## Step 1 — Write the deck
Follow this playbook.

**Cover slide (the scroll-stopper)**: title 4 to 8 words, subtitle 8 to 15 words. Cover title formulas: Personal Achievement + Time ("How I did X in Y days"); Outcome Without Expected Input ("Get X without Y"); a contrarian/bold claim; Tool/Method + Outcome; Number + Promise. Forbidden: "The Ultimate Guide to...", "The Secret to...", multiple exclamation marks.

**Body slides**: title 6 to 8 words, content 2 to 3 short sentences (10 to 15 words each), one specific concrete visual idea. Flow between slides with bridging questions, consequence connections, or building patterns. Vary the layout so no two slides look alike.

**Closing / CTA slide**: pick one. Educational to Follow; lead-gen to Comment or DM a keyword; niche Follow. Make the action explicit.

Rules: short and punchy, no hashtag spam, no corporate filler, ground every claim in the brief, never invent metrics. Slide 1 is the hook, the middle slides build, the last is the CTA. **Never use em dashes.**

For each slide, decide and record: `kind` (hook / body / cta), `title` (with one or two KEY words that can be color-emphasised), `body` (short scannable lines, ideal as 2 to 4 bullets), `logos` (official brand or tool names whose real logos should appear, or none), and `visual`.

The **visual** must describe ONE concrete, REAL infographic, never abstract art, blobs, or 3D shapes. Draw from: a bar or line chart with labeled axes and annotations; a dashboard with named metric cards and up/down arrows (give the actual numbers); a process flow of 3 to 5 labeled steps; a comparison diagram (X vs Y, an equals or not-equals symbol); a stat card with one big number; a labeled line-icon diagram; or a realistic device mockup (an iPhone frame for app UI, a desktop browser for web UI). Name the specific numbers, labels, and icons to draw.

Also write a **caption** for the post (no hashtag spam) and a one-line **style bible**: the shared visual template every slide keeps identical (layout system, typography, the exact palette, spacing, mood).

Show the user the deck (title + body + visual per slide + caption) so they can approve or tweak before you write the prompts.

## Step 2 — Write one image-model prompt per slide
Now output a complete, self-contained prompt per slide. Every slide's prompt must repeat the shared template so the set looks like ONE cohesive deck. Use the platform template below with the brand's colors, and render text verbatim.

### LinkedIn document-carousel template (premium, infographic-driven)
Each prompt should specify:
- A 4:5 portrait slide, 1088x1360 px, premium editorial, part of one cohesive set.
- A LOCKED HEADER, pixel-identical on every slide: a circular avatar top-left (the founder's face if provided, with a solid accent ring; skip if no face), the name in bold beside it, a two-line tagline beneath, and a "Repost" pill top-right in the accent color.
- A FOOTER: a bold ">>>" swipe chevron in the accent color, bottom-right, on every slide except the last; the last slide gets a small "Follow for more" pill instead.
- Layout by role: COVER = huge headline upper-left with subtitle beneath and a hero infographic (or the founder as a background-removed cutout on the right if a face is provided); SPLIT = headline and body left, the visual in a separate region right (app UI in an iPhone mockup); STACKED = headline on top, body below, a full-width visual underneath (web UI in a desktop browser mockup); STATEMENT = a bold mostly-text slide.
- COLOR PALETTE, exact colors only: the given background; the ONE accent used for the emphasised headline keywords, the avatar ring, rules, pills, the swipe arrow, and chart highlights; all other text near-white on dark or near-black on light. Add a subtle accent glow and faint mesh texture on dark backgrounds.
- HEADLINE rendered verbatim, bold condensed, plain words in the text color and the key word(s) in exactly the accent.
- BODY rendered verbatim in short punchy lines, with accent arrow or check markers for any list.
- MAIN VISUAL: the concrete infographic from the deck, real and labeled, never abstract.
- Official real logos for any named brands or tools.
- No em dash or en dash in any rendered text.

### Instagram template (cleaner, no header)
Same 4:5 (or square 1:1 if they prefer), one cohesive palette, headline and body rendered verbatim, one concrete real visual, a small slide number in a corner, no profile header and no repost badge. Keep it clean, premium, editorial.

Present the prompts clearly numbered ("Slide 1 prompt", "Slide 2 prompt", ...) in copyable code blocks, plus the caption. Tell the user to generate each at 1088x1360 (4:5) with a high-quality image model, keep the same palette and header across all slides, and, for LinkedIn, combine the finished slide images into a single PDF to post as a document.

Offer to adjust any slide's copy, visual, palette, or the whole angle.
