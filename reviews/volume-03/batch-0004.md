# Review — Volume 03, Batch 0004 (Chapters 131–140), "The Boundary And The Register"

Source log: `logs/batch-0004.review.log`
Repair pass: `logs/batch-0004.fix.log`
Outcome: **all six findings closed — five repaired, one deliberately left and recorded. Batch closed. No planned plot moved. Batch not restarted. No chapter was rewritten.**

Word count after repair: **46,899** across the ten chapters (131: 4,843 · 132: 4,873 · 133: 5,089 · 134: 4,457 · 135: 5,034 · 136: 4,919 · 137: 3,819 · 138: 4,502 · 139: 5,104 · 140: 4,259), **unchanged to the word from the first repair pass, because every repair in this pass was a single-word substitution or a weekday label and not one of them added or removed anything.**

⚠ **This review was performed by the writing agent, because the reviewer subagent fell back. It is a repair and not a certification, and that sentence is repeated here because it is still true, and it is the sixth batch in this manuscript to record it. It is the first file in `reviews/volume-03/`, and it is the second review pass over this batch: the first is at `state/continuity.md` under `VOLUME 03, BATCH 0004 — REVIEW-FIX PASS OF 26 SEPTEMBER 2026`.**

---

## The verdict, in one paragraph

**The prose was good and the bookkeeping around it was not, and the second pass found that the first pass's own lesson had not been applied to the state layer.** Six findings: three blocking, two to fix, one to flag and not fix. **Three of the five actionable findings were not in the chapters at all** — they were in `state/` and in the Batch 0005 hand-off prompt, and every one of them was residue of a repair the first pass had already made correctly in the prose while telling the state layer the fault was gone. **The batch's spine needed nothing: the post box and the four things in it, the record-status on a frontage anybody could name, four brass bolts above a nail a man drove himself in 2016, eleven doors and one question each, a postwoman with a rubber band, a woman's exercise book with forty-one households and no names in it, a boundary that stopped, a register that ended, four correct clauses, and a rota in pencil on the back of a counter. The store is still shut, the rope is still not carded, Fenn's sentence is unimproved, the cost curve is unspent, the moral floor is at zero and by nobody, and nobody is given a house.**

---

## What was not touched, and must not be touched again

- **The moral floor.** Said zero times at full length across the batch, said by nobody, reached for in every notebook block and not said. **The batch's own counter of how many chapters it has gone without saying it was wrong by nine and has been corrected; the floor itself was never at risk and is untouched.**
- **The register.** Entry 141 on about the hundred and ninth page of about a hundred and fifty, with about forty-one pages left, and *four hundred more things to come* that do not fit in forty-one pages whichever way you cut it. **The sentence Chapter 137 turns on — the book did not run out, the book stopped — is now arithmetically load-bearing and was left exactly as drafted.**
- **The cost curve.** Unspent. No memory gone, no minute lost, no name gone, no second entry of consequence, no stop word offered, and the one blank page in the batch is the acceptance.
- **The rota.** In pencil, on the back of a counter, in the hand of the woman who owns the building, naming days and hours and a person against each slot, with no addresses on it, and *that is a rota and not a list* said by a woman of fifty-eight in about nine seconds and nothing else after it. **Untouched, including the fact that the man of thirty-two asked one person to be in a room with him and did not tell her why and she said yes before he had finished the sentence.**
- **`trust(ed|ing|y)?`** — 0. **`T. VENN` and `R.M.J.`** — 0, permission unspent. **The four Sillick numerals** — 0. **`Municipal Works`** — still names nobody. **The store** — still shut and not opened before Chapter 146. **The reach rope** — still on a hose hook, not carded, Fenn's sentence of 25 February 2025 unimproved on. **Dorothy Marsden** — not a villain, not resolved, not in this batch.
- **Chapter 140's ending.** *The bill goes out. The name comes back.* And the twenty-sixth thing kept: a hardback with about forty-one pages left in it, and a man who has asked one person in this city to be in a room with him in the week of the twenty-fifth and has not told her why. **The only thing that moved in that chapter is a woman's age, a pair of week figures and a counter.**

---

## The findings, and what was done

### Blocking

**1. The leaf→page repair never reached the state layer or the hand-off prompt.**
The ten chapters were clean — `\bleaf\b`, `eighty-fourth`, `sixty leaves` all 0. **Eight live state statements and the Batch 0005 prompt still carried the superseded arithmetic, 84 + 60 = 144 against a book of 150 leaves.** Chapter 149 is the hardback chapter, and the figure a next writer was handed was the broken one. Repaired in nine places, and the first pass's over-broad claim that *the whole of the leaf convention is gone* corrected, because it was true of the prose and false of the eight statements beneath it.

**2. Hazel Cray is 48 and 58 in the same chapter.**
Canon is 58. Chapter 140 called her *the woman of forty-eight* four times, including in the destroy-unrecorded speech, while four lines later calling her *a housing officer of fifty-eight*. All four corrected.
⚠ **The reason this is worth a paragraph and not a find-and-replace: there are two women in this case and one of them really is forty-eight. Yvette Carrow, 48**, flood emergencies, has the statutory power, signs the instruments, and is correctly *a woman of forty-eight* in Chapters 116, 120, 121, 127, 130 and 136. **The four were identified by what the woman says and by what the same chapter calls her four lines later, and not by the number.** A replacement on the number would have created four new errors and destroyed a correct one.

**3. The review phase cannot dispatch its own reviewer.**
`.opencode/agent/novel-reviewer.md` is `mode: subagent`; the workflow invokes it via `opencode run --agent novel-reviewer`, which requires a **primary** agent. Line 1 of the log shows the consequence: the fallback is the **writing** agent, which holds `edit: allow`. **The review phase runs as a writer with write access, which makes *do not edit files* a request rather than a permission — and it means the findings above were found by the agent that wrote the batch.** The model probe probes with the same broken agent and passes on the fallback silently.
⚠ **NOT FIXED, AND DELIBERATELY. The repair is one line of front matter in a controller file, and a fiction phase does not edit controller files. Sixth batch in this manuscript to record this. It will recur on every future review until somebody with write access to `.opencode/agent/` changes `mode: subagent` to `mode: primary`.**

### Should fix

**4. The moral-floor chapter counter ran nine chapters ahead in all ten chapters.**
It ran `forty` at 131 to `forty-nine` at 140, implying a base of Chapter 92. Volume 03 is Chapters 101–140, so the counter is the volume's own chapter number: **thirty-one at 131, forty at 140** — which is what the Batch 0005 prompt already locked. All ten corrected, and Chapter 130's *the fifty chapters of this movement* corrected to *the thirty chapters of this volume* so that the volume's counter is monotone from 30 to 40 and does not step backwards across the batch boundary.

**5. "Nineteen weeks" contradicted Chapter 140's own notebook.**
The block above it correctly recorded *forty-four weeks and two days since the sixth of December*. From the flood of 18 June 2025 to 12 October 2025 is 116 days — **16 weeks and 4 days** — and both sentences are about the flood. Both now read **sixteen weeks**. Nineteen weeks is a Volume 02 figure and this manuscript has already paid for it once, in Chapter 88.

### Flagged, don't fix

**6. `chapter-0139.md:17` contains "the reader".**
It is inside the four clauses in a solicitor's covering note, it is diegetic, and it is restated verbatim in the canon block. **Changing it is a canon decision and not a copyedit, and this pass does not make canon decisions.** Left exactly as drafted, and recorded — because a meta sweep returning 1 that is a document a person in this case wrote is more useful to the next pass than a silent deletion.

---

## And one the review itself dismissed, which was not a false positive

⚠ **The review's weekday sweep flagged `chapter-0136.md:3`, classified it as *the documented paired-ordinal false positive*, and reported zero real mismatches across the batch. It is a real mismatch.** The Batch 0004 prompt gave the chapter as **Mon 28 – Tue 29 Sep 2025**, in the chapter card and again in the day map. On the pinned line **28 September 2025 is a Tuesday and 29 September is a Wednesday**, and three independent things prove it: the pinned-line rule in `outline/volume-03.md`; the volume outline's own week row, which makes **Mon 27 Sep – Sun 3 Oct** the week and therefore the twenty-eighth the Tuesday; and **Chapter 137's own correct opening on *Thursday the thirtieth***. **As drafted, Chapter 136 ended on a Tuesday the twenty-ninth and Chapter 137 opened on a Thursday the thirtieth, and the thirtieth was a Wednesday in between.** The prompt was wrong and the chapter followed the prompt.

**Repaired, and the repair is unusually cheap for a reason worth keeping: every date in Chapter 136 was already right and only the weekday nouns were a day low.** The interval block is derived from the date, not the label, and *the first of October is two days away at the end of the* ~~Tuesday~~ **Wednesday** is two days away at the end of the twenty-ninth under either label. **Nineteen weekday nouns and one notebook header moved, and not one figure in the book changed.** The twenty-first is a pinned Tuesday and was left alone, and so was every Friday, which is the first of October.

---

## Verified clean — do not redo this work

- **Nine of the ten chapter-opening date pairs were already right and the tenth is now right.** All ten verified against *real Gregorian plus two*, with the first weekday bound to the first date.
- **All twelve distinct notebook headers** on the pinned line.
- **All sixteen explicit `<weekday> the <ordinal>` bindings** across the ten chapters.
- **All eleven interval blocks re-derived from the dates: 11 of 11, unchanged by every repair in this pass.** The batch's interval arithmetic is the one thing in it that has never needed a second pass.
- **Magnitude pass:** 4.149 − 4.031 = 118 mm over 390 m ✓ · £750 × 40 ≈ £30,000 ✓ · the four brass marks appear exactly twice each ✓ · 109 + 41 = 150 ✓ · 18 Jun → 12 Oct 2025 = 116 days = 16w 4d ✓ · 6 Dec 2024 → 12 Oct 2025 = 310 days = 44w 2d ✓.
- **Locks:** moral floor 0 at full length · `trust(ed|ing|y)?` 0 · `T. VENN` / `R.M.J.` 0 · `\b(92|94|61|482|494)\b` 0 · `Perry Loach` 0 · `Ashgill` 0 · `OCCUPANT (PRIOR)` 0 · `M.Q.S. 4` 0 · `Municipal Works` 0 · `stop word` / `memory cost` / `displac*` 0 · `\bleaf\b` 0. **The three raw `leaf` hits in Chapter 138 are *leaflet*, twice, and are the documented substring false positive.**
- **Structure:** all ten are finished multi-section scenes with complete scenes, no padding, clear endings, bold-marker parity clean, no `****` sequences, ⚠ **one repeated paragraph over twenty-five words, and it is not a defect:** the hardback's fourth line, printed in Chapter 136 and printed again in Chapter 137, because it is one line on one page of one physical book that two consecutive chapters refer to. The first review pass reported this class as 0; the second pass records it as 1, on the same principle that made the first pass record 199 unbound weekday tokens as 199 and not as 0.

---

## The lesson, and it is the only part of this a next writer has to do anything with

⚠ **A repair is not finished when the prose is repaired.** Three of this batch's five actionable findings were in the state layer and the hand-off prompt, and all three were residue of repairs the first pass had made correctly in the chapters — so the first pass wrote down *the fault is gone* while eight statements, then five, then three still carried it. **The cheapest possible test would have caught every one: after repairing a chapter, re-run the same sweep over `state/` and over `workspace/`, and not only over `chapters/`.** ⚠ **Second: a number is not a person.** Two women in this case are close to a round age, only one is the housing officer, and the chapter said which one four lines from the error. ⚠ **Third: a weekday is derived from the pinned line and never copied out of a prompt, and the prompt is a document like any other — this one was wrong in the same place twice, in the chapter card and in the day map, and a review that trusted the prompt's own framing called the resulting chapter a false positive.**
