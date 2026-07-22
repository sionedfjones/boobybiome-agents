---
name: boobybiome-brand
description: Booby Biome's Instagram brand voice, WHO Code compliance, visual guidelines, and Canva production notes — the persistent source of truth for any Booby Biome social content
metadata:
  tags: boobybiome, brand-voice, instagram, canva, compliance
---

This is the canonical, persistent version of Booby Biome's brand rules for Instagram content. It replaces any session-scoped `boobybiome-brand-voice` / `brand-language` / `boobybiome-brand-guidelines` skill that may appear in a Claude desktop app's ephemeral cache — if one of those is found live in the environment, treat it as a possible newer source and reconcile, but don't wait on it existing.

## Two registers, always kept separate

Talking to Sioned about this work can be warm and informal. Anything actually produced for Booby Biome (captions, on-slide copy, scripts) follows the brand voice below exactly, with no personality, jokes, or puns leaking in — this subject is never trivialised.

## Voice — four principles, apply everywhere

1. Make the science land — accurate and accessible, aim for "oh, that's cool," never dumbed down.
2. Defendable, sourced, caveated — say one thing you can stand behind over five you can't.
3. Every parent, every journey — never imply breastfeeding, formula, donor milk, or any feeding path is better than another, never make a parent feel judged, scared, or guilty.
4. Walk alongside, warm by default, plain when it matters.

**Register for consumer social:** high warmth, medium playfulness, low plainness, low technical. Playfulness is allowed here (unlike HCP or anything WHO Code-adjacent) only where it rewards the science rather than distracts from it — serious topic, warm tone, not jokey.

## Hard language rules

- British English throughout.
- **Never use long dashes** — no em dashes, no en dashes outside date ranges. Use commas, full stops, or rewrite the sentence.
- Oxford comma always.
- Sentence case headlines, never Title Case.
- Spell out one to nine, numerals from 10.
- Contractions fine in warm registers.
- "We", never "it", as the brand.

**Forbidden words/phrases:** magic/magical, mama/mumma/mummy, boost/boosts immunity, superfood/powerhouse/super-charged, holistic, game-changer/revolutionary/breakthrough, clean/pure/toxin-free, tribe, any anti-formula language, any causation claim where only association is supported. "Natural" only as a literal descriptor, never a superlative.

**Exception, confirmed from a real published post ("Not magic. / Just science."):** "magic/magical" can be used in a negated, contrastive sense that explicitly rejects magical thinking in favour of evidence — this reinforces voice principle 2 (defendable, sourced) rather than violating it. The rule bans using it as a positive descriptor of the product or its effect ("magic ingredient," "works like magic"), not this specific rhetorical foil.

**WHO Code — non-negotiable:** breastfeeding is always framed as the first option where a parent can do it; never rank feeding choices; every product claim must be defendable, sourced, caveated. Never publish "as good as breast milk," "a substitute for breast milk," "just like breast milk," "the next best thing to breastfeeding," "for when you can't breastfeed," "replaces"/"replacement" language, or anything implying a baby or parent is worse off without a Booby Biome product. When in doubt, stop and flag it rather than publish.

**Founders — full name and title every time:** Dr Lydia Mapstone, Dr Sioned Jones, Dr Tara O'Driscoll, Associate Professor Dr Mona Bajaj-Elliott. No first-name-only references.

## Palette

Teal/sage-led: Holder Teal `#1F4A4A`, Dewy White `#F4F1E8` (never pure white), Eucalyptus `#B8C9B5`. Soft Blush `#E8C4BC` capped at ~4% of any layout as the sole accent.

No clinical white rooms, no bottles with teats.

**Real vault photos are the default imagery source (updated 2026-07-22, supersedes the same-day "AI-generated imagery permitted brand-wide" note this replaces):** the background-repetition problem that earlier note was solving for is now solved properly, with a real photo vault, rather than by leaning on AI generation. The vault's source of truth is Sioned's own Google Drive, but the copies that actually get used live natively inside Canva, as plain image items in two folders:

- **Image Vault → Science** (Canva folder id `FAHQHesZH6Y`) — macro/petri/molecular/lab imagery for Behind the Biome.
- **Image Vault → Lifestyle** (Canva folder id `FAHQHfnM-1s`) — intimate parent/baby imagery for Behind the Brand's cover/closing pair.

Files are named `byomi_<category>_<descriptor>_<YYYYMM>.png`, matching their Drive originals. Any file with `_archive_` in its name is retired — never use it or rotate it in. These are native Canva image assets, not external files being fetched: `list-folder-items` on either folder id (filtered to `item_types: ['image']`) returns each photo's real Canva asset id directly, and that asset id can be passed straight into `update_fill`/`insert_fill` in `perform-editing-operations` — no upload step, no URL, no public sharing of any kind required. (An earlier version of this vault relied on Drive link-sharing and `upload-asset-from-url`; that was dropped once Sioned uploaded the photos directly into Canva, which is simpler and needs no exposure at all.) Not every vault photo has necessarily been uploaded yet — check the folder's actual contents each time rather than assuming the full Drive set is mirrored.

AI-generated imagery is still permitted, but only as a fallback: when no vault photo fits the topic, or the ones that fit have all been used too recently and the remaining pool is thin (this is currently the case for Lifestyle, which has only three usable photos against Science's fifteen). Where AI generation is used, the result still doesn't need to pass as real photography — an obviously illustrated or stylised AI look is fine — and generic corporate stock-photo gloss stays off-brand regardless of source, so keep favouring the macro/tactile/naturally-lit treatment already established (see the petri dish reference below) or genuinely illustrative styles, over anything that reads as generic stock.

## Behind the Biome carousel format (confirmed from real published posts)

Numbered multi-slide carousels, not single images:

- **Page indicator:** "0X/0Y" bottom-left on every slide, small tracked caption text.
- **CTA:** full-pill "SWIPE →" on every slide except the last, fill adapted for legibility — solid sage fill/white text on photo or dark-teal backgrounds, sage-outlined/teal text on lighter sage/mid-tone backgrounds.
- **Logo:** the "B" mark top-left, follows the background-darkness rule — white/cream mark on photo or dark-teal (Holder Teal/Glasshouse) backgrounds, dark teal mark on lighter (Eucalyptus/sage, Dewy White) backgrounds.
- **Headline accent:** usually ends in a full stop; a genuine question ends in a question mark instead — match punctuation to what the sentence actually is. The italicised accent can be a phrase or a single key figure/statistic. The accent is usually rendered in a secondary muted brand tone rather than plain italics in the body colour — Soft Blush on dark-teal backgrounds, a muted sage/teal shift on lighter (Dewy White) backgrounds. Confirmed from multiple real posts, not just the dark-teal case.
- **On-slide citations:** any slide stating a specific *external* research finding or statistic gets a small "Author et al., Year" credit bottom-left beneath the body copy, same muted weight as the page indicator. Must be a citation actually verified via web search — never invented. Slides that aren't citing external literature don't need one — this includes rhetorical/question slides, but also slides describing Booby Biome's own process or methodology (e.g. "this is how we grow it, store it, and study it" — a real published slide with no citation, since it's describing their own lab work, not citing a paper). Not needing an on-slide citation never means skipping verification — any factual claim, including about internal process, still has to be true and defensible.
- **Opening slide device — rotate, don't default:** the search-bar autocomplete hook is only one option among several, not the default — it became reflexive purely because duplicating that one design was the easiest way to stay on-brand, which is a build-convenience reason, not a creative one. Before opening a new carousel, check what device the last 2-3 Behind the Biome posts in the Social Canva folder actually used, and actively pick a different one. Devices to rotate through:
  - Straight headline-on-photo (no UI mock-up).
  - A "this or that" / myth-vs-fact framing on the cover.
  - A single bold stat or number as the visual hook.
  - A direct question addressed straight to the reader.
  - A mocked-up text-message/chat-bubble hook, if a real on-brand reference exists to duplicate.

**Petri dish / bacteria imagery reference** (confirmed from a real published carousel, "Breast milk is *alive*."): shallow-depth macro shot of an actual petri dish on a warm sand/oat surface, raking natural window light, soft directional shadow, a second dish softly blurred in the background. Bacterial colonies as a calm streak-plate pattern in cream/off-white tones, not red, not starburst-shaped, not alarming. Headline over the lower-left of the photo in white/cream serif text with one italicised accent word, no separate text-panel needed. The real carousel this comes from continues the device across 2 slides (cover, then a closer macro crop with a second observational line — "Each tiny dot is a *colony* of living bacteria"), then transitions to a solid background colour-matched to the photo's own sand/oat tone for a process/methodology slide ("Millions of cells. All descended from *one*." / "This is how we grow it, store it, and study it."), before closing on a plain sage slide with a values statement ("Not magic. / Just science.") and the wordmark. Not every Behind the Biome carousel needs external citations — this one has none, because it's describing Booby Biome's own lab process and a brand-values statement rather than citing literature.

## Behind the Brand carousel format (confirmed from a real published carousel, "A love letter to the 3am feed.")

A different, more emotive shape from Behind the Biome — no page counter, no on-slide "Author et al." citations. Structure:

1. **Cover:** intimate, low-light imagery (e.g. a parent breastfeeding at night) — pull from the Lifestyle vault folder first (see the imagery-sourcing note under Palette above), AI-generated (photographic or stylised) only as a fallback once that small pool is genuinely exhausted. Headline hook directly on the photo, bottom-left, white/cream serif with one italicised accent word. "BEHIND THE BRAND" tag top-right, logo top-left, wordmark bottom-left, swipe pill bottom-right.
2. **1-2 short "atmosphere" slides:** plain solid-colour background (dark teal or Dewy White), a few short standalone lines building the emotional beat, no imagery. Last line often italicised as the turn ("*Maybe you have.*").
3. **2-3 "science-fact" slides:** one line of headline stat/mechanism copy (with an italicised accent) plus one supporting line of body copy, paired with a small, muted, single-colour line-art diagram (a molecule structure, an antibody/Y-shape, a bacteria motif) bottom-left or top-right — not a photo. These are genuine factual claims (e.g. melatonin content, saliva-triggered antibody response) and must be verified the same as any Behind the Biome claim; since the slide has no room for an on-slide citation, put the citation in the caption instead of on the slide.
4. **1 punchy resolution slide:** plain solid colour, short parallel-structure lines building to one italicised final beat.
5. **Closing slide:** matching imagery to the cover (same shoot/scene, different crop or angle), a short emotional payoff line, wordmark, no swipe pill (last slide).

Real vault photography from the Image Vault → Lifestyle folder is always the first choice for the cover/closing pair — check the folder (excluding any `_archive_` file) and the last 2-3 Behind the Brand posts' thumbnails to avoid repeating the same photo two posts running. Only generate AI imagery for the cover/closing pair once that small pool has genuinely been exhausted by recent use, keeping the same intimate, low-light, emotionally warm treatment the real posts established.

## Background image variety

Real vault photos are the default and first choice, now that the vault exists (folder ids, naming convention, and the archive-exclusion rule are under Palette above). Rotation works the same way the opening-slide device already rotates: before building, check the last 2-3 same-pillar posts' thumbnails, identify which vault photo each one used — the vault is a small, namable set, so this is a visual match ("that's the petri-bacteria one"), not a file-content lookup — and pick a different one from the remaining pool.

Generate AI imagery only as a fallback: when no vault photo fits the topic, or the ones that fit have all been used too recently and the remaining pool is thin — check the pool size before deciding, since Lifestyle currently has only three usable photos against Science's fifteen. Where AI generation is used, keep rotating both the **opening-slide device** (bold stat, direct question, myth-vs-fact, chat-bubble, straight headline-on-photo) and the **imagery treatment** itself — don't let one AI-generated image become a new reflexive default the way the search-bar cover once did.

## Canva production notes

Freeform `generate-design` AI calls have repeatedly drifted off-brand on *structure* (wrong colours, invented filler copy, fabricated citations, missing logo/page-number/citation elements) even with a brand kit supplied — this is a separate concern from whether AI-generated *imagery* is allowed (it now is, brand-wide, see above), and still applies. Prefer duplicating a real existing on-brand design (`copy-design`) and editing it via `start-editing-transaction`/`perform-editing-operations` for layout, text, logo, and citations, generating or swapping in AI imagery only for the background/photo element itself rather than letting AI generation own the whole design. Use `find_and_replace_text` on specific substrings rather than `replace_text` on a whole element where the element has multiple per-run text regions (e.g. an italicised accent word) — a full replace collapses the runs and loses formatting.

The `/d/...` short URLs from `start-editing-transaction`/`generate-design` aren't stable — refetch from `get-design` (`urls.view_url`/`urls.edit_url`) at the moment you actually need to hand a link over, don't reuse one from earlier.

**Speed:** don't check `get-design-thumbnail` after every single `perform-editing-operations` call — that per-edit-check loop is the main driver of slow runs. Batch all edits for a slide (or a whole small design) into as few transactions as practical, verify with one thumbnail/content check before committing, plus one final check after commit. Never skip that final post-commit check, and never skip citation verification to save time — those two checks are the speed floor, not places to cut. For the final post-commit check specifically, use `get-design-content` rather than `get-design-thumbnail` or `get-design-pages` — confirmed twice now that Canva's thumbnail cache can lag behind the actual saved document right after a commit, briefly showing stale pre-edit content even when the save succeeded. A content-level check is the reliable ground truth; a thumbnail immediately post-commit is not.

**Discovery step:** before building anything, a single `list-folder-items` call on the Social folder gives both the title list (for sequential numbering) and a thumbnail URL for the most recent items — that's enough to check device/background rotation at a glance. Don't call `get-design-content`/`get-design-pages` on prior posts just to decide what to build next; that deep inspection was the single biggest driver of slow runs in testing and isn't needed for this decision.

**Pulling a vault photo into a design:** call `list-folder-items` on the relevant Image Vault subfolder (`FAHQHesZH6Y` for Science, `FAHQHfnM-1s` for Lifestyle) filtered to `item_types: ['image']`. Skip any item whose name contains `_archive_`. Each remaining item's `image.id` is a real Canva asset id — pass it directly as `asset_id` (with `asset_type: "image"`) into an `update_fill` (swapping an existing photo/background element) or `insert_fill` (adding a new one) operation in `perform-editing-operations`. There is no upload step and no URL involved; the photo is already a native Canva asset the moment it shows up in the folder listing.

Call `list-brand-kits` first and use the Booby Biome kit if one exists, though its API exposes little (no font/colour introspection) — real published-post screenshots are a more reliable calibration source than the brand kit when in doubt.

Once a design is finished and saved, move it into the Canva **Social** folder (`FAFwzxEqbus`, nested inside Marketing) via `move-item-to-folder` automatically, without being asked.

**Sequential naming (updated 2026-07-22 — permanent scheme):** `BB001` is the fixed project prefix — it never changes, it isn't a batch number. Every post ever produced under this project gets the next number in one single, never-resetting sequence: `BB001_1`, `BB001_2`, `BB001_3`, and so on indefinitely. Before creating a new design, call `list-folder-items` on the Social folder and scan existing titles for the `BB001_(\d+)` pattern; take the highest N found and use N+1. Format: `BB001_N · <Pillar> · <short topic>` (e.g. `BB001_5 · Behind the Biome · Entero-mammary pathway`). This replaces the earlier `BB0XX` (BB002, BB003...) per-post numbering — if any design is ever found still using that old style, it's a leftover from before this scheme existed, not a sign the scheme changed again.

## Compliance layer (org policy, applies on top of brand voice)

- Any scientific, health, or regulatory claim must be verified via web search against an authoritative source and cited — never asserted from memory. If it can't be sourced, flag it as unverified rather than stating it plainly.
- Never include supplier names, pricing, formulations, patent-adjacent IP, or unpublished research in any public-facing draft, even in passing.
- Before presenting any copy as ready, check: British English and no long dashes; no forbidden words; WHO Code-safe; defendable and sourced where claims are made; couldn't make any parent feel scared, guilty, or judged; right register for the context; founders named in full.
