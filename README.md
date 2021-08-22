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


### Attack papers 2020
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2020 | **Quantifying Privacy Leakage in Graph Embedding** | White-box; Black-box | Graph Embedding Models | NeurIPS Workshop |[Link](https://arxiv.org/abs/2010.00906) | [Link](https://github.com/vasishtduddu/GraphLeaks)|

### Attack papers 2019
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
|2019 | **Exploiting unintended feature leakage in collaborative learning**| White-box | Classification Models | S&P | [Link](https://ieeexplore.ieee.org/abstract/document/8835269?casa_token=eYvm-5MHJ5EAAAAA:jJfXg2OLofzNw4ZZgRxuoMcEu6flf1epeMeRKZkNln9W99yar_N2WFawsaohM2XRicRA0vnujw) | [Link](https://github.com/csong27/property-inference-collaborative-ml)|
| 2019 | **Comprehensive Privacy Analysis of Deep Learning: Passive and Active White-box Inference Attacks against Centralized and Federated Learning** | Black-box; White-box | Classification Models | S&P | [link](https://ieeexplore.ieee.org/abstract/document/8835245?casa_token=2VTmu69Ze5YAAAAA:cNBfmpyOtRzlcjC17vP_fvqWINaGcGCAA1BGWxfBzEveksH6GRAMfrmGSH7ULi4Wf_G0NzJNnw) | [Link](https://github.com/privacytrustlab/ml_privacy_meter) |
| 2019 | **ML-Leaks: Model and Data Independent Membership Inference Attacks and Defenses on Machine Learning Models** | Black-box | Classification Models | NDSS | [Link](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_03A-1_Salem_paper.pdf) | [Link](https://github.com/AhmedSalem2/ML-Leaks) |
|2019 | **LOGAN: Membership Inference Attacks Against Generative Models** | Black-box; White-box | Generation Models | PoPETs | [Link](https://arxiv.org/abs/1705.07663) | [Link](https://github.com/jhayes14/gen_mem_inf)|

### Attack papers 2018
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
|2018 | **Privacy Risk in Machine Learning: Analyzing the Connection to Overfitting** | Black-box | Classification Models | CSF | [Link](https://ieeexplore.ieee.org/abstract/document/8429311?casa_token=NQu6-mEb9JMAAAAA:LTU3BPSYc8ALHF89ifdWs1zl__ABgBzIr44xFoN2t8HwjTb5vm20S00VeH9JSmaBU-miBt5Ucg) | [Link](https://github.com/samuel-yeom/ml-privacy-csf18) |

### Attack papers 2017
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
|2017  | **Membership inference attacks against machine learning models** | Black-box | Classification Models | S&P | [link](https://ieeexplore.ieee.org/abstract/document/7958568?casa_token=YOmVjvUemFUAAAAA:gGeuARxnjASvh9gnPkijkLD7d7HD1VV1JZkooXtS6tb6LGfKqHgBbyoaI-0-X7kFeP-3bjUR2A) | [Link](https://github.com/csong27/membership-inference) |
