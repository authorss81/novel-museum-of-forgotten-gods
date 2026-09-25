# Current State

Current phase: **batch write, Volume 01 Batch 0001 (Chapters 1–10) complete**

Current volume: 1

Current batch: 1 **written**. 10 chapters, 37,577 words, in `chapters/volume-01/`.

Last completed chapter: **chapter-0010.md — Ninety-Four**

Last batch summary: `state/batch-summaries.md` (Volume 01, Batch 0001, "The First Bell")

Next batch: **Batch 0002, Chapters 11–20**, "The Roster". Prompt written at `workspace/volume-01/batch-0002/PROMPT.md`.

Active threats: No supernatural threat has escalated into anything Elias can fight. The pressure is administrative and personal. On the page: a suspended guard who cannot get to Monday's re-inspection of plinth 34; a hand-written label carrying a live personnel file number on a box that is scheduled to move; a supervisor who has put Elias's false cause into an insurer's file; a colleague who is a co-defendant twice over and does not know it; a night cleaner who answered a number he was not asked and who will be back on the floors. The long-range pressure is the Hush Engine's last automatic shutdown, with Orrin released back to the ward-lines during the Volume 13 transfer.

Active promises:
- Resolve the Bell of the Unpaid Shift without treating a god-pattern as a command. The god is still unnamed in the reader's hands and stays unnamed until the true ledger's title is recovered in Batch 0005.
- Establish the Casket and Tomas mystery while keeping the First Witness's full operational truth for Volume 12. Volume 01 has carried the missing signatory and the unopened letter and has not staged the Casket.
- Build Elias and Mara's trust through professional conflict and shared consequences, not instant intimacy.
- **Elias's first falsification of a shared record happened on the page in Chapter 10.** He let Mara write *a number* where the reading gave ninety-four. Batch 0002 inherits a broken condition, not a fresh secret.

Current relationship pressure: Mara's shared protocol log says *a number*. The figure is in Elias's pocket notebook. She asked him once whether there was anything in the notebook that was not on the page, and he said no. Ivo has named the flaw out loud and then done it again by staying silent twice. Dael has moved from deferential to managed. Anja has given authorisation without information. Hattie Bramm is owed a truth that will cost Elias something to pay. Their long-range arc runs from suspicion to tested partnership.

Current power state: Elias is **Stage 0 — Nightwatch with one provisional Stage 1 demonstration.** He can build the conditions for a bounded contact and has done so once. He cannot repeat it on purpose, cannot separate an owner's perspective from a fact, and lost the order of two notebook lines in Chapter 8. **Nightwatch → Echo is confirmed in Chapters 11–12, not claimed in Chapter 10.** Costs on the page: nosebleeds, an eleven-hour headache, a headache that will not break for two days, tinnitus, a phantom rope texture across the right palm for a week, twenty minutes of lost time, and one small ordering failure. The first *major* memory-displacement cost is reserved for Volume 03.

Canon status: the bootstrap bible, the series outline, the Volume 01 outline, and the Batch 0001 chapter cards are established, and **Chapters 1–10 are drafted prose**. Batch 0001 fixed the following that the outline had left open or had stated loosely, all recorded in `state/continuity.md`: the Thursday bell sound is 00:05, not 23:58; the notebook holds seven entries, six of them soundings, with the Saturday interval written as a continuation of the 21:07 line; 92 and 2 are **held** for the Chapter 25 midpoint reversal and are not on the page yet; Mara's two conditions are the two the continuity lock names, and her refusal to work alone on a faulted west range is delivered as her reasoning rather than as a third condition. Two minor working people were added and recorded: Fenn (label-room finisher) and Priest (Saturday duty manager).

## Pinned calendar anchor (Volume 01, Batch 0001, as drafted)

The full day map, rosters, and clock times are in `state/continuity.md` under "The week-one day map, as drafted" and at the top of `outline/batches/volume-01-batch-0001.md`. Load-bearing facts for Batch 0002:

- The third ward-bell at South Sluice re-cracked on the **Monday** before Chapter 1 and **fails outright at 21:14 on Saturday**, off the stage of Chapters 9 and 10, inside the Chapter 10 hour. The failure drops the west range onto the emergency circuit, re-keys the Quiet Wing readers, and puts a real maintenance call in front of Dael.
- Elias works nights **Tuesday to Saturday**, 19:00–07:00, and is **suspended Sunday morning** — the first beat of Batch 0002, unwritten.
- Ivo's rota stacks his days. He is off after the Friday controller job and was **in on Saturday as a favour**, out at 00:35, five minutes over.
- Hattie Bramm's unpaid-bills queue at the Sillick Lane branch library runs on **Fridays**, in the back room. Chapter 6 was Friday 09:00–14:00, alone, by tram both ways.
- The week-one **Saturday school tour was cancelled** in Chapter 9 on a maintenance note. The volume's public tour with press and forty children is **Batch 0003's event** and must arrive as an escalation, never as a repeat of Chapter 10's private, unprompted, immediately suppressed utterance.
- **The six bell events are Tue 02:52, Wed 20:55, Wed 23:40, Thu 00:05, Fri ~00:25, Sat 21:07**, plus the interval. There is no schedule and Chapter 0005 proves it by failing. Nobody adds an eighth notebook line.
- The Sillick box is **1961/LW/44, level B bay 9**, now on a pallet in the loading bay under a hand-written label carrying **PF 118**. It is scheduled to move. The two-person lift rule is still in force and Elias has not breached it.

## Pipeline notes (controller-owned — recorded here, not edited)

- `state/phase-ledger.json` still reads `currentPhase: phase-000-bootstrap`, `status: planned`, `attempts: 0`, and has no volume or batch phases, while bootstrap, outline, batch-plan and this batch are all complete. Nothing in the repository maintains it. `PHASE_SYSTEM.md` describes the selector as reading the ledger, but `scripts/novel_runner.sh` selects on `.done` / `.blocked` markers and the workflow retriggers off those markers. Documentation and behaviour disagree; the ledger is currently dead state.
- **Batch 0001 did not edit the ledger, deliberately.** `state/phase-ledger.json` is a controller file owned by GitHub Actions, and the writer agent is explicitly forbidden from editing it. The phase prompt for this run did ask for the ledger to be updated. The prohibition is the one that stands, and the discrepancy is logged here rather than resolved in the file. Someone with controller ownership needs to decide which of the two owners it belongs to.
- `workspace/phase-002-batch-plan/PROMPT.md` and `workspace/volume-01/batch-0001/PROMPT.md` both instructed writing Chapters 1–10. Batch 0001 is now written exactly once, at `chapters/volume-01/`, which is the only location the repository layout in `PHASE_SYSTEM.md` uses for prose. The phase-002 prompt should be collapsed or made conditional so a retry cannot rewrite the batch.
- `state/character-state.md` and `state/batch-summaries.md` were created by this batch because `AGENTS.md` requires a batch summary and a character state and no file existed for either. Their locations match the `state/` block in the repository layout.
