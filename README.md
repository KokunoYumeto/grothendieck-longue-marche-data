# Grothendieck programme: large data files of the Longue Marche and Montpellier archive runs

The papers, results tables, reports and code of these runs are in
[grothendieck-longue-marche](https://github.com/KokunoYumeto/grothendieck-longue-marche) (`raw/pro_returns/`). This
repository holds their large data files: computation outputs, tables, test records and certificates, at the same
paths under `data/<run folder>/`. GPT-6 Astra (OpenAI, ChatGPT Pro mode) produced them, 11-17 November 2026.

- Files over 45 MB are split into parts `NAME.part01`, `NAME.part02`, ...; `NAME.parts.sha256` gives the SHA-256 of
  the joined file and the command that joins it (`cat NAME.part* > NAME`).
- Left out as duplicates: copies of earlier checkpoints that a run carried inside later ones (history archives, packed
  chunks), rendered page images, and identical copies of a file already here.
- Nothing here has been refereed. AI-produced; dedicated to the public domain under CC0 1.0.
