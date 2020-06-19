---
permalink: /publications/generating-adversarial-examples/
layout: single
title: "Generating Adversarial Examples Using Uniform Pixels and Neighbor Aggregation"
author_profile: true
classes: wide
---


Glenn Paul P. Gara & Arnulfo P. Azcarraga  
*20th Philippine Computing Science Congress, 2020*

![image-center](/assets/files/publications/generating-adversarial-examples/gara2020_generatingadversarial.jpg){: .align-center height=100 width=150}

**ABSTRACT**  
Deep neural networks have gained popularity due to its exceptional performance on several challenging tasks such as image classification, object detection, semantic segmentation, and image generation. Unfortunately, these networks are highly vulnerable to carefully crafted human imperceptible perturbations based on so- called adversarial examples. Adversarial examples have been used to mislead deep neural networks into predicting an incorrect output (i.e. category, label or class), sometimes with high confidence. Most approaches in constructing adversarial inputs require access to the gradients of the network, which is applicable only to gradient-based techniques. Others require only some access to the output function making these methods model-agnostic. In this work, we propose a mechanism that considers the neural network as a black-box by assuming that the network output is observed based only on the examined inputs. We focus our experiments on a model-agnostic adversarial example generation. Specifically, without exploiting the network gradients, we show that by aggregating neighboring images of an input image represented within a low dimensional input space and combine this with a perturbation technique referred to as "uniform pixels", both convolutional neural network and vanilla neural network are vulnerable to incorrect predictions. As such, the proposed method can serve as a basis for designing more robust neural network models.

**BIBTEX**
```
@inproceedings{gara2020_generatingadversarial,
title={Generating Adversarial Examples Using Uniform Pixels and Neighbor Aggregation},
author={Gara, Glenn Paul P. and Azcarraga, Arnulfo P.},
booktitle={Proceedings of the 20th Philippine Computing Science Congress},
year={2020},
location=
pages={7--13},
organization={Computing Society of the Philippines}
}
```
