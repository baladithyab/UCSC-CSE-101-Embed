# UCSC CSE 101 — Algorithms (Winter 2020)

Interactive visualizations of the data structures and algorithms from
Patricia Lopez's CSE 101 at UCSC. Source artifacts are TypeScript
ports of the original C++ assignments, instrumented with step-by-step
animations so the algorithm is visible, not just runnable.

Embeds via codeseys.io's project-embed pipeline. See the manifest
(`web.codeseys.json`) for asset metadata.

## Original source

C++ implementations of all four homeworks live at
[baladithyab/UCSC-CSE-101-W20](https://github.com/baladithyab/UCSC-CSE-101-W20)
(or wherever they're being served from in the future). This repo is
the *visualization* layer — same algorithms, different presentation.

## Assignments

- **HW1 — Bard**: insert Shakespeare's vocabulary into a sorted linked
  list, query for word frequencies. Original was a perf benchmark of
  insertion-sort vs merge-sort on ~5K unique words.
- **HW2 — N-Queens**: place N queens on an N×N board such that none
  attack each other. Backtracking with constraint propagation.
- **HW3 — Wordrange**: AVL tree of strings, query for words in a
  lexicographic range. Self-balancing on insertion + deletion.
- **HW4 — Six Degrees**: BFS shortest-path between actors in a
  Hollywood collaboration graph. Original used a 50K-node co-star
  network from IMDB scrapes; the demo uses a smaller fixture.

## License

MIT.
