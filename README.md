# Technical Deep Dives

Long-form technical articles that build from a concrete problem to worked examples, mathematics, implementation, and evaluation.

- [Synthure](synthure_deep_dive.html): clinical extraction, code retrieval, calibrated readiness, report generation, and review.
- [Replays AI](replays_ai_deep_dive.html): sports data, event selection, caching, personalization, LoRA, and reliable state.
- [Platonic Universe](eleutherai_platonic_universe_deep_dive.html): representation geometry, physical transfer, statistical testing, and GPU infrastructure.
- [Combined Synthure + Replays edition](synthure_replays_engineering_masterclass.html): both product articles with a cross-system comparison.

Open `index.html` locally, or serve the repository with `python3 -m http.server 8765`. No build step is required. Each article is self-contained and includes navigation, search, a theme toggle, print styles, code excerpts, and diagrams. The PDF cheatsheets remain in `study-guides/`.

## Editorial approach

The articles introduce the motivation before the mechanism, define notation alongside its use, and explain tradeoffs through concrete examples. The two Chip Huyen posts supplied as editorial references—[RLHF](https://huyenchip.com/2023/05/02/rlhf.html) and [multimodality](https://huyenchip.com/2023/10/10/multimodal.html)—informed this explanatory structure. The article prose is original.

Code excerpts link to the source revisions discussed. Worked examples are illustrative, reported metrics retain their dataset and provenance, and proposed improvements are distinguished from implemented behavior. The editorial rewrite does not claim new model training, clinical evaluation, production benchmarks, or scientific reproduction.

## GitHub Pages

The site uses relative links and can be served from the repository root. In Settings → Pages, select the intended branch and `/ (root)` if configuring branch-based publishing. Keep the article filenames and section anchors stable when editing; older links and the cheatsheets may refer to them.

The combined edition contains the same rewritten product chapters. When editing either standalone article, update its corresponding combined chapters as well.
