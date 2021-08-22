# Membership Inference Attacks and Defenses on Machine Learning Models Literature
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated list of membership inference attacks and defenses papers on machine learning models.

Paper are sorted by their released dates in descending order.

This repository serves as a complement of the survey below.

[**Membership Inference Attacks on Machine Learning: A Survey**] (https://arxiv.org/abs/2103.07853)

````bibtex
@article{hu2021membership,
  title={Membership Inference Attacks on Machine Learning: A Survey},
  author={Hu, Hongsheng and Salcic, Zoran and Dobbie, Gillian and Zhang, Xuyun},
  journal={arXiv preprint arXiv:2103.07853},
  year={2021}
}
````

If you feel this repo is helpful, please cite the survey above.

## Membership Inference Attack

### Attack papers 2021
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2021 | **On the Difficulty of Membership Inference Attacks** | White-box | Classification Models | CVPR | [Link](https://openaccess.thecvf.com/content/CVPR2021/html/Rezaei_On_the_Difficulty_of_Membership_Inference_Attacks_CVPR_2021_paper.html) | [Link](https://github.com/shrezaei/MI-Attack) |
| 2021 | **Quantifying Privacy Leakage in Graph Embedding** | White-box; Black-box | Graph Embedding Models | NeurIPS Workshop |[Link](https://arxiv.org/abs/2010.00906) | [Link](https://github.com/vasishtduddu/GraphLeaks)|
| 2021 | **Label-only membership inference attacks** | Black-box | Classification Models | ICML | [Link](http://proceedings.mlr.press/v139/choquette-choo21a.html) | [Link](https://github.com/cchoquette/membership-inference) |
| 2021 | **On the Privacy Risks of Model Explanations** | Black-box | Classification Models | AIES | [Link](https://dl.acm.org/doi/abs/10.1145/3461702.3462533?casa_token=N1y7W8SoFxQAAAAA:FDsVwyOBIS98rwYWsUpE2dlcmDaJXiKJnJOV1aAkiy1iE4K7Xn8cO184o5hAfQctNbxEpX2WM6XIwA) | |
| 2021 | **Systematic evaluation of privacy risks of machine learning models** | White-box; Black-box | Classification Models | USENIX Security | [Link](https://www.usenix.org/conference/usenixsecurity21/presentation/song) | [Link](https://github.com/inspire-group/membership-inference-evaluation)|


 

### Attack papers 2020
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2020 | **Quantifying Privacy Leakage in Graph Embedding** | White-box; Black-box | Graph Embedding Models | NeurIPS Workshop |[Link](https://arxiv.org/abs/2010.00906) | [Link](https://github.com/vasishtduddu/GraphLeaks)|
| 2020 | **Gan-leaks: A taxonomy of membership inference attacks against generative models** | White-box; Black-box | Generative Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3372297.3417238?casa_token=5npei5-D6vUAAAAA:aXjBRatnngBs0Hyd01LfDQGc60aL_XnEc93SJPPjsiWPLQzzXc4U6wRQFNmYMtZv6Y_Zgz9EaSAomQ) | [Link](https://github.com/DingfanChen/GAN-Leaks) |
| 2020 | **Stolen Memories: Leveraging Model Memorization for Calibrated White-Box Membership Inference** | White-box | Classification Models | USENIX Security | [Link](https://www.usenix.org/conference/usenixsecurity20/presentation/leino) | |
| 2020 | **Information leakage in embedding models** | Black-box | Text Embedding Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3372297.3417270?casa_token=qSdKKvBuMlsAAAAA:pvtisX5ke3aHgg2xt3AuATThaogPwPUZes1s2Td2um1Zn3ZxXR5XsjNcPObf4E6gBJHkl_0zXn1qVw) | |
| 2020 | **When machine unlearning jeopardizes privacy** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2005.02205) | |
| 2020 | **Revisiting membership inference under realistic assumptions** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2005.10881) | [Link](https://github.com/bargavj/EvaluatingDPML)|
| 2020 | **Membership inference attacks on sequence-to-sequence models: Is my data in your machine translation system?** | Black-box | Text Generation Models | TACL | [Link](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00299/43536/Membership-Inference-Attacks-on-Sequence-to) | [Link](https://github.com/sorami/tacl-membership) |




### Attack papers 2019
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


### Attack papers 2018
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2018 | **Privacy Risk in Machine Learning: Analyzing the Connection to Overfitting** | Black-box | Classification Models | CSF | [Link](https://ieeexplore.ieee.org/abstract/document/8429311?casa_token=NQu6-mEb9JMAAAAA:LTU3BPSYc8ALHF89ifdWs1zl__ABgBzIr44xFoN2t8HwjTb5vm20S00VeH9JSmaBU-miBt5Ucg) | [Link](https://github.com/samuel-yeom/ml-privacy-csf18) |
| 2018 | **Understanding membership inferences on well-generalized learning models** | Black-box | Classification Models | Arxiv | [link](https://arxiv.org/abs/1802.04889) | |

### Attack papers 2017
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2017  | **Membership inference attacks against machine learning models** | Black-box | Classification Models | S&P | [link](https://ieeexplore.ieee.org/abstract/document/7958568?casa_token=YOmVjvUemFUAAAAA:gGeuARxnjASvh9gnPkijkLD7d7HD1VV1JZkooXtS6tb6LGfKqHgBbyoaI-0-X7kFeP-3bjUR2A) | [Link](https://github.com/csong27/membership-inference) |
