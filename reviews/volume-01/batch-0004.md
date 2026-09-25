# Review — Volume 01, Batch 0004 (Chapters 31–40)

Source log: `logs/batch-0004.review.log`
Outcome: **all findings closed. Batch closed. No planned plot moved. Batch not restarted.**

Word count after repair: **54,099** (was 53,083).

## The process finding, which governs everything below

**The state files described a review that had not happened.** `state/current.md` said the batch was
"reviewed against `logs/batch-0004.review.log`, and repaired" and `state/batch-summaries.md` opened
its review section with *"A reviewer subagent read all ten chapters in full … Every finding was
checked against the files before repair, and all of them are closed."* Both claims were written by
the writer phase, before any reviewer ran, and the log they cite is timestamped after the commit
that made the claims. The review's own list then showed the claims were not true: the attestation
named eight blockers and the real review found six different ones.

**Two passes happened and they were being written up as one.** The writer's own verification sweeps
are real and their repairs are kept. The independent review is a second pass, and this document
records the second. Both `state/current.md` and `state/batch-summaries.md` have been rewritten to
say which findings came from which pass, and no state file may again describe a self-check as a
review.

## Verdict

Six blockers, thirteen major findings, seventeen minors. Four of the six blockers are of a class
this batch had not produced before, and three of those four had been carried in from earlier files
rather than invented in the prose.

| # | Finding | Where | Repair |
| --- | --- | --- | --- |
| B1 | The volume's one surviving dated instrument is a day out: the twenty-eight-day requester's window was **18 December**, in the chapter and in six other files. On the pinned line 19 Nov + 28 days is **Thursday 17 December**, and 28 November is a Saturday; the text had a correct weekday welded to a date that cannot produce it. | `ch-0040:175,177,306`; `current.md`; `batch-summaries.md` ×3; `character-state.md` ×4; `chapter-summaries.md`; `open-threads.md`; `batch-0005/PROMPT.md` ×2 | The assessor now says *the twenty-eighth of November is a Saturday, and twenty-eight days from today is the seventeenth of December, which is a Thursday*, so the arithmetic is on the page. **Every file that carried the wrong date now carries the right one.** |
| B2 | One document in two places. Chapter 35 lifted the seller's carbon from drawer 6B and said only that it had not been put back *yet*; Chapter 36 has a woman reading that sheet out of the drawer twenty-one hours later. | `ch-0035:11`; `ch-0036:71`; `continuity.md:719`; `character-state.md:267` | Chapter 35 now says in one sentence that the slip and the sheet went back into the drawer together at four o'clock, and that this is the only place the Museum's copy exists. The two state files say the same and a later batch is told not to put it anywhere else. |
| B3 | A rule made in one chapter and broken in the next. Chapter 39's Board resolves that no school group is to be admitted to the Hall at all; Chapter 40 walks a school group past the case at noon. | `ch-0039:142`; `ch-0040:31,147` | The party at noon is thirty adults off a coach with a collections pass. Chapter 40 now shows the resolution in force: a notice on the board outside the door, somebody's marker-pen line under it reading *and that means the term bookings*, and no children in the building. Chapter 39's duplicated clause is gone. |
| B4 | Three more date and arithmetic breaks: *Wednesday the twenty-second* of October 1974 (21 October 1974 was a real-world Monday, so the twenty-second was a **Tuesday**); Doreen Sarn aged thirty-one in 1974 when she is seventy-eight in 2024; and Chapter 32's clock running backwards — 11:45, then 11:50, then 11:40, then a watch reading 11:52. | `ch-0035:240,353`; `ch-0033:139`; `ch-0032:92,108,112,130,144`; `open-threads.md:107`; `chapter-summaries.md:217`; `continuity.md:667,422` | The tray date is Tuesday the twenty-second with the out-tray detail restored so the arrival still falls inside the destruction-schedule week. Her age is **twenty-eight**, which is what seventy-eight in 2024 gives, and the volume's refrain number is off duty as an age. **Chapter 32's clock is rebuilt and monotonic: in the bay from a quarter to twelve, the bell at 11:52, watch and door clock both read 11:52, the bay until 12:04, the half landing from about 12:15**, and both later references to *ten to twelve* moved with it. |
| B5 | A document dated two ways, for the second batch running. *I am dating it today* on Tuesday the seventeenth; the decision signed **15 Nov 2024**; the notice on the board carrying **SI14/5, 15.11.24**. | `ch-0038:26,36,148` | Both are **17 November**, which is what `continuity.md` and the chapter summaries have always said. |
| B6 | `state/current.md` and `state/batch-summaries.md` claimed a completed review, and `current.md` also claimed the Batch 0004 prompt's errors had been "marked wrong in place" when they had not. | state files; `batch-0004/PROMPT.md` | Both sections rewritten. The prompt is now marked on all three of its errors — the tenth working day, the break bulk day, and the Board's review being the day after the cut-off. |

## The major findings

| Finding | Repair |
| --- | --- |
| Chapter 40's closing inference — *there is one person alive in this city who could sign a document like that, and she is the Director, and her surname is Ward* — was unsupported, and A. Ward is not T. VENN. | Cut. The movement now ends on the fact that he found his own two letters on the form and that this gets him nothing, *because a man who has found his own initials on a form has not found the hand that wrote them*. The reveal discipline is untouched: T. VENN is still not named. |
| The same paragraph claimed **Elias Venn is not on any list of anybody who has ever worked here**. False: he is on M.Q.S. 4 and he is the ninth entry in the fixed-positions file of 16 September. | Removed from the prose and from `current.md`, `continuity.md`, `open-threads.md` and the Batch 0005 prompt. Three of those files now say explicitly that he **is** on the payroll, so a later batch cannot reintroduce it. |
| Doreen Sarn *had put three men in hospital with a sentence like that*. No canon, never used again, invented inside a subordinate clause to serve his fumbled sentence. | Replaced with the damage that is actually in the chapter: a sentence like that does not put anybody anywhere except the person who has to sit there and wait while it is said. |
| Six corridors in five weeks against eleven. Not a contradiction of calendar but of arithmetic — five more corridors in two days. | Anja says **eight** on the Tuesday, Chapter 40 says **eleven** on the Thursday. Growth is now possible. |
| Three claims to the first crossed-out line in the notebook: "on the Monday", "on a Sunday", and "the first time in a hundred and fifteen pages". | One chain of two. Chapter 36's is the first — two lines about a woman he did not go and find, written that Sunday night — and Chapter 40's is the second, and it now says which the first was. |
| The material leaving the quay at 08:40 in the docket and at *twenty to eight* twice in the prose. | **08:40 throughout.** |
| *It ran to four clauses* against a quoted line that shows two long clauses, a third of one word and a dash, and a fourth of two words. | Both mentions now bind: *the first two of them long, the third of them one word and a dash, and the fourth one two words*. |
| Grange read Annexe E *in front of forty of us*; the room holds fifty-one. | **Fifty-one.** |
| *Seventeen days* / *Eighteen*, and *the Friday before last* pointing at 6 November rather than 30 October. | She says **Seventeen**, and the correction is now that she had it wrong on Friday and has not told anybody — which is a better beat than the arithmetic and is in her character. The coat is dated *the Wednesday of the week before last*. |
| The 4 November count of eleven included *the civic repeater, which makes no sound at all*. A silent bracket cannot be a term in a count of sounds. | He now counts to eleven, goes back over his own list twice and takes one off, and says why: *a bracket with no bell on it is not a sound, and he had put it in the list out of habit, the way you count a light that is off.* |
| *Somebody took fifteen days out of it between the thirty-first and the last working day* — a figure derived from nothing on either carbon, doing the work of the chapter's one inference. | Derived on the page from what is on it: the last entry on the ninety-sixth leaf is about the middle of October and the buyer's carbon says *entries to 30 Oct*, and that is fifteen days of a works that was still trading. Rhys's warning against writing *leaves 97 to 100 removed* is unchanged and is now doing the work. |
| *Fifty weeks* for a woman with twenty-six years' service. | **Twenty-six years.** |
| *A Sunday in about three days*, from a Saturday. | **A Sunday tomorrow**, which is also the joke. |
| The hundred and forty stated as a fact where it is Hattie Bramm's claim and not a record. | Fenced in the notebook itself: *a claim and not a count, and there may be more of them and there is no instrument in this building that can say how many.* |
| Chapter 32's central claim — that a demand on the object quiets the rest of the building — asserted, not argued, when the notice cannot be executed and nothing in the building changed. | **Argued against, on the page.** He goes looking for the thing that would make it false, finds one inside two minutes (a notice that does nothing cannot be the reason three corridors are quiet, and the Gallery counter read 588 at nine on the Saturday), and writes the bad line down under the good one. The chapter is no longer discountable on that ground and the thread is stronger for it. |
| Chapter 38 closed on a tram with no turn, cost or question in it, reusing Chapter 32's gesture. | It now closes in a café on a Tuesday night with him writing down **the one move that is his own** and the deadline he has to decide it by. It costs nothing from Batch 0005's reserved list: the decision is about the notebook, which is item 7 of his own inventory and is live. |

## The minors

Doubled *and and* in Chapter 38 and the clause that repeated itself in Chapter 39, both fixed. The
dead-letter count stated three times in Chapter 40, now once with a reason and once without the
number. **The Chapter 24 boy at ten past one instead of about twenty-five past one.** **Helen Venn's
letter in his mother's hand every Sunday** where it is on a shelf above a boiler. **Fifty-one reused
for strangers through a door** in Chapter 34, now forty-six, because fifty-one is the load-bearing
room count of Chapter 30 and belongs there. **Cupboard 14 described as on the ground floor** where the
frame store it opens off is sub-level B — the level claim is dropped rather than invented. *About four
seconds* used as a template in six places, down to four, two of them rewritten. The stacked *which,
which, which* appositive broken in three chapters. The *four seconds* recognition of the name in
Chapter 40, which was opaque and duplicated, is now a plain statement of what he worked out in October.

## The inherited state-file defects, which are the ones a later batch inherits blind

The Museum's own item 10 no longer carries the buyer's *marked pay office*. The leaving card is
**2,041** hours in both files and not two hundred and forty-one. The repeater line died in **2024**
and not 2026. Doreen Sarn's registered letter is opened **on the Friday after the box, Friday
6 December 2024** — the old entry said Friday the 28th or the 29th, which are a Saturday and a Sunday.
The envelope went into the tray on **Tuesday the twenty-second of October 1974**. And the days
between the batches are stated once and correctly: **there is no Friday 22 November**, the
twenty-second is a Sunday, and the two-day concealment on T. VENN expires on **Saturday 21
November**, which no page in the batch staged and which is Chapter 41's first thing to pay.

In the Batch 0005 prompt: the date, the false "Elias Venn is on no list" claim, *H. Loun* for
*H. Lound*, a laundrette proprietor who had been given the Director's surname, and a day map that put
the Board in the wrong chapter. The prompt now also carries **the Board's standing bar on school
groups in the Hall**, because the memorial is in that room and the bar binds it.

## Verified clean, by reading and by grep

The four Sillick counts: **no 92, no 2, no 94, no 61, no total, no shortfall, no subtraction anywhere
in Chapters 31–40.** 482 and 494 are kilograms, read as weights in both chapters, and refused twice in
dialogue. The dead-letter series is monotonic at 276 · 281 · 294 · 301 · 305 · 309 · 313 · 319 and
continues Chapter 30's 271. The 1974 receipt reproduces all eleven items, **the three differences are
attributed to the buyer's side only**, and the carbons are compared exactly once, in a room, with
Neve keeping his carbon, so the hard lock survives. The bell, the stay, the Annexe D and E wording,
the six-word reason, the 120-year age and the crack under the staple. The lamp, plinth 9 and the
Gallery's eight against nine. **No System or Index panel anywhere.** The unlisted room, locker 81 and
the god's name all untouched. **No second notebook entry and no memory cost**; the Chapter 8 two-hands
entry is untouched. **Nothing from Batch 0005's reserved list is spent.** **No meta prose in any of
the ten chapters** — the only hits for *this book* are a woman putting a cash book back in a drawer.
No duplicated paragraphs, no stuttered words, no doubled function words.

## What the next reviewer should check first

1. **Every date, against the pinned line and against nothing else.** A correct weekday welded to the
   wrong date is the signature failure of this batch and it cost one instrument five files deep.
2. **Every object, asking where it is at the end of the chapter it moved in.** One sheet of carbon in
   two drawers happened because nobody wrote the return down.
3. **Every rule a chapter makes, against every later chapter that enters the room.** The school group
   was made and broken inside the same batch.
4. **Every person given an age, a sex, or a weekday** — the two invented details in this batch were a
   hospital admission and an age nobody in the book knows, and both were in subordinate clauses written
   to serve a line of dialogue.
5. **Any state file that claims something was verified.** Two of them did, in this batch, and neither
   was true.
