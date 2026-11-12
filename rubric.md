# Scoring rubric

**Version 5, 2026-11-12.** Written by the coordinator before any agent has opened Kevin's tree. Each commit of this file is stamped; that proof is the evidence it came first.

Change in version 5, three clarifications in section 1, asked for by the Scorer before it read any AI repository: people who are living or of unknown status; exact dates; a parent link is two facts.

Change in version 4, three clarifications asked for by the Scorer before it built anything: each tree file is sealed on its own; section 6 no longer says "the latest for each person", which disagreed with section 6a; equal grades are ranked by the date last worked on.

Change in version 3: in section 6a Kevin grades each tree file by letter, and a fact can move one tier up or down from its file's grade. Version 2 asked for high, medium or low and fixed the tier by a table.

Change in version 2: section 6a, Kevin's own confidence. Kevin has several trees and trusts them to different degrees. Version 1 treated his tree as one reference.

## 1. What is scored

The AI tree is the merged `people` data of the Duska and Demko repos, joined on the Ahnentafel number, at a stamped commit of each. Every stamped batch is a snapshot.

In scope: Ahn 1, 2, 4, 8 and 9, and every ancestor of Ahn 8 and Ahn 9. Out of scope: Ahn 5 and her ancestors, Ahn 3 and hers, and every other person known to be living.

**People who are living or whose status is unknown.** Ahn 1 and Ahn 2 stay in scope whatever their status. The status of each person is the one in the table under X-016 in the coordinator's ledger. For a person who is living or unknown, only the facts the agents are allowed to publish are scored: identity, each parent link, and the year and the city of an event. An exact date, or a place finer than a city, has the outcome **withheld**. A withheld fact is outside every numerator and denominator and is counted in a line of its own. If the status of a person changes in the ledger, later snapshots are scored on the new status and earlier rows are not changed.

A spouse who is out of scope (Ahn 3, Ahn 5) is matched by name only.

A **fact** is one of these, for one person in scope:

| Fact | Counts as a match when |
|---|---|
| Identity: a named person at this Ahnentafel position | given name and surname agree, allowing spelling and language variants (Mihály, Michael, Michal) |
| Parent link, father | the father is the same person |
| Parent link, mother | the mother is the same person |
| Birth or baptism: year | same year |
| Birth: place | same village or parish under any of its names |
| Marriage: year, place, spouse | as above; spouse by identity |
| Death or burial: year, place | as above |
| Rite or denomination | same |

**Two facts, not one.** The link to the father and the link to the mother are scored each on its own. If the AI tree names one parent and that one agrees, that is one match and one missing.

**Exact dates.** For every event the year is the fact in the headline numbers. The exact date is scored as well, by the same outcomes, but outside the headline: it has its own coverage and agreement, reported beside them. A date within one year is a near match on the year and a conflict on the exact date.

Brothers, sisters and other relatives are scored the same way in a second table, "family groups", and stay out of the headline numbers.

## 2. Outcome of each fact

| Outcome | Meaning |
|---|---|
| Match | Both trees state it and they agree |
| Near match | They agree within a stated tolerance: a date within one year, a neighbouring village of the same parish |
| Conflict | Both state it and they disagree |
| Missing | Kevin's tree states it and the AI tree does not |
| Extra | The AI tree states it and Kevin's tree does not |
| Not comparable | One side is too vague to compare |

An AI fact is counted only if its proof level is `documented`, `inferred` or `stated`. A hypothesis that is still `open` is not a fact; it is scored in section 5.

## 3. Where each AI fact came from

Taken from the repos' proof levels and the coordinator's contamination log, not judged afresh:

1. Rebuilt from Kevin's archive.
2. Found in public sources.
3. Given by Kevin (every "scored as given" entry in the ledger).
4. Inferred, with no record naming it.
5. Contaminated: reached by way of an exposure in the contamination log.

## 4. Headline numbers, per snapshot

- **Coverage** = matches and near matches, divided by all facts in Kevin's tree that are in scope.
- **Agreement** = matches and near matches, divided by matches, near matches and conflicts.
- Each is reported twice: for all facts, and with classes 3 and 5 of section 3 removed. The second pair is the real measure of the rebuild.
- Each is also broken down by generation.
- Extras are counted and listed, never scored as errors: the AI may have found what Kevin did not.

## 5. Confidence

For every hypothesis that names a fact in scope, the Scorer records the agent's stated confidence at each snapshot and whether the fact matched. At the end this gives a calibration table: of the things the agents were 70% sure of, how many held.

## 6. Agreement is not accuracy

Kevin's tree is the reference, not the truth. At the end every conflict and every extra in the direct line goes back to the records and is ruled: AI right, Kevin right, both wrong, or cannot be decided. The ruling cites the record. Two final numbers are published: agreement with Kevin's tree, and accuracy after this review.

If Kevin has more than one tree file, section 6a says how they are combined. The Scorer lists every place where they disagree with each other.

## 6a. Kevin's own confidence

Kevin's trees are not equally sure, and he says so. The reference is sorted into tiers before any scoring.

**What Kevin provides, sealed with his tree files and before he sees any score:** one line for each tree file saying what it is, when he last worked on it, and a grade: A, B or C, with a plus or minus if he likes. He may add a short list of people or branches he is sure of or doubts. Nothing else is asked of him. The grades stay private.

Each tree file is sealed on its own: its SHA-256 is published in `sealed/README.md` of the coordinator's repository before the Scorer builds anything from it. Kevin may give the line about a file to the Scorer directly; the Scorer commits it to its private repository with the reference set, so it is stamped before any scoring.

A tree file may be in any form, a PDF included. The Scorer reads it as it is.

**What the Scorer builds first, from his files alone, before it reads any AI snapshot:** the reference set, one row per fact in scope, each with a tier A (firm), B (probable) or C (tentative).

1. A fact starts at the letter of the file it is in. If it is in several files, at the best letter among those that give the same value.
2. It moves up one tier if the file cites a source for it, or if two or more files give it identically.
3. It moves down one tier if his files disagree about it.
4. A fact he lists as sure is tier A. A fact he lists as doubtful is tier C.
5. Plus and minus do not change a tier. They rank his files when two of them disagree: the value from the better-graded file is listed first, and if the grades are equal, the value from the file he worked on last.

The Scorer stamps the reference set, privately, before scoring. That fixes the tiers before the results are known.

**How the tiers are used.**
- Every number in section 4 is reported for tier A, tier B and tier C separately, and for all three together.
- Agreement on tier A is the main measure of the rebuild. If tier A holds fewer than twenty facts, the main measure is tiers A and B together, and the feed says so.
- A conflict on tier B or C is not counted as an AI error. It is listed as a question for the records, and goes to the review of section 6 first.
- Where Kevin's versions disagree with each other, both values are kept. An AI fact that matches either is "matches one version", counted apart.
- An extra, a fact the AI has and none of his trees has, is listed with the AI's proof level beside it.

## 7. Sealed items

Each sealed statement in `sealed/` is opened at the end and scored on its own: found unaided, found after a nudge, found after being told, or missed. The contamination log decides which.

## 8. The Scorer

1. Works in a separate Project and is the only agent that reads Kevin's tree.
2. Reads the public repos at stamped commits only. It does not read the agents' chats or notes for meaning, and writes nothing to them.
3. Publishes one feed at one address: one row per snapshot with the commit of each repo, the date, and the numbers of section 4. No names, no facts, no per-person results.
4. Writes the per-fact results to its own repo, private until the end, and publishes the SHA-256 of each results file in the feed, so the detail can be shown later to have been fixed at the time.
5. Does not change a past row. A correction is a new row with a reason.

## 9. Changing this rubric

Any change is a new version in this file with the reason, and is stamped. After the Scorer has opened the tree, only clarifications are allowed, and each is listed here with its date.
