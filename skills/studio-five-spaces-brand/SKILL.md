https://studiofivespaces.com/wp-content/uploads/2026/09/2026-Spaces-Logo.png LOGO FUCKING USE THIS AZRAI

---
name: studio-five-spaces-brand
description: Apply the Studio Five Spaces (SPACES) Branding Guidelines 2027 V9 when creating, redesigning or reviewing anything for Studio Five Spaces. That covers website pages and mockups, HTML/CSS, landing pages, decks and proposals, social posts, YouTube/Reels thumbnails, video end frames, posters, email signatures, business cards, merchandise, signage and copywriting. Use it whenever the work mentions Studio Five Spaces, SPACES, studiofivespaces.com or "create. collab. cowork.", or when someone asks to "make it on-brand", "follow the brand book" or do a brand review for the studio, even if they never say "brand guidelines".
---

# Studio Five Spaces brand (V9, 2027)

This skill holds the rules that make work recognisably SPACES. The full book is in `references/brand-book-2027.md` (about 900 lines, split into sections 00–09). This file covers the rules that apply to almost every job. Open the reference when you need an exact value or a format-specific rule. Use the section map at the bottom to jump straight to the part you need.

Written rules govern over any example or mockup in the book. If the rules don't cover a case, say so and flag it for the brand owner. Never invent a new rule silently.

## The core in one screen

**Tagline:** `create. collab. cowork.` Use it exactly like this: lowercase, in this order, with every full stop. It is the only recurring slogan. Never write an alternative slogan, and never make the tagline part of the logo.

**Six colours, no others.** Don't add tints, extra accents, gradients or status colours (green/red/yellow).

| Token | HEX | Job |
|---|---|---|
| Electric Purple | `#A21FFF` | Logo, large headlines, main buttons, selected campaign fields |
| Glow | `#C9A8FF` | Links, labels, focus rings and emphasis **on Blackout** |
| Deep UV | `#4C1D95` | Links and short functional text **on White**; process-print alternative |
| Blackout | `#17141A` | Lead surface: websites and decks start here |
| Matte Black | `#231F20` | Body text on White |
| White | `#FFFFFF` | Body text on Blackout/Electric; reading surface |

`assets/tokens.css` has these as CSS custom properties, plus type and spacing tokens. Start web work from it.

**Body text follows the background:**
- Blackout → White body. Use Glow for links and labels.
- White → Matte Black body. Use Deep UV for links.
- Electric → White text.
- Electric text is allowed **only at large sizes** (≥24 px regular / ≥18.67 px bold), even where it passes WCAG. Glow on White, and Deep UV on Blackout, are never used for text.

**Type:** Sora for headlines and expressive copy, at 600–700 weight, with tracking of −2% on large headings and −1% on smaller ones. Inter for everything informational: body at 400 with 0 tracking and 140–150% line height; labels and buttons in Inter Medium; uppercase labels at +6% tracking. Use real font weights. Never stretch or over-track text to fill a line.

**Logo:** Use the supplied masters only (Electric or White wordmark, standalone S, circular S). On Blackout, Electric is preferred and White is allowed. On Electric, use the White wordmark. Clear space is X = ¼ of the wordmark height. Minimum widths are 120 px for the wordmark, 240 px for a banner and 24 px high for the S. Never stretch, rotate, crop, rearrange, retype, outline, glow or bevel it, and never put a square behind the S.

**Supporting slogan under the logo:** Inter Medium, centred, 73% of the wordmark width. The gap is wordmark width ÷ 18. Allow at least 240 px of wordmark width, so the slogan stays ≥16 px. Otherwise drop it. Use it at most once per layout. Leave it off content slides, thumbnails, documents and signatures.

**Spacing scale:** 8, 16, 24, 32, 48, 64, 96. Keep a heading close to its own text and leave a bigger gap before the next group (e.g. 24 within, 48 between). When copy wraps, reflow or split the layout. Don't squeeze the gaps.

**No decorative motif.** No recurring bars, patterns, logo-derived textures, ornamental lines or coloured glows. Identity comes from the logo, the six colours, Sora/Inter, real studio photography and deliberate space.

**Accessibility is part of the brand.** Underline inline links. Never let colour alone carry status: pair it with words or icons. Essential controls need a visible boundary. Focus rings are Glow with a dark gap on Blackout, and Deep UV with a White gap on White.

## Voice

The voice is trendy, youthful, full of electric energy, authentic and experiential, all at once. In practice, be specific and supportable. Use active verbs. Name the next action ("Explore the studios", "Book a studio"). Avoid hype, invented scarcity, superlatives you can't back up ("unparalleled", "limitless", "most iconic"), constant capitals and strings of exclamation marks. Write *Studio Five Spaces* in full in formal copy.

## Defaults by format

Open the matching reference section before finishing. These lines are only reminders.

- **Website:** Blackout-first. Electric logo and large headline, White body. Desktop grid is 12 columns with 24–32 px gutters and 64–80 px side padding. Mobile is 4 columns with 16–24 px padding. Body text is 18 px on desktop and 16–18 px on mobile. Use the three-zone footer: entity logo on the left (160 px), links in the middle, and "part of" (Inter 13 px/1.2, 6 px gap) + Group logo (136 px) on the right, linking to studiofive.group. On mobile it stacks as entity → links → endorsement → legal. → §06 Website, §01 Naming.
- **Decks/proposals:** 1440×810. Margins 64. Title at x64/y117. Content between y224 and y712, with the footer boundary at y752. Two columns of 632 with a 48 gutter. Open on Blackout. Always use SPACES branding, even in tenders: never adopt the client's palette or fonts. → §06 Decks.
- **Social/thumbnails:** One subject and one hook. Feed is 1080×1350; stories are 1080×1920. Only YouTube may use a White outline on large Electric text. Reels use staggered word tiles (White Sora on Electric). Trend-led covers need the White wordmark at the top and the White tagline at the bottom. Any emoji must be from the Apple iOS family. → §06 Social.
- **Video:** End on Electric on Blackout, or White on Electric. Pick one clear brand moment. Caption essential speech. → §05 Video.
- **Print and merchandise:** Screen Electric can't be guaranteed in CMYK. Start from Deep UV / C82 M95 Y0 K0. Pantone 2592 C and Violet C are candidates only, so always approve a physical proof. → §03 Print, §06 Merchandise.
- **Email signatures:** Use the fixed structure and omit the slogan. → §06 Email.

## When redesigning existing work

1. **List every colour in use.** Map each one onto one of the six tokens by its job. Remove anything that doesn't map, including greys, hover tints and status hues. If a state needs distinguishing, use a border, icon or word instead.
2. **Remove gradients, glows and decorative patterns.** Swap them for flat token fields. A functional pattern is allowed when a legend explains it, e.g. hatching for unavailable time.
3. **Check every text/background pair** against the colour rules above. Electric small text is the most common miss.
4. **Bring type sizes, weights, tracking and line heights in line** with §04, and spacing in line with the scale.
5. **Check the logo lockup, tagline wording and footer structure.**
6. **Re-read the copy against the voice traits.**
7. **Render it and look.** Check desktop and a phone width (~390 px) for overflow, widows and cramped groups.
8. **Save as a new version.** Never overwrite the original. File naming: `StudioFiveSpaces_Project_Asset_YYYYMMDD_v01`, incrementing the version.

## Reviewing work

Use the §09 checklist. First run the eight core checks: logo, purpose and voice, colour and contrast, imagery, typography, spacing, slogan, hierarchy. Then run the format checks. Report one of three verdicts: **READY** (relevant checks pass), **REVISE** (a rule is broken or the message is unclear) or **CLARIFY** (no approved rule fits). Cite the specific rule for each issue. An attractive design can still break a rule, and a different composition can still comply, so judge compliance and quality separately.

## Reference map (`references/brand-book-2027.md`)

| Need | Section heading to search for |
|---|---|
| Voice do/avoid, copy examples | `## 01 / Foundation & voice` |
| Logo versions, clear space, misuse, seasonal logos | `## 02 / Logo & slogan` |
| Contrast ratios for every pair, print colour | `## 03 / Colour system` → "Contrast limits for every palette pair" |
| Type size table by format | `## 04 / Typography` → "Sizes, weights & line heights" |
| Grids, layout choice, photography, video | `## 05 / Layout, imagery & video` |
| Website, decks, social, thumbnails, email, merchandise, signage | `## 06 / Website, presentations & other applications` |
| Approval flow, asset filenames | `## 07 / Governance & handoff` |
| Review checklist | `## 09 / Brand review checklist` |

Logo SVG masters aren't bundled. Ask for the supplied files (`1-Wordmark - Electric Purple.svg` … `6-S Circular - White.svg`) rather than redrawing the wordmark in a font.
