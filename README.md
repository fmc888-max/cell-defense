# Cell Defense (version 1.1)

An original tower defense browser game for AP Biology practice. Level 1 covers Campbell Biology (13th ed.) chapters 6–12: cell structure, membranes, enzymes, cellular respiration, photosynthesis, cell communication and the cell cycle (AP Units 2–4).

- Towers are cell parts (peroxisome, central vacuole, cytoskeleton, kinase cascade, chloroplast, mitochondrion) and the currency is ATP.
- One data-based multiple-choice question before every wave (30 in the bank, with spaced repetition), plus free-response experiment questions before waves 5, 10, 20, 30, 40 and 50 (four different questions).
- 50 waves with a boss every 10 (Rogue Growth Signal, Giant Virus, Oxidative Storm, Cyanide Cloud, Runaway Division). Waves 31–50 are a harder tier with tougher, faster threats and mutant viruses. Organelles upgrade to level 5, and Repair DNA turns spare ATP into Health.
- Placing related organelles side by side unlocks connections that explain the biology.
- Progress saves in the browser; a save code moves it to another computer. An optional Anthropic API key (Settings) lets Claude mark free-response answers.

Everything is in `index.html`, with no build step. Play it at https://fmc888-max.github.io/cell-defense/ once GitHub Pages is switched on (Settings → Pages → Deploy from branch `main`, folder `/`).

Questions are written in AP format for practice. They are not official College Board questions.
