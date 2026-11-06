---
target: the Trip Tracker mockup
total_score: 26
max_score: 40
na_heuristics: 
p0_count: 0
p1_count: 4
target_identity: "file:/workspace/Trip-Tracker/prototype-design-a.html"
target_fingerprint: "sha256:d2f3e9ed167cc760c412b2f629a77f6ac91aaaf1e07da43d6fc18e03c608e9ca"
target_path: /workspace/Trip-Tracker/prototype-design-a.html
timestamp: 2026-11-06T12-51-05Z
slug: prototype-design-a-html
---
Method: dual-agent (A: design review · B: detector and browser)

Design Health Score: 26/40 (Acceptable). 1 Status 3 · 2 Real world 3 · 3 Control 3 · 4 Consistency 2 · 5 Error prevention 3 · 6 Recognition 3 · 7 Efficiency 2 · 8 Minimalist 2 · 9 Error recovery 2 · 10 Help 3.

Design specificity: structure and content are specific (Singapore-centred map, timetable, per-night/per-person calculators, Next up, driver address). The look is a generic "Atelier" paper-and-serif preset that any app could wear; nothing in colour or type says travel. Detector: 1 finding, cream-palette (page background rgb(241,236,230)), on all views.

Priority issues
1. [P1] Muted grey 14.9px text carries 28-40% of characters (85% on Overview); APCA Lc 72.8 on paper, 67.6 in wells. Fix: 16-17px for content, darker muted, ink for content. (typeset)
2. [P1] One muddy beige band: surfaces 1.09-1.22:1 apart, rules 1.54:1, one dusty accent doing seven jobs; washes out outdoors. Fix: clean light neutral, near-black ink, one confident accent, category colours shared by bars, ledger and pins, blue sea on the map. (colorize)
3. [P1] Light display serif on the key figures (total, In 14 days, 12:30, per-night). Fix: serif for page titles only; figures in the sans at 600 with tabular numerals. (typeset)
4. [P1] Itinerary always in edit mode; Overview repeats each place three times. Fix: read-first with per-item Edit; notes behind a toggle. (distill, layout)
5. [P2] Phone ledger pushes amounts off-screen (min-width 46rem); Budget tab clipped. (adapt)

Persona red flags: Sam (low-contrast quiet buttons 1.54:1, colour-only status, map labels on a 1.19:1 map); Casey (beige Next-up card in daylight, top toasts, hidden amounts on phone); Alex (no shortcuts, unsorted ledger, four ways to reorder).

Minor: placeholders look like values; day strip cut without a scroll cue; backup links duplicated; Settings icon unlabelled; head tags inside body; Kyoto/Osaka label over Taipei.
