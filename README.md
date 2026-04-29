Hi, I’m Jared Winslow (@jaredwins99)

I'm a data scientist within Stanford's Quantitative Sciences Unit. Before that, I studied stats at Columbia and math at IU (which included five years of tutoring anything and everything quantitative: intro courses to graduate seminars).

Selected projects I've worked on (more, including personal projects, pinned below):
- [*Multilevel INGARCH for alt proteins*](https://github.com/jaredwins99/alt-protein-sales-effects): Fully custom Stan model for forecasting sales and estimating the effect of introducing alternative proteins in restaurants. Individual models were run on HPC clusters for seven days (do not try at home). *(Specs: partial pooling across restaurants, hierarchical ITS within & across restaurants, zero inflation, count-valued, overdispersion, autoregression, regularization, and more.)*

  **RESULT**: USEFUL. Great as a model, but for alt proteins displacing demand, not so much...


- [*MARL for leader-follower dynamics*](https://github.com/jaredwins99/marl-leader-follower): Custom-built environment for reinforcement learning agents to cooperate on a foraging task. The idea was to assess whether, dependent on environmental features, the agents would specialize into different roles.

  **RESULT**: SO-SO. Do the agents cooperate? Yes. Do they adopt leader-follower dynamics? Somewhat. To the extent that mice do? Not at all.


- [*Interpretable deep learning research*](https://github.com/jaredwins99/lrp-feature-attribution): Analysis of layerwise-relevance-propagation, a feature attribution method, on neural networks, but specifically using simulated data with features correlated in network patterns. LRP backtracks feature importance using customized layer-dependent heuristics, but it has difficulty correctly attributing importance when features are interrelated in nontrivial ways.

  **RESULT**: USELESS. Probably skip LRP unless improved.


- [*Probabilistic machine learning for lead hazards*](https://github.com/jaredwins99/lead-hazard-gp-modeling): Co-regionalized Gaussian Process model for predicting lead contamination from X-rays, used for real lead hazard. Geospatial data is highly spatially autocorrelated. GPs solve this by specifying a smooth prior over the space to improve prediction and uncertainty quantification.

  **RESULT**: USEFUL.


- [*Agent retrieval for Stan modeling*](https://github.com/jaredwins99/llm-reproducibility-hooks): Harness for making Claude better at Stan (a statistical programming language). Aggregated statistical case studies and harder-to-find dev features, to hook references and validation practices. Testing on simulations and replicating papers.

  **RESULT**: ONGOING.


📫 How to reach me: jaredwins99@gmail.com

<!---
jaredwins99/jaredwins99 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
