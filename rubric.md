# Scoring rubric

**Version 2, 2026-11-12.** Written by the coordinator before any agent has opened Kevin's tree. Each commit of this file is stamped; that proof is the evidence it came first.

Change in version 2: section 6a, Kevin's own confidence. Kevin has several trees and trusts them to different degrees. Version 1 treated his tree as one reference.

## 1. What is scored

The AI tree is the merged `people` data of the Duska and Demko repos, joined on the Ahnentafel number, at a stamped commit of each. Every stamped batch is a snapshot.

In scope: Ahn 1, 2, 4, 8 and 9, and every ancestor of Ahn 8 and Ahn 9. Out of scope: Ahn 5 and her ancestors, Ahn 3 and hers, and all living people other than Ahn 1.

A **fact** is one of these, for one person in scope:

| Fact | Counts as a match when |
|---|---|
| Identity: a named person at this Ahnentafel position | given name and surname agree, allowing spelling and language variants (Mihály, Michael, Michal) |
| Parent link: this person is the child of that father and that mother | both parents are the same people |
| Birth or baptism: year | same year. Scored separately: exact date |
| Birth: place | same village or parish under any of its names |
| Marriage: year, place, spouse | as above; spouse by identity |
| Death or burial: year, place | as above |
| Rite or denomination | same |

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

If Kevin's tree exists in more than one version, the Scorer uses the latest for each person and lists every place where the versions disagree with each other.

## 6a. Kevin's own confidence

Kevin's trees are not equally sure, and he says so. The reference is sorted into tiers before any scoring.

**What Kevin provides, sealed with his tree files and before he sees any score:** one line for each tree file saying what it is, when he last worked on it, and how far he trusts it: high, medium or low. He may add a short list of people or branches he is sure of or doubts. Nothing else is asked of him.

**What the Scorer builds first, from his files alone, before it reads any AI snapshot:** the reference set, one row per fact in scope, each with a tier.

| Tier | A fact is in this tier when |
|---|---|
| A, firm | It is in a tree Kevin rates high and carries a source citation there; or every version of his trees gives it identically; or he lists it as sure |
| B, probable | It is in a high tree without a source, or in a medium tree with one |
| C, tentative | Everything else: it is only in a low tree, or his versions disagree about it, or he lists it as doubtful |

The Scorer stamps the reference set, privately, before scoring. That fixes the tiers before the results are known.

**How the tiers are used.**
- Every number in section 4 is reported for tier A, tier B and tier C separately, and for all three together.
- Agreement on tier A is the main measure of the rebuild.
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
