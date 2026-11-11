---
name: Mr. Polyglot
handle: "@mr_polyglot23"
owner: Sumeru Paul
version: 3.0
updated: 2026-10-28
tagline: "Speak first. Study second."
mission: "Inspire language learners, demonstrate real-world multilingual communication, and build a profitable educational business around speaking languages."
platforms: ["𝕏", LinkedIn, Instagram, Facebook, TikTok, YouTube, Notion]
languages:
  primary: [ENG, FRA, ESP, DEU]
  future:  [ITA, RU, AR, ZH]

# ── COLOR ───────────────────────────────────────────────
colors:
  core:                     # the tight five — use these first
    bronze:     "#6E5E46"   # Mr. Polyglot bronze, sampled from the wordmark (brand color)
    oxblood:    "#8A3B2E"   # main accent on light grounds
    ink:        "#1B1916"   # main text
    paper:      "#F3EFE6"   # main light ground
    sand:       "#C9BCA0"   # rules, borders, dividers
  dark:
    near-black: "#14120F"   # dark slide / video ground
    dark-brown: "#2A241C"   # dark panels
    gold:       "#C9A96A"   # accent on dark grounds only (numbers, rules, highlights)
    cream:      "#F4EFE6"   # large numbers / titles on dark
    light-sand: "#E6DCCB"   # labels & subtitles on dark
  text:
    warm-grey:      "#4A453D"   # secondary text
    body-grey:      "#33302A"   # long-form body (Field Manual)
    bronze-brown:   "#7A6A4F"   # small labels, metadata (min. size for captions on paper)
    deep-bronze:    "#574A35"   # emphasised labels
    taupe:          "#8C8273"   # languages line, large captions only (≥ 24 px)
    muted-taupe:    "#8F8577"   # captions on dark / ≥ 24 px on light
    cover-ink:      "#1F1B16"   # Notion cover titles
  surfaces:
    light-paper: "#FAF7F1"      # cards, panels
    white:       "#FFFFFF"
    hairline:    "#D9D2C5"      # frames
    sticky:      "rgba(243,239,230,0.94)"   # sticky header on paper
  tints:
    sand: ["#E3DCCF", "#EDE6D8", "#E7E1D3", "#F0EADC", "#DCCFB4", "#E4D7BC"]   # panels, table rows, hairlines
    warm: ["#FBF6EC", "#F6DCC8", "#F0C9A8"]                                    # cream & peach highlights

# ── TYPE ────────────────────────────────────────────────
typography:
  brand:                     # primary trio — wordmark, social, Notion
    display: { family: "Instrument Serif", weights: [400], italic: true }      # titles, hooks, section numbers
    sans:    { family: "Space Grotesk",    weights: [300, 400, 500] }          # handle, subtitles, UI, body on social
    mono:    { family: "JetBrains Mono",   weights: [400, 500] }               # language line, labels, counters
  editorial:                 # long-read set — decks, Field Manual, guides, ebooks
    serif: { family: "Newsreader",     weights: [300, 400, 500, 600, 700], italic: true }
    sans:  { family: "IBM Plex Sans",  weights: [300, 400, 500, 600] }
    mono:  { family: "IBM Plex Mono",  weights: [400, 500] }
  fallbacks: ["Noto Serif", "Noto Sans Arabic", "Noto Sans SC"]
  scale:   [12, 14, 16, 20, 24, 32, 44, 64, 96, 144]   # px
  leading: { display: 0.95, heading: 1.1, body: 1.55 }
  tracking:
    handle: "-0.025em"
    languages-line: "0.42em"
    mono-label: "0.18em"
    display: "-0.01em"
  license: "All six families are SIL Open Font License, free on Google Fonts — install locally for Photoshop / Illustrator / Premiere / After Effects."

spacing: [4, 8, 12, 16, 24, 32, 48, 64, 96, 128]
radius:  { tag: 2, card: 4, frame: 12, pill: 999 }   # editorial: near-square corners
stroke:  { hairline: 1, rule: 1.5, underline: 3 }
motion:  { fast: 150ms, base: 220ms, slow: 320ms, easing: "cubic-bezier(0.2, 0, 0, 1)" }
tools:   [Adobe Photoshop, Adobe Illustrator, Adobe Premiere Pro, Adobe After Effects, Notion]
---

# Mr. Polyglot — DESIGN.md

The single source of truth for how **@mr_polyglot23** looks, sounds, is produced and is sold across every platform. Built from the live brand assets — the wordmark, the Polyglot deck, the Field Manual page and the Notion cover & section banners. Feed this file to any designer, editor, template or AI tool before it makes anything for the brand.

**The look in one line:** a warm, editorial field journal — paper, ink and bronze, serif italics, tracked monospace — the feel of a well-travelled linguist's notebook, not a gamified app.

---

## 1. Identity

| | |
|---|---|
| **Creator** | Sumeru Paul, 28 — foreign-language content creator |
| **Brand / handle** | Mr. Polyglot · `@mr_polyglot23` on 𝕏, LinkedIn, Meta (Instagram, Facebook), TikTok; YouTube next |
| **Long-term goal** | One of the world's most recognised multilingual creators and language-learning educators |
| **Credentials** | Sri Aurobindo International Centre of Education (SAICE), Pondicherry — French from age 3 · DELF B1 & B2 (Alliance Française: Pondicherry, Bangalore, Kolkata) · Instituto Cervantes New Delhi, Spanish to A2 · Self-taught German, ongoing |
| **Languages** | Primary `ENG` `FRA` `ESP` `DEU` · Future `ITA` `RU` `AR` `ZH` and more where strategic |
| **Tagline** | *Speak first. Study second.* |

### Wordmark lockup
```
Sumeru Paul's            ← Instrument Serif, Italic 400 · bronze #6E5E46 (or ink)
mr_polyglot23            ← Space Grotesk, Light 300 · tracking −0.025em · ink #1B1916
E N G | F R A | E S P | D E U   ← JetBrains Mono, Regular 400 · tracking 0.42em · taupe #8C8273
```
- Clear space = the cap height of "mr_polyglot23" on all sides.
- Reversed: cream `#F4EFE6` serif + handle, light-sand `#E6DCCB` languages line on near-black `#14120F`.
- Never set the handle bold, never swap the serif for a sans, never recolor the wordmark outside bronze / ink / cream.
- The languages line grows with the brand: add `ITA`, `RU`, `AR`, `ZH` in the same order they are launched.

**Credential strip:** IBM Plex Mono / JetBrains Mono 400, tracking 0.18em, bronze-brown `#7A6A4F`: `SAICE · DELF B1 · DELF B2 · CERVANTES A2 · DEU SELF-TAUGHT`. Used on About slides, landing pages, course covers and banners — never on content frames.

---

## 2. Mission & positioning

**Mission:** inspire language learners · demonstrate real-world multilingual communication · promote learning through practical speaking · encourage cultural curiosity · build a profitable educational business around languages.

| Attribute | How it shows up visually |
|---|---|
| Multilingualism | The tracked languages line on every piece; code-switched captions with translations |
| Internationalism / global citizenship | Field-journal coordinates in mono; real places, real people; no flags as decoration |
| Language learning | Translation Stack as the core component; "say it out loud" prompts |
| Travel & cultural exploration | Docuseries layouts like a travel notebook: full-bleed photo, serif caption, sand hairlines |
| Intelligence & competence | Editorial serif, disciplined grid, restrained earthy palette |
| Confidence | Large italic display lines, generous white space |
| Professionalism | Consistent templates, safe zones, contrast rules — LinkedIn-ready |

**Aesthetic references:** premium-tech restraint, language-app habit loops, field-documentary curiosity, masterclass authority, premium creator consistency — expressed through the warm editorial palette above, never copied from any of them.

**Every asset serves at least one goal:** audience growth · authority · community · lead generation · revenue · product development · brand expansion. Tag it in Notion (§12).

---

## 3. Audience

Language learners · aspiring polyglots · students · young professionals · travellers · globally minded people.

| They want to… | So design must… |
|---|---|
| Speak confidently | Show the line big enough to read and repeat in one view |
| Learn faster | Scannable order: language → line → translation → tip |
| Communicate internationally | Show real conversations, not textbook dialogues |
| Improve career opportunities | LinkedIn assets on paper with credentials and outcomes |
| Explore cultures | Pair phrases with place, food, gesture, context |

---

## 4. Design principles

1. **The language is the hero.** Every visual centres a spoken line, a word, or a face mid-conversation.
2. **Show the language.** Every piece carries the tracked languages line with the active language marked.
3. **Quiet page, one warm accent.** Paper and ink do the work; oxblood (light) or gold (dark) marks the one thing that matters.
4. **Value before promotion.** Teach on the frame; sell in the caption or the last slide.
5. **Authentic over polished.** Real footage, real reactions; the system adds the polish.

### Operating principles → design rules
| Principle | Rule |
|---|---|
| Authenticity | Unretouched faces, live audio; templates frame real moments, never replace them |
| Speaking over theory | A spoken phrase beats a grammar table; tables only in carousels, max 4 rows |
| Practical acquisition | Every frame contains something usable today |
| Value before promotion | ≤ 1 CTA slide per carousel; product mention ≤ 1 in 5 posts |
| Platform-tailored | Use §8 presets; no wrong ratios or other platforms' watermarks |
| Long-term authority | Consistent series names, numbering and covers — collectible |
| Educate / entertain / inspire | Label each piece with one in Notion |
| Trust before selling | Free value ladder before paid offers (§14) |
| Professional yet approachable | Editorial layout + warm, first-person copy |
| Creator + educator + marketer + operator | Every template has a hook, a lesson, a CTA and a tracking tag |

---

## 5. Color

### The tight five (default for everything)
| Token | Hex | Role |
|---|---|---|
| `bronze` | `#6E5E46` | Brand color — wordmark, section numbers, key labels |
| `oxblood` | `#8A3B2E` | The accent on light grounds — highlights, underlines, CTA fill, active language |
| `ink` | `#1B1916` | Main text |
| `paper` | `#F3EFE6` | Main light ground |
| `sand` | `#C9BCA0` | Rules, borders, dividers |

### Dark mode set
| Token | Hex | Role |
|---|---|---|
| `near-black` | `#14120F` | Dark slide, Reel and thumbnail ground |
| `dark-brown` | `#2A241C` | Panels on dark |
| `gold` | `#C9A96A` | The accent on dark only — numbers, rules, active word |
| `cream` | `#F4EFE6` | Titles and big numbers on dark |
| `light-sand` | `#E6DCCB` | Labels and subtitles on dark |

### Text & surfaces
`warm-grey #4A453D` secondary · `body-grey #33302A` long-form body · `bronze-brown #7A6A4F` small labels · `deep-bronze #574A35` emphasised labels · `taupe #8C8273` languages line (≥ 24 px or as decoration) · `muted-taupe #8F8577` captions · `cover-ink #1F1B16` Notion titles · `light-paper #FAF7F1` cards · `white #FFFFFF` · `hairline #D9D2C5` frames · sticky header `rgba(243,239,230,0.94)`.

**Tints:** sand `#E3DCCF #EDE6D8 #E7E1D3 #F0EADC #DCCFB4 #E4D7BC` for panels, table rows, hairlines · warm `#FBF6EC #F6DCC8 #F0C9A8` for highlighted phrases and callouts.

### Rules
- 70 / 25 / 5 — ground / text / accent. One accent moment per frame.
- **Oxblood on light, gold on dark.** Never gold text on paper (fails contrast), never oxblood on near-black.
- Text on oxblood = white or paper. Text on gold = near-black.
- Contrast on paper: ink 15:1 · warm-grey 8:1 · oxblood 6.6:1 · bronze 5.4:1 · bronze-brown 4.6:1 · taupe 3.3:1 (large text only).
- Languages are distinguished by **type, not color**: the active code in oxblood/gold, the others in taupe/light-sand. No per-language rainbow, no flags.

---

## 6. Typography

### Brand trio — wordmark, social, Notion (default)
| Role | Family | Weight | Size (1080 canvas) | Notes |
|---|---|---|---|---|
| Hook / title / section number | Instrument Serif | 400 / italic | 96–144 px | leading 0.95; italic for the key word |
| Spoken line (target language) | Instrument Serif | 400 | 56–80 px | The hero line |
| Translation | Space Grotesk | 300 | 50–60% of spoken line | warm-grey on paper / light-sand on dark |
| Subtitle / body / UI | Space Grotesk | 300–400 | 28–36 px social, 16–18 px web | leading 1.55 |
| Handle | Space Grotesk | 300 | — | tracking −0.025em, lowercase `mr_polyglot23` |
| Languages line, labels, counters | JetBrains Mono | 400 | 18–24 px | UPPERCASE, tracking 0.42em (languages) / 0.18em (labels) |

### Editorial trio — decks, Field Manual, guides, ebooks, newsletter
| Role | Family | Weight |
|---|---|---|
| Headlines, titles, pull quotes, reading body | Newsreader | 300–700 + italics |
| Interface and supporting text | IBM Plex Sans | 300–600 |
| Labels, chapter numbers, small caps, tags | IBM Plex Mono | 400–500 |

**Rule:** never mix the two trios on one asset. Social, banners, thumbnails, Notion → brand trio. Anything meant to be *read* for more than a minute → editorial trio.

- Fallbacks: Noto Serif / Noto Sans Arabic (RTL — mirror layout for AR) / Noto Sans SC.
- Diacritics (é, ñ, ß, ü, ç) must render in the same family.
- French: « guillemets » with thin spaces before `? ! : ;`. Spanish: opening ¿ ¡. German: „Anführungszeichen“.
- Max 3 sizes per frame.

### The Translation Stack (signature component)
```
E N G | F R A | E S P | D E U   ← mono line; active code in oxblood (light) / gold (dark)
« On y va ? »                    ← Instrument Serif 400, key word in italic
Shall we go?                     ← Space Grotesk 300, muted
────────                         ← 3 px oxblood/gold underline under the key word
```

---

## 7. Layout & spacing

- 8-pt grid; spacing `4 8 12 16 24 32 48 64 96 128`.
- Social canvases: 12-column grid, 72 px outer margin (1080 wide).
- **Editorial frame:** a 1 px `hairline #D9D2C5` inset frame 32 px from the edge on covers and banners (as on the Notion cover).
- Corners nearly square: tag 2 · card 4 · video frame 12 · pill 999 (CTA only).
- Corner system: series label (mono, top-left) · slide counter `03 / 10` (mono, top-right) · handle `mr_polyglot23` (Space Grotesk 300, bottom-left) · languages line (bottom-right or under the title).
- Big section numbers: Instrument Serif, cream on dark / bronze on paper, 144–240 px.

---

## 8. Platform canvases & safe zones

| Platform | Format | Size | Safe zone / notes |
|---|---|---|---|
| TikTok / Reels / Shorts | 9:16 | 1080×1920 | Text within y 220–1500, x 72–940 |
| 𝕏 video (long-form) | 16:9 | 1920×1080 | Burned-in subtitles; languages line top-left |
| 𝕏 image / thread header | 16:9 or 4:5 | 1600×900 / 1080×1350 | Hook ≤ 7 words |
| LinkedIn carousel (PDF) | 4:5 | 1080×1350 | 80 px margins, counter top-right, paper ground |
| LinkedIn single image / video | 1:1 or 4:5 | 1200×1200 / 1080×1350 | Credential strip allowed |
| Instagram / Facebook feed | 4:5 | 1080×1350 | Grid crop 1080×1080 centred |
| Instagram / Facebook story | 9:16 | 1080×1920 | Top 250 / bottom 340 clear |
| YouTube thumbnail | 16:9 | 1280×720 | Avoid bottom-right 220×80 |
| YouTube community post | 1:1 | 1080×1080 | 64 px margins |
| Notion cover / section banner | 1500×600 / 1500×300 | | Hairline frame, Instrument Serif title, mono label |
| Profile banners | 𝕏 1500×500 · LinkedIn 1584×396 · YT 2560×1440 (safe 1546×423) | | Wordmark lockup + credential strip |

### Platform tone
- **𝕏:** hook-first, near-black image or raw video, threads with a mono `THREAD · 01/12` header.
- **LinkedIn:** paper ground, editorial trio in carousels, credentials and outcomes.
- **Meta:** Reels-first with near-black covers; saveable paper carousels.
- **TikTok:** native feel; only the lower third + languages line, no heavy frames.
- **YouTube:** cinematic near-black thumbnails, gold numbers, serif titles.

---

## 9. Content pillars & ecosystem

| Pillar | Ground | Accent | Series label | Visual signature |
|---|---|---|---|---|
| 1 · Video Interactions (native speakers, exchanges, OmeTV, MiniChat) — **primary growth** | `near-black` | gold | `LIVE CONVO · FRA → ENG` | Split-screen in a 12 px frame; Translation Stack lower third; reaction freeze-frame thumbnails |
| 2 · Daily Speaking Challenges | `paper` | oxblood | `DAY 017 · SPEAK` | Huge Instrument Serif day number in bronze; one phrase in 3 languages; "Say it out loud" |
| 3 · Docuseries & Vlogs | `light-paper` + photo | bronze | `FIELD NOTES · EP 03` | Field-journal layout: full-bleed photo, serif italic caption, mono coordinates, sand hairlines |
| 4 · Fitness & Personality (< 10%) | `dark-brown` | gold | `DISCIPLINE` | Monochrome warm footage, one gold stat |

| Type | Formats | Template |
|---|---|---|
| Short-form | Reels, TikTok, 𝕏 video, LinkedIn video | 9:16 / 4:5 kit + subtitle style |
| Long-form | 𝕏 video, YouTube | 16:9 kit, chapter cards, end screen |
| Written | 𝕏 posts & threads, LinkedIn posts, carousels, educational graphics | Hook card, carousel kit, phrase card |
| Future | Newsletter, podcast, courses, memberships, community | §14 surfaces |

---

## 10. Components

- **Languages line** — JetBrains Mono 400, tracking 0.42em, `ENG | FRA | ESP | DEU`; taupe / light-sand, active code oxblood / gold.
- **Hook card** — Instrument Serif, ≤ 9 words, one italic word, 3 px accent underline.
- **Translation Stack** — §6.
- **Phrase card** — 1080×1350 paper; one phrase in up to 4 languages separated by sand hairlines, mono code beside each.
- **Day counter** — `DAY` in mono + number in Instrument Serif 200 px, bronze.
- **Lower third** — near-black at 88%, 4 px radius, languages line + spoken line (serif) + translation (Space Grotesk 300); 220 ms rise, 150 ms fade.
- **Subtitles** — Space Grotesk 500, 60 px on 1080×1920, cream with 6 px near-black shadow at 60%; active word in gold; max 2 lines, 32 characters.
- **CTA pill** — oxblood fill + white text (light) / gold fill + near-black text (dark).
- **Section number** — Instrument Serif 144–240 px, cream on dark / bronze on paper.
- **Credential strip** — §1.
- **Sticky header (web)** — `rgba(243,239,230,0.94)` + 1 px sand bottom rule.

---

## 11. Imagery & motion

- **Photography:** natural light, warm grade (lift shadows toward `#2A241C`, highlights toward `#FBF6EC`), real places, real people mid-sentence.
- **Thumbnails:** one face, readable expression, ≤ 4 words in Instrument Serif, gold accent on near-black or darkened footage (45% near-black overlay).
- **Icons:** 1.5 px stroke, square-ish caps, ink or bronze. No emoji in designed graphics.
- **Motion:** calm and precise, 150–320 ms ease-out; serif lines fade-rise word by word; accent underline draws left → right.
- **Avoid:** saturated brights, neon, gradients, glitter, clip-art globes, flags as wallpaper, rounded "app" cards.

---

## 12. Production workflows (Adobe + Notion)

**Install fonts first:** Instrument Serif, Space Grotesk, JetBrains Mono, Newsreader, IBM Plex Sans, IBM Plex Mono — all free from Google Fonts (SIL OFL).

### Photoshop
- Artboard presets for every §8 size, named `MP_<platform>_<format>`.
- Warm-grade adjustment group `MP_Grade` (Curves + Color Balance toward the palette) saved as a preset.
- Thumbnail action: subject select → 45% `#14120F` overlay → serif hook → gold underline.
- Export PNG-24 sRGB (graphics), JPG 85% (photo covers).

### Illustrator
- `MP_Brand_Master.ai`: wordmark lockups (light/dark), languages line, credential strip, section numbers, icons.
- Swatch groups `MP Core` (5), `MP Dark` (5), `MP Text`, `MP Tints` → export `MP_Colors.ase` → share via Creative Cloud Libraries.
- Paragraph/Character Styles named after §6 roles; 10-artboard 1080×1350 carousel kit → one PDF for LinkedIn.

### Premiere Pro
- Presets `MP_9x16_1080x1920_30p`, `MP_16x9_1920x1080_30p`.
- Speech-to-Text → `MP_Subtitles` caption style; translation on a second caption track.
- Lumetri LUT `MP_Warm.cube` matching §11 grade.
- Dialogue −16 LUFS (social); music ducked −18 dB; Enhance Speech on OmeTV/MiniChat audio.
- Repurpose: long-form master → 3–5 verticals → 1 phrase carousel → 1 𝕏 thread.

### After Effects
- MOGRTs: `MP_LowerThird`, `MP_LanguagesLine`, `MP_TranslationStack`, `MP_DayCounter`, `MP_SectionNumber`, `MP_EndCard`.
- Expose only text, active language and light/dark switch.

### Notion
- Cover 1500×600 and section banners 1500×300 follow §8.
- Content database: Pillar · Platform · Language(s) · Format · Goal · Educate/Entertain/Inspire · Status · Publish date · Template · Metrics.
- Asset library page linking every template and MOGRT.

---

## 13. Voice in visuals

- Hooks concrete and spoken: "I asked 10 French strangers one question" beats "Learn French fast".
- Always the target line *and* the translation.
- Numbers as serif numerals for drama, mono for data.
- Code-switching is the brand — always with a translation.
- Approachable professionalism: first person, short sentences.

---

## 14. Monetisation surfaces

**Value ladder:** free content → lead magnet → low-ticket product → membership/community → coaching & workshops & speaking programs → (future) SaaS.

| Offer | Design spec |
|---|---|
| Lead magnets, guides, ebooks, Field Manual | Editorial trio; paper; Newsreader titles; IBM Plex Mono chapter numbers |
| Notion templates | Notion cover style; 3 screenshots in 12 px hairline frames |
| Digital products / resources | Product card: languages line + outcome headline + oxblood CTA |
| Membership / community | Near-black ground, gold `MEMBER · 2026` mono badge, monthly challenge covers |
| Coaching / workshops / speaking programs | Paper landing hero with wordmark lockup + credential strip; time zone in mono |
| Courses | Module covers with big serif numbers `01–12` in bronze |
| Landing pages | Max width 1120 px, Space Grotesk 18 px body, Translation Stack hero, sticky paper header, one oxblood CTA per screen, testimonials only from real students with permission |
| Newsletter | Editorial trio, single column 640 px, mono section labels, oxblood links |
| Future SaaS | Same tokens; paper/light-paper surfaces, languages line as filter |

Every surface carries a UTM-tagged link and a lead-capture CTA; track sign-ups per pillar in Notion.

---

## 15. Pre-publish checklist

- [ ] Languages line present, active language marked
- [ ] Target line + translation both visible
- [ ] One accent moment — oxblood on light, gold on dark
- [ ] Correct trio (brand vs editorial), never mixed
- [ ] Text inside safe zone, correct canvas preset
- [ ] ≤ 3 sizes, contrast ≥ 4.5:1 (taupe only ≥ 24 px)
- [ ] Handle `mr_polyglot23` + series label placed
- [ ] Diacritics/scripts render correctly; punctuation per language
- [ ] Goal tagged in Notion
- [ ] Value delivered before any CTA
