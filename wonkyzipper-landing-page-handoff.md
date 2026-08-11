# Wonky Zipper — First Landing Page Handoff

## Outcome

Build a deliberately sparse first page for `wonkyzipper.com`. It should feel like the cover sheet of an intriguing, unfinished project—not a conventional ecommerce site or a literal “coming soon” page.

The reaction to aim for: *Whoa. What is this? I want to see what happens here.*

## Essential Asset

Use Craig’s final supplied image of the white-paper **W** over the pale pink plaid layer. It is the hero mark and should not be redrawn, recolored, cropped tightly, or overlaid with text.

Its visual logic matters:

- A clean white sheet covers the bottom portion.
- Three curled cuts fall from the straight upper edge and make the W through shadows on the faint plaid below.
- Lighting feels as though it comes from below the image.

## Page Composition

### Desktop

- A full-width pale pink plaid header band: approximately `220–260px` tall.
- Place the W image large at the upper left (`150–210px` wide), overlapping the boundary between the plaid header and white page body by roughly one third of its height.
- Set `WONKY ZIPPER` to the right of the mark, vertically aligned near the top of the header. Keep it clean, confident, and not overly large.
- Do **not** add navigation until there are real destinations. Empty shop/about links would make the page feel unfinished in the wrong way.
- Keep the rest of the page almost entirely white and spacious.
- Place the only copy low on the page, left-aligned with the logo edge. It should feel discovered, not like a hero headline.

### Mobile

- Keep the plaid as a shallow band (`128–160px`).
- Keep the W anchored at top-left and overlapping into the white body.
- Move `WONKY ZIPPER` beneath or just to the right of the W as space allows; never shrink it to illegibility.
- The statement can sit around the lower third of the viewport, with generous white space above and below.

## Exact Copy

Use this casing and punctuation exactly:

> detailed disorder<span style="color:#F35B21; font-size:0.55em; vertical-align:baseline;">.</span>

Implementation notes:

- Both words are lowercase.
- The sentence is charcoal or near-black, not hot pink.
- The final dot is the persistent M.D orange: `#F35B21`.
- Make the orange dot noticeably small—about `45–55%` of the text’s cap height—rather than a standard punctuation mark.
- Use normal text/HTML plus a styled dot (not an image) so it remains selectable and accessible. Screen-reader text should simply read “detailed disorder.”

## Color and Type

| Role | Value / Direction |
| --- | --- |
| Brand pink | `#D9006C` — hot but slightly deep; use for `WONKY ZIPPER` and any future hover/link state |
| Accent dot | `#F35B21` — small and persistent |
| Page white | `#FFFFFF` / very near-white only |
| Plaid | Use the supplied image texture; keep it pale and washed-out, never saturated |
| Main text | Charcoal, approximately `#252321` |
| Display type | Elegant editorial serif—Playfair Display is a good starting point |
| Supporting type | Simple restrained sans-serif, if needed; do not introduce a playful rounded font |

The texture, mark, and pink provide enough personality. Typography and layout should be quiet.

## Optional, Very Small Footer

Only if Craig has a live destination to link: `Instagram` and/or `Contact` in small hot-pink text. Otherwise omit the footer entirely for this first version.

## Interaction and Motion

- No carousels, product grids, email capture, countdowns, or “launching soon” language.
- No strong animation. At most, let the W and wordmark fade in once over `350–500ms` on first load.
- Respect `prefers-reduced-motion`.
- Hover states, if links exist, should be a simple underline or modest opacity shift.

## Guardrails

- Do not add zipper imagery elsewhere on the page. The W image already contains the mystery and construction idea.
- Avoid a conventional fashion-brand black wordmark, centered layout, or ecommerce navigation.
- Avoid oversized marketing copy. The restraint is the point.
- Treat the page as an atmospheric cover, ready to grow later into bags, objects, garments, patterns, and experiments.

## Acceptance Check

At a glance, the page should show: pale plaid above, white below, the strange curled-paper W at upper left, `WONKY ZIPPER` in pink, and one quiet line—`detailed disorder.`—with its tiny orange dot. Nothing needs to explain itself yet.
