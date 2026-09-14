## Anamaya Sharma

**Risk analytics at Axis Bank.** I work on credit risk reporting and portfolio
analytics, and I spend most of my time turning things that were done by hand
into things that run on their own.

Right now that means moving the Risk Analytics team off legacy SAS MIS onto
automated Power BI — migrating 100+ SAS tasks to PySpark on the Big Data Lake,
wiring BDL → Azure through Informatica Cloud, and building the monitoring layer
on top of it. Outside work I build small, complete things and put them online.

---

### Things that are live

| | |
|---|---|
| **[Bhav](https://bhav.anamaya.fyi)** | An inflation index built from scratch. 3.1M price observations from five retailers across 193 cities, SKUs canonicalised so the same product matches across shops, and an RBI-style chained index that links only on matched shops — so growing the sample can't fake a price move. |
| **[SenpaiScope](https://senpaiscope.anamaya.fyi)** | Content-based anime recommendations that explain themselves. Rebuilt in Aug 2026 to +49% nDCG against held-out AniList votes, and the popularity prior was deleted once matched distractors showed most of its benefit was confounding. |
| **[Foglight](https://foglight.anamaya.fyi)** | A reader for difficult classics — focus mode, plain-English rewrites, spoiler-safe character tracking, tap-to-look-up for any word or phrase. |
| **[NPA Explorer](https://npa.anamaya.fyi)** | Twenty years of non-performing assets across 115 Indian banks, from RBI DBIE. Heatmap, drill-down, advances-weighted group averages matching RBI Financial Stability Report methodology. |
| **[Scorecard Playground](https://scorecard.anamaya.fyi)** | Move the inputs of a credit scorecard and watch the score and the cutoff decision move with them. Built to make "why was I declined" a question with a visible answer. |
| **[Tumour Segmentation](https://tumor.anamaya.fyi)** | A U-Net segmenting low-grade gliomas in brain MRI, running client-side in ONNX. Split by patient rather than by slice, because adjacent slices of one brain are near-duplicates and splitting by slice buys you Dice that isn't there. |
| **[AI Text Checker](https://aitext.anamaya.fyi)** | Detects machine-written prose and shows the per-word arithmetic behind every verdict. Scores 99.9% on its own test split, then calls *Pride and Prejudice* machine-written — which is the more useful half of the demo. |

### Back from college

Everything I wrote between 2021 and 2023, running again. The algorithms were
re-implemented in JavaScript from the original Python — same operators, same
heuristics — so they run in a browser instead of a terminal I no longer own.

| | |
|---|---|
| **[N-Queens by GA](https://nqueens.anamaya.fyi)** | A population of random chessboards bred until no queen can see another. Selection, crossover, mutation, and a fitness that counts attacking pairs. *(2021)* |
| **[8-Puzzle](https://puzzle.anamaya.fyi)** | Greedy best-first search, plus the inversion-parity test that refuses the half of all shuffles nobody can solve. Watch it return 51 moves for a 14-move board. *(2021)* |
| **[Binary Search Tree](https://bst.anamaya.fyi)** | Insert, search and traverse, with the comparison path drawn. Insert 1…15 in order and watch it degenerate into a linked list. *(2021)* |
| **[Bollywood Connector](https://bollywood.anamaya.fyi)** | Six degrees of Indian cinema — BFS over 250 films and 362 actors, naming the film behind every hop. *(2021)* |
| **[Galaxy](https://galaxy.anamaya.fyi)** | The endless procedural track from a Kivy game, and the quartic projection that gives it a horizon. *(2021)* |
| **[The Attic](https://attic.anamaya.fyi)** | Nine evening projects from one year — a breathing timer, a countdown, a memory game. *(2021)* |

The full list, dated, is at **[anamaya.fyi/catalogue](https://anamaya.fyi/catalogue)** —
50 projects since 2021. The early ones are not good. They are there because the
distance between them and the recent ones is the only part of a portfolio that
is actually evidence.

---

More at **[anamaya.fyi](https://anamaya.fyi)**.

---

### What I actually work with

**Risk & domain** — credit risk reporting · portfolio analytics · enterprise
risk management · emerging and change risk · CECL · corporate forecasting

**Data** — Python · PySpark · SQL across Hive, Spark, Oracle and Impala ·
credit risk modelling

**Platforms** — Power BI (DAX, Power Query, semantic models) · Tableau ·
Informatica Cloud · Azure Data Lake · Dataverse

**Automation & GenAI** — Power Automate · Copilot Studio · LLM applications ·
Bitbucket · Jenkins

---

### Research

**"The Scorer Is Not the System: Three Separable Ways Offline Evaluation and a
Deployed Scoring Path Can Disagree"** — built on SenpaiScope. Three findings:
80% of catalog mass has zero inclusion propensity so IPS is undefined there;
popularity-matched candidates show a popularity prior's whole benefit was
residual confound; and the same 1,190 probes pick a different winner on the
research scorer than on the production one. Section 8.4 re-runs it on a
different answer key and retracts one of the paper's own conclusions.

Code and data are public — Zenodo
[10.5281/zenodo.22013094](https://doi.org/10.5281/zenodo.22013094),
plus [senpaiscope-threshold-data](https://github.com/Anamaya1729/senpaiscope-threshold-data).
Desk-rejected twice without review. Still the most careful thing I've built.

---

### Background

**Axis Bank** — Risk Analytics (Jan 2025–), Business Intelligence Unit (2023–24),
where a detractor closed-loop framework routed customer feedback by ticket size
and moved NPS 5%.

**IIT Mandi** — Minor in Computer Science & Advanced Technologies
**Punjab Technical University** — B.Sc. Artificial Intelligence & Machine Learning
**WorldQuant University** — MSc Financial Engineering, in progress

Copilot Champion 2026 · Anchors Award for Speed 2025 · FIDE ACM title (chess),
and I'll take the game if you're offering.

---

📫 **[Anamaya1729@gmail.com](mailto:Anamaya1729@gmail.com)** ·
💼 **[LinkedIn](https://linkedin.com/in/Anamaya1729)** ·
🌐 **[anamaya.fyi](https://anamaya.fyi)**
