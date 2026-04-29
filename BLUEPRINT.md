# The Sandwich Spot — Palm Springs · BLUEPRINT
**Mode:** PRO-MAX (research + blueprint phase, build deferred)
**Date:** 2026-04-28
**Contact:** Dena Banes (Denabanes@aol.com)
**Live brand contact:** Corlyn Saldana (current owner since 2021, per NBC Palm Springs)

---

## 1. Brand Synopsis

The Sandwich Spot Palm Springs is a beloved, independent, **mom-and-pop counter-service deli at 276 N Palm Canyon Drive**, tucked into the Henry Frank Arcade across from the Hyatt. It's part of a 30+ location California-rooted chain founded in Sacramento (2007), but the Palm Springs shop has its own personality and is operated as a community institution. The previous owner passed in 2021 and was deeply mourned by the local business community — the place carries that legacy.

What makes Palm Springs different from "any Sandwich Spot":

- **#4 of 345 restaurants on TripAdvisor**, 4.7⭐ on Yelp with **2,457+ reviews**.
- A **proprietary Dutch Crunch bread**, baked fresh daily in-house — universally cited as the signature draw.
- A menu of **24 specialty sandwiches at $14.75**, every one named after a Palm Springs cultural icon or tennis legend:
  - **Tennis royalty** (BNP Paribas Open at Indian Wells is in their backyard): The Federer, The Djokovic, The Rafa, The Indian Wells, The French Open, The Serve and Volley.
  - **Palm Springs Hollywood/Rat Pack legends**: The Chairman of the Board (Sinatra), Thanks for the Memories (Bob Hope), The Copacabana (Manilow), The Dinah (Dinah Shore), The Gene Autry, The Sunny and Share (Sonny & Cher), The Thighmaster (Suzanne Somers).
  - **Cheeky / innuendo**: The DILF, The MILF, The Dirty Weekend, But It's a Dry Heat, The Frowzy Red Head, Dream Killer, Bear Necessities.
- **"LOVE ALL ♥ FEED ALL"** is the franchise tagline — the tennis double-meaning fits Palm Springs perfectly.
- **Atmosphere**: small, packed at lunch, friendly staff treating regulars "like BFFs," indoor + courtyard patio, complimentary lollipops on the way out, sun-brewed iced tea, 100-option soda fountain. Daily 10am–6pm.
- **Reviewer obsessions**: Dutch Crunch, the Bomb Sauce, the marinated chicken, the size of the sandwiches, "worth the wait."

**The differentiation problem**: the corporate franchise site (`thesandwichspot.com/palm-springs-menu`) is a tired Wix template — text-only menu, no real photography, no sense of place, no humor, no Palm Springs. Dena wants Palm Springs to feel like its **own thing** — comedic, hometown, irreverent, deeply local, distinguishable from any other Sandwich Spot from the second the page loads.

---

## 2. The Strategic Insight

The brand already does the comedy work — the sandwich names *are* the joke. Every name is a punchline tied to Palm Springs identity (tennis week, mid-century celebrity, dry-heat irony, mom-and-pop innuendo). The website's job is to **let that voice out of jail**. The corporate site mutes it; Dena's site should turn the volume up.

The "sandwich emergency" framing fits because The Sandwich Spot is, locally, the place you go when you're starving, hungover at the Saguaro pool, jet-lagged off the JetBlue red-eye, late for a tee time at Indian Wells, or just need an enormous Dutch Crunch sandwich *immediately*. We can lean into that as a comedic operating system for the brand voice.

**Doodle illustrations** are the right move because:
1. They lock in the comedic, hand-made-by-mom-and-pop authenticity.
2. They sidestep the "AI photorealism uncanny" trap — doodles are honest about being illustrations.
3. They can depict the actual sandwiches and Palm Springs landmarks without falsely claiming to be photos of *the actual building or the actual food*.
4. They're cheap to generate, easy to swap, and look intentional, not budget.

---

## 3. Two Unique Directions — Distinct, Decisive, Mobile-First

Both share the doodle illustrations, the playful voice, and the "don't look like a franchise" mandate. They differ in **register**: A is comedy-club loud, B is supper-club refined-but-cheeky. They are not color swaps — they pull on different design languages, different signature moves, different reading rhythms.

---

### 🎯 Direction A — **"SANDWICH EMERGENCY"**
*Comedy-club loud · Newbrutalist + Anti-polish hand-drawn collage · Mom & pop dispatched as a 911 hotline*

**Mood (one sentence)**
A Palm Springs sandwich emergency hotline running out of a converted radio station — chunky black borders, screaming red headlines, mustard ticker tape, doodles taped on at angles, customer reviews ripped out like newspaper clippings.

**Style backbone** (per `ui-ux-pro-max` skill output)
- **Style A**: Vibrant & Block-based + Neubrutalism (chunky 3px black borders, hard 4px offset shadows, no gradients)
- **Style B**: Anti-Polish / Raw Aesthetic (paper textures, hand-drawn SVG, slight rotation on stickers)
- **Style C**: Memphis squiggles in moderation as decorative accents

**Color palette**
- **Primary** `#E63946` — Tomato red (alarm/emergency, pickled cherry, classic deli)
- **Secondary** `#FFC83D` — Mustard yellow (bread crust, taxi-cab "URGENT")
- **Accent** `#6B8E23` — Pickle green (fresh, sour, plays against the loud reds)
- **Ink** `#111111` — Marker black (every border, every doodle outline)
- **Canvas** `#FAF6E9` — Warm mayo cream (paper-bag warmth, never pure white)

**Typography**
- **Display heading**: Anton (single-weight 900, condensed) — for "SANDWICH EMERGENCY," the ticker, sandwich numbers
- **Display secondary**: Caveat (handwritten marker) — for sticker copy, doodle labels, "Dena's note from the kitchen"
- **Body**: Inter (300/500/700) — readable menu copy, hours, contact

Why not Playfair: this direction is yelling, not whispering. Anton + Caveat says "deli sign + Sharpie." Playfair would feel polite.

**Layout pattern**
1. **Top emergency bar** — sticky 24px-tall scrolling marquee in tomato red: `★ SANDWICH EMERGENCY HOTLINE · DIAL (760) 778-7900 · HOURS 10AM–6PM DAILY · ★ DUTCH CRUNCH BAKED THIS MORNING · ★` (referencing 21st.dev Text Marquee, see `21st-sources/marquee-text-marque.tsx`).
2. **Hero** — 3-column collage:
   - Left: huge stacked headline "SANDWICH / EMERGENCY / RESPONSE / TEAM" (Anton, hard kerning, last word in tomato).
   - Middle: a doodle of a sandwich-on-a-stretcher being rushed through ER doors (commissioned via Grok).
   - Right: phone receiver doodle + "WE TRIAGE LUNCH · EST. SOMEWHERE BETWEEN A DUTCH CRUNCH AND THE LAST RAT PACK SHOW" body copy + a CTA "ORDER A RESCUE → (760) 778-7900."
3. **"WHAT'S YOUR EMERGENCY?" picker** — a comedic 3-card chooser (Mild Hunger / Severe Hangover / Total System Failure) that scrolls you to recommended sandwiches.
4. **The Menu (the showstopper)** — numbered classified-ad-style entries, each with a doodle illustration on the left, the sandwich name in Anton on the right, ingredients in Inter. Every 4–5 sandwiches there's a celebrity Palm Springs Easter egg sticker (a tiny doodle of Sinatra's hat next to The Chairman, Bob Hope's golf club next to Thanks For The Memories).
5. **"DOCTOR DENA'S DIAGNOSIS"** — a recurring doodle character who annotates 3–4 menu items with hand-written notes ("warning: addictive," "discharge papers attached," etc.).
6. **Reviews-as-clippings** — pulled Yelp / Google review quotes presented like newspaper cut-outs, taped at angles, with ⭐⭐⭐⭐⭐ stamped over them.
7. **Location/Hours block** — hand-drawn map sketch of Palm Canyon Drive, the Henry Frank Arcade marked with a giant red ❌, sun-tea pitcher doodle, hours table set in Anton.
8. **Footer** — dispatch radio call sign aesthetic ("OVER AND OUT — 276 N PALM CANYON DR · PS 92262"), social icons as taped-on badges, then the Banana Bytes credit.

**Signature moves (the things people remember)**
- The scrolling **EMERGENCY HOTLINE ticker** at the top.
- The **"WHAT'S YOUR EMERGENCY?" interactive picker**.
- **Doctor Dena**, a recurring doodle persona who annotates the menu in the margins.

**Animation approach**
- IntersectionObserver-triggered "tape down" reveal — stickers, doodles, and review clippings rotate 0–3° and drop in with a subtle bounce as the user scrolls.
- Hover on a menu doodle: it wiggles ~2° in either direction.
- Marquee runs continuously at slow speed (CSS `animation-duration: 40s`).
- All animations gated behind `@media (prefers-reduced-motion: reduce)`.

**What to avoid**
- ❌ Subway green / Jersey Mike's red — too generic-fast-food.
- ❌ Centered hero with Inter heading "Welcome to The Sandwich Spot."
- ❌ Polished hero stock photography (the whole point is rawness).
- ❌ Memphis squiggles everywhere — they're seasoning, not sauce.

**Risks to watch**
- The emergency framing must read as silly, not anxiety-inducing — heavy use of the cream canvas + pickle green keeps it warm.
- Comedy has a fatigue ceiling — we'll cap doodles per section so the page breathes.

---

### 🌴 Direction B — **"DESERT POSTCARD, 1962"**
*Editorial · Mid-century Palm Springs travel postcard meets sun-bleached scrapbook · Cheeky margin doodles*

**Mood (one sentence)**
A vintage Palm Springs travel magazine — heavy serif headlines, cream paper stock, terracotta and desert-sage accents, polaroid sandwich photos pinned with washi tape, and tiny hand-drawn doodles whispering jokes in the margins.

**Style backbone** (per `ui-ux-pro-max` skill output)
- **Style A**: Editorial Grid / Magazine (asymmetric grid, drop caps, pull quotes, multi-column)
- **Style B**: Vintage Analog / Retro Film (subtle grain, warm sepia tint, light leak gradients)
- **Style C**: Nature Distilled (terracotta, sand, sage palette anchoring)

**Color palette**
- **Canvas** `#F4ECDC` — Sun-bleached cream (vintage paper, never pure white)
- **Primary** `#C7572B` — Terracotta (Palm Springs adobe, cocktail-hour Negroni)
- **Secondary** `#8FA787` — Desert sage (cactus, golf-course-gone-dry, palm shadow)
- **Accent** `#1F3A56` — Vintage navy (Sinatra suit, deep poolside shade)
- **Highlight** `#F2A03F` — Citrus marigold (used sparingly — drop caps, key CTAs, the lone "OPEN" sign glow)

**Typography**
- **Display heading**: Big Caslon (or Cormorant Garamond as close substitute on Google Fonts) — high contrast, editorial
- **Subhead / pull quotes**: Karla 600/700 — humanist sans, breathes against the serif
- **Marginalia / doodle labels**: Caveat — handwritten, but used sparingly so it stays personal not chaotic
- **Body**: Karla 400 — clean, readable, modern foil to the serif

**Layout pattern**
1. **Magazine cover hero** — full viewport, sun-bleached cream canvas, big editorial layout:
   - Top-left: "VOL. XV · ISSUE 4 · APRIL 2026" + a serial number
   - Center: Big Caslon headline "THE SANDWICH SPOT" (single line, oversized clamp(3rem, 11vw, 9rem))
   - Subhead in Karla, cap-locked: "276 NORTH PALM CANYON DR · OPEN DAILY · DUTCH CRUNCH SINCE 2007"
   - A pinned polaroid of the storefront with washi tape rotated 4°, captioned in Caveat: "the only address that matters"
   - Bottom: cover-line teases ("INSIDE: HOW DOCTOR DENA INVENTED THE BOMB SAUCE · A LETTER TO THE FEDERER · WHY THE LINE IS WORTH IT")
   - One small marginalia doodle: a martini glass next to "open at 10am — yes, even on Sundays."
2. **Drop-cap intro paragraph** — a single 2-paragraph editorial-style intro to the shop. First paragraph opens with a 4em terracotta drop cap. Pulled-out pull quote in the right column: "Open the door. The bread is *that* good."
3. **The Menu — laid out as a magazine spread** — two-column asymmetric grid. Left column wider, items numbered in Big Caslon, ingredients in Karla. Right column floats two polaroid-style doodle illustrations per page-fold with washi tape, captioned in Caveat. Drop caps every 6 entries to break rhythm.
4. **"THE PALM SPRINGS HALL OF FAME" sidebar** — small Caveat-annotated portraits explaining the celebrity references behind the menu (Sinatra, Hope, Manilow, Dinah, Sonny & Cher, Federer, Djokovic) — gives tourists context, gives locals a smile.
5. **A travel-magazine aside on Dutch Crunch bread** — half-page editorial deep-dive with a sketched cross-section diagram of the loaf, labeled like a Wired-magazine infographic ("the crust: shatters at exactly 0.4 bar of pressure," "the crumb: 30% air, 100% honest").
6. **Reviews as letters-to-the-editor** — 3 customer quotes formatted as blockquotes in Karla italic, with sender attribution like "Andrea S., Indian Wells · April 2026."
7. **Address / hours / map** — a designed-postcard block, terracotta border, "WISH YOU WERE HERE" stamp graphic in citrus marigold, address typed like a postcard, map sketch in navy ink.
8. **Footer** — single-line "© THE SANDWICH SPOT, PALM SPRINGS · LOVE ALL ♥ FEED ALL · MMVII–PRESENT" in Big Caslon small-caps, social icons as classified-ad badges, Banana Bytes credit.

**Signature moves**
- **The magazine cover hero** — most editorial sandwich-shop site you'll ever see.
- **Dutch Crunch infographic deep-dive** — turns their signature bread into a story.
- **Hall of Fame sidebar** — turns the menu into a Palm Springs history lesson.

**Animation approach**
- Page-flip-style scroll: very subtle parallax on polaroids (translateY shifts on scroll), film grain overlay (`::before` SVG noise filter), light-leak gradient that drifts at 30s loop in the corner of hero.
- Polaroids reveal on scroll with a soft fade + 1° rotation.
- Drop caps fade in with the section.
- All gated by `prefers-reduced-motion`.

**What to avoid**
- ❌ Aged-paper kitsch (we want refined-vintage, not Pinterest farmhouse).
- ❌ Sepia overdose — use grain at ~10% opacity, never more.
- ❌ Hand-drawn EVERYTHING — Caveat is the seasoning, Big Caslon is the meal.
- ❌ Liquid glass / morphism (the skill suggested it; we're rejecting — wrong register entirely for this brand).
- ❌ Centered everything — magazine spreads are asymmetric or they're nothing.

**Risks to watch**
- Editorial style needs serious hierarchy discipline — if any column gets 3+ doodles it collapses.
- Big Caslon at heavy weight on cream canvas needs careful contrast tuning to hit WCAG AA.

---

## 4. How A and B Are Meaningfully Different

| Dimension | Direction A — Emergency | Direction B — Postcard |
|---|---|---|
| **Register** | Loud, comedic, urgent | Refined, editorial, quietly cheeky |
| **Primary feel** | Punk-zine + 911 dispatch + diner | Travel magazine + scrapbook + supper club |
| **Color anchor** | Tomato red on mayo cream | Terracotta on sun-bleached cream |
| **Type voice** | Anton SCREAMING + Caveat scribble | Big Caslon STORYTELLING + Caveat whispers |
| **Layout DNA** | Block grid, hard borders, 4px offset shadows | Asymmetric magazine columns, drop caps, pull quotes |
| **Doodle role** | Front and center — every section has 3+ | Marginalia — used as accent, not lead |
| **Hero metaphor** | Hotline dispatcher, ER triage | Magazine cover, postcard rack |
| **Best when** | Dena wants to lean fully into the comedy | Dena wants Palm Springs heritage front and center |

A reader landing on A laughs first. A reader landing on B feels the place's history first, then catches the joke.

---

## 5. The Doodle Illustration Set — Three-Tier Generation Plan

Both directions share a doodle illustration vocabulary. We'll generate ~10–14 doodles to cover both mockups, with style consistency locked at the prompt level. Generation route per the project tier system:

**Style lock (same for every prompt — copy this paragraph into every prompt)**
> *"Single-weight black ink hand-drawn doodle on warm cream paper, like a Sharpie sketch in a deli notebook. Loose confident lines, slight wobble, no shading except minimal cross-hatch for texture, no color fills, no background, transparent or paper-cream backdrop. Style of a 1960s diner placemat doodle crossed with a New Yorker spot illustration."*

This locks character consistency. Every prompt below is **subject + scene** added to the style lock.

### 5A. Auto-pipeline tier order (per CLAUDE.md)

| Slot type | Tier 1 (default) | Tier 2 (escalate if QA fails) |
|---|---|---|
| **Pure shape doodle (sandwich, palm tree, racket)** | Grok Imagine Standard 2K ($0.02) | Gemini Nano Banana 2 2K ($0.101) |
| **Doodle WITH text on sign / banner / patch** | Skip Grok — text rendering — start at Gemini NB Pro 2K ($0.134) | (already at Pro; flag for Daddy if fails) |

### 5B. The Doodle Set (final list — 12 illustrations)

| # | Slot | Aspect | Has Text? | Tier 1 |
|---|---|---|---|---|
| D1 | Hero illustration: sandwich on a stretcher | 1:1 | No | Grok |
| D2 | Hero illustration: vintage rotary phone | 1:1 | No | Grok |
| D3 | Doctor Dena character (recurring annotator) | 4:5 | No | Grok |
| D4 | Sinatra fedora + martini glass | 1:1 | No | Grok |
| D5 | Tennis racket + tennis ball | 1:1 | No | Grok |
| D6 | Suzanne Somers Thighmaster (the device) | 1:1 | No | Grok |
| D7 | Bob Hope golf club + golf ball | 1:1 | No | Grok |
| D8 | Dutch Crunch loaf cross-section diagram (with arrows + text labels) | 16:9 | YES | Gemini NB Pro |
| D9 | "WISH YOU WERE HERE" postcard stamp | 1:1 | YES | Gemini NB Pro |
| D10 | Palm tree + palm canyon mountains skyline | 16:9 | No | Grok |
| D11 | Map sketch — Palm Canyon Drive with shop marked | 4:3 | No | Grok |
| D12 | Hand holding a Dutch Crunch sandwich, mid-bite | 4:5 | No | Grok |

**Estimated cost**: 10× Grok = $0.20 + 2× NB Pro = $0.27 → **$0.47 total** (well under $0.75 build cap).

### 5C. The actual prompts — Grok-optimized (Tier 1)

For each, **prepend the Style Lock paragraph** then add the subject/scene. Aim for 50–80 words total. Built per `GROK_IMAGE_PROMPTS.md` guidance.

**D1 — Hero: sandwich on a stretcher**
> [STYLE LOCK]. A heroic 4-tiered Dutch Crunch sandwich strapped to a hospital stretcher, two tiny EMT figures rushing it through swinging ER doors. The sandwich has tomato slices and lettuce poking out comically. Motion lines suggest urgency. Composition: full subject centered, slightly low angle, single-weight black ink, loose confident strokes.

**D2 — Hero: vintage rotary phone**
> [STYLE LOCK]. A 1950s rotary telephone, receiver lifted off the cradle, a curling phone cord. Above the receiver, three radiating sound waves. The phone slightly tilted ~5° to the right. Composition: phone fills frame, paper background visible, no shadow base.

**D3 — Doctor Dena (recurring character)**
> [STYLE LOCK]. A friendly middle-aged woman in a deli apron, wearing a doctor's stethoscope around her neck and a white paper cap, holding a Dutch Crunch sandwich up to the light like a doctor reading an X-ray. Warm laugh lines around her eyes, kind smile. Bust-up framing, three-quarter angle. She must look approachable and matronly, not clinical.

**D4 — Sinatra fedora + martini**
> [STYLE LOCK]. A 1960s Rat Pack-era fedora resting on top of a classic V-shaped martini glass with an olive on a toothpick. The hat brim casts no shadow but its silhouette overlaps the rim of the glass. Composition: centered, vertical, both elements equal weight.

**D5 — Tennis racket + ball**
> [STYLE LOCK]. A wooden vintage tennis racket (laced strings, oval head) leaning at 30° with a tennis ball resting in its sweet spot. Loose hatching on the strings. The racket head fills the upper-left, handle extending to lower-right. Composition: dynamic diagonal, single subject, clean negative space.

**D6 — Thighmaster**
> [STYLE LOCK]. A 1980s Suzanne Somers Thighmaster exercise device — two padded grips connected by a curved spring. Drawn from a three-quarter angle with the spring slightly compressed. Composition: object centered, isolated, single confident black line.

**D7 — Bob Hope golf club + ball**
> [STYLE LOCK]. A wooden golf driver with a checkered grip resting at a 45° angle, a golf ball just below the club face with motion lines suggesting it was just struck. Composition: centered diagonal, hatching on the club face for grip texture.

**D10 — Palm tree + Palm Canyon mountains**
> [STYLE LOCK]. A single tall California fan palm tree on the left third of the frame, its fronds drawn loosely. Behind it, the silhouette of the San Jacinto Mountains as simple jagged lines stretching across the horizon. A rising sun (just an arc and three rays) in the upper-right. Composition: 16:9 landscape, low horizon line, lots of sky.

**D11 — Palm Canyon Drive map sketch**
> [STYLE LOCK]. A hand-drawn map of a small downtown street grid — North Palm Canyon Drive running vertically, two cross streets. A bold ❌ marker on one block labeled "U R HERE" in slight all-caps handwriting. Tiny doodles of a palm tree on one corner, a mountain range to the west. Loose, like a pirate map. 4:3 landscape composition.

**D12 — Hand holding Dutch Crunch mid-bite**
> [STYLE LOCK]. A human hand from the wrist up holding a giant Dutch Crunch sandwich, one bite already taken (visible jagged tooth marks). Sandwich layers visible at the bite — bread, lettuce, tomato, meat. The hand drawn loosely, fingers expressive. Composition: 4:5 portrait, hand centered, sandwich filling 60% of frame.

### 5D. The text-bearing prompts — Nano Banana Pro (Tier 2 first attempt)

Nano Banana Pro renders text correctly ~94% of the time vs. Grok's ~50% — for these two we skip Grok.

**D8 — Dutch Crunch cross-section infographic**
> [STYLE LOCK — modified: this one allows arrow callouts and letter labels]. A side-view cross-section of a Dutch Crunch loaf cut in half. The crust is drawn with a textured cracked-pattern doodle. The crumb shows airy holes. Three thin black arrows point to: (1) "THE CRUST · shatters on contact" labeled in handwritten Caveat-style letters (2) "THE CRUMB · 30% air" (3) "BAKED AT DAWN · daily." All text rendered in clean handwritten black ink, no other colors. Composition: 16:9 landscape, loaf centered, arrows fanning out.

**D9 — "WISH YOU WERE HERE" stamp**
> [STYLE LOCK]. A vintage rectangular postcard postage-stamp design with perforated edges, drawn as a doodle. Inside the stamp: the words "WISH YOU WERE HERE" in clean handwritten block letters, and below them a tiny doodle of a martini glass with a sandwich speared on the toothpick. Composition: 1:1 square, stamp centered, paper-cream background visible around it.

### 5E. ChatGPT (gpt-image-1.5) backup prompts — for Daddy to run manually

Per project policy, OpenAI is **manual-only post-delivery** if Grok + Gemini both fail. Per the OpenAI cookbook prompting guide, gpt-image-1.5 likes the structure: **`background/scene → subject → key details → constraints + medium reference`**, with quotes around literal text and explicit "no" lists.

When a doodle slot fails Grok and fails Gemini, here's how to write the gpt-image-1.5 fallback:

**Template**
```
Medium: hand-drawn black ink doodle illustration, single-line-weight, loose confident pen strokes, no color, no shading except minimal cross-hatch, transparent background.

Subject: [the thing — e.g., "a Dutch Crunch sandwich strapped to a hospital stretcher being rushed through ER doors"]

Key details: [composition, angle, what's centered, what fills the frame]

Constraints: no watermark, no logos, no color fills, no photograph realism, no AI-generated rendering style, no shadow gradients, no background scenery beyond what's described.

Reference: the doodle should feel like a 1960s diner placemat sketch crossed with a New Yorker spot illustration. Aspect ratio 1:1. Quality: high.
```

**Why this template works for gpt-image-1.5 specifically**:
1. Leads with **medium** — the cookbook says quality cues should come early and use specific medium references ("technical illustration") not generic words ("good quality").
2. Uses the **labeled-segment structure** the cookbook recommends for complex prompts.
3. Lists **explicit exclusions** ("no watermark, no logos, no color") — gpt-image-1.5 honors negative space.
4. Locks **literal text in quotes** when text is required (e.g., `the words "WISH YOU WERE HERE" rendered as block letters`).
5. Sets **quality='high'** because doodle linework is detail-sensitive — medium quality muddies fine line strokes.
6. Sets **background='transparent'** in the API param (or use the prompt phrase "transparent background") so we can layer doodles cleanly into the HTML.

**Daddy's workflow**: when a flagged doodle comes back from auto-pipeline, paste the template into ChatGPT (or the OpenAI Images API), swap [Subject] and [Key details], generate, drop the result into `images/`, and we'll commit it.

---

## 6. Image Shot List — for a Real Photoshoot (Future Upgrade)

If Dena ever wants to invest in real photography (highly recommended for the hero polaroids in Direction B), here's the prioritized shot list. Keep the shoot in-store one weekday morning before opening — natural light through the storefront, no flash.

**Priority A — must-haves**
1. **Storefront from across Palm Canyon Drive** — wide, with the Henry Frank Arcade architecture visible. Morning light, no people. Used in B's hero polaroid.
2. **Counter staff making a sandwich** — over-the-shoulder, hands and bread visible, faces optional. Captures the mom-and-pop labor.
3. **Dutch Crunch loaf cross-section** — natural light, on a wooden board, single sandwich cut to show the crumb. The hero shot of the brand's signature.
4. **The patio courtyard** — wide, with a sandwich basket on a table, natural shadow from the umbrella.
5. **Customer mid-bite** — candid, 3/4 angle, eyes closed in joy. The "worth the wait" payoff shot.

**Priority B — nice-to-haves**
6. The lollipop bin by the register (a tiny detail reviewers obsess over).
7. The sun-tea pitcher on the counter.
8. A flat-lay of 3 sandwich halves (Federer, Chairman, Dinah) on parchment.
9. The Open neon sign in the window (B-roll for hero animations).
10. Dena and/or Corlyn behind the counter (only if they want — this is the most powerful brand shot if they're game).

Style: warm, natural light, slightly desaturated (matches B's vintage palette), no harsh flash, no overhead fluorescent shots.

---

## 7. Copy Audit & Voice Recommendations

The current Wix site is text-only and almost monastic — no voice anywhere. Suggested copy positioning across both directions:

**Hero positioning options** (Direction A favors #1, Direction B favors #2)
1. *"Sandwich emergency response team. Operating since the dawn of Dutch Crunch. 276 N Palm Canyon."*
2. *"Twenty-four sandwiches. One Dutch Crunch. Fifty years of Palm Springs in every bite."*

**About-section options**
- *"We've been feeding Palm Springs since 2007 — locals, tourists, tennis pros, tour buses, the lunch rush at City Hall, and at least one famous insurance commercial. The bread is baked here every morning. The sandwiches are named after people you'd recognize. We'd rather make you laugh than make you feel fancy."*

**Menu intro**
- *"Twenty-four sandwiches. Each named after someone who either won a Grand Slam, sang at the Riviera, or made Palm Springs Palm Springs. None of them are subtle."*

**Doctor Dena's prescriptions** (Direction A only)
- *"This will fix what ails you. Twice daily. Do not consume on an empty calendar."*
- *"Recommended for: hangover. Heartbreak. Indian Wells fatigue."*

**Letter-to-the-editor voice** (Direction B reviews)
- Frame customer reviews as "Dear editors — I would like to submit my findings on the Dutch Crunch."

**Words to keep using**: bomb sauce, Dutch Crunch, Love All ♥ Feed All, "since 2007"
**Words to retire**: "movement," "ethos," "vibes" (current franchise voice — too generic)

---

## 8. Production Notes (when we eventually build)

**Stack**: vanilla HTML + Tailwind CDN per CLAUDE.md, no build step. Both directions can ship as side-by-side mockups (`direction-emergency.html` and `direction-postcard.html`) with an `index.html` selector page.

**Performance budget**:
- Total page weight target < 2MB (12 doodles + ~3 hotlinked photos + fonts + Tailwind CDN).
- Tailwind CDN is unoptimized — accept the tradeoff for mockup speed.
- Doodles served as 2K JPEG (Grok native) but the HTML uses `loading="lazy"` and CSS `image-rendering: crisp-edges` to keep linework clean at smaller display sizes.

**Type loading**:
- Direction A: `<link>` Anton + Caveat + Inter from Google Fonts — 3 families, ~80kb.
- Direction B: `<link>` Cormorant Garamond + Karla + Caveat — ~95kb.
- Use `display=swap` on both.

**Required share preview** (per CLAUDE.md):
- `og.jpg` 1200×630 — Direction A: hero collage with the title; Direction B: magazine cover hero crop.
- `favicon.png` from the existing circle Sandwich Spot logo (we have this — visible on the storefront photo at `research/sandwich-spot-5.jpg`).
- Per-direction OG sub-pages for the two mockup variants.

**Required Banana Bytes footer** (per CLAUDE.md): styled to blend with each direction.

**Trends used (BLAST mode rule, sanity-check only)**:
- Direction A: Anti-polish hand-drawn (matches `TRENDS_QUICK_REFERENCE.md`); Newbrutalism/heavy-borders.
- Direction B: Editorial magazine; vintage analog grain; desert-earth palette.

> Note: PRO-MAX mode skips `TRENDS_QUICK_REFERENCE.md` per CLAUDE.md. Listed above only as cross-check that both directions are currently fashionable, not derivative.

---

## 9. 21st.dev Component Provenance (cached)

Saved to `21st-sources/` for HANDOFF:
- `marquee-text-marque.tsx` — driving the Direction A emergency ticker.
- `menu-item-card.tsx` — base card structure for both menu lists.
- `connoisseur-stack-interactor.tsx` — Direction B menu navigator hover/clip-path pattern.
- `polaroid-flick-through.tsx` — Direction B polaroid scatter; Direction A sticker-pile chaos.

Additional components surfaced (not yet cached) to grab during the build:
- A neubrutalist glass card (Direction A "WHAT'S YOUR EMERGENCY?" picker)
- An asymmetric editorial hero with drop-cap (Direction B magazine cover)
- A footer with vintage-postcard frame (Direction B postcard-block)

---

## 10. Open Questions for Dena

Confirm before build starts:

1. **Owner / contact name on the site** — should Dena, Corlyn, or both be named? Any reference to the late previous owner you'd like preserved (subtle, tasteful)?
2. **Phone vs. online ordering** — site currently routes to phone only. Is online ordering planned, or stick with `tel:` link?
3. **Catering CTA priority** — currently buried on the franchise menu. Is this a real revenue driver Dena wants surfaced?
4. **The cheeky names** — are The DILF, The MILF, The Dirty Weekend explicitly **on the site** (they're on the in-store menu)? Some clients prefer to keep edgier names off the website. Default assumption: keep them, they're the brand.
5. **Photoshoot appetite** — willing to budget for a 2-hour pro shoot? Cheap (~$300–500) and would unlock Direction B's full potential.
6. **Direction preference signal** — A or B? Or build both and let her pick?

---

## 11. Build Time Estimate

When we move to BUILD phase (next session per Daddy's note):

| Phase | Direction A | Direction B | Both |
|---|---|---|---|
| READ (already done) | 0 | 0 | 0 |
| DIRECTION (already done in this brief) | 0 | 0 | 0 |
| BUILD (HTML + animations) | ~4–5 min | ~4–5 min | ~8–10 min |
| Image generation (10 Grok + 2 NB Pro) | ~3 min | (shared) | ~3 min |
| QA + edits | ~2 min | ~2 min | ~3 min |
| VERIFY + BRIEF + PUBLISH | ~2 min | ~2 min | ~3 min |
| **Live link delivery** | ~10 min | ~10 min | **~17 min** |

Image cost: ~$0.47 for the doodle set (covers both mockups).

---

## 12. Reference

- Source site: https://www.thesandwichspot.com/palm-springs-menu
- Independent PS site: https://www.sandwichspotps.com/
- Yelp: https://www.yelp.com/biz/the-sandwich-spot-palm-springs
- TripAdvisor: https://www.tripadvisor.com/Restaurant_Review-g32847-d3407245-Reviews-The_Sandwich_Spot-Palm_Springs_Greater_Palm_Springs_California.html
- Instagram (PS-specific): @thesandwichspotps
- Background photo source: California Through My Lens — sandwich-spot-5.jpg (storefront), sandwich-spot-3.jpg (sandwich + chips), sandwich-spot-4.jpg (Dinah cross-section)
- 21st.dev components saved in `21st-sources/`
- OpenAI gpt-image-1.5 prompting guide: https://developers.openai.com/cookbook/examples/multimodal/image-gen-1.5-prompting_guide
