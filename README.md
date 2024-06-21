# Membership Inference Attacks and Defenses on Machine Learning Models Literature

A curated list of membership inference attacks and defenses papers on machine learning models.

Papers are sorted by their released dates in descending order.

This repository serves as a complement to the survey below.

[**Membership Inference Attacks on Machine Learning: A Survey**](https://arxiv.org/abs/2103.07853) **(More than 100 papers reviewed).**

````bibtex
@article{hu2022membership,
  title={Membership inference attacks on machine learning: A survey},
  author={Hu, Hongsheng and Salcic, Zoran and Sun, Lichao and Dobbie, Gillian and Yu, Philip S and Zhang, Xuyun},
  journal={ACM Computing Surveys (CSUR)},
  volume={54},
  number={11s},
  pages={1--37},
  year={2022},
  publisher={ACM New York, NY}
}
````

If you feel this repository is helpful, please cite the survey above.

## How to Search?
Search keywords like conference name (e.g., ```CCS```), adversarial knowledge (e.g., ```Black-box```), or target model (e.g., ```Classification Model```) over the webpage to quickly locate related papers.

## Quick Links
**Attack papers sorted by year:** | [2024](#attack-papers-2024) |[2023](#attack-papers-2023) |[2022](#attack-papers-2022) |[2021](#attack-papers-2021) | [2020](#attack-papers-2020-back-to-top) | [2019](#attack-papers-2019-back-to-top) | [2018](#attack-papers-2018-back-to-top) | [2017](#attack-papers-2017-back-to-top) |

**Defense papers sorted by year:** | [2023](#defense-papers-2023-back-to-top) |[2022](#defense-papers-2022-back-to-top) | [2021](#defense-papers-2021-back-to-top) | [2020](#defense-papers-2020-back-to-top) | [2019](#defense-papers-2019-back-to-top) | [2018](#defense-papers-2018-back-to-top) |

## Membership Inference Attack
### Attack Papers 2024
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2024 | **Do Parameters Reveal More than Loss for Membership Inference?** | White-box | Classification Models | ICML Workshop | [Link](https://arxiv.org/abs/2406.11544) | [Link](https://github.com/iamgroot42/iha_hild) |
| 2024 | **Low-Cost High-Power Membership Inference Attacks** | Black-box | Classification Models | ICML | [Link](https://openreview.net/pdf?id=sT7UJh5CTc) | [Link](https://github.com/privacytrustlab/ml_privacy_meter/tree/master/research/2024_rmia) |
| 2024 | **LLM Dataset Inference Did you train on my dataset?** | Black-box | LLM | Arxiv | [Link](https://arxiv.org/abs/2406.06443) | [Link](https://github.com/pratyushmaini/llm_dataset_inference/) |
| 2024 | **Shadow-Free Membership Inference Attacks: Recommender Systems Are More Vulnerable Than You Thought** | Black-box | Recommender System| IJCAI | [Link](https://arxiv.org/abs/2405.07018) | [Link](https://github.com/XiaoxiaoChi-code/shadow-free-MIAs) |
| 2024 | **Is My Data in Your Retrieval Database? Membership Inference Attacks Against Retrieval Augmented Generation** | Black-box | Generative Models | Arxiv | [Link](https://arxiv.org/abs/2405.20446) | |
| 2024 | **A Comprehensive Analysis of Factors Impacting Membership Inference** | White-box; Black-box | Classification Models | CVPR workshop | [Link](https://openaccess.thecvf.com/content/CVPR2024W/SAIAD/html/Dealcala_A_Comprehensive_Analysis_of_Factors_Impacting_Membership_Inference_CVPRW_2024_paper.html) | |
| 2024 | **Lost in the Averages: A New Specific Setup to Evaluate Membership Inference Attacks Against Machine Learning Models** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2405.15423) | |
| 2024 | **Better Membership Inference Privacy Measurement through Discrepancy** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2405.15140) | |
| 2024 | **OSLO: One-Shot Label-Only Membership Inference Attacks** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2405.16978) | |
| 2024 | **Please Tell Me More: Privacy Impact of Explainability through the Lens of Membership Inference Attack** | Black-box | Classification Models | S&P | [Link](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a120/1Ub23teQ7PG) | |
| 2024 | **Is my Data in your AI Model? Membership Inference Test with Application to Face Images** | White-box; Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2402.09225) | |
| 2024 | **Understanding Practical Membership Privacy of Deep Learning** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2402.06674) | |
| 2024 | **Evaluating Membership Inference Attacks and Defenses in Federated Learning** | White-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2402.06289) | [Link](https://github.com/Liar-Mask/FedMIA) |
| 2024 | **Uncertainty, Calibration, and Membership Inference Attacks: An Information-Theoretic Perspective** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2402.10686) | |
| 2024 | **Do Membership Inference Attacks Work on Large Language Models?** | Black-box | LLM | Arxiv | [Link](https://arxiv.org/abs/2402.07841) | [Link](https://github.com/iamgroot42/mimir) |
| 2024 | **Learning-Based Difficulty Calibration for Enhanced Membership Inference Attacks** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2401.04929) | [Link](https://github.com/horanshi/LDC-MIA) |
| 2024 | **Scalable Membership Inference Attacks via Quantile Regression** | Black-box | Classification Models | NeurIPS | [Link](https://assets.amazon.science/61/10/fe6e935b49bf89bb34dded96a17b/scalable-membership-inference-attacks-via-quantile-regression.pdf) | [Link](https://github.com/amazon-science/quantile-mia) |

### Attack Papers 2023
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2023 | **Link Membership Inference Attacks against Unsupervised Graph Representation Learning** | White-box/Black-box | Graph Embedding Models | ACSAC | [Link](https://dl.acm.org/doi/abs/10.1145/3627106.3627115) | [Link](https://gitfront.io/r/user-8658281/Mpx6p294FzeZ/LMIA/) |
| 2023 | **Low-Cost High-Power Membership Inference by Boosting Relativity** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2312.03262) | [Link](https://github.com/privacytrustlab/ml) |
| 2023 | **Practical Membership Inference Attacks against Fine-tuned Large Language Models via Self-prompt Calibration** | Black-box | Language Models | Arxiv | [Link](https://arxiv.org/pdf/2311.06062.pdf) | | 
| 2023 | **A Probabilistic Fluctuation based Membership Inference Attack for Diffusion Models** | Black-box | Generative Models | Arxiv | [Link](https://arxiv.org/pdf/2308.12143.pdf) | | 
| 2023 | **Practical Membership Inference Attacks Against Large-Scale Multi-Modal Models: A Pilot Study** | Black-box | Classification Models | ICCV | [Link](https://openaccess.thecvf.com/content/ICCV2023/papers/Ko_Practical_Membership_Inference_Attacks_Against_Large-Scale_Multi-Modal_Models_A_Pilot_ICCV_2023_paper.pdf) | [Link](https://github.com/ruoxi-jia-group/CLIP-MIA) | 
| 2023 | **Privacy Side Channels in Machine Learning Systems** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/pdf/2309.05610.pdf) | |
| 2023 | **White-box Membership Inference Attacks against Diffusion Models** | White-box | Generative Models | Arxiv | [Link](https://arxiv.org/abs/2308.06405) | [Link](https://anonymous.4open.science/r/GSA/README.md) |
| 2023 | **Scalable Membership Inference Attacks via Quantile Regression** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2307.03694) | |
| 2023 | **Synthetic is all you need: removing the auxiliary data assumption for membership inference attacks against synthetic data** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2307.01701) | |
| 2023 | **Towards More Realistic Membership Inference Attacks on Large Diffusion Models** | Black-box | Generative Models | Arxiv | [Link](https://arxiv.org/abs/2306.12983) | |
| 2023 | **Fortifying Federated Learning against Membership Inference Attacks via Client-level Input Perturbation** | White-box | Classification Models | Arxiv | [Link](https://yinzhicao.org/CIP/DSN-23-CIP.pdf) | | 
| 2023 | **Gaussian Membership Inference Privacy** | White-box | Classification Models | NeurIPS | [Link](https://arxiv.org/abs/2306.07273) | [Link](https://github.com/tleemann/gaussian_mip) |
| 2023 | **TMI! Finetuned Models Leak Private Information from their Pretraining Data** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2306.01181) | |
| 2023 | **SoK: Membership Inference is Harder Than Previously Thought** | Black-box | Classification Models | Arxiv | [Link](https://www.petsymposium.org/2023/files/papers/issue3/popets-2023-0082.pdf) | [Link](https://bitbucket.org/srecgrp/sok-membership-inference-public/src/master/) |
| 2023 | **Re-aligning Shadow Models can Improve White-box Membership Inference Attacks** | White-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2306.05093) | |
| 2023 | **Membership inference attack with relative decision boundary distance** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2306.04109) | |
| 2023 | **Membership Inference Attacks against Language Models via Neighbourhood Comparison** | Black-box | Language Models | ACL | [Link](https://arxiv.org/abs/2305.18462) | [Link](https://github.com/mireshghallah/neighborhood-curvature-mia) & [Link](https://github.com/justusmattern27/neighbour-mia) |
| 2023 | **How to Combine Membership-Inference Attacks on Multiple Updated Machine Learning Models** | Black-box | Classification Models | PoPETs | [Link](https://petsymposium.org/popets/2023/popets-2023-0078.pdf) | [Link](https://github.com/stanleykywu/model-updates) |
| 2023 | **AgrEvader: Poisoning Membership Inference against Byzantine-robust Federated Learning** | White-box | Classification Models | WWW | [Link](https://dl.acm.org/doi/abs/10.1145/3543507.3583542) | [Link](https://github.com/PrivSecML/AgrEvader) |
| 2023 | **Membership Inference Attacks Against Sequential Recommender Systems** | Black-box | Recommender System | WWW | [Link](https://dl.acm.org/doi/abs/10.1145/3543507.3583447) | |
| 2023 | **A Blessing of Dimensionality in Membership Inference through Regularization** | Black-box | Classification Models | AISTATS | [Link](https://proceedings.mlr.press/v206/tan23b.html) | [Link](https://github.com/tanjasper/benign_overparam_MI) |
| 2023 | **Active Membership Inference Attack under Local Differential Privacy in Federated Learning** | White-box | Classification Models | AISTATS | [Link](https://arxiv.org/abs/2302.12685) | [Link](https://github.com/trucndt/ami) | 
| 2023 | **Membership Inference Attacks against Synthetic Data through Overfitting Detection** | Black-box | Generative models | AISTATS | [Link](https://arxiv.org/abs/2302.12580) | [Link](https://github.com/vanderschaarlab/DOMIAS) |
| 2023 | **Students Parrot Their Teachers: Membership Inference on Model Distillation** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2303.03446) | |
| 2023 | **Membership Inference Attacks against Diffusion Models** | White-box; Black-box | Generative Models | Arxiv | [Link](https://arxiv.org/abs/2302.03262) | |
| 2023 | **Interaction-level Membership Inference Attack Against Federated Recommender Systems** | White-box | Recommender System | WWW | [Link](https://arxiv.org/abs/2301.10964) | |
| 2023 | **Are Diffusion Models Vulnerable to Membership Inference Attacks?** | Black-box | Generative Models | Arxiv | [Link](https://arxiv.org/abs/2302.01316) | |
| 2023 | **Accuracy-Privacy Trade-off in Deep Ensemble: A Membership Inference Perspective** | Black-box | Classification Models | S&P | [Link](https://arxiv.org/abs/2105.05381) | [Link](https://github.com/shrezaei/MI-on-EL) |
| 2023 | **Membership Inference of Diffusion Models** | Black-box | Generative Models | Arxiv | [Link](https://arxiv.org/abs/2301.09956) | |
| 2023 | **MiDA: Membership inference attacks against domain adaptation** | Black-box | Classification Models | ISA Transactions | [Link](https://www.sciencedirect.com/science/article/pii/S0019057823000228) | | 

### Attack Papers 2022
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2022 | **On the Discredibility of Membership Inference Attacks** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2212.02701) | |
| 2022 | **Membership Inference Attacks Against Semantic Segmentation Models** | Black-box | Semantic Segmentation Models | Arxiv | [Link](https://arxiv.org/abs/2212.01082) | [Link](https://github.com/ctom2/seg-mia) |
| 2022 | **Similarity Distribution based Membership Inference Attack on Person Re-identification** | Black-box | Person Re-identification | AAAI | [Link](https://arxiv.org/abs/2211.15918) | |
| 2022 | **Amplifying Membership Exposure via Data Poisoning** | Black-box | Classification Models | NeurIPS | [Link](https://arxiv.org/abs/2211.00463) | [Link](https://github.com/yfchen1994/poisoning_membership) |
| 2022 | **Canary in a Coalmine: Better Membership Inference with Ensembled Adversarial Queries** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2210.10750) | [Link](https://github.com/YuxinWenRick/canary-in-a-coalmine) |
| 2022 | **Membership Inference Attacks Against Text-to-image Generation Models** | Black-box | Text-to-image Models | Arxiv | [Link](https://arxiv.org/abs/2210.00968) | |
| 2022 | **Membership Inference Attacks Against Robust Graph Neural Network** | Black-box | Classification Models | CSS | [Link](https://link.springer.com/chapter/10.1007/978-3-031-18067-5_19) | |
| 2022 | **No-Label User-Level Membership Inference for ASR Model Auditing** | Balck-box | Automatic Speech Recognition Model | ESORICS | [Link](https://link.springer.com/chapter/10.1007/978-3-031-17146-8_30) | |
| 2022 | **Membership Inference Attacks and Generalization: A Causal Perspective** | Black-box; White-box | Classification Models | CCS | [Link](https://arxiv.org/abs/2209.08615) | |
| 2022 | **M^4I: Multi-modal Models Membership Inference** | Black-box | Multi-modal Models | NeurIPS | [Link](https://arxiv.org/abs/2209.06997) | [Link](https://github.com/multimodalmi/multimodal-membership-inference) |
| 2022 | **Membership Inference Attacks by Exploiting Loss Trajectory** | Black-box | Classification Models | CCS | [Link](https://arxiv.org/abs/2208.14933) | [Link](https://github.com/DennisLiu2022/Membership-Inference-Attacks-by-Exploiting-Loss-Trajectory) |
| 2022 | **Auditing Membership Leakages of Multi-Exit Networks** | White-box; Black-box | Classification Models | CCS | [Link](https://arxiv.org/abs/2208.11180) | [Link](https://github.com/zhenglisec/Multi-Exit-Privacy) |
| 2022 | **Label-Only Membership Inference Attack against Node-Level Graph Neural Networks** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2207.13766) | |
| 2022 | **Membership-Doctor: Comprehensive Assessment of Membership Inference Against Machine Learning Models** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2208.10445) | |
| 2022 | **On the Privacy Effect of Data Enhancement via the Lens of Memorization** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2208.08270) | |
| 2022 | **Membership Inference Attacks via Adversarial Examples** | White-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2207.13572) | |
| 2022 | **Label-Only Membership Inference Attack against Node-Level Graph Neural Networks** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2207.13766) | |
| 2022 | **Semi-Leak: Membership Inference Attacks Against Semi-supervised Learning** | Black-box | Semi-supervised Learning Models | ECCV | [Link](https://arxiv.org/abs/2207.12535) | [Link](https://github.com/xinleihe/Semi-Leak) |
| 2022 | **Debiasing Learning for Membership Inference Attacks Against Recommender Systems** | Black-box | Recommender System | KDD | [Link](https://arxiv.org/abs/2206.12401) | |
| 2022 | **Membership Inference via Backdooring** | Black-box | Classification Models | IJCAI | [Link](https://arxiv.org/abs/2206.04823) | [Link](https://github.com/hongshenghu/membership-inference-via-backdooring) |
| 2022 | **Membership Inference Attacks Against Machine Learning Models via Prediction Sensitivity** | Black-box | Classification Models | IEEE Trans Dependable Secure Comput | [Link](https://ieeexplore.ieee.org/abstract/document/9793586) | [Link](https://github.com/Wangyiiiiii/Aster)| 
| 2022 | **Subject Membership Inference Attacks in Federated Learning** | White-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2206.03317) | |
| 2022 | **Membership Feature Disentanglement Network** | White-box | Classification Models | ASIA CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3488932.3497772) | |
| 2022 | **Understanding Disparate Effects of Membership Inference Attacks and their Countermeasures** | Black-box | Classification Models | ASIA CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3488932.3501279) | |
| 2022 | **l-Leaks:Membership Inference Attacks with Logits** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2205.06469) | |
| 2022 | **CS-MIA: Membership inference attack based on prediction confidence series in federated learning** | White-box | Classification Models | J. Inf. Secur. Appl | [Link](https://www.sciencedirect.com/science/article/pii/S2214212622000801) | |
| 2022 | **Evaluating Membership Inference Through Adversarial Robustnes** | White-box | Classfication Models | The Computer Journal | [Link](https://arxiv.org/abs/2205.06986) | [Link](https://github.com/plll4zzx/evaluating-membership-inference-through-adversarial-robustness) |
| 2022 | **How to Combine Membership-Inference Attacks on Multiple Updated Models** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2205.06369) | [Link](https://github.com/stanleykywu/model-updates) |
| 2022 | **An Efficient Subpopulation-based Membership Inference Attack** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2203.02080) | |
| 2022 | **Assessing the Impact of Membership Inference Attacks on Classical Machine Learning Algorithms** | Black-box | Classification Models | DRCN | [Link](https://ieeexplore.ieee.org/abstract/document/9758025) | [Link](https://github.com/gonz-mart/Assessing-the-Impact-of-Membership-Inference-Attacks-on-Classical-Machine-Learning-Algorithms) |
| 2022 | **Optimal Membership Inference Bounds for Adaptive Composition of Sampled Gaussian Mechanisms** | White-box; Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2204.06106) | |
| 2022 | **Perfectly Accurate Membership Inference by a Dishonest Central Server in Federated Learning** | White-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2203.16463) | [Link](https://github.com/g-pichler/dishonest_mia) |
| 2022 | **Leveraging Adversarial Examples to Quantify Membership Information Leakage** | White-box; Black-box | Classification Models | CVPR | [Link](https://arxiv.org/abs/2203.09566) | [Link](https://github.com/ganeshdg95/Leveraging-Adversarial-Examples-to-Quantify-Membership-Information-Leakage) |
| 2022 | **Quantifying Privacy Risks of Masked Language Models Using Membership Inference Attacks** | Black-box | Masked Language Models | Arxiv | [Link](https://arxiv.org/abs/2203.03929) | |
| 2022 | **User-Level Membership Inference Attack against Metric Embedding Learning** | Black-box | Metric Embedding Models | Arxiv | [Link](https://arxiv.org/abs/2203.02077) | |
| 2022 | **Label-Only Membership Inference Attacks and Defenses In Semantic Segmentation Models** | Black-box | Segmentation Models | IEEE Trans Dependable Secure Comput | [Link](https://ieeexplore.ieee.org/abstract/document/9723588/keywords#keywords) | |
| 2022 | **Membership Inference Attacks and Defenses in Neural Network Pruning** | Black-box | Classification Models | USENIX Security |[Link](https://arxiv.org/abs/2202.03335) | [Link](https://github.com/machine-learning-security-lab/mia_prune)|
| 2022 | **Parameters or Privacy: A Provable Tradeoff Between Overparameterization and Membership Inference** | Black-box | Regression Models | Arxiv | [Link](https://arxiv.org/abs/2202.01243) | |
| 2022 | **LTU Attacker for Membership Inference** | White-box; Black-box | Classification Models | AAAI Workshop | [Link](https://hal.archives-ouvertes.fr/hal-03522633/) | [Link](https://github.com/JiangnanH/ppml-workshop)|

### Attack Papers 2021
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------| 
| 2021 | **Membership Inference Attacks From First Principles** | White-box; Black-box | Classification Models | S&P | [Link](https://arxiv.org/abs/2112.03570) | [Link](https://github.com/tensorflow/privacy/tree/master/research/mi_lira_2021) |
| 2021 | **SHAPr: An Efficient and Versatile Membership Privacy Risk Metric for Machine Learning**| Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2112.02230) | |
| 2021 | **Enhanced Membership Inference Attacks against Machine Learning Models** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2111.09679) | [Link](https://github.com/privacytrustlab/ml_privacy_meter) |
| 2021 | **Do Not Trust Prediction Scores for Membership Inference Attacks** | Black-box | Classification Models | IJCAI | [Link](https://arxiv.org/abs/2111.09076) | [Link](https://github.com/ml-research/Do-Not-Trust-Prediction-Scores-for-Membership-Inference-Attacks) |
| 2021 | **On the Importance of Difficulty Calibration in Membership Inference Attacks** | White-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2111.08440)| |
| 2021 | **Membership Inference Attacks against GANs by Leveraging Over-representation Regions** | White-box | Generative Models | CCS |[Link](https://dl.acm.org/doi/abs/10.1145/3460120.3485338) | |
| 2021 | **Membership Inference Attacks Against Recommender Systems** | Black-box | Recommender Systems | CCS | [Link](https://arxiv.org/abs/2109.08045) | [Link](https://github.com/minxingzhang/MIARS) |
| 2021 | **Source Inference Attacks in Federated Learning** | Black-box | Classifcation Models | ICDM | [Link](https://arxiv.org/abs/2109.05659) | [Link](https://github.com/HongshengHu/source-inference-FL) |
| 2021 | **Adapting Membership Inference Attacks to GNN for Graph Classification: Approaches and Implications** | Black-box | Classification Models | ICDM | [Link](https://arxiv.org/abs/2110.08760) | [Link](https://github.com/TrustworthyGNN/MIA-GNN/) |
| 2021 | **On The Vulnerability of Recurrent Neural Networks to Membership Inference Attacks**| Black-box | Text Generation Models | Arxiv | [Link](https://arxiv.org/abs/2110.03054) | [Link](https://github.com/yunhaoyang234/Membership-Attack-Privacy-Preserving) |
| 2021 | **On the Difficulty of Membership Inference Attacks** | White-box | Classification Models | CVPR | [Link](https://openaccess.thecvf.com/content/CVPR2021/html/Rezaei_On_the_Difficulty_of_Membership_Inference_Attacks_CVPR_2021_paper.html) | [Link](https://github.com/shrezaei/MI-Attack) |
| 2021 | **Quantifying Privacy Leakage in Graph Embedding** | White-box; Black-box | Graph Embedding Models | NeurIPS Workshop |[Link](https://arxiv.org/abs/2010.00906) | [Link](https://github.com/vasishtduddu/GraphLeaks)|
| 2021 | **Label-only membership inference attacks** | Black-box | Classification Models | ICML | [Link](http://proceedings.mlr.press/v139/choquette-choo21a.html) | [Link](https://github.com/cchoquette/membership-inference) |
| 2021 | **On the Privacy Risks of Model Explanations** | Black-box | Classification Models | AIES | [Link](https://dl.acm.org/doi/abs/10.1145/3461702.3462533?casa_token=N1y7W8SoFxQAAAAA:FDsVwyOBIS98rwYWsUpE2dlcmDaJXiKJnJOV1aAkiy1iE4K7Xn8cO184o5hAfQctNbxEpX2WM6XIwA) | |
| 2021 | **Systematic evaluation of privacy risks of machine learning models** | White-box; Black-box | Classification Models | USENIX Security | [Link](https://www.usenix.org/conference/usenixsecurity21/presentation/song) | [Link](https://github.com/inspire-group/membership-inference-evaluation)|
| 2021 | **Practical blind membership inference attack via differential comparisons** | Black-box | Classification Models | NDSS |[Link](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_5C-2_24293_paper.pdf) | [Link](https://github.com/hyhmia/BlindMI) |
| 2021 | **On the (In) Feasibility of Attribute Inference Attacks on Machine Learning Models** | White-box; Black-box | Classification Models | EuroS&P | [Link](https://arxiv.org/abs/2103.07101) | |
| 2021 | **Bounding Information Leakage in Machine Learning** | White-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2105.03875) | |
| 2021 | **How Does Data Augmentation Affect Privacy in Machine Learning?** | Black-box | Classification Models | AAAI | [Link](https://www.aaai.org/AAAI21Papers/AAAI-353.YuD.pdf) | [Link](https://github.com/dayu11/MI_with_DA)|
| 2021 | **Node-Level Membership Inference Attacks Against Graph Neural Networks** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2102.05429) | |
| 2021 | **The Audio Auditor: User-Level Membership Inference in Internet of Things Voice Services** | Black-box | Automatic Speech Recognition Model | PoPETs | [Link](https://researchonline.jcu.edu.au/64660/) | |
| 2021 | **Reconstruction-Based Membership Inference Attacks are Easier on Difficult Problems** | Black-box | Image Translation Models; Image Segmentation Models | ICCV | [Link](https://arxiv.org/abs/2102.07762) | [Link](https://github.com/avitalsh/reconst_based_MIA)|
| 2021 | **This Person (Probably) Exists. Identity Membership Attacks Against GAN Generated Faces** | Black-box | Generative Models | Arxiv | [link](https://arxiv.org/abs/2107.06018) | |
| 2021 | **Membership Inference Attack Susceptibility of Clinical Language Models** | White-box; Black-box | Clinical Language Models | Arxiv | [Link](https://arxiv.org/abs/2104.08305) | |
| 2021 | **Killing four birds with one Gaussian process: the relation between different test-time attacks** | Black-box | Classification Models | ICPR | [Link](https://ieeexplore.ieee.org/abstract/document/9413290?casa_token=RxUKWNuCdsAAAAAA:eg4blFMRYcf9sWqjagDPFqunYNKjN1cwASboegqbvOJyC8ERxy8WOAH0MNvCA5IhAJfJUGnS8g) | |
| 2021 | **Evaluating the Vulnerability of End-to-End Automatic Speech Recognition Models To Membership Inference Attacks** | Black-box | Speech Recognition Models | Interspeech | [Link](https://assets.amazon.science/48/f3/f8d1b62c4bf8bd63cf7a069eff24/evaluating-the-vulnerability-of-end-to-end-automation-speech-recognition-models-to-membership-inference-attacks.pdf) | |
| 2021 | **Membership Inference Attacks on Knowledge Graphs** | Black-box | Knowledge Graph Embedding Models | Arxiv | [Link](https://arxiv.org/abs/2104.08273) | |
| 2021 | **Membership Leakage in Label-Only Exposures** | Black-box | Classification Models | CCS | [Link](https://arxiv.org/abs/2007.15528) | |
| 2021 | **Membership inference attack on graph neural networks** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2101.06570) | |
| 2021 | **Membership Inference Attacks on Deep Regression Models for Neuroimaging** | Black-box | Regression Models | MIDL | [Link](https://arxiv.org/abs/2105.02866) | |
| 2021 | **Membership Inference Attacks on Lottery Ticket Networks** | Black-box | Classification Models | ICML Workshop | [Link](https://openreview.net/forum?id=4lyXal2ZWB3) | |
| 2021 | **Membership Inference on Word Embedding and Beyond** | Black-box | Word Embedding Models | Arxiv | [Link](https://arxiv.org/abs/2106.11384) | | 
| 2021 | **EncoderMI: Membership Inference against Pre-trained Encoders in Contrastive Learning** | Black-box | Image Encoder Models | CCS | [Link](https://arxiv.org/abs/2108.11023) | |
 
### Attack Papers 2020 [[Back to Top](#membership-inference-attacks-and-defenses-on-machine-learning-models-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2020 | **GECKO: Reconciling Privacy, Accuracy and Efficiency in Embedded Deep Learning** | Black-box | Classification Models | NeurIPS Workshop | [Link](https://arxiv.org/abs/2010.00912) | |
| 2020 | **Gan-leaks: A taxonomy of membership inference attacks against generative models** | White-box; Black-box | Generative Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3372297.3417238?casa_token=5npei5-D6vUAAAAA:aXjBRatnngBs0Hyd01LfDQGc60aL_XnEc93SJPPjsiWPLQzzXc4U6wRQFNmYMtZv6Y_Zgz9EaSAomQ) | [Link](https://github.com/DingfanChen/GAN-Leaks) |
| 2020 | **Stolen Memories: Leveraging Model Memorization for Calibrated White-Box Membership Inference** | White-box | Classification Models | USENIX Security | [Link](https://www.usenix.org/conference/usenixsecurity20/presentation/leino) | |
| 2020 | **Information leakage in embedding models** | Black-box | Text Embedding Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3372297.3417270?casa_token=qSdKKvBuMlsAAAAA:pvtisX5ke3aHgg2xt3AuATThaogPwPUZes1s2Td2um1Zn3ZxXR5XsjNcPObf4E6gBJHkl_0zXn1qVw) | |
| 2020 | **When machine unlearning jeopardizes privacy** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2005.02205) | |
| 2020 | **Revisiting membership inference under realistic assumptions** | Black-box | Classification Models | PoPETs | [Link](https://arxiv.org/abs/2005.10881) | [Link](https://github.com/bargavj/EvaluatingDPML)|
| 2020 | **Membership inference attacks on sequence-to-sequence models: Is my data in your machine translation system?** | Black-box | Text Generation Models | TACL | [Link](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00299/43536/Membership-Inference-Attacks-on-Sequence-to) | [Link](https://github.com/sorami/tacl-membership) |
| 2020 | **Segmentations-leak: Membership inference attacks and defenses in semantic image segmentation** | Black-box | Image Segmentation Models | ECCV| [Link](https://link.springer.com/chapter/10.1007/978-3-030-58592-1_31) | [Link](https://github.com/SSAW14/segmentation_membership_inference)|
| 2020 | **Performing co-membership attacks against deep generative models** | White-box | Generative Models |ICDM | [Link](https://ieeexplore.ieee.org/abstract/document/8970995?casa_token=_QVk9Y51OCYAAAAA:rZ2t3JfMxXDs-CvoR-Uvh7a8oLGHDRUXruJBWjVA0_qD7B5piJBBhuiwaVEAnFWHQspmTxrFwA) | |
| 2020 | **On the privacy risks of algorithmic fairness** | Black-box | Classification Models | EuroS&P | [Link](https://arxiv.org/abs/2011.03731) | |
| 2020 | **A Comprehensive Analysis of Information Leakage in Deep Transfer Learning** | Black-box | Classification Models | Arxiv| [Link](https://arxiv.org/abs/2009.01989) | |
| 2020 | **Gan enhanced membership inference: A passive local attack in federated learning** | White-box | Classification Models | ICC |[Link](https://ieeexplore.ieee.org/abstract/document/9148790?casa_token=TwA2PQfrAooAAAAA:TKJlyEVcg4h_Dcq29OLJz_HU29YUFwmtzAnhFCABIv7gpNEvQBbzIlYjjiH37zjILdNO5SoqqA) | |
| 2020 | **Privacy analysis of deep learning in the wild: Membership inference attacks against transfer learning** | Black-box | Classification Models | Arxiv| [Link](https://arxiv.org/abs/2009.04872) | |
| 2020 | **Data and model dependencies of membership inference attack** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2002.06856) | |
| 2020 | **A Pragmatic Approach to Membership Inferences on Machine Learning Models** | Black-box | Classification Models | EuroS&P | [Link](https://ieeexplore.ieee.org/abstract/document/9230385?casa_token=rReHm3AMDfwAAAAA:tbLfZUjLhEO368PbybwT6RVNgzAwFD9t0_Xhy9KnrZ9eX9dxJq9IunO6GH6Wm7fk7OPHfHF0AQ) | |
| 2020 | **Quantifying Membership Inference Vulnerability via Generalization Gap and Other Model Metrics** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2009.05669) | 
| 2020 | **Investigating the Impact of Pre-trained Word Embeddings on Memorization in Neural Networks** | Black-box | Word Embedding Models | TSD | [Link](https://link.springer.com/chapter/10.1007/978-3-030-58323-1_30) | |
| 2020 | **Beyond Model-Level Membership Privacy Leakage: an Adversarial Approach in Federated Learning** | White-box | Classification Models | ICCCN | [Link](https://ieeexplore.ieee.org/abstract/document/9209744?casa_token=Zd05FWW-sLQAAAAA:wP4jc9aCILSpCREa3E4Zo8zCuWetxaZrW78Yi2Q8ZI3Ztr9rer70G3bFa_sNeuHo7O8YyZ4nxQ) | |
| 2020 | **Practical Membership Inference Attack Against Collaborative Inference in Industrial IoT** | White-box | Classification Models | IEEE Trans. Industr. Inform. | [Link](https://ieeexplore.ieee.org/document/9302683?denied=) | |



### Attack Papers 2019 [[Back to Top](#membership-inference-attacks-and-defenses-on-machine-learning-models-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2019 | **Exploiting unintended feature leakage in collaborative learning**| White-box | Classification Models | S&P | [Link](https://ieeexplore.ieee.org/abstract/document/8835269?casa_token=eYvm-5MHJ5EAAAAA:jJfXg2OLofzNw4ZZgRxuoMcEu6flf1epeMeRKZkNln9W99yar_N2WFawsaohM2XRicRA0vnujw) | [Link](https://github.com/csong27/property-inference-collaborative-ml)|
| 2019 | **Comprehensive Privacy Analysis of Deep Learning: Passive and Active White-box Inference Attacks against Centralized and Federated Learning** | Black-box; White-box | Classification Models | S&P | [link](https://ieeexplore.ieee.org/abstract/document/8835245?casa_token=2VTmu69Ze5YAAAAA:cNBfmpyOtRzlcjC17vP_fvqWINaGcGCAA1BGWxfBzEveksH6GRAMfrmGSH7ULi4Wf_G0NzJNnw) | [Link](https://github.com/privacytrustlab/ml_privacy_meter) |
 |2019 | **ML-Leaks: Model and Data Independent Membership Inference Attacks and Defenses on Machine Learning Models** | Black-box | Classification Models | NDSS | [Link](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_03A-1_Salem_paper.pdf) | [Link](https://github.com/AhmedSalem2/ML-Leaks) |
| 2019 | **LOGAN: Membership Inference Attacks Against Generative Models** | Black-box; White-box | Generative Models | PoPETs | [Link](https://arxiv.org/abs/1705.07663) | [Link](https://github.com/jhayes14/gen_mem_inf)|
| 2019 | **White-box vs Black-box: Bayes Optimal Strategies for Membership Inference** | Black-box | Classification Models | ICML | [Link](http://proceedings.mlr.press/v97/sablayrolles19a.html) | |
| 2019 | **Auditing data provenance in text-generation models** | Black-box | Text Generation Models | KDD | [Link](https://dl.acm.org/doi/abs/10.1145/3292500.3330885) | [Link](https://github.com/csong27/auditing-text-generation) |
| 2019 | **Socinf: Membership inference attacks on social media health data with machine learning** | Black-box | Classification Models | IEEE Trans. Comput. Soc. Syst. | [Link](https://ieeexplore.ieee.org/abstract/document/8728167?casa_token=4RgQ9tuXHiYAAAAA:RpcPcXmjOfNGr5joJQN8J0NAPsan_1aXygP4SR21qXWJuDbAzbVj-YVU6ASV_zCzPqK4fzWBCQ) | |
| 2019 | **Monte Carlo and Reconstruction Membership Inference Attacks against Generative Models.** | White-box; Black-box | Generative Models | PoPETs | [Link](https://petsymposium.org/2019/files/papers/issue4/popets-2019-0067.pdf) | [Link](https://github.com/SAP-samples/security-research-membership-inference-against-generative-networks) |
| 2019 | **Disparate Vulnerability: on the Unfairness of Privacy Attacks Against Machine Learning** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/1906.00389) | |
| 2019 | **Demystifying the membership inference attack** | Black-box | Classification Models | CMI | [Link](https://ieeexplore.ieee.org/abstract/document/8962136) | |
| 2019 | **Differential Privacy Defenses and Sampling Attacks for Membership Inference** | Black-box | Classification Models | NeurIPS Workshop | [Link](https://arxiv.org/abs/2009.00395) | |
| 2019 | **Privacy Risks of Securing Machine Learning Models against Adversarial Examples** | Black-box | Classification Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3319535.3354211) | [Link](https://github.com/inspire-group/privacy-vs-robustness) |
| 2019 | **Membership Inference Attacks against Adversarially Robust Deep Learning Models** | Black-box | Classification Models | S&P Workshop | [Link](https://ieeexplore.ieee.org/abstract/document/8844607?casa_token=Afs5maC5j74AAAAA:JQ6Jy-Gq3N4XFZqpX35qGzbjTx5e1p9tkIVoFYc4QDdIpIsvkHl__rsawNYpQ7K5ZvyBORo86A) | |
| 2019 | **Demystifying Membership Inference Attacks in Machine Learning as a Service** | Black-box | Classification Models | IEEE Trans. Serv. Comput. | [Link](https://ieeexplore.ieee.org/abstract/document/8634878?casa_token=MC0Uw6Ni-HgAAAAA:zJ32LbWViM5adpNr6sh8tNMZI-Or50HI-QawC1hyMTjPiDxDe8kAAbtdBC0saPOz88Y0aqkLNw) |  |


 
### Attack Papers 2018 [[Back to Top](#membership-inference-attacks-and-defenses-on-machine-learning-models-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2018 | **Privacy Risk in Machine Learning: Analyzing the Connection to Overfitting** | Black-box | Classification Models | CSF | [Link](https://ieeexplore.ieee.org/abstract/document/8429311?casa_token=NQu6-mEb9JMAAAAA:LTU3BPSYc8ALHF89ifdWs1zl__ABgBzIr44xFoN2t8HwjTb5vm20S00VeH9JSmaBU-miBt5Ucg) | [Link](https://github.com/samuel-yeom/ml-privacy-csf18) |
| 2018 | **Understanding membership inferences on well-generalized learning models** | Black-box | Classification Models | Arxiv | [link](https://arxiv.org/abs/1802.04889) | |

### Attack Papers 2017 [[Back to Top](#membership-inference-attacks-and-defenses-on-machine-learning-models-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2017  | **Membership inference attacks against machine learning models** | Black-box | Classification Models | S&P | [link](https://ieeexplore.ieee.org/abstract/document/7958568?casa_token=YOmVjvUemFUAAAAA:gGeuARxnjASvh9gnPkijkLD7d7HD1VV1JZkooXtS6tb6LGfKqHgBbyoaI-0-X7kFeP-3bjUR2A) | [Link](https://github.com/csong27/membership-inference) |


## Membership Inference Defense
### Defense Papers 2023 [[Back to Top](#membership-inference-attacks-and-defenses-on-machine-learning-models-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2023 | **Mitigating Membership Inference Attacks via Weighted Smoothing** | Black-box | Classification Models | ACSAC | [Link](https://dl.acm.org/doi/abs/10.1145/3627106.3627189) | [Link](https://github.com/BennyTMT/weighted-smoothing) |
| 2023 | **MIST: Defending Against Membership Inference Attacks Through Membership-Invariant Subspace Training** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2311.00919) | |
| 2023 | **Overconfidence is a Dangerous Thing: Mitigating Membership Inference Attacks by Enforcing Less Confident Prediction** | Black-box | Classification Models | NDSS | [Link](https://arxiv.org/abs/2307.01610) | [Link](https://github.com/DependableSystemsLab/MIA_defense_HAMP) |
| 2023 | **LoDen: Making Every Client in Federated Learning a Defender Against the Poisoning Membership Inference Attacks** | White-box; Black-box | Classification Models | Asia CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3579856.3590334) | [Link](https://github.com/UQ-Trust-Lab/LoDen) |

### Defense Papers 2022 [[Back to Top](#membership-inference-attacks-and-defenses-on-machine-learning-models-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2022 | **Defense against membership inference attack in graph neural networks through graph perturbation** | White-box | Graph Embedding Models | Int. J. Inf. Secur. | [Link](https://link.springer.com/article/10.1007/s10207-022-00646-y) | |
| 2022 | **Provable Membership Inference Privacy** | White-box; Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2211.06582) | |
| 2022 | **Repeated Knowledge Distillation with Confidence Masking to Mitigate Membership Inference Attacks** | White-box; Black-box | Classification Models | AISec | [Link](https://dl.acm.org/doi/10.1145/3560830.3563721) | |
| 2022 | **NeuGuard: Lightweight Neuron-Guided Defense against Membership Inference Attacks** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2206.05565) | |
| 2022 | **Defending against Membership Inference Attacks with High Utility by GAN** | White-box; Black-box | Classification Models | TDSC | [Link](https://ieeexplore.ieee.org/abstract/document/9773984) | | 
| 2022 | **RelaxLoss: Defending Membership Inference Attacks without Losing Utility** | White-box; Black-box | Classification Models | ICLR | [Link](https://openreview.net/forum?id=FEDfGWVZYIn) | [Link](https://github.com/DingfanChen/RelaxLoss) |
| 2022 | **Assessing Differentially Private Variational Autoencoders under Membership Inference** | Black-box | Generative Models | Arxiv | [Link](https://arxiv.org/abs/2204.07877) | [Link](https://github.com/SAP-samples/security-research-vae-dp-mia) |
| 2022 | **Membership Privacy Protection for Image Translation Models via Adversarial Knowledge Distillation** | Black-box | Image Translation Models | Arxiv | [Link](https://arxiv.org/abs/2203.05212) | |
| 2022 | **MIAShield: Defending Membership Inference Attacks via Preemptive Exclusion of Members** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2203.00915) | |
| 2022 | **Privacy-preserving Generative Framework Against Membership Inference Attacks** | White-box; Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2202.05469) | |

### Defense Papers 2021 [[Back to Top](#membership-inference-attacks-and-defenses-on-machine-learning-models-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2021 | **Enhanced Mixup Training: a Defense Method Against Membership Inference Attack** | Black-box | Classification Models | ISPEC | [Link](https://link.springer.com/chapter/10.1007/978-3-030-93206-0_3) | |
| 2021 | **Mitigating Membership Inference Attacks by Self-Distillation Through a Novel Ensemble Architecture** | White-box; Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2110.08324) | |
| 2021 | **On the privacy-utility trade-off in differentially private hierarchical text classification** | White-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2103.02895) | |
| 2021 | **MLCapsule: Guarded Offline Deployment of Machine Learning as a Service** | Black-box | Classification Models | CVPR | [Link](https://openaccess.thecvf.com/content/CVPR2021W/TCV/html/Hanzlik_MLCapsule_Guarded_Offline_Deployment_of_Machine_Learning_as_a_Service_CVPRW_2021_paper.html) | |
| 2021 | **Comparing Local and Central Differential Privacy Using Membership Inference Attacks** | White-box | Classification Models | DBSec | [Link](https://link.springer.com/chapter/10.1007/978-3-030-81242-3_2) | [Link](https://github.com/SAP-samples/security-research-membership-inference-and-differential-privacy)|
| 2021 | **Adversary Instantiation: Lower Bounds for Differentially Private Machine Learning** | White-box | Classification Models | S&P | [Link](https://conferences.computer.org/sp/pdfs/sp/2021/893400a866.pdf) | |
| 2021 | **When Does Data Augmentation Help With Membership Inference Attacks?** | Black-box | Classification Models | ICML | [Link](http://proceedings.mlr.press/v139/kaya21a.html) | [Link](https://github.com/yigitcankaya/augmentation_mia) |
| 2021 | **Against Membership Inference Attack: Pruning is All You Need** | Black-box | Classification Models | IJCAI | [Link](https://www.ijcai.org/proceedings/2021/0432.pdf) | |
| 2021 | **Membership Privacy for Machine Learning Models Through Knowledge Transfer** | White-box; Black-box | Classification Models | AAAI | [Link](https://www.aaai.org/AAAI21Papers/AAAI-8428.ShejwalkarV.pdf) | |
| 2021 | **Quantifying Membership Privacy via Information Leakage** | Black-box | Classification Models | IEEE Trans. Inf. Forensics Secur. | [Link](https://ieeexplore.ieee.org/abstract/document/9406982) | |
| 2021 | **Membership Inference Attacks and Defenses in Classification Models** | Black-box | Classification Models | CODASPY | [Link](https://dl.acm.org/doi/abs/10.1145/3422337.3447836?casa_token=OgVGtSGexk4AAAAA:OL1PF_yI4hvGMZRuAg4AmHdGsy8kNbvNDMDCK4Bf-42sGR4PJ0YYdBKwMKaAmUbplZecpyivNS0OmA) | |
| 2021 | **Digestive Neural Networks: A Novel Defense Strategy Against Inference Attacks in Federated Learning** | White-box | Classification Models |  Computers & Security | [Link](https://www.sciencedirect.com/science/article/pii/S0167404821002029) | |
| 2021 | **Resisting Membership Inference Attacks through Knowledge Distillation** | Black-box | Classification Models | Neurocomputing | [Link](https://www.sciencedirect.com/science/article/pii/S0925231221006329?casa_token=c1IzeuYRtpUAAAAA:0wsZqqvYC_MDDxxmJiX6ukGXUz1ZWeXrrs3ZM7HNS22peJvUcI-ED4PuN8RzYTJyMzsTIH-dIvY) | |
| 2021 | **privGAN: Protecting GANs from membership inference attacks at low cost to utility** | White-box | Generative Models | PoPETs| [Link](https://petsymposium.org/2021/files/papers/issue3/popets-2021-0041.pdf) | |
| 2021 | **Generating Private Data Surrogates for Vision Related Tasks** | White-box | Generative Models | ICPR | [Link](https://ieeexplore.ieee.org/abstract/document/9413067?casa_token=-TsmURst7cIAAAAA:7JmyRDPMEqGQumYXCRMMDnqsfw_bQrIbl8Om7GvjU07Py58rR7exbhl6kX3ChllJaLp5hrMXXg) | |
| 2021 | **Membership Inference Attack with Multi-Grade Service Models in Edge Intelligence** | Black-box | Classification Models | IEEE Network | [Link](https://ieeexplore.ieee.org/abstract/document/9355044?casa_token=kRgvvXyazeEAAAAA:op3d_NR3gAdao2j_6pThCiCJYF8YzuAY3wYYPgKfsTRYNZajUjHiF76hiaeBcaqynjDg723Wgg) | |
| 2021 | **PAR-GAN: Improving the Generalization of Generative Adversarial Networks Against Membership Inference Attacks** | White-box | Generative Models | KDD | [Link](https://dl.acm.org/doi/abs/10.1145/3447548.3467445?casa_token=nrRQY7saHGMAAAAA:Hm5z6sD94Titemm-rXcuZ9SWCvxlmuYxYIzMzw9szKC5zo2ZKf5X_RJ0mK5qMfetLCdPG6LzaAnOTQ) | [Link](https://github.com/shilab/PAR-GAN)|
| 2021 | **Defending Medical Image Diagnostics against Privacy Attacks using Generative Methods: Application to Retinal Diagnostics** | Black-box | Classification Models | MICCAI Workshop | [Link](https://arxiv.org/abs/2103.03078) | |
| 2021 | **Defending Privacy Against More Knowledgeable Membership Inference Attackers** | White-box; Black-box | Classification Models | KDD | [Link](https://dl.acm.org/doi/abs/10.1145/3447548.3467444) | [Link](https://github.com/yyinfaramita/Crystal) |
   
### Defense Papers 2020 [[Back to Top](#membership-inference-attacks-and-defenses-on-machine-learning-models-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2020 | **Privacy for All: Demystify Vulnerability Disparity of Differential Privacy against Membership Inference Attack** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2001.08855) | |
| 2020 | **Privacy for All: Demystify Vulnerability Disparity of Differential Privacy against Membership Inference Attack**  | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2001.08855) | |
| 2020 | **Differential Privacy Protection Against Membership Inference Attack on Machine Learning for Genomic Data** | Black-box | Classification Models | Biocomputing | [Link](https://www.worldscientific.com/doi/abs/10.1142/9789811232701_0003) | |
| 2020 | **A Secure Federated Learning Framework for 5G Networks** | White-box | Classification Models | IEEE Wireless Communications | [Link](https://ieeexplore.ieee.org/abstract/document/9170265?casa_token=mQO49_zNRZ8AAAAA:WY1Jk5fA6olK16zTOpOkE8pHUkGWMA7wvStZIAUwYTHzZ0hSeFUW_-xY2SwNl7usgf4xFQY7OQ) | |
| 2020 | **Auditing Differentially Private Machine Learning: How Private is Private SGD?** | Black-box | Classification Models | NeurIPS | [Link](https://proceedings.neurips.cc/paper/2020/hash/fc4ddc15f9f4b4b06ef7844d6bb53abf-Abstract.html) | [Link](https://github.com/jagielski/auditing-dpsgd) |
| 2020 | **Toward Robustness and Privacy in Federated Learning: Experimenting with Local and Central Differential Privacy** | White-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2009.03561) | |
| 2020 | **Defending Model Inversion and Membership Inference Attacks via Prediction Purification** | Black-box | Classification | Arxiv | [Link](https://arxiv.org/abs/2005.03915) | | 
| 2020 | **Alleviating Privacy Attacks via Causal Learning** | Black-box | Classification Models | ICML | [Link](http://proceedings.mlr.press/v119/tople20a.html) | [Link](https://github.com/microsoft/robustdg) |
| 2020 | **On the Effectiveness of Regularization Against Membership Inference Attacks** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2006.05336) | |
| 2020 | **Characterizing Membership Privacy in Stochastic Gradient Langevin Dynamics** | Black-box | Classification Models | AAAI | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/6107) | |
| 2020 | **Differentially Private Learning Does Not Bound Membership Inference** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2010.12112) | |
| 2020 | **Privacy-Preserving in Defending against Membership Inference Attacks** | Black-box | Classification Models | PPMLP | [Link](https://dl.acm.org/doi/abs/10.1145/3411501.3419428?casa_token=ndUU_v6d6HwAAAAA:-dFHWyvi34EVE97Dl8J-k-hoTwqTu6Z8I6Lz5IBYpMss_ogfP0OeP8-fLRxQRhfdy6B0AluwZ_XlPw) | |


### Defense Papers 2019 [[Back to Top](#membership-inference-attacks-and-defenses-on-machine-learning-models-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2019 | **Evaluating Differentially Private Machine Learning in Practice** | Black-box | Classification Models | USENIX Security | [Link](https://www.usenix.org/conference/usenixsecurity19/presentation/jayaraman) | [Link](https://github.com/bargavj/EvaluatingDPML) |
| 2019 | **MemGuard: Defending against Black-Box Membership Inference Attacks via Adversarial Examples** | Black-box | Classification Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3319535.3363201) | [Link](https://github.com/jjy1994/MemGuard) |
| 2019 | **Generalization in Generative Adversarial Networks: A Novel Perspective from Privacy Protection** | White-box; Black-box | Generative Models | NeurIPS | [Link](https://papers.nips.cc/paper/2019/hash/47d1e990583c9c67424d369f3414728e-Abstract.html) | |
| 2019 | **Cronus: Robust and Heterogeneous Collaborative Learning with Black-Box Knowledge Transfer** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/1912.11279) | |
| 2019 | **ML Defense: Against Prediction API Threats in Cloud-Based Machine Learning Service** | Black-box | Classification Models | IWQoS | [Link](https://dl.acm.org/doi/abs/10.1145/3326285.3329042) |  |
| 2019 | **Effects of Differential Privacy and Data Skewness on Membership Inference Vulnerability** | Black-box | Classification Models | TPS-ISA | [Link](https://ieeexplore.ieee.org/document/9014384) | | 
| 2019 | **Generating Artificial Data for Private Deep Learning** | Black-box | Generative Models | PAL | [Link](https://infoscience.epfl.ch/record/269025) | |



### Defense Papers 2018 [[Back to Top](#membership-inference-attacks-and-defenses-on-machine-learning-models-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2018 | **Machine Learning with Membership Privacy using Adversarial Regularization** | Black-box | Classification Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3243734.3243855) | [Link](https://github.com/SPIN-UMass/ML-Privacy-Regulization) |
| 2018 | **Privacy-preserving Machine Learning through Data Obfuscation** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/1807.01860) | |
| 2018 | **Differentially Private Data Generative Models** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/1812.02274) | |
| 2018 | **Membership Inference Attack against Differentially Private Deep Learning Model** | Black-box | Classification Models | Transactions on Data Privacy | [Link](http://www.tdp.cat/issues16/tdp.a289a17.pdf) | |


