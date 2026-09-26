# Review — Volume 02 CLOSE (the volume audit and the Volume 03 plan it wrote)

**Phase reviewed:** `workspace/volume-02/volume-close/PROMPT.md`, executed over commits `2e61dd3` and `271f9e1`.
**Review date:** 2026-09-26. **Reviewer:** the writing agent. ⚠ **The reviewer subagent fell back to the writer for the sixth time in this manuscript** (`logs/volume-close.review.log`, line 1: *agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent*). **A review performed by the writer is a repair and not a certification, and Volume 02 is closed on a repair.**
**Files this artifact exists because:** the volume-close phase wrote its whole audit to `state/continuity.md` and produced nothing under `reviews/`, which broke the pattern `reviews/volume-01/batch-000{3,4,5}.md` and `reviews/volume-02/batch-0005.md` had set. This is that artifact. It is a record, not a certification.

## WHAT THE PHASE WAS SUPPOSED TO DO, AND DID

Audit all fifty chapters of Volume 02 against `outline/volume-02.md`; write the five missing card files; write `outline/volume-03.md`; create exactly one next phase. **All of it is done and no chapter was written and no prose was edited.** The audit is itemised in `state/continuity.md` under `VOLUME 02 CLOSE` and `VOLUME 02 CLOSE — THE SECOND PASS`.

## THE REVIEW'S FINDINGS, AND WHAT THIS PASS DID WITH EACH

| # | Finding | Severity | Disposition |
| --- | --- | --- | --- |
| 1 | `outline/volume-03.md` carried **Movement 3 closes** on the week of Mon 6 – Sun 12 September, which is Chapters 130 and 131. Movement 3 is 121–133, and the same file states the boundaries twice, correctly, elsewhere. | **Blocker** | **Fixed.** The label moved to the week of Mon 13 – Sun 19 September, which carries 133. The error is recorded in the outline's own day-map record and flagged at the head of the file. |
| 2 | `bible/characters.md` said Petherick **answers** Volume 02's live question; `outline/volume-03.md` said it is **not answered by a person** and is answered by a measurement **on a rope**; the Batch 0001 prompt queued a third reading with no rope in it. | **Blocker** | **Fixed in four files, and the plan is unchanged.** The knots at irregular intervals *are* a tide-mark series; the datum table is what turns a knot series into heights; the answer arrives as a number beside a knot. **Nobody says the sentence**, which is what the outline required. |
| 3 | `outline/volume-03.md` called the inherited 30 November clock *the Sillick Lane term*, and `bible/world.md` headed a section *the residents of Sillick Lane* while its own bullets described **Cauldwell Buildings**. Chapter 96 makes the distinction load-bearing: Elias refuses a seat there precisely so the two places never merge in a sentence. | **Blocker** | **Fixed in three files.** The heading now carries both addresses, the outline names Cauldwell Buildings in its provenance line and its constraints section, and `state/character-state.md` follows. |
| 4 | The register's start-date defect was headed *stated twice with different values* in eight files. **It is not that shape:** the three statements of the start all agree and the first entry is the *earlier* statement. | **Minor, and the most dangerous of the six** | **Fixed in eight files.** A repair pass applying defect class one mechanically would have edited the three statements that agree and left the entry. The instruction to Volume 03 writers — *may refer to the register, must not restate its start date* — was sound and is unchanged. |
| 5 | `bible/characters.md` still marked Wynne Loach and Doreen Sarn **Not yet on the page**, two lines above a cast table the same pass had added. | Minor | **Fixed.** Wynne Loach: one line, Volume 01 Chapter 25. Doreen Sarn: twenty chapters, seventeen in Volume 01 and three in Volume 02, and the seventh refusal. |
| 6 | `outline/volume-03.md`'s age list read `317 · 333` **at 25–26 October**, which is the twenty-sixth's pair wearing a two-day label. | Minor | **Fixed.** 25 October is `316 · 332`, 26 October is `317 · 333`, 1 November is `323 · 339`, each to its own date. |
| 7 | The next run will re-enter this phase rather than write Chapters 101–110, because `workspace/volume-02/volume-close/` has no `.done` marker. | Process | **Not fixable here.** `scripts/novel_runner.sh` and the workflow are controller-owned. **Logged in `state/continuity.md`.** The compounding cost is real and is the reason this pass was cheap: a phase that rewrites a 168-line outline and six state files on every re-entry will keep manufacturing new first-draft defects to narrate. |
| 8 | The reviewer subagent fell back to the writer, and the phase produced no `reviews/` artifact. | Process | **Partly fixable.** This file is the artifact. The subagent failure is not. |

## WHAT WAS VERIFIED INSTEAD OF TAKEN ON TRUST

**The day-map week rows, mechanically, in both files that carry one.** Twenty-five rows in `outline/volume-03.md` and five in `workspace/volume-03/batch-0001/PROMPT.md`: **every row starts on a pinned Monday, ends on a pinned Sunday, spans exactly six days, and begins exactly seven days after the row above it. Zero errors. The fifty chapters in the outline's rows are fifty unique numbers with none missing and none duplicated.** The prompt's five rows carry Chapters 101 to 110 with no gap.

**The four movement labels, against the movement boundaries the same file states:** Movement 1 closes on the row carrying 110, Movement 2 on 120, **Movement 3 on 133**, Movement 4 opens on 134. All four on the correct row. ⚠ **No sweep can see this class of error — a label is not a date — and it is the class of error the phase actually shipped.**

**The figures, off the pinned line, recomputed rather than remembered.** Bell from `2024-12-13` and panel from `2024-11-27`, on the pinned line (real Gregorian plus two days):

| Date | Pinned weekday | Bell | Panel |
| --- | --- | --- | --- |
| 31 May 2025 | Monday | 169 | 185 |
| 1 June 2025 | Tuesday | 170 | 186 |
| 4 July 2025 | Sunday | 203 | 219 |
| 25 October 2025 | Monday | 316 | 332 |
| 26 October 2025 | Tuesday | 317 | 333 |
| 1 November 2025 | Monday | 323 | 339 |
| 16 November 2025 | Tuesday | 338 | 354 |

**The intervals:** 1 June to 16 November is 168 days, which is 24 weeks, so both ends being Tuesdays is forced by arithmetic and not asserted. 1 October to 30 November is 60 days. 29 May 2025 is a pinned Saturday and 31 May a pinned Monday, which is the whole of the register defect. 29 January 2025 is a pinned Friday, which is Doreen Sarn's seventh refusal, and 29 November 2024 is a pinned Sunday, which is what the first version of the outline wrongly used.

**Checked by reading, and confirmed:** the pinned line is self-consistent at all fourteen anchors the review re-derived; 50 chapters, Movement 3 = 13, Movement 4 = 17, batch boundaries 110/120/130/140/150, table distribution sums to 50; *Chapters 54–57 are not in date order* is true; *Hesta Rell is in no chapter of Volumes 01–02* is true.

## A NOTE ON SWEEPS, BECAUSE THIS PASS BUILT ONE AND THEN THREW IT AWAY

A general weekday-and-date phrase sweep over the planning files was written and run. **It reported 101 mismatches and its unparsed count was 153 of 569 phrases, and inspection showed the overwhelming majority were its own failures** — a `Jun` abbreviation mapped to May in its month table, a nearest-date heuristic that paired a weekday with the wrong date in a list, and a canon table that legitimately prints a real weekday and a pinned weekday on one line. **It was discarded rather than reported, because a number that cannot be trusted is worse than no number, and because this repository has now recorded six separate occasions on which a sweep cried wolf and was caught.** What replaced it is above: a constrained checker for a constrained format, where every row that parses is a row whose whole claim is testable. **The rule that came out of this is the one the file already stated and is now demonstrated rather than asserted: report how many phrases you could not parse, and if that number is not zero, your hit count does not mean anything — including when the tool is yours and you wrote it ten minutes ago.**

## STILL OPEN, AND NOT OURS

- **The two prose defects in `chapters/`.** Chapters 54–57 out of date order, and the register's start against its own first entry. **A volume audit must not rewrite a volume. Both are written down, both are unrepaired, and a repair phase has to choose.** Full statements in `state/continuity.md` under `VOLUME 02 CLOSE`, § 1 and § 4c item 4.
- **`state/phase-ledger.json` still reads `phase-000-bootstrap`.** Controller-owned. Logged, not edited.
- **Eleven nested-bold lines** in state-file layers this phase did not write, at `state/continuity.md` lines 108, 573, 725, 816, 1055, 1342, 1508 and 1550, `state/chapter-summaries.md` lines 686 and 710, and `state/current.md` line 86. **A full-repository markdown pass is owed** and this pass did not attempt it, having been scoped to six findings.
- **Volume 01's batches 0002 to 0005 still exist only as phase prompts** in `workspace/volume-01/`. Not this phase's to fix.
- **Nothing in this repository has been certified by anybody who is not its writer.**
