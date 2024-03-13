---
layout: blog
title: Research
slug: /research
---
### Nucleus-aware Self-supervised Pretraining Using Unpaired Image-to-image Translation for Histopathology Images
- Accepted by [IEEE Transactions on Medical Imaging, 2023](https://ieeexplore.ieee.org/document/10234386);
- Codes and pretrained weights are available at [https://github.com/zhiyuns/UNITPathSSL](https://github.com/zhiyuns/UNITPathSSL).

Self-supervised pretraining attempts to enhance model performance by obtaining effective features from unlabeled data, and has demonstrated its effectiveness in the field of histopathology images. Despite its success, few works concentrate on the extraction of nucleus-level information, which is essential for pathologic analysis. In this work, we propose a novel nucleus-aware self-supervised pretraining framework for histopathology images. The framework aims to capture the nuclear morphology and distribution information through unpaired image-to-image translation between histopathology images and pseudo mask images. The generation process is modulated by both conditional and stochastic style representations, ensuring the reality and diversity of the generated histopathology images for pretraining. Further, an instance segmentation guided strategy is employed to capture instance-level information. The experiments on 7 datasets show that the proposed pretraining method outperforms supervised ones on Kather classification, multiple instance learning, and 5 dense-prediction tasks with the transfer learning protocol, and yields superior results than other self-supervised approaches on 8 semi-supervised tasks. Our project is publicly available at [https://github.com/zhiyuns/UNITPathSSL](https://github.com/zhiyuns/UNITPathSSL).
![](/assets/img/content/UNITPathSSL.png)

### Alias-Free Co-modulated Network for Cross-modality Synthesis and Super-resolution of MR Images
- Accepted by [Medical Image Computing and Computer Assisted Intervention (MICCAI), 2023](https://link.springer.com/chapter/10.1007/978-3-031-43999-5_7);
- Codes are available at [https://github.com/zhiyuns/AFCM](https://github.com/zhiyuns/AFCM).

Cross-modality synthesis (CMS) and super-resolution (SR) have both been extensively studied with learning-based methods, which aim to synthesize desired modality images and reduce slice thickness for magnetic resonance imaging (MRI), respectively. It is also desirable to build a network for simultaneous cross-modality and super-resolution (CMSR) so as to further bridge the gap between clinical scenarios and research studies. However, these works are limited to specific fields. None of them can flexibly adapt to various combinations of resolution and modality, and perform CMS, SR, and CMSR with a single network. Moreover, alias frequencies are often treated carelessly in these works, leading to inferior detail-restoration ability. In this paper, we propose Alias-Free Co-Modulated network (AFCM) to accomplish all the tasks with a single network design. To this end, we propose to perform CMS and SR consistently with co-modulation, which also provides the flexibility to reduce slice thickness to various, non-integer values for SR. Furthermore, the network is redesigned to be alias-free under the Shannon-Nyquist signal processing framework, ensuring efficient suppression of alias frequencies. Experiments on three datasets demonstrate that AFCM outperforms the alternatives in CMS, SR, and CMSR of MR images. Our codes are available at [https://github.com/zhiyuns/AFCM](https://github.com/zhiyuns/AFCM).
![](/assets/img/content/AFCM.png)

