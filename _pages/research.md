---
layout: archive
title: "Research Experience"
permalink: /research/
author_profile: true
---

<!-- {% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %} -->


- [Attacks Meet Interpretability (AmI) Evaluation](#attacks-meet-interpretability-ami-evaluation)
- [Intrusion Detection for Cellular Network](#intrusion-detection-for-cellular-network)
- [Landscape of Neural Network and Its Robustness](#landscape-of-neural-network-and-its-robustness)



# Attacks Meet Interpretability (AmI) Evaluation 

:school: Penn State Prof. Mehnaz’s Lab <br>
:woman_teacher: Advisor: [Shagufta Mehnaz][Shagufta Mehnaz] <br>
:mantelpiece_clock: January - August 2023


- **Motivation**: Attackers can exploit model explanations, initially intended to enhance transparency in machine learning systems, potentially empowering them to launch more powerful attacks. I investigated the application of model explanations in generating and detecting adversarial examples
- Conducted experiments that revealed the limitations of a paper using model explanation to detect adversarial samples. (["Attacks Meet Interpretability: Attribute-Steered Detection of Adversarial Samples"][AmI])
- Discovered a significant flaw in Nicholas Carlini's evaluation of the AmI model. (["Is AmI (Attacks Meet Interpretability) Robust to Adversarial Examples?"][NC_AmI])
- Proposed and implemented a fair evaluation of AmI; Currently writing a report that covers our discoveries




# Intrusion Detection for Cellular Network

:school: [Penn State Systems and Network Security (SyNSec) Research Group][SyNSec Lab] <br>
:man_teacher: Advisor: [Syed Rafiul Hussain][Syed Rafiul Hussain] <br>
:mantelpiece_clock: May 2021 - April 2023 

- **Motivation**: Because the increasing scale and complexity of modern systems (e.g., cellular networks) make traditional rule-based defensive approaches ineffective, I applied cutting-edge machine learning techniques to protect cellular networks, the critical infrastructure of the digital world, from evolving attacks
- Designed and implemented a novel machine learning architecture in PyTorch that uses LSTM on top of BERT, which considers relationships between segments of messages (i.e., inter-window context) for intrusion detection
- Applied contrastive learning for BERT-based window encoder - encodes each window to an embedding; Trained LSTM-based message tagger that assigned benign/attack label to each incoming message
- Achieved 95.64% test accuracy and 95.44% test F1 score on 13 common cellular network attacks
- Selected for Student Engagement Network Grant and Schreyer Honors College’s Summer Research Grant



# Landscape of Neural Network and Its Robustness

:school: [Penn State Center for Computational Mathematics and Applications][CCMA] <br>
:man_teacher: Advisors: [Jinchao Xu][Jinchao Xu] and [Jonathan Seigel][Jonathan Seigel] <br>
:mantelpiece_clock: July 2020 - August 2021

- **Motivation**: In an attempt to understand why adversarial examples can fool state-of-the-art neural networks, I studied the neural network as a function of its input space (e.g., pixels in an image) to evaluate the impact of certain pixels on the prediction of each class (e.g., digit 0, cat)
- Found that neural network functions (e.g., ResNet, VGG, DenseNet) become more sensitive to changes in input pixels as training progresses, which explains why even slight changes in pixel values can cause the neural network to produce very different results
- Selected for College of Engineering Equity REU and Multi-Campus Summer REU research scholarship



[Link References]: #

[Jinchao Xu]: https://www.mri.psu.edu/mri/personnel-directory/jxx1
[Syed Rafiul Hussain]: https://syed-rafiul-hussain.github.io/
[Shagufta Mehnaz]: https://smehnaz.github.io/
[Jonathan Seigel]: https://jwsiegel2510.github.io/

[SyNSec Lab]: https://synsec-den.github.io/
[CCMA]: https://ccma.math.psu.edu/

[AmI]: https://proceedings.neurips.cc/paper_files/paper/2018/file/b994697479c5716eda77e8e9713e5f0f-Paper.pdf
[NC_AmI]: https://arxiv.org/abs/1902.02322#:~:text=Is%20AmI%20(Attacks%20Meet%20Interpretability)%20Robust%20to%20Adversarial%20Examples%3F,-Nicholas%20Carlini&text=No.
