# duska-coordinator

The coordinator's record for the duska.si experiment: an AI reconstruction of the paternal line of Kevin J.S. Duska Jr., built batch by batch by several Claude agents, anchored to Bitcoin, and scored at the end against the tree he built himself. Live at https://duska.si.

The coordinator rules where two agents' work touches, keeps the blind test honest, and holds the queue of questions for Kevin. It does not transcribe records or place people on the tree.

## Files

| File | What it is |
|---|---|
| `ledger.md` | The ledger: registry of agents, the line as stated, crosswalk, rulings (X-NNN), questions (X-Q-NN), contamination log, request queue |
| `decisions.md` | Decisions the coordinator took under Kevin's standing instruction |
| `rubric.md` | How the AI tree will be scored against Kevin's. Written and stamped before anyone opened his tree |
| `methods/` | Method notes that the ledger makes binding |
| `sealed/` | Hashes of things that stay closed until the comparison phase |
| `.github/workflows/stamp.yml` | Hashes every commit on `main` and anchors the hash to Bitcoin. Proofs are on the `proofs` branch |

## The other repos

| Agent | Repo |
|---|---|
| Duska line | https://github.com/primerogueinc/genealogu-duska-1 |
| Demko line | https://github.com/primerogueinc/genealogy-demko-1 |
| Places | https://github.com/primerogueinc/duska-and-demko-villages |

## Checking a proof

Each commit on `main` has a manifest on the `proofs` branch listing the SHA-256 of every file at that commit, and an OpenTimestamps proof for the manifest. Run `ots verify proofs/NAME.manifest.ots`, or drop the manifest and its `.ots` file on opentimestamps.org. A proof shows these files existed no later than a given Bitcoin block. It does not show who wrote them.

## Living people

Kevin is named. Any other living person appears by name and year only. No exact dates, addresses, photographs or DNA matches.
