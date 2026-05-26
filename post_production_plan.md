# Post-Production Plan — "The Port That Runs the World"

> **Source of Truth:** `production_package.md`  
> **Final Runtime Target:** 2:45 ± 10 seconds (2:35–2:55 acceptable)  
> **Tone:** Cinematic, clear, exciting  
> **Intended Workflow:** Solo creator or small team using stock footage, motion graphics, and standard NLE (Premiere Pro / DaVinci Resolve)

---

## 1. Master Editing Checklist (Execution Order)

### Phase A — Pre-Edit Setup
- [ ] Import V.O. recording into project; verify clean audio (no pops, breaths trimmed)
- [ ] Set timeline: 4K (3840×2160), 24 fps, 48 kHz audio
- [ ] Create folder structure: `/footage`, `/motion-graphics`, `/music`, `/sfx`, `/vo`, `/exports`
- [ ] Drop V.O. onto track A1; verify total narration length ≈ 2:30–2:40 (leaves room for pacing)
- [ ] Mark V.O. with scene markers at: 0:00 / 0:15 / 0:40 / 1:05 / 1:40 / 2:10 / 2:30

### Phase B — Rough Cut (Picture Lock Priority)
- [ ] Lay placeholder cards for all 7 scenes (colored solids with scene names)
- [ ] Place stock footage clips on V1, rough-cutting to narration rhythm
- [ ] Insert motion-graphic placeholders (still frames or low-res renders) on V2
- [ ] Verify pacing: each scene hits its target duration ±2 s
- [ ] Review rough cut end-to-end; confirm total runtime 2:35–2:55
- [ ] Adjust pacing — tighten or breathe — until within target

### Phase C — Fine Cut
- [ ] Replace placeholders with final motion graphics (V2/V3)
- [ ] Add on-screen text / lower thirds on V4 (per timestamped list below)
- [ ] Apply transitions: dissolves for Scene 3 history; smash cuts for Scene 1/4
- [ ] Trim all cuts to hit musical beats where possible
- [ ] Add speed ramps / time-lapse effects where noted
- [ ] Insert split-screen composite at 1:25–1:30 (Scene 4)

### Phase D — Audio Mix
- [ ] Place music bed on A2; edit to scene transitions
- [ ] Add SFX on A3/A4 per sound-design guide
- [ ] Mix levels: V.O. @ -6 dB, Music @ -18 dB (under V.O.) / -12 dB (no V.O.), SFX @ -12 dB
- [ ] Apply subtle compression + EQ to V.O. (warmth, clarity)
- [ ] Verify no SFX masks narration; duck music during key stat callouts
- [ ] Add 0.5 s silence at 1:18 for dramatic pause

### Phase E — Color & Polish
- [ ] Apply unified LUT / color grade: teal & orange (night/tech scenes), navy & gold (text overlays)
- [ ] Match exposure across stock clips (avoid jarring brightness jumps)
- [ ] Add film grain or subtle vignette for cinematic texture (optional)
- [ ] Verify text legibility on all backgrounds (contrast check)
- [ ] Confirm all motion graphics integrate cleanly (no edge artifacts)

### Phase F — Review & Deliver
- [ ] Watch full cut at 1× speed; note any pacing/dead spots
- [ ] Fact-check all on-screen statistics against risk list (Section 8)
- [ ] Export preview (1080p H.264) for review
- [ ] Make final revisions
- [ ] Export master file (see Section 7)
- [ ] Generate .srt caption file
- [ ] Design and export thumbnail
- [ ] Upload and schedule

---

## 2. Timestamped Edit Decision List (EDL-Style Outline)

| TC In | TC Out | Dur | Track | Source / Description | Transition | Notes |
|-------|--------|-----|-------|---------------------|------------|-------|
| 00:00 | 00:03 | 3 s | V1 | BLACK + SFX foghorn | Hard cut in | Bass rumble builds |
| 00:03 | 00:08 | 5 s | V1 | Aerial night time-lapse — Yangshan port | Smash cut from black | Slow push-in; teal & orange grade |
| 00:08 | 00:12 | 4 s | V2 | Title card: "PORT OF SHANGHAI" | Fade in / fade out | Bold sans-serif, centered |
| 00:08 | 00:12 | 4 s | V1 | Ships at anchor — wide aerial | Under title card | Slight left-to-right track |
| 00:12 | 00:15 | 3 s | V1 | Beacon light close-up on crane | Cut | Detail / texture |
| 00:15 | 00:20 | 5 s | V1 | Satellite zoom: space → China coast | Dissolve from Sc.1 | Google Earth style or MoGraph |
| 00:20 | 00:28 | 8 s | V2 | MoGraph: containers multiply on globe | Over V1 dark BG | Animated counter underneath |
| 00:28 | 00:33 | 5 s | V2 | Counter animation: 0 → 850,000,000 | Continues | Yellow bold numbers |
| 00:33 | 00:37 | 4 s | V1 | Overhead stacked containers — day | Cut | Wide, saturated |
| 00:37 | 00:40 | 3 s | V1 | Port control room screens | Cut | Interior |
| 00:40 | 00:44 | 4 s | V1 | Historical Shanghai waterfront (archival) | Dissolve | Sepia tone / illustrated |
| 00:44 | 00:49 | 5 s | V2 | Animated map: mainland → Yangshan | Over V1 | Dotted line draws |
| 00:49 | 00:57 | 8 s | V1 | Donghai Bridge aerial tracking shot | Cut | Low altitude, dramatic |
| 00:57 | 01:00 | 3 s | V1 | Waves against bridge supports | Cut | Slow-mo |
| 01:00 | 01:05 | 5 s | V1 | Yangshan terminal reveal from bridge | Cut / slight dissolve | "Arrival" beat |
| 01:05 | 01:09 | 4 s | V1 | STS crane — low angle looking up | Hard cut (beat sync) | Dramatic scale |
| 01:09 | 01:12 | 3 s | V1 | Spreader locks onto container | Cut | Close-up detail |
| 01:12 | 01:18 | 6 s | V1 | AGV trucks overhead drone | Cut | No humans visible |
| 01:18 | 01:18.5 | 0.5 s | — | **SILENCE** | — | Beat drop moment |
| 01:18.5 | 01:23 | 4.5 s | V1 | AI control room — slow pan | Cut in on beat | Screens glowing |
| 01:23 | 01:28 | 5 s | V1+V2 | Split-screen: live feed vs. digital twin | Wipe / composite | Side-by-side |
| 01:28 | 01:33 | 5 s | V1 | Robotic yard cranes stacking | Cut | Overhead |
| 01:33 | 01:37 | 4 s | V1 | Night terminal — automated, no people | Cut | Eerie wide shot |
| 01:37 | 01:40 | 3 s | V1 | Transition buffer / port exterior | Dissolve | Bridge to Sc.5 |
| 01:40 | 01:48 | 8 s | V1 | Product montage: phone, shoes, coffee, laptop | Quick cuts (2 s each) | Shipping-label overlay |
| 01:48 | 01:52 | 4 s | V1 | Objects on conveyor belt → container | Cut | Visual metaphor |
| 01:52 | 01:58 | 6 s | V2 | World map: shipping lanes radiate | Over V1 dark BG | Red pulse animation |
| 01:58 | 02:03 | 5 s | V1 | Congested ports / empty shelves (2021) | Cut | News-style, muted color |
| 02:03 | 02:07 | 4 s | V1 | Container ship at sea — aerial | Cut | Return to cinematic |
| 02:07 | 02:10 | 3 s | V1 | Shanghai port — wide, ships moving | Dissolve | Transition to Sc.6 |
| 02:10 | 02:15 | 5 s | V1/V2 | Future terminal concept render | Dissolve | Green tint |
| 02:15 | 02:20 | 5 s | V2 | Port footprint expansion MoGraph | Over V1 | Building animation |
| 02:20 | 02:24 | 4 s | V1 | Solar panels / shore-power at port | Cut | Clean energy feel |
| 02:24 | 02:30 | 6 s | V1 | Sunset aerial — full port rising camera | Slow dissolve out | Golden hour |
| 02:30 | 02:38 | 8 s | V1 | Wide pull-back drone — port to ocean | Continuous move | Cinematic exit |
| 02:38 | 02:45 | 7 s | V2 | End card: logo + subscribe + thumbnails | Dissolve in | Branded template |

---

## 3. Asset Acquisition List

### 3A — Stock Footage

| Priority | Description | Search Terms | Suggested Source | Difficulty | Fallback |
|----------|-------------|--------------|-----------------|------------|----------|
| **HIGH** | Yangshan port aerial — night | "yangshan port night aerial drone" | Artgrid, Shutterstock | ⚠️ Moderate — limited available | Use any large port night aerial (Rotterdam, Singapore) + text overlay identifying it as Shanghai |
| **HIGH** | Donghai Bridge aerial tracking | "donghai bridge china aerial" | Pond5, Shutterstock | ⚠️ Moderate | Use long sea-bridge aerial (Hong Kong–Zhuhai) + map overlay for context |
| **HIGH** | AGV autonomous trucks — formation | "automated port vehicles agv" | Shutterstock, YouTube (CC) | ⚠️ Hard — very specific | Use wide shot of any automated terminal floor; add HUD overlay in post |
| **HIGH** | Ship-to-shore crane — low angle | "container crane loading ship" | Artgrid, Storyblocks | ✅ Easy | — |
| **HIGH** | Container ship at sea — aerial | "cargo ship ocean aerial drone" | Artgrid | ✅ Easy | — |
| **MED** | Port control room interior | "port control room monitors" | Shutterstock | ⚠️ Moderate | Use generic server room / NOC footage + screen-replacement composite |
| **MED** | Product montage: phone, sneakers, coffee | "smartphone close-up," "sneakers shelf," "coffee beans pour" | Storyblocks, Pexels (free) | ✅ Easy | — |
| **MED** | Stacked containers overhead | "container yard overhead drone" | Artgrid, Shutterstock | ✅ Easy | — |
| **MED** | Sunrise / sunset port wide shot | "port sunset golden hour aerial" | Artgrid | ✅ Easy | — |
| **MED** | Waves crashing on bridge / pier | "waves bridge supports slow motion" | Storyblocks | ✅ Easy | — |
| **LOW** | Port congestion / empty shelves 2021 | "supply chain crisis 2021 port" | Pond5, AP Archive | ⚠️ Moderate — editorial pricing | Use royalty-free "empty shelves" + newspaper headline overlay |
| **LOW** | Solar panels on industrial rooftop | "solar panels industrial" | Storyblocks, Pexels | ✅ Easy | — |
| **LOW** | Electric ship charging / shore-power | "electric ship charging port" | Pond5 | ⚠️ Hard — rare topic | Use EV charging close-up + port composite; or motion graphic illustration |
| **LOW** | Rotating beacon light | "warning light crane night" | Shutterstock | ✅ Easy | — |

### 3B — Archival Footage / Images

| Asset | Era | Suggested Source | Notes |
|-------|-----|-----------------|-------|
| Old Shanghai waterfront painting / photo | 1800s–1930s | Wikimedia Commons, Getty Archive, Library of Congress | Verify public domain or CC license |
| Early Shanghai port operations | 1950s–1980s | British Pathé, AP Archive | May require editorial license fee |
| Yangshan / Donghai Bridge construction | 2002–2005 | CCTV archives (rights complex), Alamy | Fallback: use animated "construction" MoGraph instead |

### 3C — Maps & Graphics to Create (Motion Graphics)

| # | Asset | Description | Estimated Effort |
|---|-------|-------------|-----------------|
| 1 | Satellite zoom | Space → China coast → port (Google Earth–style) | 4–6 hrs (After Effects + Earth Studio) |
| 2 | Container globe animation | Containers multiply and wrap around a 3D globe | 6–8 hrs (C4D/Blender or AE with Element 3D) |
| 3 | Counter animation | 0 → 850,000,000 (ticking with commas) | 1–2 hrs (AE expressions) |
| 4 | Animated map: mainland → Yangshan | Dotted line draws from shore to island | 2–3 hrs (AE or Illustrator + AE) |
| 5 | Shipping lanes world map | Red/orange pulse radiates from Shanghai to all continents | 4–5 hrs (AE) |
| 6 | Timeline graphic | 1300s → 2005 → 2035, scrolling left-to-right | 2–3 hrs |
| 7 | Port expansion animation | Current footprint grows with new terminal areas | 3–4 hrs |
| 8 | Split-screen HUD overlay | Tech overlay on live-feed side + digital twin on other | 2–3 hrs |
| 9 | Shipping-label overlays | Small animated labels on products (origin → Shanghai → dest) | 2–3 hrs |
| 10 | Title card: "PORT OF SHANGHAI" | Bold sans-serif, animated reveal | 1 hr |
| 11 | End card template | Logo center, subscribe button, 2 video thumbnails, container-motif border | 2–3 hrs |
| 12 | On-screen stat text package | Consistent lower-third style for all stat callouts (20+ instances) | 3–4 hrs (template + swap) |

**Total estimated motion-graphics time: 32–44 hours**

### 3D — Sound Effects

| SFX | Timestamp | Source Suggestion |
|-----|-----------|-------------------|
| Ship foghorn (deep, resonant) | 0:00, 2:42 | Freesound.org, Epidemic Sound SFX |
| Ocean waves, wind ambience | 0:00–0:15 | Freesound.org |
| Whoosh / swipe (counter punctuation) | 0:15–0:40 (×5–6) | Epidemic Sound, SoundSnap |
| Seagulls | 0:40–0:50 | Freesound.org |
| Wind over open water | 0:40–1:05 | Freesound.org |
| Industrial crane whir | 1:05 | SoundSnap, Epidemic Sound |
| Hydraulic hiss | 1:10–1:35 | SoundSnap |
| Electric motor hum | 1:10–1:35 | Freesound.org |
| Data processing blips | 1:20–1:35 | Epidemic Sound, ZapSplat |
| Shopping bag rustle | 1:40 | Freesound.org |
| Coffee pour | 1:42 | Freesound.org |
| Phone notification ding | 1:44 | Freesound.org (check Apple/Google sound trademark) |
| Low tension drone | 1:58–2:06 | Epidemic Sound, design in DAW |
| Gentle electrical hum | 2:10 | Freesound.org |
| Distant ship horn (single) | 2:42 | Match same source as 0:00 |

### 3E — Music

| Segment | Style Needed | Duration | Search Terms | Platform |
|---------|-------------|----------|--------------|----------|
| Intro (Sc.1) | Dark cinematic tension build | 15 s | "cinematic tension intro," "dark orchestral build" | Epidemic Sound, Artlist |
| Body (Sc.2–3) | Epic pulse-driven orchestral | 50 s | "epic documentary," "orchestral pulse" | Epidemic Sound, Musicbed |
| Tech (Sc.4) | Electronic / techy beat | 35 s | "tech reveal," "electronic corporate" | Artlist, Epidemic Sound |
| Reflective (Sc.5) | Personal → tense → resolving | 30 s | "reflective documentary," "tension resolve" | Epidemic Sound |
| Future (Sc.6) | Hopeful ascending swell | 20 s | "hopeful future," "ascending orchestral" | Artlist |
| Outro (Sc.7) | Uplifting resolve + fade | 15 s | "uplifting ending," "warm resolution" | Match Sc.6 track (extended) |

**Recommendation:** Use 2–3 tracks maximum from one library to maintain tonal consistency. Ideal: one long cinematic track that naturally transitions moods, or a 2-track approach (orchestral Sc.1–3/5–7 + electronic Sc.4).

---

## 4. Motion Graphics Brief for Designer

### Project Overview
Create motion-graphic assets for a 2:45 YouTube explainer about the Port of Shanghai. Assets will be composited over stock footage in Premiere Pro or DaVinci Resolve.

### Style Guidelines
- **Color palette:** Primary — deep navy (#0A1628), electric teal (#00E5FF); Accent — warm amber/gold (#FFB300); Stat numbers — bold yellow (#FFD600) on dark backgrounds
- **Typography:** Montserrat ExtraBold for statistics / headings; Montserrat Regular or Medium for context/captions. All caps for big stats; sentence case for explanatory text.
- **Animation style:** Clean, confident keyframes. Ease-in/ease-out (no linear moves). Subtle motion blur on fast elements. Inspired by Vox / Wendover Productions infographic style.
- **Delivery format:** ProRes 4444 (with alpha) at 3840×2160, 24 fps. Separate files per asset. Name convention: `MG_[scene#]_[descriptor]_v[#].mov`

### Asset Specifications

| # | Asset Name | Dimensions | Duration | Key Requirements |
|---|-----------|-----------|----------|-----------------|
| 1 | `MG_02_satellite_zoom` | 4K full frame | 5 s | Start from realistic space view; resolve into recognizable Yangtze Delta coastline |
| 2 | `MG_02_container_globe` | 4K full frame | 8 s | 3D globe; containers appear as small icons forming a line; line wraps globe 3×; dark background |
| 3 | `MG_02_counter` | Lower-third (safe area) | 5 s | Animated number: 0 → 850,000,000. Commas tick in. Yellow on dark navy. |
| 4 | `MG_03_map_yangshan` | 4K full frame | 5 s | Simplified map; animated dotted line from Shanghai coast to Yangshan island; labels fade in |
| 5 | `MG_05_shipping_lanes` | 4K full frame | 6 s | World map (mercator or Robinson); orange/red pulse lines radiate from Shanghai dot to all continents |
| 6 | `MG_03_timeline` | Lower-third or full | 4 s | Horizontal timeline: markers at "1300s," "2005," "2035"; slides left to right; highlight each era |
| 7 | `MG_06_port_expansion` | 4K full frame | 5 s | Simplified port footprint outline; new sections animate in (draw-on effect), labeled "Phase V" / "Green Terminal" |
| 8 | `MG_04_hud_overlay` | 4K full frame (alpha) | 5 s | Semi-transparent tech UI: scanning lines, data read-outs, grid lines. Overlays live footage. |
| 9 | `MG_05_shipping_labels` | Small overlays (~400×200 px each) | 2 s each (×4) | Animated mini-cards that appear on products: "Made in Shenzhen → Shanghai → Los Angeles" style |
| 10 | `MG_01_title_card` | 4K full frame | 4 s | "PORT OF SHANGHAI" — bold reveal animation (scale up + slight tracking in); white on dark |
| 11 | `MG_07_end_card` | 4K full frame | 7 s | Channel logo center; subscribe button lower-center; 2 thumbnail placeholders (16:9); container-pattern animated border |
| 12 | `MG_ALL_stat_package` | Lower-third (multiple) | 1–3 s each | Template-based: bold stat top line, context line below. ~20 instances; deliver as AE template or individual renders |

### Delivery Deadline Suggestion
Motion graphics are on the critical path. Recommend completing assets 1–4, 10, 12 first (needed for rough-cut validation), then 5–9, 11 for fine cut.

---

## 5. Voiceover Recording Brief

### Script
Full narration text (to be read exactly as written unless changes flagged):

---

**SCENE 1 (0:00–0:15)**
"Every year, the equivalent of every car on Earth — stacked in shipping containers — passes through ONE port. This is the Port of Shanghai… and it never, ever sleeps."

**SCENE 2 (0:15–0:40)**
"Stretching over 3,600 kilometers of coastline, Shanghai's port handles more than 850 million tons of cargo every year. That's roughly 47 million containers. Line them up end-to-end and they would circle the entire planet — three times. To put it another way, a container leaves Shanghai every 0.7 seconds, around the clock, every single day."

**SCENE 3 (0:40–1:05)**
"Shanghai has been a trading hub for over 700 years — since the days of the Yuan Dynasty. But the modern megaport was born in 2005 when engineers did something extraordinary: they built an island. The Yangshan Deep-Water Terminal sits on a chain of tiny rocky islands 30 km offshore, connected to the mainland by the Donghai Bridge — 32 kilometers of concrete and steel stretching over the open East China Sea."

**SCENE 4 (1:05–1:40)**
"Step inside and it's a city unto itself. Giant ship-to-shore cranes — some taller than the Statue of Liberty — lift 40-ton containers off vessels in under a minute. But here's what's truly mind-blowing: almost nobody is there. Yangshan Phase IV is the world's largest fully automated container terminal. Laser-guided cranes lock onto containers with millimeter precision. Fleets of autonomous electric trucks shuttle loads without a driver in sight. And a central AI brain coordinates it all from a control room that looks straight out of a science fiction film — managing thousands of moves per hour, 24/7, 365 days a year."

**SCENE 5 (1:40–2:10)**
"So why does the world's largest port matter to you? Because roughly 90 percent of everything you own spent time on a container ship. That smartphone in your pocket. The sneakers on your feet. The coffee you drank this morning. Chances are they all passed through Shanghai. When this port slows down — even by a little — the entire world feels it. In 2021, a single week of congestion here triggered shipping delays that lasted for months across Europe and North America. Shanghai isn't just moving boxes. It's moving the global economy."

**SCENE 6 (2:10–2:30)**
"And it's only getting bigger. Shanghai has plans to expand capacity by another 20 percent by 2035 — adding new AI-driven terminals and green energy infrastructure, including shore-power for electric ships. As global trade grows, so does this port's role as the nerve center of commerce."

**SCENE 7 (2:30–2:45)**
"Shanghai's Port isn't just the busiest harbor in the world. It's the heartbeat of everything you buy, use, and depend on. If you found that fascinating, hit subscribe — because next time, we're going inside the most automated factory on Earth."

---

### Recording Specifications

| Parameter | Value |
|-----------|-------|
| Format | WAV / AIFF, uncompressed |
| Sample rate | 48 kHz |
| Bit depth | 24-bit |
| Channels | Mono (single narrator) |
| Noise floor | ≤ -60 dB |
| Room tone | Record 10 s of silence for noise reduction |
| Delivery | One continuous take + individual scene splits |

### Performance Direction
- **Pace:** Conversational but confident. Not rushed — let numbers breathe.
- **Energy arc:** Start with restrained intrigue (Sc.1) → build excitement (Sc.2–4) → drop to personal/reflective (Sc.5) → hopeful and forward-looking (Sc.6) → warm and inviting (Sc.7/CTA)
- **Emphasis words (bold in delivery):** ONE, never sleeps, 850 million, three times, 0.7 seconds, built an island, nobody is there, world's largest, 90 percent, you, months, heartbeat
- **Pauses:** Insert 0.5 s micro-pause before each big stat reveal. 1 s pause between scenes for editing flexibility.
- **Pronunciation guide:**
  - Yangshan = "yahng-SHAHN"
  - Donghai = "dohng-HI"
  - Yuan = "yoo-AHN"
  - AGV = spell out "A-G-V" (if ever ad-libbed)

### Total Narration Word Count
~560 words. At ~150 wpm conversational pace = ~3:44 raw. **The narrator must target ~140–145 wpm to land at ≈2:30 of spoken audio** (remaining 15 s is music-only / end card). Record slightly slow; speed can be micro-adjusted ±5% in post without artifacts.

---

## 6. Thumbnail Brief

### Concept
An arresting aerial image of a massive container port at dusk/night with bold, high-contrast text overlay.

### Layout (16:9, 1280×720 minimum / 2560×1440 preferred)

```
┌─────────────────────────────────────┐
│                                     │
│   [Aerial port image fills frame]   │
│                                     │
│   ┌───────────────────────┐         │
│   │  WORLD'S LARGEST      │ ← White │
│   │  PORT                 │   bold  │
│   └───────────────────────┘         │
│                                     │
│        850 MILLION TONS ← Yellow    │
│                                     │
│                          [channel   │
│                           logo]     │
└─────────────────────────────────────┘
```

### Specifications

| Element | Details |
|---------|---------|
| Background image | Aerial shot of port at golden hour / night — cranes lit, many containers, dramatic sky |
| Main text | "WORLD'S LARGEST PORT" — white, Montserrat ExtraBold, drop shadow, upper-left quadrant |
| Sub-text | "850 MILLION TONS A YEAR" — yellow (#FFD600), slightly smaller, below main text |
| Channel logo | Small, lower-right corner (semi-transparent if needed) |
| Expression/face | N/A (no presenter face) — rely on epic imagery |
| Color treatment | Boost contrast; teal shadows + orange highlights; slight vignette to draw eye to center |
| File format | PNG (lossless), 2560×1440 |

### Thumbnail Dos and Don'ts
- ✅ Ensure text is legible at mobile size (small YouTube card)
- ✅ Keep text to ≤6 words total
- ✅ High contrast between text and background
- ❌ Don't use more than 2 type sizes
- ❌ Don't clutter with too many visual elements
- ❌ Don't use thin fonts

---

## 7. Export & Delivery Checklist

### Master Export

| Parameter | Value |
|-----------|-------|
| Resolution | 3840 × 2160 (4K UHD) |
| Frame rate | 24 fps |
| Codec | H.264 (YouTube) or H.265 (archive) |
| Bitrate | 45–65 Mbps (VBR, 2-pass) |
| Audio codec | AAC, 320 kbps, stereo |
| Color space | Rec. 709 |
| Loudness | -14 LUFS integrated (YouTube standard) |
| True peak | ≤ -1 dBTP |
| File name | `port_of_shanghai_explainer_FINAL_v[#]_4K.mp4` |

### Deliverables Checklist

- [ ] Master 4K export (.mp4)
- [ ] 1080p proxy export (.mp4, H.264, 20 Mbps) — for quick review
- [ ] Thumbnail (.png, 2560×1440)
- [ ] Captions / subtitles (.srt file, English)
- [ ] Chapter markers list (for YouTube description):
  - 0:00 — Hook
  - 0:15 — Scale & Numbers
  - 0:40 — History
  - 1:05 — Automation
  - 1:40 — Why It Matters
  - 2:10 — The Future
  - 2:30 — Outro
- [ ] Video description draft (SEO-optimized, with sources/credits)
- [ ] Tags list (15–20 relevant tags)
- [ ] End-screen elements configured in YouTube Studio (subscribe + next video)
- [ ] Cards configured (link to source / related video at key moments)

### Archive

- [ ] Project file saved (.prproj or .drp)
- [ ] All source assets backed up to cloud storage
- [ ] Motion graphics project files (.aep) archived with fonts listed

---

## 8. Risk List — Fact-Check & Source Verification

### Statistics & Claims Requiring Citation

| # | Claim (from script) | Scene | Risk Level | Source Needed | Notes |
|---|---------------------|-------|-----------|---------------|-------|
| 1 | "equivalent of every car on Earth — stacked in containers" | 1 | 🟡 MEDIUM | Needs math verification: ~1.4B cars globally ÷ containers per car equivalent | Poetic framing; verify math is defensible or soften to "imagine every car on Earth…" |
| 2 | "#1 busiest port since 2010" | 2 | 🟢 LOW | World Shipping Council, AAPA rankings | Well-documented; verify it hasn't been surpassed by Singapore in latest year |
| 3 | "3,600 km of coastline" | 2 | 🟡 MEDIUM | Unclear if this refers to Shanghai municipality coastline or the entire port system | Verify source; may be overstated — Shanghai's actual coastline is ~160 km; this may conflate China's total coast |
| 4 | "850 million tons of cargo / year" | 2 | 🟢 LOW | Shanghai International Port Group (SIPG) annual reports | Check latest year's figure — varies annually |
| 5 | "47 million containers" | 2 | 🟢 LOW | SIPG annual TEU figures (47.03M TEU in 2022) | Confirm latest available year |
| 6 | "Circle the planet 3 times" | 2 | 🟡 MEDIUM | Math: 47M × 6.1m (TEU length) ≈ 286,700 km; Earth circumference ≈ 40,075 km → 7.15× | **DISCREPANCY:** Math yields ~7×, not 3×. Script says 3×. MUST VERIFY or correct to "more than seven times" |
| 7 | "Container leaves every 0.7 seconds" | 2 | 🟡 MEDIUM | Math: 47M ÷ 365 ÷ 24 ÷ 3600 ≈ 1.49/sec → one every 0.67 s | Approximately correct; round to "every second" if uncomfortable with precision |
| 8 | "Trading hub for 700 years / Yuan Dynasty" | 3 | 🟢 LOW | Historical record supports Shanghai as a trading town since ~1300s | Standard historical claim |
| 9 | "Yangshan opened 2005" | 3 | 🟢 LOW | Phase I opened Dec 2005 | Accurate |
| 10 | "30 km offshore" | 3 | 🟢 LOW | ~30 km from mainland Shanghai | Accurate (some sources say 32 km) |
| 11 | "Donghai Bridge 32 km / world's longest cross-sea bridge" | 3 | 🟡 MEDIUM | 32.5 km; was longest at opening (2005) but surpassed by HK-Zhuhai-Macau (2018, 55 km) | Script says "at time of opening" — this qualifier is important. Keep it. |
| 12 | "Cranes taller than Statue of Liberty" | 4 | 🟡 MEDIUM | STS cranes ~70–100m; Statue of Liberty (to torch) = 93m | Roughly comparable; defensible but not precise for all cranes |
| 13 | "40-ton container in under a minute" | 4 | 🟢 LOW | Standard quay crane cycle ≈ 60–90 s per move | Slightly optimistic; "about a minute" is safer |
| 14 | "World's largest fully automated terminal" | 4 | 🟡 MEDIUM | Yangshan Phase IV widely reported as such at opening (2017) | Verify no larger has opened since (e.g., Tuas Singapore Phase 1, 2022) |
| 15 | "Laser-guided / millimeter precision" | 4 | 🟢 LOW | ZPMC and SIPG marketing materials confirm this | Standard industry claim |
| 16 | "90% of everything you own on a container ship" | 5 | 🟡 MEDIUM | Common claim; original source is International Chamber of Shipping (~90% of world trade by volume) | "90% of world trade" ≠ "90% of what you own." Safer to say "90% of world trade travels by sea" |
| 17 | "2021 — single week of congestion → months of delays" | 5 | 🟡 MEDIUM | Multiple events in 2021 (Suez, Yantian, Shanghai COVID 2022) | Verify timing: major Shanghai congestion was actually **2022** (COVID lockdown, Apr–Jun). 2021 was Yantian (June). Conflation risk. Recommend changing to "2022" or making it generic: "when this port slows down…the world feels it for months." |
| 18 | "+20% capacity by 2035" | 6 | 🟡 MEDIUM | Shanghai 14th Five-Year Plan + port master plan references | Verify specific percentage; may be throughput target vs. physical expansion |
| 19 | "Shore-power for electric ships" | 6 | 🟢 LOW | Shore-power being rolled out; "electric ships" as a category is still emerging | Accurate in spirit; few fully electric cargo ships exist yet |

### Hard-to-Source Visuals — Flags & Fallbacks

| Visual | Difficulty | Reason | Fallback |
|--------|-----------|--------|----------|
| Yangshan Phase IV AGVs in formation | ⚠️ Hard | Very few stock providers carry this specific footage | Use any automated terminal (Rotterdam's Maasvlakte II or Qingdao's QQCTN) + text overlay "Yangshan Phase IV" |
| Donghai Bridge full aerial tracking | ⚠️ Moderate | Limited drone footage available commercially | Use partial bridge shot + animated map showing full length |
| AI control room interior | ⚠️ Moderate | Security-restricted; stock rarely shows real port control rooms | Use generic NOC / data center + add simulated port UI overlay in post |
| Historical Shanghai harbor (pre-1900) | ⚠️ Moderate | Public domain images exist but quality varies | Use illustrated/painted interpretation (commission or use AI-assisted illustration with disclosure) |
| Construction of Yangshan (2002–2005) | ⚠️ Hard | Chinese state broadcaster archives; licensing complex | Replace with motion-graphic "island building" animation |
| Electric ship at shore-power berth | ⚠️ Hard | Very few examples exist in real life as of 2024 | Use conventional ship at berth + animated "charging" graphic overlay |
| 2021 supply chain crisis news footage | ⚠️ Moderate | Editorial-licensed footage can be expensive | Use royalty-free "empty shelves" + newspaper headline graphic overlay |

### Recommendations Summary
1. **Fix the "3× around Earth" claim** — math shows ~7×. Either correct the number or re-word.
2. **Verify the 2021 date** — the major Shanghai-specific disruption was 2022. Either change to 2022, or generalize.
3. **Soften "90% of everything you own"** — change to "90% of global trade moves by sea" (sourced from ICS).
4. **Confirm "world's largest automated terminal"** — check if Tuas (Singapore) Phase 1 has surpassed it.
5. **Confirm "3,600 km of coastline"** — this number appears to be China's total port coastline, not Shanghai's. Either clarify or remove.
6. **Budget extra time** for hard-to-source footage (AGVs, Donghai Bridge, control room). Plan fallbacks from Day 1.

---

## Appendix: Suggested Workflow Timeline (Solo Creator)

| Week | Tasks |
|------|-------|
| 1 | Record V.O.; begin stock footage search; commission motion graphics |
| 2 | Receive MoGraph batch 1 (titles, counter, map, stat package); build rough cut |
| 3 | Receive MoGraph batch 2 (globe, shipping lanes, HUD, end card); fine cut |
| 4 | Audio mix; color grade; fact-check review; thumbnail design |
| 5 | Final export; captions; upload & schedule; prepare description + tags |

**Total estimated post-production time: 40–60 hours across 4–5 weeks** (solo pace, excluding motion graphics outsourced).
