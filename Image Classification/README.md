## Image Classification: EfficientNet
In this notebook, I will build a model for binary image classification of histological images using EfficentNet.

<p align="center">
  <img height = 500 width=800 src="https://www.researchgate.net/publication/333000330/figure/fig2/AS:757019443200003@1557498908844/Results-of-the-first-phase-of-training-on-Warwick-QU-dataset-Left-to-right-source.jpg"/>
</p>

We use the [Warwick QU gland segmentation (GlaS)](https://warwick.ac.uk/fac/sci/dcs/research/tia/glascontest/download/) 
data set consisting of H&E stained histological images from the GlaS@MICCAI 2015 competition.

### Introduction
> Glands are important histological structures which are present in most organ systems as the main mechanism for secreting proteins and carbohydrates. It has been shown that malignant tumours arising from glandular epithelium, also known as adenocarcinomas, are the most prevalent form of cancer. The morphology of glands has been used routinely by pathologists to assess the degree of malignancy of several adenocarcinomas, including prostate, breast, lung, and colon.

> Accurate segmentation of glands is often a crucial step to obtain reliable morphological statistics. Nonetheless, the task by nature is very challenging due to the great variation of glandular morphology in different histologic grades. Up until now, the majority of studies focus on gland segmentation in healthy or benign samples, but rarely on intermediate or high grade cancer, and quite often, they are optimised to specific datasets.

> In this challenge, participants are encouraged to run their gland segmentation algorithms on images of Hematoxylin and Eosin (H&E) stained slides, consisting of a variety of histologic grades. The dataset is provided together with ground truth annotations by expert pathologists. The participants are asked to develop and optimise their algorithms on the provided training dataset, and validate their algorithm on the test dataset 
