Hi, I’m Jared Winslow (@jaredwins99)

I'm a data scientist at HSFL within Stanford's Quantiative Sciences Unit. Before that, I studied stats at Columbia and math at IU (which included five years of tutoring anything and everything quantitative, from intro courses to graduate seminars).

Selected projects I've worked on:
- ML-ZINB-INGARCHX: Designed and optimized a fully custom Stan model for forecasting sales and estimating the effect of introducing alternative proteins in restaurants, incorporating partial pooling across restaurants, hierarchical ITS within and across restaurants, zero inflation, overdispersion, count emission modeling, autocorrelation, exogenous shocks, regularization, and more. Individual models were run on HPC clusters for seven days (do not try at home).

RESULT: USEFUL. Great as a model, but for the alt proteins displacing demand, not so much...

- RAG for Stan modeling: Aggregated all statistical case studies done with the Stan programming language, including harder to find dev features. Designed a test to evaluate Claude's performance with forced (by hook) pre-referencing of gold-standard Stan practices and forced validation practices, on simulated modeling tasks as well as recent empirical ones. Simulated tasks require the composition of known features since Claude already excels at user-guide-level tasks.

RESULT: ONGOING.

- MARL for leader-follower dynamics: Designed and implemented a custom system and environment for two reinforcement learning agents to cooperate on a foraging task. The idea was to assess whether, dependent on environmental features, the agents would specialize into different roles.

RESULT: SO-SO. Do the agents cooperate? Yes. Do they adopt leader-follower dynamics? Somewhat. To the extent that mice do? Not at all.

- Interpretable deep learning research: Evaluated layerwise-relevance-propagation as a method for attributing feature importance in neural networks, specifically using complex simulated data with network structures. LRP backtracks feature importance using customized layer-dependent heuristics, but it has difficulty correctly attributing importance when features are interrelated in nontrivial ways.

RESULT: USELESS. Probably skip LRP.

- Probabilistic machine learning: Developed a co-regionalized Gaussian Process (GP) regression model to predict lead contamination in soil from X-ray fluorescence, helping an environmental firm remediate a real-world lead hazard. The difficulty in managing geospatial data is in its significant spatial autocorrelation. GPs solve this by implicitly positing a smooth prior over the space, enabling enhanced prediction and uncertainty quantification.

RESULT: USEFUL.

- Pokemon card identification: Developed a system for identifying Pokemon cards comparable with state-of-the-art methods, including concurrent multi-card identification, variant detection (e.g., 1st edition), multiple language support, and individual-sales condition-level pricing. Used at real life convention.

RESULT: USEFUL.



📫 How to reach me: jaredwins99@gmail.com

<!---
jaredwins99/jaredwins99 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
