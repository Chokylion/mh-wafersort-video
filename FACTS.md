# FACTS (English version): every number and claim on screen, and where it comes from

Sources, in order: the owner's final deck `MH-Wafersort-Final-DMAIC-v3.pptx` (26 Nov 2026; slide numbers below),
the owner's notes of 26 Nov 2026, and the video brief `video-brief\MH-Wafer-Sort-5min-PRD-TH.md`.
Rule of the film: nothing is drawn that is not in this table. `tools/audit.mjs` fails the build if a number appears
on screen that is not listed here, if a real tester or lot ID appears, or if any Thai text is drawn.

## Owner's notes of 26 Nov 2026

| Note | Used as |
|---|---|
| MH table = a normal table with a computer and a barcode scanner | the three MH CSP desks in the 3D floor |
| Wafer Sort is on Floor 1 | S01 tag `Wafer Sort · Floor 1` |
| Ricmar photo, black FOUP photo | outline of the Ricmar and the FOUP models; "black FOUP" in S03 |
| MH use a cart, 6–8 lots a trip (aluminium, two tiers) | the cart in S03; `6–8 lots on a cart` |
| MH push the cart themselves from the MH station; the time is one leg; the lots are a mix of FOUPs and canisters (revision note) | S03: MH C takes the cart parked at the desks, pushes it to the pass box, loads FOUPs and canisters, pushes it back |
| Opening: a better, more detailed factory (revision note) | S01, 0–7 s: campus model built from public press photos of the plant; no claim about where Wafer Sort is inside it |
| First tester slowly with real time, compare with Statusphere, decide, then the fast scroll (revision note) | S05 |
| No "revise" at 24.5 h: "backtest once more on all the data of that day" (revision note) | S08 card 4 and its line |
| No terminal: "the hours on the EWB + our rule = the list", then tick / write why / extra lot (revision note) | S09 |
| QA time is irrelevant | the QA step shows no time |
| Ricmar and ink map: use the time-study minutes | S03 uses the deck's per-lot times (slide 5) |
| "make it all English", "use my slide elements", "2D infographics" | English narration and text; 2D scenes follow the deck's layouts |

## Numbers

| On screen | Scene | Kind | Source |
|---|---|---|---|
| `90+ min` a round | S01 S03 S05 S06 S10 | timed, before | deck 2, 5, 25 |
| `20 min`, with `day round we timed · best case` | S01 S10 | timed, best case, day round (5 Nov) | deck 25 |
| `3 MH on each shift`, `84 CSP testers in the system`, `14.7 lots withdrawn a day`, `07:00–19:00` | S01 S02 | station facts | deck 4 |
| Lot flow: Die Bank → Withdraw lot → Tester → Check Map → QA check → Return lot | S02 | process | deck 4 |
| Steps and times: Decide `90+ min` · Withdraw `4.7 min` · Prepare `14.2 min` · Ricmar `6 min` · Test `Varies` · Check Map `2 × 14 min` · QA, return | S03 | per-lot model from the time study | deck 5 |
| `6–8 lots on a cart` | S03 | owner, 26 Nov | note above |
| `≈ 6–7 min one way`, incl. waiting at the pass box | S03 | owner's account, 21 Oct | brief §7.5 |
| `About an hour of MH work for every lot` | S03 | 62.9 min a lot | deck 5 |
| Pareto `49% 13% 11% 10% 7% 2% 2% 5%`, cumulative `73%`, `1,800 work minutes`, `3 CSP MH`, windows on `19, 20 and 27 Oct` | S04 | observed shift built from three windows | deck 17 |
| `80+ testers`, four systems (EWB, Statusphere, Camstar, IGS) | S05 | today's round | deck 6, 10, 54 |
| `“+6” = 18 hours`, `12 h day shift + 6 h`, `07:00 19:00 01:00 07:00` | S05 | the rule MH tell | deck 6 |
| One tester, slowly: `25 wafers left` (of 25) · `1.72 h a wafer` (planned) · `43.0 h of work` | S05 | the EWB block of the deck's worked example, tester and lot names replaced | deck 12 |
| Statusphere: `wafer 24 done at 07:04` · `Real: 0.93 h` · `56 min, 06:08 to 07:04` · `Not close` (plan 1.72 h) | S05 | the tester's own log for the same lot, equipment ID replaced | deck 11, 12 |
| `This tester: 43 h of work left` · `more than 18 h, so it runs past 01:00` · `WAIT` | S05 | the “+6” rule applied to that tester | deck 6 |
| Clock `00:00 …` beside the first tester = real film seconds; then `fast-forward` to `90+ min` · `timed: one round, by hand`; counter `Tester 1…84 of 84` | S05 | the clock shows film time, not a per-tester measurement; 90+ min is the timed round | deck 2, 5, 25 |
| `25 / 5`, `6.7` inside the EWB shot; `LOT-R`, `LOT-N`, `TESTER-A…F` | S05 S09 | real reference shot, names replaced | brief §8.1 |
| `≈ 97%` busy; `61%` = `46 of the 75 lots` on the “+6” list | S06 | observed day; scored on 6 days | deck 8, 20 |
| `5.9 h + 7.9 h = 13.8 h`, `threshold = ?` | S07 | example from the prototype shot | brief §8.1 |
| Flow: Paste the EWB → Add hours left → `≤ threshold?` → Withdraw the next lot / Wait → One list | S07 | the rule | deck 23 |
| `13 Oct · 75 lots · 6 days to 21 Oct` | S08 card 1 | data collected | deck 22 |
| `15 Oct · 5 windows · 19 to 27 hours · 24 h` | S08 card 2 | window chosen | deck 22 |
| `19 Oct – 10 Nov · 82% · 157 of 192 · old rule 54%` | S08 card 3 | blind test, 24 h | deck 22 |
| `11 Nov · Backtest again · on all the data up to that day: 17 days, 224 lots · 24.5 h` | S08 card 4 | backtest repeated on all the data collected by then | deck 22, 23 |
| `11 – 19 Nov · 85% · 68 of 80 · old rule 56%` | S08 card 5, S10 | blind test on 7 new days | deck 22, 29, 30 |
| `Hours on the EWB` + `Our rule: IF hours left ≤ 24.5 h, withdraw the next lot` (`hours left = running lot + lots already at the tester`) → `The list` (16 rows, real output of 19 Nov, names replaced) | S09 | the script's own output page; column names shown in English | brief §16.2, deck 23 |
| Marks on the list: `Withdrawn · tick the lot`, `Not withdrawn · write why`, `Extra lot taken · not on the list: write why` | S09 | how MH use the page | owner, revision note |
| `target ≤ 72 min`, `−70 min a round back` | S10 | KPI of objective 3; 90 − 20 | deck 15, 25 |
| `56% · 45 of 80`, `target 90%`, `5 points short` | S10 | same 7 days; target not yet met | deck 30 |
| `140 min a day back`, `70 a round × 2 · night assumed` | S11 | estimate: night round taken as the day round | deck 25, 26 |
| `÷ 62.9` · `= 2.2` · `× 5.8` · `≈ +13 more testers (estimate, from our model)` | S11 | model, whole Wafer Sort | deck 26 |
| `≈ $7,200 a year, if the plant adds those testers (estimate)`, `Cost avoided, not a job cut` | S11 | cost avoided | deck 26, 27 |
| Title, `Kittayod Watamathurot`, `Advisor: Poom Luangjarmekorn`, `IE Co-op Final Project 2026` | closing card | deck cover | deck 1 |

## Not shown, on purpose

- Any count of stopped testers or lost output (no data). The "tester waits" card in S06 is tagged `illustration`.
- QA time (owner: irrelevant). The n8n headcount side project. Check Map automation.
- MOVE, yellow status, CHANGE LOG, automatic withdrawal in EDS, live links to EWB / Statusphere / Camstar / IGS.
- Real lot IDs, tester names, product names, staff names, the student ID.
- 27 h shadow rule, the 17-day backtest score (191 of 224), exact-lot 79%. A terminal or any code on screen.

## Changes from the first (Thai) version

- English narration and text; 11 scenes instead of 12. "How MH work" is now one walk-through of the seven steps (S03).
- Script revised from the deck: the “+6” = 18 h rule is explained; the trial story uses the deck's five steps
  (collect, try 5 windows, blind test 82%, revise to 24.5 h, blind test on new days 85%).
- The result claims are unchanged: 90+ → 20 min (best case, day round), 85% vs 56% on 7 new days, target 90% not yet met.

## Revision of 26 Nov 2026 (owner's five points; the rest untouched)

1. 0–7 s: new campus model (ribbon façade, glass corner towers, lobby with logo, forecourt, fence and gate, solar car park, older plant beside it), built from public press photos.
2. From 0:42: MH C takes the cart at the MH station, pushes it to the pass box, loads a mix of FOUPs and canisters and brings it back. `≈ 6–7 min one way`.
3. S05: the first tester is done slowly with a real-time clock, the Statusphere log is opened to compare (plan 1.72 h a wafer, real 0.93 h), the “+6” rule gives WAIT, then the fast scroll through 84 testers to `90+ min`.
4. S08: card 4 says "Backtest again", not "revise".
5. S09: no terminal. Hours on the EWB + our rule = the list; then tick, write why, or note an extra lot.
6. Length 299.75 s (not over 5 minutes). The owner will record his own voice over the music version.
