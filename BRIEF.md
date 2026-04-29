# The Sandwich Spot — Palm Springs · Design Brief

**Mode**: PRO-MAX (`ui-ux-pro-max` skill + 21st.dev Inspiration + Logo Search)
**Built**: 2026-04-28
**Contact**: Dena Banes · Denabanes@aol.com · (760) 778-7900
**Operator**: Corlyn Saldana (current owner since 2021); franchise of Sandwich Spot, founded 2007 in Sacramento, CA

---

## Brand Synopsis

The Sandwich Spot Palm Springs is an independently-operated franchise location at 276 N Palm Canyon Drive — Henry Frank Arcade, across from the Hyatt — that has built a beloved local identity distinct from any other Sandwich Spot in California, Nevada, Arizona, or Texas. **4.7★ on Yelp with 2,457+ reviews · #4 of 345 restaurants on TripAdvisor · 1,651 photos.** The shop's signature is its proprietary Dutch Crunch bread, baked fresh in-house every morning, and a menu of 24 specialty sandwiches at $14.75 each — every sandwich named after either a tennis legend (Federer, Djokovic, Rafa, Indian Wells, French Open, Serve and Volley — referencing the BNP Paribas Open at Indian Wells in their backyard) or a Palm Springs cultural icon (Sinatra, Bob Hope, Manilow, Sonny & Cher, Dinah Shore, Suzanne Somers, Gene Autry). The voice is irreverent (sandwiches called The DILF, The MILF, The Dirty Weekend, But It's a Dry Heat), the staff treats everyone like family, and the line at noon during BNP Paribas week is real.

**The differentiation problem the redesign solves**: the official franchise site is a tired Wix template that mutes all of this. Dena wants the Palm Springs branch to feel like its own thing — comedic, hometown, deeply local, distinguishable from the franchise the second the page loads.

---

## Design Decisions — Two Directions

Both directions share: doodle illustrations from the same artist's hand, real verified content, "LOVE ALL ♥ FEED ALL" tagline, mobile-first responsive layout, IntersectionObserver scroll reveals gated by `prefers-reduced-motion`, full OG/Twitter/favicon meta, Banana Bytes credit footer.

They differ in **register**: A is comedy-club loud, B is supper-club refined-but-cheeky.

### Direction: A — "SANDWICH EMERGENCY" 🚨
**File**: `direction-emergency.html`

- **Mood**: A 911 sandwich emergency hotline running out of a converted radio station — chunky black borders, screaming red headlines, mustard ticker tape, doodles taped on at angles, customer reviews ripped out like newspaper clippings.
- **Style backbone** (per `ui-ux-pro-max --design-system`): Vibrant & Block-based + Newbrutalism (chunky 4px black borders, hard 6px offset shadows, no gradients), with Anti-Polish hand-drawn texturing accent.
- **Fonts**: Anton (display, single-weight 900 condensed) + Caveat (handwritten marker accent) + Inter (body 400/500/600/700). Loaded via Google Fonts `<link>` with `display=swap`.
- **Colors**:
  - `#E63946` Tomato red (primary — alarm, deli classic)
  - `#FFC83D` Mustard yellow (secondary — bread crust, taxi-cab "URGENT")
  - `#6B8E23` Pickle green (accent — handwritten captions)
  - `#111111` Marker black (every border, every doodle outline)
  - `#FAF6E9` Mayo cream (canvas — paper-bag warmth)
- **Layout**: Newbrutalist block grid with intentional rotation (-3° to +3°) on stickers, doodles, review clippings.
- **Signature moves**:
  1. Sticky scrolling **EMERGENCY HOTLINE ticker** at the top (referencing 21st.dev Text Marquee).
  2. **"What's Your Emergency?" 3-card triage picker** (Mild Hunger / Severe Hangover / Total System Failure).
  3. **"Doctor Dena"** — a recurring doodle character who annotates the menu in three handwritten Caveat margin notes.
  4. **24-sandwich classified-ad menu chart** with celebrity Easter-egg doodles interspersed (fedora+martini for Sinatra, tennis racket for the tennis trio, golf club for Hope, Thighmaster for Somers).
  5. **Reviews-as-newspaper-clippings** with star-stamped headers.
- **Trends used (BLAST mode rule, kept as a sanity check)**: Newbrutalism, Anti-Polish, Vibrant Block-based.
- **Logos used (Logo Search)**: none — kept all icons as text/SVG/Anton type to maintain the aesthetic.

### Direction: B — "DESERT POSTCARD, 1962" 🌴
**File**: `direction-postcard.html`

- **Mood**: A vintage Palm Springs travel magazine — heavy serif headlines, cream paper stock, terracotta and desert-sage accents, polaroid sandwich photos pinned with washi tape, and tiny hand-drawn doodles whispering jokes in the margins.
- **Style backbone** (per `ui-ux-pro-max --design-system`): Editorial Grid / Magazine + Vintage Analog / Retro Film + Nature Distilled. We rejected the skill's first suggestion (Liquid Glass) as a category error for the brand and went with the second-tier matches that fit better.
- **Fonts**: Cormorant Garamond (display + body serif, 400/500/600/700, italics) + Karla (sans for masthead/labels/small caps tracking) + Caveat (margin doodles only, used sparingly). Loaded via Google Fonts `<link>` with `display=swap`.
- **Colors**:
  - `#F4ECDC` Sun-bleached cream (canvas)
  - `#C7572B` Terracotta (primary — Palm Springs adobe, cocktail-hour Negroni)
  - `#8FA787` Desert sage (secondary — palm-shadow green)
  - `#1F3A56` Vintage navy (deep — Sinatra suit, poolside shade)
  - `#F2A03F` Citrus marigold (highlight — drop caps, key CTAs, marigold accents on navy)
- **Layout**: Asymmetric magazine-spread grid with drop caps, pull quotes, multi-column menu lists, and side-by-side polaroids with washi-tape `::after` pseudo-elements.
- **Signature moves**:
  1. **Magazine-cover hero** with a Vol/Issue masthead, oversized serif headline, pinned-polaroid storefront photo with washi-tape, four cover-line teasers in italic serif.
  2. **Drop-cap editorial story** with terracotta drop cap and a navy-bordered pull quote.
  3. **Dutch Crunch field-guide infographic** — the cross-section diagram (NB Pro generated) with three labeled callouts treated as a Wired-magazine deep-dive.
  4. **"The Palm Springs Hall of Fame" sidebar** (on a navy background with marigold accents) explaining the celebrity references behind 9 menu items — turns the menu into a Palm Springs history lesson.
  5. **Postcard visit block** — a navy-bordered postcard frame with palm/mountains doodle on the left and address card on the right, WISH YOU WERE HERE stamp pinned in the corner.
  6. **Letters-to-the-editor reviews** — customer quotes formatted as italicised serif blockquotes with sender attribution.
- **Trends used**: Editorial Grid, Vintage Analog (subtle SVG noise grain at 55% opacity multiply, light-leak gradient at 25% opacity), Nature Distilled palette.
- **Logos used (Logo Search)**: none — same reasoning as A; the editorial typography sets the tone.

### How A and B differ — quick reference table

| Dimension | Direction A | Direction B |
|---|---|---|
| Register | Loud, comedic, urgent | Refined, editorial, quietly cheeky |
| Hero metaphor | Hotline dispatcher | Magazine cover |
| Color anchor | Tomato red on mayo cream | Terracotta on sun-bleached cream |
| Type voice | Anton screams + Caveat scribbles | Cormorant tells stories + Caveat whispers |
| Doodle role | Front and center, every section | Marginalia accent only |
| Best when | Dena wants the comedy out | Dena wants Palm Springs heritage out |

---

## 21st.dev Component Provenance (cached for HANDOFF)

Saved to `21st-sources/`:

| Mockup section | 21st.dev component | Search query | Source file | What we borrowed |
|---|---|---|---|---|
| Direction A — Top emergency ticker | Text Marquee | `marquee scrolling ticker bar` | `21st-sources/marquee-text-marque.tsx` | Marquee animation pattern (CSS keyframe simpler in vanilla) |
| Both — menu item card structure | Menu Item Card | `menu list illustrated cards` | `21st-sources/menu-item-card.tsx` | Card framing, image+meta hierarchy reference |
| Direction B — menu navigator hover pattern | Connoisseur Stack Interactor | `menu list illustrated cards` | `21st-sources/connoisseur-stack-interactor.tsx` | Big numbered titles + clip-path image-reveal pattern (translated to static editorial layout) |
| Direction B — polaroid scatter | Polaroid Flick-Through | `sticker collage scrapbook` | `21st-sources/polaroid-flick-through.tsx` | Polaroid styling with washi-tape `::after`, scatter+rotate animation reference |

Used as **inspiration only** — translated visual logic from React/Tailwind into vanilla HTML + Tailwind CDN, stripped React scaffolding. All four cached for HANDOFF MODE if Dena moves to a Next.js production build.

---

## Content Inventory

### Real images pulled
- `images/storefront.jpg` — 2015 photo of the actual storefront (CaliforniaThroughMyLens, watermark visible — flagged in ACCURACY.md for replacement before production)
- `images/sandwich-tray.jpg` and `sandwich-mid-bite-real.jpg` — also CaliforniaThroughMyLens reference photos (currently unused)

### AI-generated doodles (12 total)
See `IMAGE_LOG.md` for full audit. Style locked across all 12 to read as a single artist's hand. Cost: $0.468 (10× Grok @ $0.02 = $0.20 + 2× Nano Banana Pro @ $0.134 = $0.268).

### Key copy
- Tagline: **LOVE ALL ♥ FEED ALL** (preserved verbatim from franchise)
- Direction A hero: "Sandwich Emergency Response Team. Operating since the dawn of Dutch Crunch."
- Direction B hero: "The Sandwich Spot. 276 North Palm Canyon Drive. Open Daily. Dutch Crunch baked at dawn. Since MMVII."
- Direction A menu intro: "24 sandwiches. Each named after someone who either won a Grand Slam, sang at the Riviera, or made Palm Springs Palm Springs. None of them are subtle."
- Direction B editorial intro: "For nineteen years, the same small storefront in the Henry Frank Arcade has been baking the same Dutch Crunch loaf at the same hour..."

### Real links preserved
- Phone: `tel:+17607787900` everywhere
- Email: `mailto:Denabanes@aol.com` for catering
- Instagram (PS-specific): `https://www.instagram.com/thesandwichspotps/`
- Facebook: `https://www.facebook.com/SandwichSpotPalmSprings/`
- TikTok (franchise): `https://www.tiktok.com/@thesandwichspotofficial`
- Yelp: `https://www.yelp.com/biz/the-sandwich-spot-palm-springs`
- Google Maps directions: deep-link formatted

---

## Share Preview

| Asset | Source | Spec |
|---|---|---|
| `images/og.jpg` (index) | Composed locally with PIL — tomato/navy split with sandwich-stretcher (A) and palm-mountains (B) doodles, "VS." composition | 1200×630, JPEG q85, ~89KB |
| `images/og-emergency.jpg` (Direction A) | Composed locally — tomato red half with "SANDWICH EMERGENCY RESPONSE TEAM" Impact text + sandwich-stretcher doodle on cream right | 1200×630, JPEG q85, ~140KB |
| `images/og-postcard.jpg` (Direction B) | Composed locally — magazine masthead "VOL. XV ISSUE 4" + serif headline "The Sandwich / Spot." + palm/mountains doodle backdrop | 1200×630, JPEG q85, ~86KB |
| `images/favicon.png` | PIL-generated tomato circle with bold "SS" cream letterforms, black ring | 192×192 |
| `images/favicon-512.png` | Same design at 512×512 for Apple touch icon | 512×512 |
| **Theme color (A)** | `#E63946` (tomato) | |
| **Theme color (B)** | `#F4ECDC` (cream) | |
| **Theme color (index)** | `#FAF6E9` (cream) | |

OG titles + descriptions written distinct per page. All `og:image` tags use absolute `https://banana-daddy.github.io/...` URLs (relative paths silently fail in preview-card renderers).

---

## Build Timing

Tracked from build start `2026-04-28 19:02:25 PDT`:

| Phase | Duration |
|---|---|
| Step 1: READ + DIRECTION (BLUEPRINT phase, prior session) | ~15 min |
| Step 2: BUILD — image generation (12 doodles, all first attempt) | 1m 45s |
| Step 3: BUILD — Direction A HTML | 4 min |
| Step 4: VERIFY — Direction A in preview | 2 min |
| Step 5: BUILD — Direction B HTML | 5 min |
| Step 6: VERIFY — Direction B in preview | 2 min |
| Step 7: BUILD — index selector page | 2 min |
| Step 8: BUILD — OG composites + favicon (PIL) | 1 min |
| Step 9: VERIFY accuracy + write BRIEF/IMAGE_LOG/ACCURACY | 4 min |
| Step 10: PUBLISH — git + Pages | (in progress) |
| **Total: prompt → live link** | **~22 min build phase + prior research** |

---

## Suggested Next Mockups

If Dena wants to expand:

1. **Catering landing sub-page** — pull the catering trays out of the menu into a focused booking page with party-tray pricing tiers, lead-time form, and an upload-to-quote workflow. Both directions can host this; in B it would feel like a "back-of-the-magazine catering ad."
2. **The Dutch Crunch story** — a long-form editorial micro-site about the bread itself (origin, technique, why it's better than its rivals), tied to a "merch corner" if they ever bake-and-ship. Lives in Direction B's voice.
3. **Tournament-week landing page** — a seasonal page that flips on during BNP Paribas Open week with a dedicated "Federer/Djokovic/Rafa pre-order" form. Goes to text/email an order. High utility, real revenue lever.
4. **Mom-and-pop history page** — a short tribute to the previous owner and the staff legacy, kept understated. Editorial Direction B is the right home.
5. **Mobile-first booking flow** — pre-order through Stripe-checkout deep link, "skip the line" upsell. Realistic for production phase, not for a mockup.

---

## Production Notes

To take this from mockup to production:

- **Stack recommendation**: **Next.js 15 + Tailwind v4 + Vercel**, keeping the same React component vocabulary cached in `21st-sources/`. The four cached components map cleanly back into the production build. CMS optional (no need for the menu — it changes rarely).
- **Hosting**: Vercel free tier covers this. Domain: `sandwichspotps.com` already exists; recommend pointing at the production Vercel project.
- **Performance budget**: Both mockups load < 2MB total (12 doodles + Tailwind CDN + Google Fonts). Production rebuild should self-host fonts and replace Tailwind CDN with the compiled bundle to drop another 200KB.
- **Real photography upgrade**: 2-hour pro shoot at the storefront (~$300–500). Replace `storefront.jpg` (currently watermarked) and add 4–6 atmospheric lifestyle shots (Dutch Crunch cross-section, counter staff hands, patio courtyard, customer mid-bite). Direction B's polaroid hero is where this matters most.
- **Real ordering integration**: site currently uses `tel:` only. Production decision needed — Toast / Square / Square Online / DoorDash / direct Stripe — based on Dena's POS today.
- **Content moderation**: confirm edgier sandwich names (DILF/MILF/Dirty Weekend) stay on the website at full visibility. Currently kept; can dim if needed.
- **Analytics**: GA4 + Vercel Analytics; track menu-anchor clicks, phone-tap conversions.
- **Accessibility audit**: both pages WCAG AA-checked at the spec level (color-contrast, focus states, alt text, reduced-motion gating). Run a lighthouse pass before launch.

Build effort estimate: **2–3 days at Claude Code (Opus, high effort)** for full production rebuild from these mockups, including the points above.
