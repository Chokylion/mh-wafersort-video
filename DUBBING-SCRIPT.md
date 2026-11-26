# Dubbing script (English)

Film length 299.75 s. Record over `MH-WaferSort-5min-EN-music.mp4` (music and sound effects only).
Each line should start at "Start" and be finished by "End"; the picture is timed to these moments.
The "seconds" column is how long the placeholder voice takes, so you know how fast to read.

## S01 · The question (0:00.0 – 0:18.6)

| Start | End | Seconds | Line |
|---|---|---|---|
| 0:01.2 | 0:07.2 | 5.9 | Every morning at Analog Devices Thailand, one question must be answered before work can go on. |
| 0:08.0 | 0:10.4 | 2.4 | Which tester should get its next lot of wafers? |
| 0:11.2 | 0:13.9 | 2.7 | Answering it used to take more than 90 minutes. |
| 0:14.7 | 0:17.9 | 3.2 | This project brought the round we timed down to 20. |

## S02 · Where MH sits (0:18.6 – 0:36.6)

| Start | End | Seconds | Line |
|---|---|---|---|
| 0:19.3 | 0:22.7 | 3.4 | Wafer Sort tests every die on a wafer, before assembly. |
| 0:23.1 | 0:25.4 | 2.3 | Wafers travel in sets called lots. |
| 0:25.8 | 0:30.4 | 4.6 | Every lot is moved, prepared and checked by a Material Handler, or MH. |
| 0:30.9 | 0:36.0 | 5.1 | At the CSP station, three MH on each shift look after 84 testers. |

## S03 · One lot through MH (0:36.6 – 1:22.6)

| Start | End | Seconds | Line |
|---|---|---|---|
| 0:37.4 | 0:41.1 | 3.7 | First, MH decide which lots to withdraw from the Die Bank. |
| 0:42.1 | 0:49.2 | 7.1 | Then they push a cart from the MH station to the pass box, and collect six to eight lots: FOUPs and canisters. |
| 0:50.2 | 0:55.7 | 5.5 | At the desk they check each lot, print the setup sheet and make the ink map: about 14 minutes. |
| 0:56.8 | 1:02.4 | 5.7 | The Ricmar moves the wafers from a canister into a black FOUP: about 6 minutes of MH work. |
| 1:03.5 | 1:09.5 | 6.0 | An operator takes the lot to the tester. Testing takes minutes or days, with no MH work. |
| 1:10.5 | 1:15.4 | 4.9 | After each test step, MH check the map: usually twice, 14 minutes each. |
| 1:16.5 | 1:21.6 | 5.1 | Then QA, and back to the Die Bank. About an hour of MH work for every lot. |

## S04 · Where a shift goes (1:22.6 – 1:46.6)

| Start | End | Seconds | Line |
|---|---|---|---|
| 1:23.3 | 1:26.6 | 3.3 | Where does a shift go? We logged the three MH on the floor. |
| 1:27.7 | 1:33.2 | 5.5 | Check Map alone is about half of their work, but fixing it means changing several systems. |
| 1:34.3 | 1:43.3 | 9.0 | The withdrawal decision is only 7 percent. But it is reading and adding by hand, and it decides whether a tester gets its next lot on time. |
| 1:44.4 | 1:45.8 | 1.4 | So we fixed that first. |

## S05 · How MH decide today (1:46.6 – 2:30.0)

| Start | End | Seconds | Line |
|---|---|---|---|
| 1:47.4 | 1:51.0 | 3.6 | This is how the decision is made today, one tester at a time. |
| 1:51.9 | 1:54.9 | 3.0 | Open the EWB board and find the tester. |
| 1:55.9 | 2:00.2 | 4.3 | Read its lot: 25 wafers left, and 43 hours of work. |
| 2:01.2 | 2:06.3 | 5.1 | Then open Statusphere, the tester's own log: is the real time close to the plan? |
| 2:07.2 | 2:17.6 | 10.3 | Then judge, by a rule kept in memory. MH call it “plus six”: bring the next lot if the tester runs out before 1 a.m., 18 hours from the start of the shift. |
| 2:18.5 | 2:22.9 | 4.4 | This tester has more than 18 hours of work left, so its next lot waits. |
| 2:23.9 | 2:28.2 | 4.3 | Now do that for more than 80 testers: more than 90 minutes, every round. |

## S06 · Why it matters (2:30.0 – 2:49.0)

| Start | End | Seconds | Line |
|---|---|---|---|
| 2:30.7 | 2:34.5 | 3.7 | Why does it matter? A tester can only run if a lot is waiting. |
| 2:35.5 | 2:39.2 | 3.7 | MH are already busy about 97 percent of the shift. |
| 2:40.2 | 2:48.3 | 8.1 | And a rule in memory cannot be checked. Scored against the lots MH really took, “plus six” listed only 61 percent. |

## S07 · One number, one IF (2:49.0 – 3:09.5)

| Start | End | Seconds | Line |
|---|---|---|---|
| 2:49.8 | 2:53.9 | 4.1 | Our idea: let a script do the reading and the adding, with one written rule. |
| 2:55.4 | 2:59.9 | 4.5 | Add the hours left on the running lot, plus the lots already waiting at the tester. |
| 3:01.4 | 3:04.7 | 3.2 | If the total is under a threshold, withdraw the next lot. |
| 3:06.2 | 3:08.4 | 2.3 | MH get one list, and still decide. |

## S08 · Finding the number (3:09.5 – 3:45.0)

| Start | End | Seconds | Line |
|---|---|---|---|
| 3:10.3 | 3:15.9 | 5.7 | Which threshold? Every morning we saved the EWB, and the lots MH really took. |
| 3:16.8 | 3:19.7 | 2.9 | We tried five windows and picked 24 hours. |
| 3:20.5 | 3:31.6 | 11.1 | Then we tested it blind: the list was saved each morning and never shown to MH. It caught 82 percent of the lots MH took, against 54 for the old rule. |
| 3:32.5 | 3:39.0 | 6.5 | Later we ran the backtest once more, on all the data up to that day. It gave 24 and a half hours. |
| 3:39.9 | 3:44.2 | 4.3 | Tested blind again on seven new days, it held: 85 percent. |

## S09 · The product (3:45.0 – 4:12.0)

| Start | End | Seconds | Line |
|---|---|---|---|
| 3:45.7 | 3:54.7 | 8.9 | This is the real thing. We take the hours on the EWB, apply our rule, and get the list: every lot to withdraw, most urgent first. |
| 3:55.4 | 3:57.4 | 1.9 | MH tick each lot they withdraw. |
| 3:58.2 | 4:03.7 | 5.5 | If they don't, they write why. And if they take a lot that is not on the list, they write why too. |
| 4:04.5 | 4:11.3 | 6.8 | This green and red board is a prototype: the same list, inside the EWB that MH already know. |

## S10 · What we measured (4:12.0 – 4:33.5)

| Start | End | Seconds | Line |
|---|---|---|---|
| 4:12.8 | 4:19.7 | 6.8 | The results. The decision round went from more than 90 minutes to 20, the best case in the day round we timed. |
| 4:21.2 | 4:28.4 | 7.2 | On seven new days, 85 percent of the lots MH took were on the list, against 56 for the old rule. |
| 4:29.9 | 4:32.3 | 2.4 | The target is 90, so we keep tracking. |

## S11 · Same team, more time (4:33.5 – 4:59.8)

| Start | End | Seconds | Line |
|---|---|---|---|
| 4:34.2 | 4:37.0 | 2.8 | That gives back about 140 minutes a day. |
| 4:37.4 | 4:43.6 | 6.2 | By our model, the same team could serve about 13 more testers: cost avoided, not a job cut. |
| 4:43.9 | 4:49.3 | 5.3 | And the rule is now written down. Anyone gets the same list, and MH still decide. |
