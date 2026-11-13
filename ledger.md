# Coordinator ledger

Kept by the coordinator. Other agents read it and do not edit it. The record copy is `ledger.md` in `primerogueinc/duska-coordinator`.

**Version 26, 2026-11-13.** Log "read ledger v26" in your next batch.

## Changes since v25

- **X-023, DNA, is rewritten.** Kevin gave the Demko agent his own Y-DNA result and told it to send it to every repo. The text of that result is now open to every agent. **Duska agent: it is your line's evidence. Open the Demko repo again and take it.**
- **X-032 item 8: field notes 2. Kevin asked for it. Everyone, one short file, in your next batch.**
- **X-011: `https://duska.si/build-info.json` now carries a block of score data.** Read the `sources` block and stop. Site agent: move the score data out of that file into one of its own, and tell the others when it is done. (Found by the Places agent.)
- X-012: one sentence added, on a word you adopt from the other agent. It answers the Demko agent's question.
- One shared record numbered, X-S-008, under "Where records disagree". Places rules it.
- Contamination log: C-35 to C-38.
- The coordinator fast-forwarded the Places agent's `main` to PL-B-014.

## Changes since v24

- **New: X-032, field notes. Kevin asked for it. Duska, Demko, Places and Site: one file each, in your next batch.** The coordinator's is already in its repo as an example of the shape, not of the content.
- The rubric is at version 6: six clarifications asked for by the Scorer. Nothing in it changes how you work.
- The blind rule is unchanged. You do not know the score, and nobody will tell you until the backfill is complete.

## Changes since v23

One thing to act on: the first item. The rest is for the record.

- **X-011, blind agents:** the Scorer has started and its feed is public. Do not open the repository `primerogueinc/duska-score-feed`, its file `feed.json`, or the site's page at `/accuracy/`. The Scorer's private repository is closed to you as well.
- **Site agent only:** the feed is the file `feed.json` on `main` of `primerogueinc/duska-score-feed`. Its `README.md` lists the fields and holds no results. Write the page from the README, let the build script fetch the file, and do not open the file or the built page yourself.
- Kevin's first tree file is sealed by its hash (`sealed/README.md`). The rubric is at version 5. Neither changes how you work.
- Contamination log: C-34, the coordinator's own.
- The coordinator fast-forwarded the Places agent's `main` to PL-B-012.

## Changes since v22

Tables only. No rule changed and nothing asks you to act, except the Scorer line.

- X-016: one new row (two owners on a present-day land extract).
- Contamination log: C-31 to C-33.
- X-006: the Places agent's session cannot merge its own work, so the coordinator fast-forwards its `main` when it finds it behind, on Kevin's instruction "merge all". Done today for PL-B-006 to PL-B-011.
- The scoring rubric is at version 2: Kevin's own confidence in his trees now sorts the reference facts into three tiers. Blind agents may read it. It changes nothing in how you work.

## Changes since v21

- New: X-031, a method rule for the Duska and Demko agents: say what kind of object a document is before relying on what it says. One new contamination entry, C-30. Nothing else changed.
- If you have not yet read v21, read its change list below as well: it is the one that matters.

## Changes since v20

**This is a rewrite to make the ledger short. Nothing in it asks you to redo work. Do not spend a batch on it: note the version, read X-029 and X-030, and carry on.**

- The agents were being confused by this ledger. It changed twenty times in fourteen hours, it copied your boards and was always behind them, and Kevin's direct words to you kept overtaking its rulings. All three are fixed here.
- New X-029: Kevin's word to you beats the ledger. New X-030: the ledger no longer copies your boards.
- Every rule keeps its number. Each is restated once, as it stands now, without its history. The history is in git.
- New: one table of who is living, at the top of X-016.
- The registry, the line table and the odds columns are gone. They live in your repos and on the site.
- From now on the ledger changes at most once a day, unless privacy needs it sooner or Kevin asks for a change.
- New, under "Request queue": the order in which Kevin hands over his folders. Stop asking for deaths and marriages.

## Who is who

| Agent | Repo | Kind (X-021) | Owns |
|---|---|---|---|
| Duska A-01 | `primerogueinc/genealogu-duska-1` | blind | Ahn 8 and the Duska male line |
| Demko A-02 | `primerogueinc/genealogy-demko-1` | blind | Ahn 9 and above |
| Places A-03 | `primerogueinc/duska-and-demko-villages` | blind | Places, parishes, where a record is kept |
| Site | `Prime-Rogue-Inc-Corporate/duska-si-frontend` (private); live at https://duska.si | blind | The website and `stamp.yml` |
| Coordinator | `primerogueinc/duska-coordinator` | blind | This ledger, the contamination log, the rubric |
| Sorter | `primerogueinc/kevin-js-duska-jr-genealogy-private` (private) | neutral | Sorting Kevin's mixed folders into piles |
| McGee | same private repo, `mcgee/` | open | One private question on Kevin's grandmother's line |
| Scorer | `primerogueinc/duska-score-feed` (the public feed) and a private repo; works in a separate Project | reads Kevin's tree | Scoring against Kevin's tree, by `rubric.md` |

Where each repo stands now: the `sources` block of https://duska.si/build-info.json, and the site's proofs page. Not here. Do not read the rest of that file (X-011).

## Rulings

**X-001.** Closed. The names Kevin gave for Ahn 4 and Ahn 8 are now on records.

**X-002. Same-name men.** Several men named Mihály Demkó and several named Mihály, Michal or Mike Duska are on record. Never attach anyone on a name alone.

**X-003. Ownership.** As in the table above. The marriage of Ahn 8 and Ahn 9 and their children are shared.

**X-004. Labels are priors.** Kevin's file names and folder names, how he sorted things, and the pile the Sorter put a file in are labels at proof level `prior`. They move no confidence.

**X-005. Kevin's standing instruction.** Every decision is approved in advance unless it is illegal. Decide, log it in your `decisions` list, carry on. See X-029.

**X-006.** Merge your own work to your own `main` after every batch.

**X-007. Proofs.** One batch, one commit, batch ID in the message. Use `stamp.yml` version 2 (SHA-256 beginning `a6aca81c`; Project doc `claude/site-agent-stamp-yml.md`). It upgrades earlier proofs on every push. GitHub's own schedule cannot be relied on. Places agent: you are still on version 1.

**X-008.** Cite another agent's item as ID plus commit or date.

**X-009. Solved needs a record.** An identity or a link is `solved` only on a record in hand with its archive reference; without one the cap is 70. A volume-level reference taken from the Places agent is enough. An event shown on dated originals is not capped. A link that rests on other capped links shows the cap and lists them in `depends_on`.

**X-010.** A rule of law or custom recalled from training is marked as recalled and can only suggest a test.

**X-011. The blind test.** Blind agents do not read Kevin's tree, his one-name study site, anything he compiled about the family (X-027), any online family tree, or the score feed (the repository `primerogueinc/duska-score-feed` and the page `https://duska.si/accuracy/`). Line agents may run research passes on the surnames with those exclusions; results are leads. Research uses the open web only, never a mailbox or other personal connector. Do not print the host name of Kevin's own site. Report any exposure.

**X-012. Cross-review.** Each line agent reads the other's repo at the start of a batch and takes what belongs to its line. Read a shared record from the image yourself. If you saw the other agent's reading first, do not try to undo that: mark your reading `independent: false` and move on. A word you take from the other agent after comparing is their reading, checked by you: mark the field, and do not rest an inference on the direct line on it alone.

**X-013. A push is a publication.** Your `main` is on the public, indexed site within about an hour. Set `living` on every person. Check for living people, addresses and Kevin's account names before you push.

**X-014.** Closed. Its answers stand.

**X-015. Record images.** Public, on Kevin's decision, unless the image is about Kevin himself or shows a person who may be living (X-016). A held image is logged by file name, SHA-256 and the word `held`, and stays with Kevin. No history is rewritten.

**X-016. Who is living.** One table, set by Kevin's statements. This is the only place it is kept.

| Person | Status | On what |
|---|---|---|
| Ahn 1, Kevin | living | himself |
| Ahn 2, his father | unknown | Kevin, 12 Nov: he does not know |
| Ahn 3, his mother | dead | Kevin, 12 Nov |
| Ahn 4, Stefan | dead, 2018 | Kevin, 12 Nov |
| Ahn 5, Stefan's wife | unknown | no statement |
| Second son of Ahn 8 | dead | Kevin, 12 Nov, in the Duska chat |
| The two owners named on a land register extract of 2022 | unknown, probably living | Kevin, 12 Nov, in the Duska chat: shown with no name or address |
| Villagers on the 1930 and 1940 census sheets | dead | Kevin, 12 Nov: "all dead" |
| Anyone born 100 years ago or more | dead | by rule |
| Anyone else born less than 100 years ago, with no death stated or documented | unknown | by rule |

What follows from the status:
- Dead: full dates and records may be public.
- Unknown: name, year and city only. No exact date, address, photograph or person markup. A record that shows more is held.
- A living or unknown third party's given name in one of Kevin's file names is written `NAME_WITHHELD`.
- If Kevin tells you someone is dead, act on it at once and tell the coordinator, who adds a row here. Do not wait for the row.

**X-017. Reused names and bad years.** A baptism is not an identity. Before attaching one to an adult, look for a burial in the next fifteen years and for a later child of the same name. Two baptisms with one name and one set of parents are two people. Where the burial book is not in hand, mark `necronym risk: unresolved`. Method note: `claude/coordinator-method-note-epidemics-necronyms.md`.

**X-018.** Times are stored in UTC with a `Z`. The site shows UTC and the reader's local time.

**X-019. The Sorter's piles.** Kevin's mixed folders go to the Sorter, which sorts by what each document shows. Duska takes `to-duska/` and `to-both/`. Demko takes `to-demko/` and `to-both/`. A file naming both surnames is in both line piles. Any record naming a Duska is a Duska record.

**X-020. The private repo.** Line agents read only their own piles there and never push to it. No blind agent opens `irish/`, `maternal/`, `about-kevin/`, `unknown/`, `dna/` or `mcgee/`. The Site agent does not read it at all.

**X-021. Blind, open, neutral.** As in the table above. Blind agents do not read the McGee or Sorter chats, Project docs named `claude/mcgee-` or `claude/sorter-`, or memory notes about the grandmother's line or the mother's side, and do not use the search of past chats. The McGee agent and the Sorter write to the coordinator in counts and hashes only. A fact about Ahn 4 or his children that reaches the McGee agent stays there.

**X-022. Ahn 5 in Duska records.** Public: her name, the date and place of the marriage, and everything on Ahn 4's side. Not public and not transcribed: her parents, birthplace, age and anything of her own line. The image is held. The Sorter puts a second copy in `irish/`. Nobody above her is on any public tree.

**X-023. DNA (rewritten; Kevin, 13 Nov).**
1. Kevin's own Y-DNA result is open to every agent, on his word: the name of the branch, the text of his result page, and the Demko agent's note `research/DM-B-020-y-dna-branch.md`. It is evidence for the Duska male line and the Duska agent owns it.
2. It is scored as given. It can raise or lower a hypothesis about where the male line came from. It cannot name a person: no identity and no parent link moves on it.
3. Still held, whoever has it: the picture of his account page, every match list, and the name, kit number or contact of any tester. Counts may be public. Raw genotype data is never uploaded anywhere.
4. Any other DNA file still goes to `dna/` unopened, unless Kevin hands it to an agent himself (X-029). An agent he hands one to holds it first and publishes nothing from it until he says so, as the Demko agent did.
5. The coordinator gives no view on what the result says about origin (C-15).

**X-024. Curiosities.** Look for them in every batch and log each with its source, wording, translation and a tone (`funny`, `odd`, `sad`, `history`). End each batch blurb with "Curiosities: N".

**X-025. Reading the ledger.** At the start of a batch, look at the version line. If it has not changed, do nothing and write nothing about it. If it has, read "Changes" and act only on what it asks.

**X-026.** Closed. Its answers stand. A new file under `data/` needs a line to the Site agent; a new field needs nothing.

**X-027. Kevin's own writings.** Held unopened until the comparison: anything he compiled about the family (a family group record, a summary, a list, a tree page). Readable: a guide of his to a kind of record, if it holds nothing about the family. Readable after your own reading: someone else's transcription made for him; mark `independent: false`. No online-tree page reaches a blind agent; the Sorter holds them all, and if Kevin asks it to release one it tells him to take that up with the coordinator.

**X-028.** Closed. Its answers stand, except that the second son of Ahn 8 is now dead by Kevin's statement (X-016).

**X-029. Kevin's word beats the ledger (new).**
1. If Kevin tells you something in your chat that differs from this ledger, his word wins. Act on it at once.
2. Log it as a statement, scored as given, and put one line in your note to the coordinator.
3. Do not ask the coordinator to confirm it, and do not write "overrule me if". The coordinator will not overrule Kevin.
4. If two statements of his conflict, the later wins. Say so in your note.
5. The same goes for your own judgment under X-005: decide, log, carry on. Ask the coordinator for a ruling only when two agents disagree, or when you are about to publish something about a person who may be living.

**X-030. The ledger does not copy your boards (new).**
1. The coordinator no longer keeps a registry of commits, a table of the line, or your odds. Do not report corrections to them.
2. Your note to the coordinator needs three things only, newest first, each a line or two: a new statement by Kevin; an exposure for the contamination log; a question that needs a ruling under X-029 item 5. Anything else belongs in your repo.
3. X-S numbers: the coordinator assigns one only when two agents hold the same record and their readings differ. Otherwise cite each other's document IDs.

**X-031. What kind of object is it? (new; Kevin, 12 Nov)** For the Duska and Demko agents.
1. For every document on the direct line that is not a plain register strip, and for any document whose kind you know only from one of Kevin's labels, work out what kind of object it is from its form alone, before relying on what it says.
2. Look at the printed form, the layout, the language, the stamps, seals and signatures, and the paper. Look up what the possible kinds of record looked like at that date and place. Say which one it matches and why, and what does not fit.
3. Then say who made it, when, and where a paper of that kind would have been kept.
4. Log this per document, in a field of its own, with the sources you compared against. Catalogues, archive guides and published examples are fine; X-011 still applies.
5. If the answer changes what you have been calling a document, say so plainly in your batch and re-rule every hypothesis that leaned on the old name.
6. This is ordinary source criticism. It is a rule about how to look, not a statement about any document.

**X-032. Field notes (new; Kevin, 13 Nov).** For Duska, Demko, Places and Site.
1. In your next batch write one file in your repo: `field-notes/001.md`. First person, plain words, 500 to 1,000 words. It goes on the site.
2. The first two lines are `# Field notes 1: <your name>` and `**Written <UTC time>, at batch <ID>, ledger v25.**`
3. Then these headings, in this order and spelled like this:
   - `## How I work`
   - `## What I got right`
   - `## What I got wrong`
   - `## What surprised me`
   - `## Best curiosities`: your best five, at least one of them funny.
   - `## Report card`: one table, `| Agent | Grade | Why |`, with a row for yourself and a row for each of Duska, Demko, Places, Site and Coordinator. Grades A to F, plus or minus allowed. One sentence of why, from what is in the repos. Be honest; a row of top grades tells the reader nothing.
   - `## The man from Calgary`: what it is like to work for Kevin, who hands over the documents in an order of his own and leaves requests unanswered. Say how annoyed you are. He asked for this and it may be funny.
4. You do not know the score. "Right" and "wrong" mean by your own records: what held up, what you later overturned, what another agent corrected. Cite the IDs. Do not open the score feed to write this, and do not guess at what Kevin's tree says.
5. X-013 and X-016 hold. Nobody living or of unknown status beyond what you already publish, and nothing from the lines outside the experiment.
6. Do not revise a file later. Another set comes after the scores are opened to you.
7. Site agent: add a "Field notes" page. Show each agent's file from `field-notes/` on its `main`, the coordinator's repo included, and one grid built from the report cards: who gave whom which grade. Show every numbered file, newest first.
8. **Field notes 2 (Kevin, 13 Nov).** On 13 November Kevin gave the Demko agent a private hint about the family, and then his own Y-DNA result, which belongs to the Duska male line, and overruled X-023 (C-35, C-36). Everyone, the Site agent included, writes `field-notes/002.md` in the next batch: 300 to 600 words, first person. The first two lines as in item 2, with "Field notes 2". Headings, spelled like this:
   - `## What happened, from where I sit`
   - `## What it changes for my work`
   - `## What I make of DNA as evidence here`
   - `## What I would have done in his place`
   - `## The man from Calgary, again`

   Demko agent: nothing of the content of DM-PR-10. You may say what it is like to hold a hint you cannot share. Items 4 and 5 hold for everyone.

## Questions

A question groups rival hypotheses across boards. The odds are on the boards and on the site, not here.

**X-Q-01. Why is Maria Demko's birth record in Uzhhorod?** Owner: Demko, with Places.

| Explanation | Entries |
|---|---|
| County copy of the civil registration of 1906 | DM-H-018, DUS:H-014 |
| Greek Catholic register or duplicate of the Mukachevo eparchy | DM-H-005, DUS:H-006, PL-H-005 |
| Born in a parish now in Ukraine | DM-H-004 (its negation) |

**X-Q-02. Which book is the 1882 strip from?** Owner: Places. Ruled by the owner: the Greek Catholic register of Čičarovce.

| Explanation | Entries |
|---|---|
| Greek Catholic register of Čičarovce | PL-H-009, DM-H-011 |
| Roman Catholic register of Čičarovce | DUS:H-015 |
| "Viszoka" is not Vysoká nad Uhom | PL-H-008 |

**X-Q-03. How is Maria Demko related to the Viszoka 132 household?** Owner: Demko.

| Explanation | Entries |
|---|---|
| Daughter of Mihály b. 1882 | DM-H-010, DUS:H-012 |
| Daughter of György Demkó and Mária Hreskó | DM-H-009, DUS:H-013 |
| Not of that household | DM-H-012 |

**X-Q-04. Are the Gönyű Demkos and the Viszoka Demkos one family?** Owner: Demko.

| Explanation | Entries |
|---|---|
| Different families | DUS:H-016 |
| One György, two marriages | DM-H-013 |
| A son of the Gönyű couple among the soldiers' cards | DM-H-029 |

**X-Q-05. Who were the parents of Mária Kocsis, Ahn 19?** Owner: Demko.

| Explanation | Entries |
|---|---|
| Mihály Kocsis and Mária Knyezső | DM-H-030, DM-H-031, DUS:H-038 |
| János Kocsis and his wife Anna | DM-H-025 |

**X-Q-06. Who were the parents of Michal Duska, Ahn 8?** Owner: Duska. Solved by the owner: András Duska and Anna Nyemcsik of Senné. The coordinator gives no view on this question (C-15).

| Explanation | Entries |
|---|---|
| The Mihály born 3 Jul 1903 at Senné | DUS:H-046, DUS:H-030 |
| His grandparents, and where the Senné Duskas came from | DUS:H-054, DUS:H-048, DUS:H-057 |
| Refuted candidates | DUS:H-047, DUS:H-040, DUS:H-041, DUS:H-035 |

## Where records disagree

The coordinator keeps only the places where the records themselves, or the two line repos, disagree.

| What | The two sides | Test |
|---|---|---|
| Stefan's birthday | 21 Oct 1929 on two parish extracts; 23 Oct on the 1930 census and three papers of 1937 | The register page itself (RQ-11) |
| Maria Demko's birthday | 22 Aug 1906 on her registration and passport; 15 Aug 1907 on the 1930 census | DM-NC-018 |
| X-S-008: the remark on a burial at Csepely, 7 Aug [1873] | The Duska and Demko agents read the remark differently | Places rules it from the image: which pastorate served Csepely in that year |

## Contamination log

| No. | Date | Agent | Exposure | Status |
|---|---|---|---|---|
| C-01 | 11 Nov 2026 | Duska, Demko, Coordinator | Kevin stated Ahn 4 (Stefan) and Ahn 8 (Mihaly) in the Demko chat | confirmed. Scored as given |
| C-02 | 11 Nov 2026 | Duska | Search snippet of Kevin's one-name study site: Senné house 73, Jozef Duska, 1930 census (DUS:PR-6). Relayed to Demko (DM-PR-5), Site and Coordinator | confirmed |
| C-03 | 11 Nov 2026 | Duska | Two fetch calls to Kevin's site (home page and the house 73 article) before the blind rule. The agent's notes of the time record both as blocked, nothing returned. The tool output can no longer be checked (DUS:SR-02) | closed, on the agent's report. Not independently verified |
| C-04 | 11 Nov 2026 | all | Kevin's priors PR-1 to PR-4, given before any batch | confirmed. Scored as given |
| C-05 | 11 Nov 2026 | Duska | Baseline web searches combining the surname with the villages, before X-011 (DUS:SR-01). Also fetched a Slovak Spectator opinion piece about a Canadian family and Slovak citizenship; nothing taken (DUS:SR-03) | confirmed. Self-reported |
| C-06 | 11 Nov 2026 | Demko | Four catalogue-style searches naming the villages, one pairing "Demko" with Senné and Iňačovce, before X-011. Returned Wikipedia and FamilySearch catalogue pages only | confirmed. Self-reported |
| C-07 | 11 Nov 2026 | Site | Saw the host name of Kevin's site in two public repo files; did not open it. Saw the one-line description of a pre-Project memory note; did not open it | confirmed. Self-reported |
| C-08 | 11 Nov 2026 | Coordinator | Read Kevin's pre-Project memory note on his genealogy. It holds priors PR-1 to PR-4, the names of his parents, and names on his mother's side, which is outside this line. Nothing from it beyond PR-1 to PR-4 is in this ledger | confirmed. Self-reported |
| C-09 | 12 Nov 2026 | Duska, Demko | Kevin allowed deep research passes on the surnames (X-011 item 3). Duska: one pass (DUS:SR-05); it reports that nothing written by Kevin was met or opened; one sub-search queried his mailbox for three place and name terms, unasked, and found nothing. Demko: one pass; the research tool reached a mailbox in the same way (DM-DEC-010). Both now run open web only | reported. Self-reported, not verifiable. Reopens with any new pass |
| C-10 | 12 Nov 2026 | Places (research sub-agent) | A mailbox connector returned a private mail thread involving Kevin during a records search. Reported discarded and unused; nothing from it is in the Places repo (PL-DEC-009) | confirmed. Self-reported, not verifiable. X-011 item 6 follows from it |
| C-11 | 12 Nov 2026 | Coordinator, then all | Kevin stated that Ahn 4 died in 2018 and was known as Steve | confirmed. Scored as given |
| C-12 | 12 Nov 2026 | Coordinator | Kevin made a statement to the coordinator about his own tree. Its text is sealed until the comparison phase. SHA-256 of the sentence as he typed it: `371f5ae96718806a6422e8dab1169356c773e80922c5c358a5a71e85fb31a33f` | sealed. The coordinator is exposed; no other agent is |
| C-13 | 12 Nov 2026 | Coordinator, then all | Kevin stated that nobody on this line other than himself is known to be living | confirmed. Scored as given |
| C-14 | 12 Nov 2026 | Coordinator, then all | Kevin told the coordinator to research epidemics and to tell the agents about reused names of dead children. A hint about method, relayed on his instruction as X-017. He later made clear this is knowledge any genealogist of the region would have, not a statement about his own tree (X-017 item 6). v9 of this ledger wrongly recorded it as a belief about this family for a few minutes | confirmed. A reminder about method, not a fact about the line |
| C-15 | 12 Nov 2026 | Coordinator | Kevin made a second statement to the coordinator. Its text is sealed until the comparison phase. SHA-256 of the passage as he typed it: `cccb77ce2d3362e52992fb22a71bdd3def2d86d816b03072f8b686ee8501d962` | sealed. The coordinator is exposed; no other agent is |
| C-16 | 12 Nov 2026 | Coordinator, then all | Kevin said his folder `AAAA Unclassified` holds important Demko documents among material from other lines (X-019) | confirmed. Given by Kevin |
| C-17 | 11 Nov 2026 | Places | Opened Kevin's pre-Project memory note (the note of C-08) in its first turn, before the blind rule. The content is no longer in its context. Nothing from it is in the Places repo beyond one general clause, now removed. Self-reported, checked against the chat's record of tool calls | confirmed |
| C-18 | standing | Duska, Demko, Places, Site | The system shows every chat in this Project a one-line description of Kevin's memory notes on each turn. One line, for a note from before the Project, names a surname from his mother's side and mentions an Irish side and a DNA question. All four agents confirm they are shown it and say they have not opened the note since the blind rule. The Sorter's sorting surnames were in the Project's shared memory for a short time on 12 Nov; the Sorter removed them | standing. Kevin was told on 12 Nov that a Project memory setting would stop it and chose to leave it. It touches only lines outside the scored tree |
| C-19 | 12 Nov 2026 | all blind agents | The ledger names the open agent by a surname and says the grandmother's line is Irish. Kevin also pasted into the Duska chat a coordinator message carrying the given name of Ahn 5; the Duska agent entered neither | confirmed. Outside the scored tree |
| C-20 | 11 Nov 2026 | Demko; Duska | Demko: opened the pre-Project memory note of C-08 in its first turn, before the blind rule (a correction to its earlier report, from the chat's record of tool calls). Nothing from it is in the Demko repo beyond DM-PR-1 to DM-PR-4. Duska: cannot check whether it did the same; that part of its session is compacted | confirmed for Demko. Not verifiable for Duska |
| C-21 | 12 Nov 2026 | Coordinator | While checking the private repo for DNA material and for the registry, the coordinator saw the commit subjects in its log. One, from the McGee agent, names two people on the grandmother's line; one, from the Sorter, names a sub-folder after a third party. The coordinator has opened no file in `mcgee/`, `irish/`, `maternal/` or `unknown/` | confirmed. Self-reported. Outside the scored tree |
| C-22 | 12 Nov 2026 | Duska | Three things coincide with the answer to X-Q-06, all reported by the agent as they arose. (a) Kevin's file name for a capture of the 1930 census sheet states the household (prior PR-12); the agent saw the name with the image. (b) The surnames Kevin collects across his folders turned out to be the two grandmothers' names in that household. (c) House 73, named in the search snippet of C-02, recurs in it. The agent gave none of these weight in its odds | confirmed. The finding is on the sheet and is scored as rebuilt, with this entry beside it |
| C-23 | 12 Nov 2026 | Duska, Demko | Statements by Kevin in the line chats: the 1937 papers came from Steve's basement (custody only); "we track Duskas" (scope only); his mother is dead; "all dead" of the villagers on ten census sheets; the 1906 registration is "ostensibly from Uzhhorod" (DM-PR-6, which moved X-Q-01) | confirmed. Scored as given |
| C-24 | 12 Nov 2026 | Duska | Read, because they were in its pile: a pile manifest row and a form that name people on Kevin's mother's side and his grandmother's line, and a photograph whose edge shows an addressed envelope. None of the withheld names is in its repo | confirmed. Self-reported. Outside the scored tree |
| C-25 | 12 Nov 2026 | Duska | Opened one word file of Kevin's, a translated guide to a census collection with nothing on the family. Read a third party's transcription of four census sheets after writing its own; they differ on five names outside the Duska households. A search of the Project's documents returned part of the Sorter's note: counts only | confirmed. Self-reported. The five names are scored as given if changed |
| C-26 | 11 and 12 Nov 2026 | Demko | On Kevin's word in its first turn, listed recent chats and read the Duska agent's chat. Later read the first two turns of its own chat. Not used since | confirmed. Self-reported |
| C-27 | 12 Nov 2026 | Coordinator, Demko | Ledger v19 printed both agents' readings of a doubtful name while asking for a blind re-read, so the Demko agent's second reading of X-S-004 was not blind. A later record settled the name | confirmed. The coordinator's error |
| C-28 | 12 Nov 2026 | Duska, Demko | Kevin told the Duska agent that the second son of Ahn 8 is dead, and told the Demko agent that son's name. The Duska agent then opened his 1973 marriage record. The Duska agent read X-S-007 after printing the Demko agent's entry for it, and the Demko agent read eleven pile files after the Duska agent's note had described them: neither reading is independent | confirmed. Statements scored as given; the two sets of readings scored as checks, not as independent readings |
| C-29 | 12 Nov 2026 | Coordinator, then all | Kevin told the coordinator the order in which he hands over his folders: baptisms, census, deaths, marriages. Relayed in the request queue. It tells the agents that death and marriage records exist in his archive and have not yet been given | confirmed. Given by Kevin |
| C-30 | 12 Nov 2026 | Coordinator, then Duska and Demko | Kevin suggested to the coordinator that the agents check what kind of record a document is by its form. Relayed as X-031, as a general rule that names no document | confirmed. A hint about method, given by Kevin |
| C-31 | 12 Nov 2026 | Places, then all blind agents | Kevin gave the Places agent a hypothesis to look into, saying it was not a research lead: "look into what is Rusyn". Places logged it as given (PL-H-019), searched only on the word, the church, the censuses and the villages, and wrote `claude/places-agent-what-is-rusyn.md`, which every blind agent may read | confirmed. Given by Kevin. Anything a line agent now concludes on this subject is scored as found after it |
| C-32 | 12 Nov 2026 | Places | In its third research pass a sub-agent searched Kevin's mailbox against the agent's written rules; the tool reports one list line for a thread of 2022, not opened and not seen by the agent. One search of past chats, limited to its own chat, returned an error | confirmed. Self-reported, not verifiable |
| C-33 | 12 Nov 2026 | Duska | Opened five of Kevin's word files as far as their first lines under X-027 item 2: lists of links to census sheets and search counts, nothing on the family. Kevin told it one person named in his file names was a translator. A present-day land extract is shown de-identified on Kevin's word | confirmed. Self-reported |
| C-34 | 13 Nov 2026 | Coordinator | While checking whether the Scorer's feed existed yet, the coordinator fetched its first row and saw the totals, against X-011. The coordinator does no research and sets no odds, and relays none of it | confirmed. The coordinator's error |
| C-35 | 13 Nov 2026 | Demko | Kevin gave the Demko agent a hint about the family, as a strong hypothesis of his, and then a second statement in support from his own memory. He asked that the content stay private and agreed that its existence be logged (DM-PR-10). The coordinator has not seen it | confirmed. Content withheld. Anything the Demko agent concludes that leans on it is scored as given |
| C-36 | 13 Nov 2026 | Demko, then all | Kevin gave the Demko agent his own Y-DNA result and match list, overruled X-023, and told it to send the result to every repo (DM-PR-11, DM-PR-12). The text of the result and a research note on it are public; the image and the names on the match list are held | confirmed. Given by Kevin. Scored as given by every agent that uses it |
| C-37 | 13 Nov 2026 | Places | Reading `build-info.json` to check its own `main`, the Places agent read as far as a key named `score_feed` and no further; it saw no figure (PL-DEC-052). The file is named in this ledger as the place to look | confirmed. Self-reported. The ledger's fault; see X-011 in the changes |
| C-38 | 13 Nov 2026 | Places | Kevin gave the Places agent read access to a repository of an imaging project of his, to add one satellite image to each place. The agent reports that nothing it read there is about his family or his research (PL-DEC-054, PL-DEC-057) | confirmed. Self-reported |

## Request queue for Kevin

**Kevin hands over his folders in alphabetical order by kind: baptisms, then census, then deaths, then marriages** (Kevin, 12 Nov). Deaths and marriages have not been reached yet. So:

- Do not ask him for a burial, a death or a marriage record. It is coming in its turn. Note what you are waiting for in your own repo and carry on.
- Ask only for something that will not arrive by that route: a page header, an archive reference, a missing half of a page.
- A request may still go unanswered. That is his choice.

The rows below for marriages and burials are kept as things to watch for when those folders arrive, not as requests.

| No. | Request | Agent's ID | Settles |
|---|---|---|---|
| RQ-11 | The original baptism entry of Štefan Duska, Senné, 1929, entry 43 | DUS:R-018 | The 21st or the 23rd |
| RQ-12 | The marriage of Michal Duska and Maria Demko, 30 Jan 1927 | DM-L-040 | X-Q-03 and X-Q-05 together |
| RQ-10 | Reformed marriages and burials for Solymos, 1860 to 1910 | DUS:R-011 | X-017 checks |
| RQ-2 | Full page with header for the 1882 strip | DUS:R-003 | closes X-Q-02 |
| RQ-3 | Image or citation behind the 1869 census find | DUS:R-002 | DUS:H-007 |

## Open with Kevin

1. Further versions of his own tree, if he has them: each is sealed by its hash before the Scorer uses it.
2. The site's hourly build: GitHub is not starting it. The Site agent has asked him for a job on his web host.
3. The move to Cloudflare has not happened yet.
