# Sealed items

Things that stay closed until the comparison phase. Only their hashes are public. When an item is opened, anyone can hash it and compare.

| Item | SHA-256 | Sealed | Opened |
|---|---|---|---|
| C-12: a statement Kevin made to the coordinator about his own tree, 12 Nov 2026. The hash is of the sentence as he typed it, UTF-8, no trailing newline | `371f5ae96718806a6422e8dab1169356c773e80922c5c358a5a71e85fb31a33f` | 12 Nov 2026 | not yet |
| C-15: a second statement Kevin made to the coordinator, 12 Nov 2026. The hash is of the passage as he typed it, UTF-8, no trailing newline | `cccb77ce2d3362e52992fb22a71bdd3def2d86d816b03072f8b686ee8501d962` | 12 Nov 2026 | not yet |
| C-15a: a note by the coordinator on how a later log entry bears on C-15. The hash is of one sentence, UTF-8, no trailing newline | `e68876c08013b58374b0efb54c65069aff86801409a132ef711094e39311d06c` | 12 Nov 2026 | not yet |
| Kevin's own tree, file 1: a PDF of 136,399 bytes. The hash is of the file itself | `7a16419fd6865d4934b8ae09275044877cb9cc9a314ccd71eb92f1895dd278ab` | 12 Nov 2026 | not yet |

## Kevin's tree files

Each tree file is sealed on its own, one row per file, as Kevin hands it to the Scorer. The hashes are also in `kevin-tree.sha256`.

The coordinator is blind and never holds a tree file. Each hash here was computed by the Scorer from the file Kevin gave it and passed on by Kevin. The proof of the date is this repository's own stamp on the commit that added the row. For file 1 the row was added after the Scorer had hashed the file and before it built anything from it.
