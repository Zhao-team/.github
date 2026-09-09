# Zhao Lab · Complete pipeline directory

[← Zhao-team overview](https://github.com/Zhao-team)

16 repository-linked tools, organized by analysis task.

**Find a tool for your analysis:** [Brain networks](#build-and-characterize-brain-networks) · [Prediction & multimodal modeling](#predict-outcomes-and-relate-modalities) · [Pathways & subtypes](#discover-pathways-and-subtypes) · [Mediation & event histories](#analyze-mediation-and-event-histories) · [Genetics](#study-connectome-genetics)

## Build and characterize brain networks

| Tool | Input → output | Environment | Start here |
| --- | --- | --- | --- |
| [**SBP**](https://github.com/wanwanx/SBP) | Voxel time series + outcome → task-informed parcels and networks | R | [Usage & simulation](https://github.com/wanwanx/SBP#usage) |
| [**SF Gradient Coupling**](https://github.com/Zhao-team/SF-Gradient-Coupling) | Structural + functional connectivity → aligned gradients, coupling, and association analyses | Python / R | [Pipeline stages](https://github.com/Zhao-team/SF-Gradient-Coupling#overview) |
| [**ABCModel**](https://github.com/selenashuowang/ABCModel) | Connectivity matrices + regional attributes → group-level connectivity estimates | R | [Tutorial](https://github.com/selenashuowang/ABCModel#usage) |

## Predict outcomes and relate modalities

| Tool | Input → output | Environment | Start here |
| --- | --- | --- | --- |
| [**GenCPM**](https://github.com/BXU69/GenCPM) | Connectomes + outcomes + optional covariates → predictions, selected edges, and performance summaries | R package | [Example](https://github.com/BXU69/GenCPM#example) |
| [**LatentSNA**](https://github.com/selenashuowang/latentSNA) | Connectomes + individual outcomes → latent network structure, associations, and predictions | R | [Tutorial](https://github.com/selenashuowang/latentSNA#usage) |
| [**HyBRiD**](https://github.com/Graph-and-Geometric-Learning/HyBRiD) | Brain functional data → learned higher-order relationships and outcome predictions | Python | [Run an experiment](https://github.com/Graph-and-Geometric-Learning/HyBRiD#usage) |
| [**COSR**](https://github.com/Naomi-Ding/COSR) | Anatomical shape features + connectivity → estimated connectivity–shape relationships | MATLAB | [Quick start](https://github.com/Naomi-Ding/COSR#quick-start) |
| [**CoCR**](https://github.com/zhaoyi1026/CoCR) | Paired covariance structures → covariance-on-covariance regression estimates | R | [Example script](https://github.com/zhaoyi1026/CoCR/blob/main/example.R) |

## Discover pathways and subtypes

| Tool | Input → output | Environment | Start here |
| --- | --- | --- | --- |
| [**BHPI**](https://github.com/Naomi-Ding/BHPI) | Disease indicators + risk factors → overlapping pathways and pathway-level associations | MATLAB | [Synthetic experiment & guide](https://github.com/Naomi-Ding/BHPI#readme) |
| [**MMBeans**](https://github.com/tqchen07/MMBeans) | Multi-state brain networks → subtypes and state-specific network modules | R | [Simulation example](https://github.com/tqchen07/MMBeans#usage) |
| [**Nebula**](https://github.com/nebula-group/nebula) | Multiple data types + biological networks → network-informed subtypes | R package | [Install & vignette](https://github.com/nebula-group/nebula#installation) |

## Analyze mediation and event histories

| Tool | Input → output | Environment | Start here |
| --- | --- | --- | --- |
| [**BNMM**](https://github.com/Zhao-team/Bayesian_Network_Mediation_Model) | Exposure + brain networks + outcome → network mediation estimates | R | [Code & notes](https://github.com/Zhao-team/Bayesian_Network_Mediation_Model#readme) |
| [**Network mediation for survival**](https://github.com/Zhao-team/bayesian-pathway-brain-mediators) | Exposure + brain networks + event times → network-mediated survival effects | R | [Implementation guide](https://github.com/Zhao-team/bayesian-pathway-brain-mediators#readme) |
| [**BMZ-DP**](https://github.com/xt83/Bayesian_semi_parametric_inference_for_clustered_recurrent_event) | Clustered recurrent and terminal events → joint event-process estimates | R | [Simulation & analysis scripts](https://github.com/xt83/Bayesian_semi_parametric_inference_for_clustered_recurrent_event#readme) |

## Study connectome genetics

| Tool | Input → output | Environment | Start here |
| --- | --- | --- | --- |
| [**NRSS**](https://github.com/zhengwu/Network-Response-Shrinkage-Model) | Genetic predictors + network phenotypes → structured genetic association estimates | R / MATLAB utilities | [Simulation & data guide](https://github.com/zhengwu/Network-Response-Shrinkage-Model#readme) |
| [**BNME**](https://github.com/xt83/Bayesian_mixed_model_inference_for_genetic_association_under_related_samples) | Genetic predictors + networks + relatedness → genetic association estimates accounting for population structure | R | [Analysis code](https://github.com/xt83/Bayesian_mixed_model_inference_for_genetic_association_under_related_samples#readme) |

### Code distributed with journal supplements

[**Biomarker trajectories before disease onset**](https://academic.oup.com/biometrics/article/81/2/ujaf064/8151984) — semiparametric joint modeling of biomarker trajectories and disease onset. The publisher supplies code through the supplemental files; use the article page to access them.

<details>
<summary><strong>Papers and citations</strong></summary>

Please cite the associated paper when using a tool. Full author lists and citation instructions are available in the papers and repositories.

| Tool | Publication |
| --- | --- |
| SBP | [Imaging Neuroscience](https://doi.org/10.1162/imag.a.56) |
| SF Gradient Coupling | [Nature Communications](https://doi.org/10.1038/s41467-026-71719-y) |
| GenCPM | [Frontiers in Neuroscience](https://doi.org/10.3389/fnins.2025.1627497) |
| LatentSNA | [Nature Methods](https://doi.org/10.1038/s41592-025-02896-9) |
| HyBRiD | [ICML 2024](https://icml.cc/virtual/2024/poster/33885) |
| COSR | [Annals of Applied Statistics](https://doi.org/10.1214/26-AOAS2154) |
| CoCR | [Biometrics](https://doi.org/10.1093/biomtc/ujaf097) |
| BHPI | [Paper](https://arxiv.org/abs/2606.07677) |
| BNMM | [Statistics in Medicine](https://doi.org/10.1002/sim.9488) |
| Network mediation for survival | [Biometrics](https://doi.org/10.1093/biomtc/ujae132) |
| NRSS | [JASA](https://doi.org/10.1080/01621459.2022.2156349) |

For ABCModel, MMBeans, Nebula, BMZ-DP, and BNME, follow the citation information in the source repository. See the [lab publication list](https://www.yizezhao.com/research) for the broader research record.

</details>

<details>
<summary><strong>Original sources and group copies</strong></summary>

The tool links above lead to original source repositories. Several also have copies in Zhao-team. Follow the original project’s contribution instructions unless the authors designate a different development location.

| Tool | Group fork |
| --- | --- |
| SBP | [Zhao-team copy](https://github.com/Zhao-team/SBP) |
| ABCModel | [Zhao-team copy](https://github.com/Zhao-team/ABCModel) |
| GenCPM | [Zhao-team copy](https://github.com/Zhao-team/GenCPM) |
| LatentSNA | [Zhao-team copy](https://github.com/Zhao-team/latentSNA) |
| COSR | [Zhao-team copy](https://github.com/Zhao-team/COSR) |
| BHPI | [Zhao-team copy](https://github.com/Zhao-team/BHPI) |
| MMBeans | [Zhao-team copy](https://github.com/Zhao-team/MMBeans) |
| Nebula | [Zhao-team copy](https://github.com/Zhao-team/nebula) |
| BMZ-DP | [Zhao-team copy](https://github.com/Zhao-team/Bayesian_semi_parametric_inference_for_clustered_recurrent_event) |
| NRSS | [Zhao-team copy](https://github.com/Zhao-team/Network-Response-Shrinkage-Model) |
| BNME | [Zhao-team copy](https://github.com/Zhao-team/Bayesian_mixed_model_inference_for_genetic_association_under_related_samples) |

</details>

Tools vary in scope, setup requirements, and maintenance. Linked examples are supplied by their authors; their inclusion here does not certify that every example or paper result has been independently reproduced.

[Zhao Lab at Yale](https://www.yizezhao.com/) · [People](https://www.yizezhao.com/team-4)
