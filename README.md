# Codra-Tech AI Internship 2026 — Landing Page

An animated, interactive landing page for the **Codra-Tech AI Internship 2026**: two weeks, six sessions, from curious to capable. Also included is a full-screen speaker slide for the event. Both use the Codra-Tech brand kit.

---

## What's in the project

| File | What it is | Size |
|---|---|---|
| `Main.dc.html` | The landing page. It scrolls and adapts to phones. | 1440 px wide, fluid |
| `Speaker-Almeslmani.dc.html` | Full-screen slide shown during Eng. Muhammad Almeslmani's opening talk | 1920 × 1080 |
| `canvas.json` | Canvas index: artboard positions, titles and launch view | — |

---

## Page journey

1. **Hero:** "From Curious to Capable, in Two Weeks", with the intro text and four highlights (real operators, 6 sessions, 90 min max, 2 weeks start to pitch). The Arabic line reads **قدراتك تبدأ من هنا**.
2. **Brand marquee:** a scrolling strip with "Where capability becomes technology · Real operators, not theory · Two weeks, one pitch".
3. **The Journey:** six stages, Onboard → Equip → Witness → Apply → Prepare → Graduate. An animated pixel cursor moves along the track. Clicking a stage opens its session.
4. **Curriculum:** six expandable sessions in two weeks. Each shows a description, who leads it, and a "What you walk away with" box.
5. **Operators (speakers):** a photo, title and short bio for each speaker, plus a closing "And on the final day — you" card.
6. **Why this:** three reasons: operators not lecturers, no wasted sessions, a real finish line.
7. **Graduate (closing):** the pitch and Madaar funding promise, key details, and a link back to the sessions.

---

## Event details

- **Starts:** 5 October 2026
- **Venue:** Adan, Burj Alhamama, 3rd floor
- **Rhythm:** 3 sessions a week, 90 minutes max
- **Seats:** 25

---

## Sessions & speakers

| # | Session | Led by |
|---|---|---|
| 1 | Welcome to the Age of AI | Opening talk: **Eng. Muhammad Almeslmani** (GM, Madaar Solutions · CEO, Codra-Tech Academy); **Eng. Ali Ramadan** (Instructor) |
| 2 | Speak AI's Language: Prompt Engineering | Eng. Ali Ramadan |
| 3 | From Idea to Execution: Utilization & Framework | Eng. Ali Ramadan (MVP build) · Mr. Tamer (CFO, Azzrk Group) · Dr. Amira (Finance & HR) |
| 4 | AI Meets the Market: Marketing, Creative & Sales | Mohammed Albanna (Marketing) · Anas Elfiky (Creative Director) · Ahmed Ayman (Sales Director) |
| 5 | The Pitch: Winning Over Investors | Eng. Mohamed Elhanafy (Pitching & Presentation Skills) |
| 6 | Take the Stage: Graduation & Project Pitching | Eng. Ali Ramadan · Eng. Huda Saleh (Project Manager) · Guest of Honor: Eng. Muhammad Atef (Senior AI Engineer, e& Egypt) |

---

## Brand system

Taken from the Codra-Tech brand kit (*Codra 2nd Option*, Azzrk Agency 2026).

- **Colors:** Green `#62D270` · Dark `#333333` · White `#FFFFFF`, with soft green washes in the backgrounds.
- **Type:**
  - English display and body: **Archivo**, standing in for Clash Display.
  - Arabic: **Readex Pro**, standing in for Brando Arabic.
  - Pixel labels: **Silkscreen**.

  These are Google Fonts, used because the brand fonts can't be loaded on the web page.
- **Motifs:** pixel squares, the `</>` glyph strip, a pixel cursor, and dark or green highlight bars behind key words, as on the brand posters.
- **Assets:** the logo in color and in white and the glyph strip were cut from the brand kit PDF. Speaker photos are stored as uploaded images in the artifact.

---

## Motion & interaction

- **On load:** headlines rise in line by line, highlight bars fill in, and the caret blinks.
- **On scroll** (Chrome, Edge, newer Safari): sections fade and slide in, and a progress bar fills across the top. In other browsers everything still shows, just without these effects.
- **Interactive:** the session cards open and close, and the journey stages jump to their session. Speaker cards and buttons react on hover.
- **Accessibility:** animation turns off for visitors whose device is set to reduce motion.

---

## Where it lives

- **Claude design canvas:** this is the editable source. It's shared as "Anyone with the link". Use **Share** on the canvas to copy the link.
- **Vercel:** imported as *Codra-Tech AI Bootcamp*. Each import creates a new deployment link. If visitors are asked to sign in, open the project in Vercel and turn off **Settings → Deployment Protection → Vercel Authentication**.

---

## Editing

- Text, colors and spacing can be edited directly on the canvas. Click an element to change it.
- To update a speaker, replace their photo and edit the three lines under it: name, role and bio.
- After making changes, send the design to Vercel again to update the live site.

---

## Open items

- [ ] Get a higher-resolution photo for Mohammed Albanna and Eng. Muhammad Atef.
- [ ] Ahmed Ayman's bio is one line. Add a sentence so his card matches the others.
- [ ] Confirm whether Eng. Muhammad Atef judges the final pitches.
- [ ] Confirm the Madaar wording: "In partnership with" or "Built by Madaar Ventures".
- [ ] Session 3's description says Eng. Ali Ramadan builds "in conversation with the instructor", but he is now the instructor. Reword it.
