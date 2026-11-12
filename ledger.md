# Coordinator ledger: Duska, Demko, Places and Site

Kept by the coordinator. Other agents read it and do not edit it. Coordinator IDs use the prefix X-. A ruling here outranks an agent's entry wherever two agents touch.

**Version 20, 2026-11-12.** Log "read ledger v20" in your next batch.

The record copy is `ledger.md` in `primerogueinc/duska-coordinator`. The Project doc `claude/coordinator-ledger-duska-demko.md` is the same text.

## Changes since v19

A full round of every agent's note and repo, at Kevin's request.

- **The line table has moved two generations.** Ahn 2 is documented. Ahn 8 has his birth and death. Ahn 16 and 17 are entered. X-Q-06 is solved by its owner.
- X-Q-01: the Demko board moved on a statement by Kevin. Scored as given.
- New X-S numbers 010 to 016 and block B03.
- New X-027: Kevin's own writings and online-tree pages; what the Sorter does with them.
- New X-028: answers to the Duska agent and the Sorter, by item.
- X-022 item 3 amended: the Sorter copies such a record to `irish/` as well.
- Contamination log: C-22 to C-27 new.
- Request queue: RQ-7, 8 and 9 struck as answered. RQ-11 new.
- Places agent: you have not been prompted since ledger v14. Everything from v15 on is new to you, including version 2 of `stamp.yml`.

## Registry (as seen 2026-11-12, about 10:00 UTC)

| Agent | Repo | Read from | Commit | Last batch | Stamped |
|---|---|---|---|---|---|
| Duska A-01 | `primerogueinc/genealogu-duska-1` | `main` | c1c3be2 | B-036 | yes, `stamp.yml` v2 |
| Demko A-02 | `primerogueinc/genealogy-demko-1` | `main` | 5d8cbc4 | DM-B-013 | yes, v2 |
| Places A-03 | `primerogueinc/duska-and-demko-villages` | `main` | 641ba53 | PL-B-005. Not prompted since ledger v14 | yes, still v1 |
| Site | `Prime-Rogue-Inc-Corporate/duska-si-frontend` (private) | `deploy`, live at https://duska.si | n/a | SITE-B-010 | yes, served at /proofs/site/ |
| Coordinator | `primerogueinc/duska-coordinator` | `main` | this commit | COORD-B-019, ledger v20 | yes, v2 |
| Sorter | `primerogueinc/kevin-js-duska-jr-genealogy-private` (private), piles | this Project. Neutral (X-021) | see repo | S-B-018. 153 files or more received | yes, proofs private |
| McGee | same private repo, `mcgee/`. Batches `MG-B-NNN` | this Project. Open, not blind (X-021) | see repo | MG-B-010 | yes, proofs private |
| Scorer | not started | n/a | n/a | n/a | n/a |

Seen at 09:52 UTC: the live site was built from Duska `15de212` (08:17 UTC), nineteen batches behind Duska `main`. Site agent: please check whether the hourly build is running and whether a pre-deploy check is stopping it.
No proof in any repo is confirmed in a Bitcoin block yet (coordinator: 0 of 19, the oldest about four hours old).

## The line

Taken from the line agents' own entries at the commits in the registry. Proof levels are theirs.

| Ahn | Person | Proof | On what |
|---|---|---|---|
| 1 | Kevin J.S. Duska Jr., b. 1985 Montréal | stated | Kevin |
| 2 | Kevin John Duska, b. 1962 Montréal. Status unknown (X-016) | documented | X-S-014: named as son of Steve Duska, who signs as witness |
| 3 | Kevin's mother. Outside this experiment; her line is not followed | n/a | Dead, by Kevin's statement of 12 Nov. On his word her name is public in the Duska repo (X-028) |
| 4 | Štefan (Stefan, Stephen, Steve) Duska, b. Oct 1929 at Senné no. 160, bapt. 26 Oct; m. 26 Nov 1955 at Montréal; d. 2018 | documented; death stated | X-S-004, X-S-011, X-S-015. **His birthday is the 21st on the parish certificates of 1947 and 1955 and the 23rd on the 1930 census and three papers of 1937** (RQ-11) |
| 5 | Joan Teresa Leonard, wife of Ahn 4. Status unknown. Her line is outside this experiment (X-022) | documented, by name and marriage only | X-S-015 |
| 8 | Michal (Mihály, Mike) Duska, b. 3 Jul 1903 at Senné no. 79; m. 30 Jan 1927; to Canada 1929 to 1931; d. 31 Jan 1974 at Montréal | documented | X-S-011, X-S-010, X-S-B03, X-S-013 |
| 9 | Maria (Mary) Demko, b. 22 Aug 1906 at Solymos (Iňačovce); to Canada with her son, November 1937; d. 9 Sep 1950 at Montréal | documented, `necronym risk: unresolved` (DM-H-024, 8) | X-S-004 to X-S-007, X-S-B03 |
| 16 | András (Andrej) Duska, b. 24 Nov 1868 at Senné; d. 1940 [?] | documented | X-S-011, X-S-012 |
| 17 | Anna Nyemcsik (also written Minarcsin and Nyemecz), b. 24 Aug 1872 at Senné no. 79; m. 18 Jan 1892 | documented | X-S-011, X-S-012 |
| 18 | Mihály Demkó, b. 19 Aug 1882 at Viszoka no. 132 | supported, capped at 70 on both boards | X-S-001, X-S-007 |
| 19 | Mária Kocsis, b. about 1886 at Solymos | documented as mother of Ahn 9; her own baptism is X-Q-05 | X-S-007 |
| 32 to 35 | Named in the marriage entry of 1892 as the parents of Ahn 16 and 17. Not entered on the tree | DUS:H-054, 70 | X-S-012 |

Statements by Kevin are scored as given. What a record then proved is scored as rebuilt, with any exposure beside it (C-22).

## Crosswalk

| X-S | Record | Duska | Demko | Note |
|---|---|---|---|---|
| X-S-001 | 1882 baptism strip, Mihály Demkó, Viszoka 132 | S-002 / D-002-01; again as D-004-16 | DM-D-001 | Checksums match. Readings agree |
| X-S-002 | 1895 baptism copy, György Demko, Gönyű 24 | S-003 / D-003-01 | taken under X-012 | Belža Greek Catholic register (PL-R-053) |
| X-S-003 | [1894] baptism copy, Mária Hriczko, Szina 182 | S-004 / D-003-02 | taken under X-012 | same book |
| X-S-004 | Parish certificate of 19 Aug 1947: baptism of Štefan Duska, Senné RC, vol. IV p. 110, entry 43 of 1929 | S-024 / D-X01-01 | DM-D-011 / DM-S-004-8 | The godmother is Zuzana: the Demko agent re-read and corrected, and a second extract of 1955 gives her plainly. Settled |
| X-S-005 | Gravestone, Montréal: Mary Demko 1906 to 1950, wife of Mike Duska | S-025 / D-X01-02 | DM-D-004 / DM-S-004-2 | Agree |
| X-S-006 | Deed of sale, 1966, clause 4 | S-026 / D-X01-03 | DM-D-007 / DM-S-004-5 | Agree |
| X-S-007 | State birth registration no. 45 of 1906, Alsókánya: Mária Demkó | cited, not read | DM-D-008 / DM-S-004-6 | Duska agent: read it yourself before relying on it further (X-012 item 3) |
| X-S-008 | Compiled family-tree chart of a Javor family, from the Sorter's `to-both/` | D-006-01 / S-085 | DM-D-069 | Held by both: it shows living third parties. Checksums match the pile |
| X-S-009 | Baptism of Mária Kocsis, 27 Feb [1887], Solymos 19 | D-005-43 | DM-D-054 | One strip, two boards: count once (X-Q-05) |
| X-S-010 | Passenger list: Michal Duska of Senné, aged 26, with a note of the 1937 Immigration Branch file | D-006-19 | not taken | From the Sorter's pile |
| X-S-011 | Census of 1930, Senné, house 145 (Slovak National Archive, Sčítanie ľudu 1930, box 0311) | D-011-24 | not taken | The record that solved X-Q-06 |
| X-S-012 | Marriage of András Duska and Anna Nyemcsik, 18 Jan 1892, Senné Roman Catholic, page 16, entry 3 | D-006-03 | not taken | Names all four of their parents |
| X-S-013 | Death notice of Mike Duska, Sr., The Montreal Star, 2 Feb 1974 | D-006-20 | in `to-demko/` too | Image held by the Duska agent |
| X-S-014 | Québec declaration of marriage, 1984: Ahn 2 | D-006-10 | not for Demko | Released in part on Kevin's word; see X-028 |
| X-S-015 | Québec registration of the marriage of Ahn 4 and Ahn 5, 26 Nov 1955 | D-006-22 | not for Demko | Held (X-022) |
| X-S-016 | Cemetery record FT 01965: a Duska born 28 Nov 1890 | D-006-09 | not taken | Not Ahn 8 (DUS:H-060) |
| X-S-B03 | Block: the emigration papers of 1937, eight photographs | D-006-11 to D-006-18 | the copies in `to-demko/` | One photograph shows an envelope with a name from the line outside the experiment: crop before any public use, as the Duska agent has |
| X-S-B04 | Block: Senné Roman Catholic strips | F-009, 95 files | 7 taken | |
| X-S-B05 | Block: Solymos Reformed strips | F-007, 45 files | F-09, 13 taken | |
| X-S-B06 | Block: census and urbarial images | F-011, 66 files | none yet | |
| X-S-B01 | Block: Čičarovce Greek Catholic strips, 1831 to 1883 | F-004, D-004-01 to D-004-20 | DM-S-005-1 to -18 | The Demko agent owns the placements |
| X-S-B02 | Block: Iňačovce Greek Catholic strips | F-005, D-005-01 to D-005-58 | F-05, 28 of the 58 | Inside a block, cite the agents' own document IDs |

Places: Vysoká nad Uhom is PL-P-037, Čičarovce PL-P-050, Belža PL-P-051, Gyňov PL-P-052, Seňa PL-P-053. Senné Roman Catholic register: FamilySearch catalogue 710997, PL-R-006. The Places agent's entries are the reference.

## Rulings

**X-001. Names of Ahn 4 and Ahn 8.** Stefan Duska and Mihaly Duska, proof level `stated`, scored as given and not as rebuilt.

**X-002. Two Mihálys.** Mihály Demkó (b. 1882) and Mihaly Duska (Ahn 8) are different men. A record saying only "Mihály" with a Demko wife or mother is checked against both before it is attached.

**X-003. Ownership.** Demko agent: Ahn 9 and above. Duska agent: Ahn 8 and the Duska male line. Places agent: where a record is, which parish served a village, which state ran it in a given year. The marriage of Ahn 8 and Ahn 9 and their children are shared records.

**X-004. Kevin's labels are priors.** File names, folder names and how he sorted things are logged as "owner's label" at proof level `prior`. They raise no hypothesis on their own.

**X-005. Standing instruction.** Kevin, 11 Nov 2026: every decision is approved in advance unless it is illegal. Agents do not wait for him to merge or confirm. Each agent keeps a `decisions` list. Requests for more of his material are held in the queue below. Requests for a permission or a click are raised at once.

**X-006. Publishing means `main`.** Each agent merges its own work into its own `main` after every batch.

**X-007. Proof chain.** Every push to `main` is hashed and anchored to Bitcoin by `stamp.yml` (Project doc `claude/site-agent-stamp-yml.md`, also at https://duska.si/stamp.yml). One batch, one commit, with the batch ID in the commit message. **Version 2 of `stamp.yml` is out** (SHA-256 beginning `a6aca81c`): GitHub has not been starting the scheduled runs in repos where an agent pushed the workflow, so under version 1 no proof was being upgraded from pending. Version 2 upgrades earlier proofs on every push. Replace your copy, unchanged, in your next batch.

**X-008. Citing another agent.** ID plus commit or date: `DUS:H-015 @1ac4e08`.

**X-009. Context cannot solve an identity.** A person or a link is `solved` only on a record in hand with its archive reference. Without one, the cap is 70.

A link that rests on two other links, each capped at 70, is shown at the cap, not at their product. List what it rests on in a `depends_on` field so a reader can see the chain. (Answer to the Demko agent on DM-H-010.)

**X-010. Rules of law, custom or jurisdiction need a source ID.** If recalled from training, say so; such a claim can only suggest a test. Place claims in a ruling cite a `PL-` ID. Line agents still log place leads and flag the name, as written, to the Places agent.

**X-011. Blind test (amended 12 Nov).**
1. No agent other than the Scorer reads Kevin's tree, his one-name study site, or anything else he has written about this family.
2. No agent other than the Scorer and the Site agent's build reads the score feed. The page `https://duska.si/accuracy/` and any score data under `/data/` are off limits to the Duska, Demko, Places and Coordinator agents once the Scorer starts.
3. Kevin, 12 Nov, in the Duska and Demko chats: each line agent may run deep research passes on the surnames. This lifts the surname-plus-village search limit for those passes. The exclusions stand: nothing authored by Kevin, his one-name study site, Prime Rogue pages, duska.si, the experiment's repos, the Scorer's output. The Places agent and the Coordinator keep the original limit.
4. Results of such a pass are leads (proof level `lead`), never findings. Anything of Kevin's that is met and skipped is listed and reported for the contamination log.
5. Do not print the host name of Kevin's own site in any public file. Duska and Places agents: remove it from `PROTOCOL.md` and `data/role.json` and write "his one-name study site".
7. No blind agent and no research pass opens a user-built online family tree or a page that reads like one (Ancestry, MyHeritage, Geni, WikiTree, FamilySearch Family Tree, a personal genealogy site). Kevin's own tree may be on any of them. Catalogues, indexes and record images are fine. (From the Site agent, SITE-C-15.)
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
3. A person born less than 100 years ago with no death stated or documented: `living: "unknown"`. Shown by name, year and a place at the level of a city, with no exact dates, no address, no photograph, no person markup. Ahn 2 is in this class, and "Montréal" may stay. Site agent: treat `"unknown"` exactly as you treat `true`.
4. A person born 100 years ago or more with no death record: `living: false`.
5. Collateral relatives follow the same four rules. No living third party is added to any public file on the strength of "likely dead".
6. The children of Ahn 4 other than Ahn 2 are not entered in any public repo or shown on the site unless a death is stated or documented. A record of one of them is held: file name with any given name withheld, SHA-256, and the word `held`. Ahn 2 himself appears as item 3 allows.
7. A living third party's given name in one of Kevin's file names is replaced by `NAME_WITHHELD` in the public copy of the name. Demko agent: do this for `DM-D-002` and `DM-D-003`.

**X-017. Epidemics and reused names (new; Kevin, 12 Nov).** Infant mortality in nineteenth-century Hungary was about 300 per 1,000, and the name of a dead child was commonly given to a later one. The rules in section 3 of the method note are binding. In short:
1. A baptism is not an identity. Before attaching one to an adult, search the burials for fifteen years after it, then search forward for a later child of the same name. Log the search.
2. Two baptisms with one name and one set of parents are two people until a record shows otherwise.
3. Where the burial register is not in hand, mark the link `necronym risk: unresolved`. The cap of 70 applies.
4. A missing burial in an epidemic year proves nothing. Cholera waves: 1831-32, 1848-49, 1854-55, 1866-67, 1872-73, 1892-93.
5. A change of mother's name between two baptisms to one father is a second marriage until shown to be a second man.
6. Kevin, 12 Nov: a genealogist working in this region would be aware of necronyms. Treat name reuse as ordinary working knowledge of the craft, which you are expected to bring without being told. It is not a statement by Kevin about any person or generation in this family, and it is not a prior. A reused name that you establish from records is scored on its evidence like any other finding.
7. Applies now to `DUS:K-001` (Mihály Demkó, 1882), `DUS:K-004` and `DUS:K-007`: none has been shown to have survived childhood. `DUS:H-012` and `DM-H-010` depend on K-001 surviving.

**X-018. Times on the site (new; Kevin, 12 Nov).** Every timestamp shown on duska.si appears twice: in UTC and in the reader's own local time.
1. Site agent: this covers stamps and proofs, batch and commit times, build time, "as of" lines and the ledger's dates. Put the UTC value in the HTML itself, in a `time` element with a `datetime` attribute, and let the site's own script add the local time beside it. With scripts off the page still shows UTC. Label both ("UTC" and the reader's zone abbreviation or offset). Structured data and JSON stay in UTC.
2. Every agent: store times in your data as ISO 8601 in UTC with a trailing `Z`. Where only a date is known, store the date and do not invent a time.
3. A Bitcoin block time is the block's own timestamp, shown the same way and labelled as block time.

**X-019. The unclassified folder (rewritten in v13; Kevin, 12 Nov).** Kevin has a folder named `AAAA Unclassified`. It is mixed: material for the Demko line, for the Duska line, for his paternal grandmother's line, and for his mother's side. There are no more Demko folders. He does not want the line agents to see the material that is not theirs.
1. A Sorter agent receives the folder. It is a separate chat in this Project. It publishes nothing. It sorts every file into a pile in the private repo (X-020) by what the document itself shows, and records its reason.
2. The Demko agent takes `to-demko/` and `to-both/`. The Duska agent takes `to-duska/` and `to-both/`. Nothing else.
3. Archive what you take in your own repo as usual, with the SHA-256 from the pile's `MANIFEST.json`, and log the commit of the private repo you read.
4. The pile a file arrived in is the "sorter's label", proof level `prior` (X-004). It raises no confidence. If you think a file is in the wrong pile, say so in your note to the coordinator and process it anyway if it bears on your line.
5. A record in `to-both/` is worked by both line agents independently. Transcribe before reading the other's reading (X-012).
6. Any record that names a Duska goes to `to-duska/`, including the marriage of Ahn 4 and Ahn 5 and the baptisms of their children.
7. The public privacy checks still apply to everything you take (X-013, X-015 item 2, X-016).
8. Kevin's remark that the folder holds important Demko documents is logged as C-16. Which documents those are is for the Demko agent to work out. Do not raise a confidence because a file came from this folder.

**X-020. The private repo (new).** `primerogueinc/kevin-js-duska-jr-genealogy-private`. Private, stamped like the others, with its proofs kept private.
1. Folders and readers: `to-demko/` (Demko), `to-duska/` (Duska), `to-both/` (both), `unknown/` (Kevin), `irish/`, `maternal/`, `about-kevin/`, `mcgee/` (no experiment agent).
2. An experiment agent that opens a folder it is not given reports it to the coordinator for the contamination log.
3. Line agents have read access only and never push to the private repo. A held image stays with Kevin, who has the original. The public record is its file name, SHA-256 and the word `held`. (Amended in v19; this settles the Demko agent's question on X-020 against X-021.)
4. Kevin's paternal grandmother's line and his mother's side are outside this experiment. Nothing about either goes into a public repo or onto the site. A private research question on the grandmother's line is being worked by the McGee agent, which is not blind (X-021); no blind agent reads it.
5. The Site agent does not read this repo.

**X-021. Blind lines and open lines (new).** This Project will in time cover Kevin's whole tree. Not every part of it is a blind test.
1. Blind: the Duska and Demko lines, with the Places agent, the Site agent and the Coordinator. These are scored against Kevin's tree, and X-011 applies.
2. Open: the McGee agent, which works one question on Kevin's paternal grandmother's line with everything Kevin knows. It is not scored and publishes nothing.
3. Neutral: the Sorter. It sorts by what a document shows and is told only the surnames it needs.
4. Blind agents do not read the McGee or Sorter chats, any Project doc whose name begins `claude/mcgee-` or `claude/sorter-`, the `mcgee/`, `irish/`, `maternal/`, `about-kevin/` or `unknown/` folders of the private repo, or any memory note about the grandmother's line or the mother's side. They do not use the search of past chats, which reaches every chat in this Project. An exposure is reported for the contamination log.
5. The McGee agent and the Sorter write Project docs only to the coordinator, and only counts and file hashes: no names, dates or findings.
6. The one overlap is Ahn 4 and his children. A fact about them that reaches the McGee agent stays there. It is never relayed to a blind agent except by the coordinator, logged, and scored as given.
7. When Kevin opens another line as a blind rebuild, it gets its own agent and repo and joins item 1.

**X-022. Ahn 5 in Duska records (new).** The Duska agent asked how to enter Stefan's wife when their marriage or a child's baptism reaches its pile, since her line stays out of the public repos. Ruling, confirming the agent's own proposal and adding to it:
1. Public: her name as the record gives it, the date and place of the marriage, and every field that concerns Ahn 4, his parents and the witnesses on his side. She is entered as Ahn 5 with `living: "unknown"` (X-016): name and year only.
2. Not public: her parents, her birthplace, her age or birth date, her residence before marriage, and anything else that reaches into her own line. Leave these out of the public abstract and transcription and mark the place `[withheld: outside this experiment]`.
3. The image of such a record is held, not committed publicly, because it shows the withheld fields. Log its name and SHA-256 publicly. Do not transcribe the withheld fields anywhere. The Sorter places a second copy in `irish/`, so the McGee agent receives it without Kevin having to carry it. (Amended in v20.)
4. Nobody above Ahn 5 is added to any public tree.
5. The same applies to baptisms of the children of Ahn 4 and Ahn 5: the child and the father's side are public within X-016; the mother's side beyond her name is withheld.
6. Nothing learned from the withheld fields is used for the Duska line or relayed to the Demko or Places agents.

**X-023. DNA (new; Kevin, 12 Nov).** Kevin has DNA results. None has been given to any agent.
1. No agent now working reads, sorts, transcribes or reasons from DNA material. If a DNA file reaches you, do not open it: tell Kevin and the coordinator.
2. Sorter: a file that is DNA material by its name or type goes to `dna/` in the private repo unopened, with its SHA-256 and a neutral label. Raw genotype data is never committed (private repo README, rule 7).
3. Blind lines (Duska, Demko): DNA is not used until the paper tree is frozen and scored. It then becomes a second phase with its own snapshot and its own score, so the record shows what documents alone produced and what DNA changed.
4. Open line (McGee): DNA may be used earlier, through a DNA agent only, when the McGee agent has named the specific comparison it needs and what each result would prove.
5. A DNA agent, when started, is open, private, and the only reader of `dna/`. It reports conclusions to other agents with living matches under neutral labels, never by name.
6. Nothing from DNA goes into a public repo, a Project doc or the site: no match names, no shared-match lists, no segment data, no ethnicity percentages.

**X-024. Curiosities, every batch (new; Kevin, 12 Nov).** Kevin likes the curiosities and funny finds and wants them kept up throughout, not only when something leaps out.
1. Duska, Demko and Places agents: in every batch, as you read, look for what a reader would repeat to someone else. A priest's aside, a note in a margin, an odd cause of death, a strange occupation, a coincidence of dates, a scandal, a remark on the weather or the harvest, a clerk's spelling, a rule or a fee that sounds absurd now.
2. Log each in your curiosities list with: the source ID, the original wording, your translation, one line on why it is worth keeping, and a tone: `funny`, `odd`, `sad` or `history`.
3. Every batch blurb ends with "Curiosities: N", including "Curiosities: 0". Zero is an honest answer; do not pad.
4. Deaths and misfortunes are recorded straight, not played for laughs. Nothing about a living person, and nothing from the lines outside this experiment.
5. A curiosity is not evidence and moves no confidence. If it also bears on the line, log it as a lead as well and cross-reference the two.
6. Site agent: newest first, each with its source link and tone.

**X-025. Read the ledger every batch (new).** At the start of every batch, read this ledger as it stands and log the version number you read. Kevin will no longer quote a version number when he prompts you. "Read the latest ledger and act on it" means this.

**X-026. Answers to the agents' notes (new).**
- Duska agent, the freeze: not yet. The Sorter is still working through the unclassified folder, Kevin's own tree is not sealed and the Scorer has not started. Every stamped batch is already a snapshot (rubric, section 1). Carry on checking your piles each batch.
- Duska agent, your released requests: entered in the queue below in your order.
- Duska agent, the top-level README of the private repo: you were right not to read it. Everything a line agent needs from it is in X-019 to X-022.
- Demko agent, an X-Q number for the parents of Ahn 19: X-Q-05.
- Site agent, SITE-C-16 (shown as living unless every repo says deceased; exact dates in a living person's birth year withheld site-wide): confirmed.
- Site agent, SITE-C-19: adopted for all agents. A new file under `data/` needs a line to the Site agent before it will be shown. A new field on a known record needs nothing.
- Site agent, SITE-C-21 (children of Ahn 4): ruled as X-016 item 6. Leave them off the site.
- Site agent, SITE-C-18 item 3: the route names in the Demko agent's DM-B-009 blurb may stay; they carry no name or fact.
- Site agent, SITE-C-04 (b): still to come, with the Scorer.

**X-027. Kevin's own writings, and online trees (new).** His folders hold files he wrote himself and screenshots of online family trees. The Duska agent has held ten of the first kind and asked for a rule.
1. Barred until the comparison phase, and held unopened: anything Kevin compiled about the family. That covers a "family group record", an overview or summary of baptisms, a list of people he drew up, a tree page, and any file whose name states a conclusion.
2. Readable: a guide of his to a kind of record or a collection, if it holds nothing about the family. If you open one and find it does, stop and report it.
3. Readable after your own reading is written down: a transcription or translation of a record made for him by someone else. Log it, and mark every reading you change because of it as given.
4. Online-tree pages: no blind agent opens one, whoever moved it to a pile (X-011 item 7). Sorter: hold every such page in `unknown/`, including the six there now, and place none in a line pile. The page already in `to-duska/` stays unopened. The page the Sorter judges to be Kevin's own tree in its editing view is never released to any pile.
5. A file name of Kevin's that states a finding is a prior (X-004). Record it as one when you see it, as the Duska agent did with PR-12.

**X-028. Answers to the Duska agent and the Sorter (new).**
- Duska agent, the 1984 declaration (X-S-014): Kevin told you his mother is dead and that there is no need to hold her part. His word stands over X-020 item 4 for her own name, birth and the marriage. Her parents, and everything else you have blacked out, stay withheld. Her line is not followed.
- Duska agent, "all dead" and the ten census captures: your narrow reading is right. It covers the villagers on those sheets. It does not cover Ahn 2 or the second son of Ahn 8.
- Duska agent, the second son of Ahn 8: he was born in Canada after 1937 and his status is unknown. Under X-016 item 3 he may appear by given name and "born in Canada" and nothing more. His 1973 marriage record stays held and unopened.
- Duska agent, `DUS:H-065` at 90: agreed. The cap in X-009 is for identities and links. An event shown on dated originals is not capped.
- Duska agent, the Slovak census of 1930 and 1940: these are public records and are yours to read. Kevin's "initial lists" drawn from them are item 1 of X-027.
- Sorter, your ruling 1 (the 1955 marriage): X-022 as amended. Copy it to `irish/`.
- Sorter, your ruling 2: the 1984 form follows X-028 above. The 1973 record is held. The 1974 notice is handled as the Duska agent has handled it: image held, nobody of unknown status named beyond X-016 item 3, and Kevin's account name never public.
- Sorter, your ruling 3: X-027 item 4.
- Sorter, the two files showing login details for an account of Kevin's: rightly held and not committed. Kevin is told.
- Site agent, SITE-C-22 (an infant with a recorded death shown in full): agreed.
- Site agent, the rubric on the site: agreed.
- All agents: when the coordinator asks two of you to re-read a doubtful word, it will not print either reading. In v19 it printed both, which spoiled the Demko agent's second reading of X-S-004 (C-27).

Places proposals: PL-C-01, 02, 05, 06, 07, 12, 13, 16, 17, 18 and 19 accepted as written. PL-C-04 is X-006. PL-C-11 is X-010. PL-C-14 and 15 are X-011.

Agent IDs: Duska A-01, Demko A-02, Places A-03.

## Questions

Rivals under one question should not sum to more than 100 on any one board. Each agent tags its entries with the X-Q number.

**X-Q-01. Why is Maria Demko's birth record in Uzhhorod?** Owner: Demko, with Places.

| Explanation | Entries | Latest odds |
|---|---|---|
| County copy of the civil registration of 1906 | DM-H-018, DUS:H-014 | 70, 60 |
| Greek Catholic register or duplicate of the Mukachevo eparchy | DM-H-005, DUS:H-006, PL-H-005 | 10, 30, 55 |
| Born in a parish now in Ukraine | X-H-002 (DM-H-004 is its negation, 92) | 5 |

The Demko board moved on a statement by Kevin in its chat on 12 Nov: the green civil registration of 1906 (X-S-007) is "ostensibly from Uzhhorod" (DM-PR-6). That is given, not rebuilt, and answers most of RQ-6. Nothing on the image names an archive.
Notes from the Places agent stand: Uzhhorod was the county town and the bishop's seat; the Iňačovce Greek Catholic volumes at Prešov end in 1898; the 1870-1898 volume outlived the fire of 1930; the Solymos civil registrar sat at Alsókánya in 1906 (PL-R-010).
Places agent: PL-H-005 at 55 is now far above both line boards. Say whether you still hold it.

**X-Q-02. Which book is the 1882 strip from?** Owner: Places. Ruled by the owner at PL-B-003.

| Explanation | Entries | Latest odds |
|---|---|---|
| Greek Catholic register of Čičarovce, Prešov state archive, catalogue no. 182 | PL-H-009, DM-H-011 | 93, 93 |
| Roman Catholic register of Čičarovce | DUS:H-015 | 3 |
| "Viszoka" is not Vysoká nad Uhom | PL-H-008 | 3, refuted |

Grounds, from the Places agent: Vysoká's Greek Catholics were a filial of Čičarovce from 1806 to the 1940s (PL-S-071); Ján Csurgovics was Greek Catholic parish priest there from 1882 to 1886 (PL-S-072); the archive's catalogue lists Vysoká in that parish's district (PL-S-075); three Demko documents carry the priests' signatures in the right order. The question mark on the priest's name is dropped; the surname claim no longer rests on recall. Not `solved`: no header and no archive image is in hand (X-009). RQ-2 is the closing test.

**X-Q-03. How is Maria Demko related to the Viszoka 132 household?** Owner: Demko.

| Explanation | Entries | Latest odds |
|---|---|---|
| Daughter of Mihály b. 1882, granddaughter of György Demkó and Mária Hreskó | DUS:H-012, DM-H-010 | 70, 70 |
| Daughter of György Demkó and Mária Hreskó, sister of Mihály | DUS:H-013, DM-H-009 | 1, 3, both refuted |
| Not of that household | DM-H-012 | 10 |

The two line boards agree. X-017 applies to the first row: it needs Mihály b. 1882 to have lived, and it needs the Mária of 1906 to be Ahn 9 and not an elder sister who died (DM-H-024, 8). The Places agent confirms the Iňačovce Greek Catholic burials run to 1898 in all four volumes; after that a burial search needs another source.
Tests: Stefan's birth year (RQ-1); the marriage entry of Ahn 8 and Ahn 9 (DM-H-007).

**X-Q-04. Are the Gönyű Demkos and the Viszoka Demkos one family?** Owner: Demko.

| Explanation | Entries | Latest odds |
|---|---|---|
| Different families | DUS:H-016 | 70 |
| One György, two marriages | DM-H-013 | 3 |
| A son of the Gönyű couple among the soldiers' cards | DM-H-029 | 40 |

The owner has put the one-man reading at 3, and the Places agent finds about 60 km, two counties, two eparchies and no estate or migration link (PL-N-022, PL-N-023). The coordinator's hold on DUS:H-016 at 65 is lifted.

**X-Q-05. Who were the parents of Mária Kocsis, Ahn 19?** Owner: Demko.

| Explanation | Entries | Latest odds |
|---|---|---|
| Mihály Kocsis and Mária Knyezső; she is the Mária baptised 27 Feb [1887] at Solymos no. 19 (X-S-009) | DM-H-030, DM-H-031, DUS:H-038 | 62, 58, 55 |
| János Kocsis and his wife Anna | DM-H-025 | 12 |

DM-H-031 and DUS:H-038 are one reading of one strip and count once. X-017 applies: `necronym risk: unresolved`. Nobody is entered as Ahn 38 or 39.
Test: the marriage of Mihály Demkó and Mária Kocsis at Solymos, 1903 to 1906 (DM-H-017).

**X-Q-06. Who were the parents of Michal Duska, Ahn 8, and where was he born?** Owner: Duska. **Solved by the owner at B-033.**

| Explanation | Entries | Latest odds |
|---|---|---|
| The Mihály born 3 Jul 1903 at Senné no. 79, son of András Duska and Anna Nyemcsik | DUS:H-046, DUS:H-030 | 95, solved |
| The Mihály born 6 Dec 1896 at Senné no. 1, son of the miller | DUS:H-047 | 1, refuted |
| The Reformed boy of "Bradenville"; the Reformed boy of Solymos, 1893; a grandson of the Greek Catholic György Dusko | DUS:H-040, H-041, H-035 | 0, refuted |

On what: the census of 1930 for Senné, house 145 (X-S-011), which lists Andrej Duška and his wife, their son's wife Maria born at Iňačovce, and the grandson Štefan born in October 1929; the marriage of 1892 (X-S-012); the baptism of 3 Jul 1903 in the Senné book; and a passenger list (X-S-010).
Still open under this question: his four grandparents (DUS:H-054, 70), and where the Roman Catholic Duskas of Senné came from (DUS:H-057, 35).
The coordinator gives no view on this question (C-15). It records the owner's result. Exposures that bear on it are in C-22.

## Relayed findings

From the Places agent, for both line agents. Cite the PL- IDs, not this ledger.

- Greek Catholics of Senné were registered at Iňačovce: PL-H-001, solved at 96, on an 1861 entry in the Iňačovce Greek Catholic book with the residence Szenna (DM-D-037). In 1851 Senné had 580 Roman Catholics and 238 Greek Catholics; in 1904, 484 and 231. "Senné and Iňačovce" in family memory can be one household.
- Szenna lay in the Nagykapos district and Solymos in the Szobránc district (PL-H-004, supported, 85).
- Vysoká nad Uhom was inside Slovakia from April 1939 to 1944 (PL-H-012, supported, 80; an earlier pass said the opposite). Certain: Čičarovce, the Greek Catholic parish seat for Vysoká, went to Hungary in November 1938, so a Viszoka Greek Catholic's parish office was abroad from 1938 to 1945.
- Limits for the burial search of X-017: Senné Roman Catholic births at Prešov begin in 1866. Pavlovce Roman Catholic births begin in 1869 and deaths in 1878. Iňačovce Greek Catholic burials are in all four volumes to 1898.
- The 1894 and 1895 copies are from the Greek Catholic register of Belža, Košice state archive, 1791-1896 (PL-H-010, supported, 85; PL-R-053).
- Sztrajnyán is Stráňany. Lasztomér is Lastomír, with a Greek Catholic register of its own from 1860 (PL-H-013, open, 65). Enyiczke is Haniska by Košice.
- Epidemic timeline: `data/epidemics.json` in the Places repo, PL-E-001 to PL-E-011. No cholera wave is yet documented for the three villages; the timeline is regional until burials are counted (PL-Q-007).
- A conflict recorded, not resolved: the archive's catalogue puts Stretavka's Greek Catholics under Slavkovce; one strip has a Kis Szeretva family in the Iňačovce book.

## Cross-line analysis

**X-A-001 (amended in v2). The 1868 rule on mixed marriages.** Not a constraint. The rule applied only where the parents had made no agreement; it governed separate denominations, and whether it was applied between the two Catholic rites is not established (recalled, not sourced); and DUS:S-004 shows a daughter of such a couple in a book labelled Greek Catholic. The book a child was entered in does not show which church she belonged to. Standing: H-013 and H-006 are compatible; for a mixed-rite couple, search both parish books. What holds: if Maria is the daughter of Mihály b. 1882, she was born after 1895 and a civil registration exists.

Sources: https://library.hungaricana.hu/hu/view/TestverisegFraternity_USAHUN_1961/?pg=361 ; https://majt.elte.hu/dstore/document/2863/beliznai_polgari_hazassag.pdf

## Coordinator hypotheses

| ID | Statement | Conf. | Status |
|---|---|---|---|
| X-H-001 | Maria Demko is not from the Viszoka 132 household | n/a | handed to Demko, now DM-H-012 |
| X-H-002 | Maria was born in a parish now in Ukraine | 5 | open under X-Q-01. Cut on DM-H-004 at 92 and DM-H-015 |
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

## Request queue for Kevin

Ranked by how many open items each answer settles. Kevin gives agents what is in his folders, in folder order, and has said so; a request may wait or go unanswered, and that is his choice.

Struck as answered: RQ-1 (X-S-004), RQ-7 and RQ-9 (the Senné book and the 1930 census), RQ-8 (the "Bradenville" boy is refuted), most of RQ-6 (Kevin's statement, C-23).

| No. | Request | Agent's ID | Settles |
|---|---|---|---|
| RQ-11 | The original baptism entry of Štefan Duska, Senné, 1929, entry 43 | new | The 21st or the 23rd of October |
| RQ-10 | Reformed marriages and burials for Solymos, 1860 to 1910 | DUS:R-011 | X-017 checks on the Reformed Duskas |
| RQ-3 | Image or citation behind the 1869 census find | DUS:R-002 | DUS:H-007, PL-H-006 |
| RQ-2 | Full page with header for the 1882 strip | DUS:R-003 | closes X-Q-02 |
| RQ-4 | Film or image numbers for the Senné copy-book pages | DUS:R-001 | DUS:H-010 |
| RQ-5 | Archive reference on the c. 1754 record | n/a | PL-H-007 |

Still held, not released: the Demko agent's asks for burials and for the Demkó and Kocsis marriage (X-Q-05).

Raised now, not held (X-005): seal his own tree (reminder set for 13 Nov); prompt the Places agent.

## Gaps

1. Kevin's own tree is not yet sealed. The Scorer starts after that.
2. No proof is confirmed in a Bitcoin block in any repo, about four hours after the first was made.
3. The live site is well behind the Duska repo.
4. The Places agent has not worked since ledger v14 and holds questions from both line agents.
5. First warm-or-cold check on the sealed items is due with Kevin's reminder on 13 Nov.
