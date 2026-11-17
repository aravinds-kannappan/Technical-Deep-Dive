# Technical Deep Dives

Beginner-friendly technical articles that build from a concrete problem to plain-language explanations, worked examples, mathematics, implementation, and evaluation.

- [Synthure](synthure_deep_dive.html): hospital origins, patient understanding, coordination, care and coverage fit, then clinical extraction, retrieval, shared encounter state, and review.
- [Replays AI](replays_ai_deep_dive.html): the personal sports desk thesis, sports data, worked ranking mathematics, autoregressive inference, attention, LoRA training, evaluation, and serving economics.
- [Platonic Universe](eleutherai_platonic_universe_deep_dive.html): representation geometry, physical transfer, statistical testing, and GPU infrastructure.
- [Combined Synthure + Replays edition](synthure_replays_engineering_masterclass.html): both product articles with a cross-system comparison.

Open `index.html` locally, or serve the repository with `python3 -m http.server 8765`. No build step is required. Each article is self-contained and includes navigation, search, a theme toggle, print styles, code excerpts, and diagrams. The PDF cheatsheets remain in `study-guides/`. All three articles include six interactive SVG plots apiece, distributed across the reading path, with local controls, explicit illustrative-data labels, and guided “try this” explanations. The plots use inline JavaScript with no external dependencies.

The PDF engineering references use the supplied CS229 cheatsheet as a layout reference: landscape pages, two columns, numbered sections, colored square-bullet concept labels, typeset mathematics, comparison tables, and technical figures. Synthure spans 12 pages, ReplaysAI 12, and EleutherAI / Platonic Universe 11; the combined edition has 35 pages. Each guide expands definitions, step-by-step mechanisms, implementation and configuration, design tradeoffs, worked examples, evaluation, and concrete failure cases. The guides include 12 original technical figures and eight tables. Implemented behavior, reported measurements, illustrative calculations, and proposed improvements are distinguished. They contain engineering notes rather than interview scripts or code listings; existing PDF URLs remain stable.

## Editorial approach

The articles introduce the motivation before the mechanism, define technical terms and notation before using them, and explain each calculation in ordinary language. Readers can follow the core explanation without already knowing machine learning. Optional disclosures retain full derivations, pinned code excerpts, and implementation edge cases. The two Chip Huyen posts supplied as editorial references—[RLHF](https://huyenchip.com/2023/05/02/rlhf.html) and [multimodality](https://huyenchip.com/2023/10/10/multimodal.html)—informed this explanatory structure. The article prose is original.

Synthure’s origin account comes from the founder’s hospital-volunteering experience. The articles distinguish company ambitions from current implementation and describe existing adjacent products without claiming an empty market. All three articles explain the intermediate calculations alongside the cheatsheet equations: feature vectors, contrastive training, attention, adapters, representation geometry, evaluation, and memory scaling.

Code excerpts link to the source revisions discussed. Worked examples are illustrative, reported metrics retain their dataset and provenance, and proposed improvements are distinguished from implemented behavior. The editorial rewrite does not claim new model training, clinical evaluation, production benchmarks, or scientific reproduction.

## GitHub Pages

The site uses relative links and can be served from the repository root. In Settings → Pages, select the intended branch and `/ (root)` if configuring branch-based publishing. Keep the article filenames and section anchors stable when editing; older links and the cheatsheets may refer to them.

The combined edition contains the same rewritten product chapters. When editing either standalone article, update its corresponding combined chapters as well.
