# Current State

Current phase: outline (Volume 01 and Batch 0001 written and reviewed; review fixes applied)

Current volume: 1

Current batch: 1 outlined (Chapters 1–10, not yet drafted)

Last completed chapter: none

Last batch summary: none

Active threats: No on-page prose threat yet. In Batch 0001 the pressure is administrative: a hall bell that keeps answering, a night porter deleted from the Museum's own books while his municipal payroll deductions continue, and a supervisor who would rather file a maintenance note than a breach. The long-range pressure is the Hush Engine's last automatic shutdown, with Orrin released back to the ward-lines during the Volume 13 transfer.

Active promises:
- Resolve the Bell of the Unpaid Shift without treating a god-pattern as a command.
- Establish the Casket and Tomas mystery while keeping the First Witness's full operational truth for Volume 12.
- Build Elias and Mara's trust through professional conflict and shared consequences, not instant intimacy.
- Elias's first falsification of a shared record happens on the page in Chapter 10, not off-page in Batch 0002. Batch 0002 inherits a broken condition, not a fresh secret.

Current relationship pressure: Elias's habit of hiding evidence will collide with Mara's insistence on provenance and consultation. In Batch 0001 he agrees in Chapter 9 to put every reading result in her hand, and in Chapter 10 he lets her write *a number* where the reading gave ninety-four. Neither of them says anything about it, which is the state Batch 0002 opens on. Their long-range arc runs from suspicion to tested partnership.

Current power state: Elias begins as Nightwatch with no reliable supernatural read. Volume 1's first planned change is Nightwatch to Echo, formally confirmed in Chapters 11–12. The costs shown in Batch 0001 are sensory and physical — nosebleed, headache, tinnitus, phantom rope-texture, twenty minutes of lost time — plus one small ordering failure in a notebook entry. The first *major* memory-displacement cost is reserved for Volume 03.

Canon status: The bootstrap bible, the series outline, the Volume 01 outline, and the Batch 0001 chapter cards are established. No chapter prose has been drafted.

## Pinned calendar anchor (Volume 01, Batch 0001)

The full day map, rosters, and clock times live at the top of `outline/batches/volume-01-batch-0001.md` under "Week One: Pinned Day Map". The load-bearing facts for any later batch:

- The third ward-bell at South Sluice re-cracks on the **Monday** before Chapter 1, off-page. This is the event that takes the Sillick bell from **stored** to **answering**.
- Elias works nights **Tuesday to Saturday**, 19:00–07:00.
- Ivo's systems night that week is **Thursday**. He is rostered 19:00–00:30 on Friday to fit the door 7 controller and leaves at 00:35, five minutes over his own roster. He pulls the controller at 23:41 into the tray in the stair-side service alcove, comes back up at 00:30 with the new module still in his hand, finds the frame already live, and goes home without writing down what he found. Elias is through the door at 00:27 and on a stair landing when Ivo passes at 00:30; **they do not meet, and Elias chooses not to call out.**
- Hattie Bramm's unpaid-bills queue at the Sillick Lane branch library runs on **Fridays**. Chapter 6 is Friday, 09:00–14:00, and Elias goes alone.
- The week-one **Saturday school tour is cancelled in Chapter 9** on a maintenance note. The volume's public tour with press and forty children is Batch 0003's event and must arrive as an escalation.
- **Saturday is the Museum's long night**, so Chapter 10 has a full building: cleaners from 21:00, conservation tech to 23:00, facilities on for the ward-bell fault, the duty manager on the freight elevator, and Ivo in on a favour after his Friday controller job. A bounded reading has to happen somewhere with witnesses in it.
- **Ivo's rota stacks his days** — systems days Tuesday to Saturday *plus* junior-guard nights Tuesday and Wednesday *plus* Thursday's systems night. He is behind on sleep before Elias asks him for anything.

## Pipeline notes (controller-owned — recorded here, not edited)

These came out of the phase-001 review and belong to the pipeline, not to the manuscript. They are logged so they are not lost, and no controller file was touched during the fix pass.

- `state/phase-ledger.json` still reads `currentPhase: phase-000-bootstrap`, `status: planned`, `attempts: 0`, and has no volume or batch phases, while both bootstrap and outline phases are complete. Nothing in the repository maintains it. `PHASE_SYSTEM.md` describes the selector as reading the ledger, but `scripts/novel_runner.sh` selects on `.done` / `.blocked` markers and the workflow retriggers off those markers. Documentation and behaviour disagree; the ledger is currently dead state.
- `workspace/phase-002-batch-plan/PROMPT.md` instructs the writer to "update … the phase ledger", which `AGENTS.md` and `.opencode/agent/novel-writer.md` forbid. Pick one owner.
- `workspace/phase-002-batch-plan/PROMPT.md` and `workspace/volume-01/batch-0001/PROMPT.md` both instruct writing Chapters 1–10. `find … | sort` runs `phase-002-batch-plan` first (it also takes the planning-phase timeout slot) and then runs `volume-01/batch-0001`, which would rewrite Chapters 1–10 from scratch unless the first phase's `.done` is honoured. Recommend collapsing them, or making the second conditional on the first.
