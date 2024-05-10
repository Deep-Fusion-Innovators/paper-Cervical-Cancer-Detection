# Overview
This repository contains data and scripts for reproducing the results accompanying the manuscript:

### Lightweight Low-Rank Adaptation Vision Transformer Framework for Cervical Cancer Detection and Cervix Type Classification
Zhenchen Hong<sup>1,#</sup>, Jingwei Xiong<sup>2,#</sup>, Han Yang<sup>3</sup>, Yu Mo<sup>4</sup>

<sup>1</sup> Department of Physics and Astronomy, University of California, Riverside, CA 92521, United States

<sup>2</sup> Graduate Group in Biostatistics, University of California, Davis, CA 95616, United States

<sup>3</sup> Department of Chemistry, Columbia University, New York, New York 10027, United States

<sup>4</sup> Department of Computer Science and Department of Biology, Indiana University, Bloomington, IN 47405, United States

<sup>#</sup> Correspondence to [jwxxiong@ucdavis.edu](mailto:jwxxiong@ucdavis.edu), [zhenchen.hong@email.ucr.edu](mailto:zhenchen.hong@email.ucr.edu)

This work is currently available on the Bioengineering-Basel at [this link](https://www.mdpi.com/2306-5354/11/5/468).

# Abstract

Cervical cancer remains a significant global health challenge, necessitating advanced methods for early detection to improve patient outcomes. This study introduces a cutting-edge digital pathology classification strategy that incorporates Low Rank Adaptation (LoRA) within a Vision Transformer (ViT) architecture, aiming to enhance the precision of cervix type classification. Our approach's core innovation lies in utilizing LoRA to enable robust model training with minimal data requirements, leveraging the state-of-the-art visual representation capabilities of Vision Transformers. This methodology surpasses popular convolutional neural network models, like ResNet and ResNeXt, in terms of performance with strong generalization ability, particularly in scenarios with limited data availability. Through meticulous experimentation and analysis on benchmark datasets, our findings affirm the superiority of our ViT with LoRA framework in accurately detecting anomaly cervix characteristics. This research marks a significant contribution to the development of advanced computer-aided diagnosis systems, offering promising directions for the early detection and treatment of cervical cancer.

# Contents

The inference code could be requested by emailing corresponding authors. Scripts for analysis and figures are contained in figures.ipynb notebook. 

## Software dependencies

Methods to infer models are implemented in Python/C++. 

## License

This repository is dual licensed as [GPL-3.0](LICENSE-GPL) (source code) and [CC0 1.0](LICENSE-CC0) (figures, documentation, and our presentation of the data).
