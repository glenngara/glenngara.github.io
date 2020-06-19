---
permalink: /publications/generating-adversarial-examples/
layout: single
title: "Generating Adversarial Examples Using Uniform Pixels and Neighbor Aggregation"
author_profile: true
classes: wide
---


Glenn Paul P. Gara & Arnulfo P. Azcarraga  
*20th Philippine Computing Science Congress, 2020*

![image-center](/assets/files/publications/generating-adversarial-examples/gara2020_generatingadversarial.jpg){: .align-center height="450" width="700"}

###### ABSTRACT
Deep neural networks have gained popularity due to its exceptional performance on several challenging tasks such as image classification, object detection, semantic segmentation, and image generation. Unfortunately, these networks are highly vulnerable to carefully crafted human imperceptible perturbations based on so- called adversarial examples. Adversarial examples have been used to mislead deep neural networks into predicting an incorrect output (i.e. category, label or class), sometimes with high confidence. Most approaches in constructing adversarial inputs require access to the gradients of the network, which is applicable only to gradient-based techniques. Others require only some access to the output function making these methods model-agnostic. In this work, we propose a mechanism that considers the neural network as a black-box by assuming that the network output is observed based only on the examined inputs. We focus our experiments on a model-agnostic adversarial example generation. Specifically, without exploiting the network gradients, we show that by aggregating neighboring images of an input image represented within a low dimensional input space and combine this with a perturbation technique referred to as "uniform pixels", both convolutional neural network and vanilla neural network are vulnerable to incorrect predictions. As such, the proposed method can serve as a basis for designing more robust neural network models.

<a href="/assets/files/publications/generating-adversarial-examples/gara2020_generatingadversarial.pdf" class="btn btn--info">Download PDF</a>

<h4 class="research-section-header">Bibtex</h4>
 <div class="citation-content">
   <div class="citation-text" id="bibtex">
       @inproceedings{Samson:2020:EFI:3334480.3382818,</br> author = {Samson, Briane Paul V. and Sumi, Yasuyuki},</br> title = {Are Two Heads Better than One? Exploring Two-Party Conversations for Car Navigation Voice Guidance},</br> booktitle = {Proceedings of the 2020 CHI Conference Extended Abstracts on Human Factors in Computing Systems},</br> series = {CHI '20},</br> year = {2020},</br> isbn = {978-1-4503-6819-3},</br> location = {Honolulu, Hawai'i, USA},</br> pages = {371:1--371:10},</br> articleno = {371},</br> numpages = {10},</br> url = {http://doi.acm.org/10.1145/3334480.3382818},</br> doi = {10.1145/3334480.3382818},</br> acmid = {3382818},</br> publisher = {ACM},</br> address = {New York, NY, USA},</br> keywords = {voice guidance; voice agents; two-party conversation; navigation applications; recommender systems; driving},</br> }
   </div>
   <div class="citation-copy">
       <a class="copy-btn" data-clipboard-target="#bibtex">
           <i class="far fa-copy"></i>
       </a>
   </div>
 </div>

BIBTEX
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
