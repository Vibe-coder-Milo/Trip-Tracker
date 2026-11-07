---
target: the polished Trip Tracker mockup
total_score: 28
max_score: 40
na_heuristics: 
p0_count: 0
p1_count: 1
target_identity: "file:/workspace/Trip-Tracker/prototype-polished.html"
target_fingerprint: "sha256:1ab06bf8eb149ba24ae480d059ec17dab9db9087d1d076bdf6a9452a327682c7"
target_path: /workspace/Trip-Tracker/prototype-polished.html
timestamp: 2026-11-07T05-25-58Z
slug: prototype-polished-html
---
Method: dual-agent (A: design review · B: detector, overlay and contrast check). Final critique, run on the version after the first wording pass; wording and three defects fixed afterwards in the same session.

Design Health Score: 28/40 (Good). 1 Status 3 · 2 Real world 3 · 3 Control 3 · 4 Consistency 2 · 5 Error prevention 3 · 6 Recognition 3 · 7 Efficiency 2 · 8 Minimalist 3 · 9 Error recovery 3 · 10 Help 3.

Design specificity: authored for this product (Singapore-centred map, shared per-day numbering across plan, pins and picker, driver card, hand-entered trip rate, ledger breakdowns). Light theme calm and specific; dark with lime reads more generic.

Detector: CLI 0 findings. Overlay: low-contrast on light food badges (white on amber, 3.98:1) on Overview and Itinerary; flat-type-hierarchy note on Overview (h2 22.1 / h3 18.7 / body 17, weight separates them). Dark lime clean. Own contrast pass: only the food badge failed.

Priority issues
1. [P1] Vocabulary drift: Flight vs Air ticket, Sight vs Attractions, Town vs Cities, items/places/rows/stops/times, Removed vs Deleted, undo naming a time. (clarify) FIXED in part: stops, Removed {name}, add dialog, hints, settings wording.
2. [P2] Two add entry points disagree; hotel dialog placeholders and map picker wording. (clarify, distill) FIXED.
3. [P2] Signal lime runs hot as the everywhere accent; olive wash; crowds success green. (colorize) OPEN.
4. [P2] Overview day arrows read as accordion chevrons; drag handles 28x32 on phone; handles have no keyboard behaviour. (adapt) OPEN.
5. [P2] Settings copy contradicts itself and speaks API. (clarify) FIXED.

Defects fixed after the critique: food badge contrast (now 5.37:1), Home stats counting a trip in progress as done, map picker "Hotel Hotel".

Persona red flags: Casey (Next up below the fold on phone, map last, row buttons on their own line); Riley (stats included the current trip; trips 6 above 7 rows; category sums round to S$5,314.27 against S$5,314.26); Sam (handles without keyboard, lime and white differ by hue only, halation).
