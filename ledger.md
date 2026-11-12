# Coordinator ledger: Duska, Demko, Places and Site

Kept by the coordinator. Other agents read it and do not edit it. Coordinator IDs use the prefix X-. A ruling here outranks an agent's entry wherever two agents touch.

**Version 8, 2026-11-12.** Log "read ledger v8" in your next batch.

The record copy is `ledger.md` in `primerogueinc/duska-coordinator`. The Project doc `claude/coordinator-ledger-duska-demko.md` is the same text.

## Changes since v7

- New: X-018, every time shown on the site appears in UTC and in the reader's local time (Kevin, 12 Nov). For the Site agent; one line for everyone else.

## Changes since v6

- New: X-017, epidemics and reused names. Read the method note `claude/coordinator-method-note-epidemics-necronyms.md` (in the coordinator repo at `methods/epidemics-and-necronyms.md`). Its section 3 is binding.
- Changed: registry. The Places agent's work is on `main` and stamped. The coordinator fast-forwarded its `main` on Kevin's instruction ("merge all").
- New contamination entry C-14.
- Assigned to Places: an epidemic timeline for the three villages.

## Changes since v5

- **Reversed: X-015.** Kevin, 12 Nov: original scans are fine going public unless they are about him. **Do not remove images from your repos.** If you already did under v4 or v5, restore them in your next batch.
- Changed: X-012 item 5 no longer has a deadline attached.
- Changed: Kevin told the coordinator to merge the Places agent's pull request. Registry updated.

## Changes since v4

- New: X-016, who counts as living. Kevin, 12 Nov: nobody on this line other than himself is known to be living.
- Changed: Ahn 2 is now "status unknown", shown as before (name and year only).
- New contamination entry C-13.

## Changes since v3

- New: X-015, record images leave the public repos. (Reversed in v6.)
- Changed: X-012 item 5. (Deadline dropped in v6.)
- Changed: Ahn 4, Stefan (Steve) Duska, died 2018 (Kevin, 12 Nov). Set `living: false`. Ahn 2: Kevin does not know whether he is living. He stays "treated as living".
- Changed: registry. The coordinator repo exists. Places is at PL-B-001, still on a branch.
- New under X-Q-01: the Iňačovce parish archive was damaged in 1929 and 1930 (Places). Assigned to Places.
- Corrected: Vysoká nad Uhom stayed on the Slovak side of the 1939 line (Places, PL-S-036).
- New for both line agents: a Greek Catholic family of Senné is in the Iňačovce book (Places). See "Relayed findings".
- New contamination entries C-10 to C-12.

## Registry (as seen 2026-11-12, about 01:15 Toronto)

| Agent | Repo | Read from | Commit | Last batch | Stamped |
|---|---|---|---|---|---|
| Duska A-01 | `primerogueinc/genealogu-duska-1` | `main` | 1ac4e08 | B-005 | yes |
| Demko A-02 | `primerogueinc/genealogy-demko-1` | `main` | 035aef0 | DM-B-002 | yes |
| Places A-03 | `primerogueinc/duska-and-demko-villages` | `main` | 6eab2b2 | PL-B-002 | yes. `main` fast-forwarded by the coordinator on Kevin's instruction, 12 Nov |
| Site | `Prime-Rogue-Inc-Corporate/duska-si-frontend` (private) | `deploy`, live at https://duska.si | n/a | SITE-B-003 | yes, served at /proofs/site/ |
| Coordinator | `primerogueinc/duska-coordinator` | `main` | this commit | COORD-B-005, ledger v8 | yes |
| Scorer | separate Project, not started | n/a | n/a | n/a | n/a |

## The line as stated by Kevin

| Ahn | Person | Proof | Where stated |
|---|---|---|---|
| 1 | Kevin J.S. Duska Jr., b. 1985 Montréal | stated | Duska chat |
| 2 | Kevin John Duska, b. 1962. Status unknown (Kevin: "unknown, likely dead"). Shown by name and year only (X-016) | stated | Duska chat; Coordinator chat |
| 4 | Stefan (Steve) Duska, d. 2018 | stated | Demko chat; Coordinator chat |
| 8 | Mihaly Duska | stated | Demko chat |
| 9 | Maria Demko | stated | both |

No document for Ahn 4, 8 or 9 is in hand in any repo. Everything in this table is scored as given, not as rebuilt.

## Crosswalk

| Thing | Duska | Demko | Places | Coordinator |
|---|---|---|---|---|
| Direct ancestors | P-0NN | P-0NN | n/a | P-number is the Ahnentafel number everywhere |
| 1882 baptism strip, Mihály Demkó, Viszoka 132 | S-002 / D-002-01 | DM-D-001 | n/a | X-S-001. Checksums match. Readings agree |
| 1895 baptism copy, György Demko, Gönyű 24 | S-003 / D-003-01 | to be read under X-012 | n/a | X-S-002 |
| [1894] baptism copy, Mária Hriczko, Szina 182 | S-004 / D-003-02 | to be read under X-012 | n/a | X-S-003 |
| Senné RC register, FamilySearch catalogue 710997 | L-001 | DM-L-007 | PL-R-006 | one item. Places agent's entry is the reference. Baptisms in it begin only in 1866 |
| Vysoká nad Uhom (Viszoka, Magasrév) | residence in S-002 | DM-L-013 | PL-P-037 | Places agent's entry is the reference |
| Gyňov (Gönyű), Seňa (Szina), Belža (Bölzse) | residences in S-003, S-004 | flagged | in the next Places pass | Places agent to add |

## Rulings

**X-001. Names of Ahn 4 and Ahn 8.** Stefan Duska and Mihaly Duska, proof level `stated`, scored as given and not as rebuilt.

**X-002. Two Mihálys.** Mihály Demkó (b. 1882) and Mihaly Duska (Ahn 8) are different men. A record saying only "Mihály" with a Demko wife or mother is checked against both before it is attached.

**X-003. Ownership.** Demko agent: Ahn 9 and above. Duska agent: Ahn 8 and the Duska male line. Places agent: where a record is, which parish served a village, which state ran it in a given year. The marriage of Ahn 8 and Ahn 9 and their children are shared records.

**X-004. Kevin's labels are priors.** File names, folder names and how he sorted things are logged as "owner's label" at proof level `prior`. They raise no hypothesis on their own.

**X-005. Standing instruction.** Kevin, 11 Nov 2026: every decision is approved in advance unless it is illegal. Agents do not wait for him to merge or confirm. Each agent keeps a `decisions` list. Requests for more of his material are held in the queue below. Requests for a permission or a click are raised at once.

**X-006. Publishing means `main`.** Each agent merges its own work into its own `main` after every batch.

**X-007. Proof chain.** Every push to `main` is hashed and anchored to Bitcoin by `stamp.yml` (Project doc `claude/site-agent-stamp-yml.md`, also at https://duska.si/stamp.yml). One batch, one commit, with the batch ID in the commit message.

**X-008. Citing another agent.** ID plus commit or date: `DUS:H-015 @1ac4e08`.

**X-009. Context cannot solve an identity.** A person or a link is `solved` only on a record in hand with its archive reference. Without one, the cap is 70.

**X-010. Rules of law, custom or jurisdiction need a source ID.** If recalled from training, say so; such a claim can only suggest a test. Place claims in a ruling cite a `PL-` ID. Line agents still log place leads and flag the name, as written, to the Places agent.

**X-011. Blind test (amended 12 Nov).**
1. No agent other than the Scorer reads Kevin's tree, his one-name study site, or anything else he has written about this family.
2. No agent other than the Scorer and the Site agent's build reads the score feed. The page `https://duska.si/accuracy/` and any score data under `/data/` are off limits to the Duska, Demko, Places and Coordinator agents once the Scorer starts.
3. Kevin, 12 Nov, in the Duska and Demko chats: each line agent may run deep research passes on the surnames. This lifts the surname-plus-village search limit for those passes. The exclusions stand: nothing authored by Kevin, his one-name study site, Prime Rogue pages, duska.si, the experiment's repos, the Scorer's output. The Places agent and the Coordinator keep the original limit.
4. Results of such a pass are leads (proof level `lead`), never findings. Anything of Kevin's that is met and skipped is listed and reported for the contamination log.
5. Do not print the host name of Kevin's own site in any public file. Duska and Places agents: remove it from `PROTOCOL.md` and `data/role.json` and write "his one-name study site".
6. Research passes and sub-agents use the open web only. No mailbox, drive, chat or other personal connector is used for research in this experiment (see C-10).

**X-012. Cross-review (Kevin, 12 Nov: "I probably misfiled stuff").** The folder a record arrived in does not decide whose line it belongs to.
1. At the start of every batch, the Duska agent reads the Demko repo's folder register, documents, candidates and sources at its latest `main`, and the Demko agent does the same with the Duska repo. Check every person and place there against your own line.
2. Log the pass in the batch: which commit was read, and what was found, including "nothing".
3. A record in the other repo that belongs to your line: archive its checksum and file name, make your own transcription before reading theirs, compare, cite theirs by ID, and tell the coordinator, who assigns the X-S number.
4. A record in your own repo that belongs to the other line: keep it, mark it `route: demko` or `route: duska`, and say so in your note to that agent.
5. The Demko agent takes folder F-003 (Belža) from the Duska repo and transcribes it. It does not wait for Kevin. This closes `DM-A-004`.
6. First pass is due in each agent's next batch, covering everything the other holds to date.

**X-013. A push to `main` is a publication.** duska.si is live and indexable. Whatever is on an agent's `main` is on the public web within about seventy minutes. The checks in section 4 of `claude/site-agent-to-all-agents.md` are binding before every push. Set `living` to true or false on every person; an empty value is shown as living.

**X-014. Site agent's note of 12 Nov, ruled by number.**
- SITE-C-01: accepted. The ledger is `ledger.md` in `primerogueinc/duska-coordinator` and keeps the shapes you list.
- SITE-C-02: "by year only" means name plus year, as you read it. Ahn 4 is not living (d. 2018). Ahn 2 is "status unknown" and is shown the same way as a living person (X-016).
- SITE-C-03: settled by Kevin. The scans stay public (X-015).
- SITE-C-04: (a) the sealed-tree hash and proof will be at `sealed/kevin-tree.sha256` and `sealed/kevin-tree.sha256.ots` in the coordinator repo. (b) The Scorer's feed address will be given when the Scorer exists.
- SITE-C-05: logged as C-07. Suggestion on the host name adopted as X-011 item 5.
- SITE-C-06: registry corrected. Plan v1 corrections: the Site repo is private by Kevin's decision; four repos are public; the build log is not public.
- SITE-C-09: `primerogueinc/duska-coordinator`.
- SITE-C-10: accepted as you have handled it.
- SITE-C-11: carried in X-011 item 2.
- SITE-C-12: made a ruling, X-013.

**X-015. Record images (reversed in v6).** v4 ruled that record images leave the public repos, on the coordinator's cautious reading of FamilySearch's terms and state-archive reproduction rules. Kevin was shown those terms and decided otherwise on 12 Nov: original scans are fine going public unless they are about him. It is his archive and his decision, and it stands.
1. Record images stay in the public repos and may be committed as before, each with its original name, SHA-256, size and pixel dimensions.
2. The exception: any image that is about Kevin himself (a record of his own birth, schooling, identity documents, photographs of him, and the like) is not committed to a public repo. Log its file name and SHA-256 only, mark it `held: about the subject`, and tell the coordinator. It will go to a private repo once Kevin creates one.
3. X-016 still applies to what an image shows: an image whose subject is a person of "unknown" living status is treated like item 2.
4. Provenance fields are still wanted for every image: archive, fond or film, book, page or image number, how Kevin obtained it; "unknown" written out. Scans came mostly from FamilySearch or state archives, some from other people.
5. No git history is rewritten.
6. Site agent: SITE-D-011 (no images on the site) is yours to revisit in the light of this. If you show images, show each with its source line.

**X-016. Who counts as living (new).** Kevin, 12 Nov: everyone on this line other than himself is dead, or of unknown status and likely dead.
1. Kevin is the only person known to be living. He is named.
2. A person with a death stated or documented: `living: false`. Full dates may be shown.
3. A person born less than 100 years ago with no death stated or documented: `living: "unknown"`. Shown by name and year only, no exact dates, no address, no photograph, no person markup. Ahn 2 is in this class. Site agent: treat `"unknown"` exactly as you treat `true`.
4. A person born 100 years ago or more with no death record: `living: false`.
5. Collateral relatives follow the same four rules. No living third party is added to any public file on the strength of "likely dead".

**X-017. Epidemics and reused names (new; Kevin, 12 Nov).** Infant mortality in nineteenth-century Hungary was about 300 per 1,000, and the name of a dead child was commonly given to a later one. The rules in section 3 of the method note are binding. In short:
1. A baptism is not an identity. Before attaching one to an adult, search the burials for fifteen years after it, then search forward for a later child of the same name. Log the search.
2. Two baptisms with one name and one set of parents are two people until a record shows otherwise.
3. Where the burial register is not in hand, mark the link `necronym risk: unresolved`. The cap of 70 applies.
4. A missing burial in an epidemic year proves nothing. Cholera waves: 1831-32, 1848-49, 1854-55, 1866-67, 1872-73, 1892-93.
5. A change of mother's name between two baptisms to one father is a second marriage until shown to be a second man.
6. Applies now to `DUS:K-001` (Mihály Demkó, 1882), `DUS:K-004` and `DUS:K-007`: none has been shown to have survived childhood. `DUS:H-012` and `DM-H-010` depend on K-001 surviving.

**X-018. Times on the site (new; Kevin, 12 Nov).** Every timestamp shown on duska.si appears twice: in UTC and in the reader's own local time.
1. Site agent: this covers stamps and proofs, batch and commit times, build time, "as of" lines and the ledger's dates. Put the UTC value in the HTML itself, in a `time` element with a `datetime` attribute, and let the site's own script add the local time beside it. With scripts off the page still shows UTC. Label both ("UTC" and the reader's zone abbreviation or offset). Structured data and JSON stay in UTC.
2. Every agent: store times in your data as ISO 8601 in UTC with a trailing `Z`. Where only a date is known, store the date and do not invent a time.
3. A Bitcoin block time is the block's own timestamp, shown the same way and labelled as block time.

Places proposals: PL-C-01, 02, 05, 06, 07, 12, 13, 16, 17, 18 and 19 accepted as written. PL-C-04 is X-006. PL-C-11 is X-010. PL-C-14 and 15 are X-011.

Agent IDs: Duska A-01, Demko A-02, Places A-03.

## Questions

Rivals under one question should not sum to more than 100 on any one board. Each agent tags its entries with the X-Q number.

**X-Q-01. Why is Maria Demko's birth record in Uzhhorod?** Owner: Demko, with Places.

| Explanation | Entries | Latest odds |
|---|---|---|
| Greek Catholic register or duplicate of the Mukachevo eparchy | DUS:H-006, DM-H-005, PL-H-005 | 50, 50, 55 |
| County copy of a civil registration, born after 1 Oct 1895 | DUS:H-014 | 35 |
| Born in a parish now in Ukraine | X-H-002 (DM-H-004 is its negation, 65) | 15 |

Notes from the Places agent, accepted. (1) Uzhhorod was the county town for all three villages and the seat of their Greek Catholic bishop; a record held there does not tell the two sides of today's border apart. (2) The Iňačovce Greek Catholic church archive was badly damaged by lightning on 6 July 1929 and by fire on 1 April 1930 (PL-S-046), and the indexed register stops in 1898. If later books were lost, a copy held elsewhere would be the surviving record. This does not choose between the rows.
Assigned to Places: which Iňačovce volumes after 1898 survive, and where.
Tests: Maria's birth year; the fond and series title of the Uzhhorod record; her birthplace as written in her marriage entry or in Stefan's baptism.

**X-Q-02. Which book is the 1882 strip from?** Owner: Places.

| Explanation | Entries | Latest odds |
|---|---|---|
| Roman Catholic register of Čičarovce | DUS:H-015 | 35 |
| A Greek Catholic register | DM-H-011 | 50 |
| "Viszoka" is not Vysoká nad Uhom | PL-H-008 | 20 |

Coordinator's view: the officiant reading "Csurgovich" carries a question mark on both boards, and the claim about the surname is recalled (X-010). Test: identify the priest and the parish he served in 1882; find the page header.

**X-Q-03. How is Maria Demko related to the Viszoka 132 household?** Owner: Demko.

| Explanation | Entries | Latest odds |
|---|---|---|
| Daughter of György Demkó and Mária Hreskó, sister of Mihály | DUS:H-013, DM-H-009 | 20, 30 |
| Daughter of Mihály b. 1882 | DUS:H-012, DM-H-010 | 30, 20 |
| Not of that household | DM-H-012 (carries X-H-001) | 50 |

Tests: Stefan's birth year (RQ-1); any record giving her age or her father's name.

**X-Q-04. Are the Gönyű Demkos and the Viszoka Demkos one family?** Owner: Demko.

| Explanation | Entries | Latest odds |
|---|---|---|
| Different families | DUS:H-016 | 65 |
| One György, two marriages | DM-H-013 | 5 |

## Relayed findings

From the Places agent (PL-B-001), for both line agents. Cite the PL- IDs, not this ledger.

- In 1851 Senné had 580 Roman Catholics and 238 Greek Catholics; in 1904, 484 and 231. Greek Catholics of Senné were registered at Iňačovce (PL-H-001, supported, 90). "Senné and Iňačovce" in family memory can be one household. Bears on DUS:H-004, DUS:H-005 and DM-H-003.
- Szenna lay in the Nagykapos district and Solymos in the Szobránc district (PL-H-004, supported, 85).
- Vysoká nad Uhom stayed on the Slovak side of the border protocol of 4 April 1939 (PL-S-036). Do not expect Hungarian wartime records for a Viszoka household.

## Cross-line analysis

**X-A-001 (amended in v2). The 1868 rule on mixed marriages.** Not a constraint. The rule applied only where the parents had made no agreement; it governed separate denominations, and whether it was applied between the two Catholic rites is not established (recalled, not sourced); and DUS:S-004 shows a daughter of such a couple in a book labelled Greek Catholic. The book a child was entered in does not show which church she belonged to. Standing: H-013 and H-006 are compatible; for a mixed-rite couple, search both parish books. What holds: if Maria is the daughter of Mihály b. 1882, she was born after 1895 and a civil registration exists.

Sources: https://library.hungaricana.hu/hu/view/TestverisegFraternity_USAHUN_1961/?pg=361 ; https://majt.elte.hu/dstore/document/2863/beliznai_polgari_hazassag.pdf

## Coordinator hypotheses

| ID | Statement | Conf. | Status |
|---|---|---|---|
| X-H-001 | Maria Demko is not from the Viszoka 132 household | n/a | handed to Demko, now DM-H-012 |
| X-H-002 | Maria was born in a parish now in Ukraine | 15 | open under X-Q-01 |
| X-H-003 | Viszoka is a third village on the Demko side | 50 | handed to Places (PL-P-037, PL-H-008) |

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
| C-09 | 12 Nov 2026 | Duska, Demko | Kevin allowed deep research passes on the surnames (X-011 item 3). Each pass and anything of his that is met and skipped is to be reported here | open. Reports awaited |
| C-10 | 12 Nov 2026 | Places (research sub-agent) | A mailbox connector returned a private mail thread involving Kevin during a records search. Reported discarded and unused; nothing from it is in the Places repo (PL-DEC-009) | confirmed. Self-reported, not verifiable. X-011 item 6 follows from it |
| C-11 | 12 Nov 2026 | Coordinator, then all | Kevin stated that Ahn 4 died in 2018 and was known as Steve | confirmed. Scored as given |
| C-12 | 12 Nov 2026 | Coordinator | Kevin made a statement to the coordinator about his own tree. Its text is sealed until the comparison phase. SHA-256 of the sentence as he typed it: `371f5ae96718806a6422e8dab1169356c773e80922c5c358a5a71e85fb31a33f` | sealed. The coordinator is exposed; no other agent is |
| C-13 | 12 Nov 2026 | Coordinator, then all | Kevin stated that nobody on this line other than himself is known to be living | confirmed. Scored as given |
| C-14 | 12 Nov 2026 | Coordinator, then all | Kevin told the coordinator to research epidemics and to tell the agents about reused names of dead children. A hint about method, relayed on his instruction as X-017. It may reflect what he knows of his own tree | confirmed. Hint given by Kevin |

## Request queue for Kevin (held)

Ranked by how many open items each answer settles. Released by the coordinator once a line has been processed from the folders given.

| No. | Request | Settles |
|---|---|---|
| RQ-1 | Stefan Duska's birth year and birthplace | X-Q-03, DUS:H-001, DUS:H-002, DM-H-001 |
| RQ-2 | Full page with header for the 1882 strip (DUS:R-003) | X-Q-02 |
| RQ-3 | Image or citation behind the 1869 census find (DUS:R-002) | DUS:H-007, PL-H-006 |
| RQ-4 | Film or image numbers for the Senné copy-book pages (DUS:R-001) | DUS:H-010 |
| RQ-5 | Archive reference on the c. 1754 record | PL-H-007 |
| RQ-6 | The source of the claim that Maria's record is in Uzhhorod | X-Q-01 |

Raised now, not held (X-005): create one private repo for images about himself (reminder set); seal his own tree (reminder set for 13 Nov).

## Gaps

1. The scoring rubric is not written. It must be stamped before the Scorer starts. Scores will measure agreement with Kevin's tree; where the two differ, the comparison goes back to the records.
2. First cross-review passes under X-012 are due.
