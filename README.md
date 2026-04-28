Hi, I’m Jared Winslow (@jaredwins99)

I'm a data scientist at HSFL within Stanford's Quantiative Sciences Unit. Before that, I studied stats at Columbia and math at IU (which included five years of tutoring anything and everything quantitative: intro courses to graduate seminars).

Selected projects I've worked on:
- [*ML-ZINB-INGARCHX*](https://github.com/jaredwins99/alt-protein-sales-effects): Designed and optimized a fully custom Stan model for forecasting sales and estimating the effect of introducing alternative proteins in restaurants. Individual models were run on HPC clusters for seven days (do not try at home). *(Model specs: partial pooling across restaurants, hierarchical ITS within and across restaurants, zero inflation, overdispersion, count-valued, autocorrelation, exogenous shocks, regularization, and more.)*

  **RESULT**: USEFUL. Great as a model, but for alt proteins displacing demand, not so much...


- [*RAG for Stan modeling*](https://github.com/jaredwins99/llm-reproducibility-hooks): Aggregated all accessible statistical case studies done with the Stan programming language, including harder-to-find dev features. Designed a test to evaluate Claude's performance on composite simulated modeling tasks as well as recent empirical ones by using hooks to pre-reference gold-standard Stan practices and force validation practices.

  **RESULT**: ONGOING.


- [*MARL for leader-follower dynamics*](https://github.com/jaredwins99/marl-leader-follower): Designed and implemented a custom system and environment for two reinforcement learning agents to cooperate on a foraging task. The idea was to assess whether, dependent on environmental features, the agents would specialize into different roles.

  **RESULT**: SO-SO. Do the agents cooperate? Yes. Do they adopt leader-follower dynamics? Somewhat. To the extent that mice do? Not at all.


- [*Interpretable deep learning research*](https://github.com/jaredwins99/lrp-feature-attribution): Evaluated layerwise-relevance-propagation as a method for attributing feature importance in neural networks, specifically using simulated data with network structures. LRP backtracks feature importance using customized layer-dependent heuristics, but it has difficulty correctly attributing importance when features are interrelated in nontrivial ways.

  **RESULT**: USELESS. Probably skip LRP unless improved.


- [*Probabilistic machine learning for lead hazards*](https://github.com/jaredwins99/lead-hazard-gp-modeling): Designed a co-regionalized Gaussian Process regression to predict lead contamination from X-rays for a real lead hazard. The difficulty in fitting geospatial data is the spatial autocorrelation. GPs solve this by specifying a smooth prior over the space, improving prediction and uncertainty quantification.

  **RESULT**: USEFUL.



📫 How to reach me: jaredwins99@gmail.com

<!---
jaredwins99/jaredwins99 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
