---
title: "Self-supervised contrastive learning on agricultural images"
collection: publications
permalink: /publication/2021-11-06-SwAV-Agriculture
#excerpt: 'We present a system to train neural-network policies for local planners, explicitly accounting for humans navigating the space.'
date: 2021-11-06
venue: 'Journal: Computers and Electronics in Agriculture, 2021'
#paperurl: 'http://ras.papercept.net/images/temp/IROS/files/0122.pdf'
authors: 'Ronja Güldenring, Lazaros Nalpantidis.'
# citation: 
---
Abstract: Agriculture emerges as a prominent application domain for advanced computer vision algorithms. As much as deep learning approaches can help solve problems such as plant detection, they rely on the availability of large amounts of annotated images for training. However, relevant agricultural datasets are scarce and at the same time, generic well-established image datasets such as ImageNet do not necessarily capture the characteristics of agricultural environments. This observation has motivated us to explore the applicability of self-supervised contrastive learning on agricultural images. Our approach considers numerous non-annotated agricultural images, which are easy to obtain, and uses them to pre-train deep neural networks. We then require only a limited number of annotated images to fine-tune those networks in a supervised training manner for relevant downstream tasks, such as plant classification or segmentation. To the best of our knowledge, contrastive self-supervised learning has not been explored before in the area of agricultural images. Our results reveal that it outperforms conventional deep learning approaches in classification downstream tasks, especially for small amounts of available annotated training images where up to 14% increase of average top-1 classification accuracy has been observed. Furthermore, the computational cost for generating data-specific pre-trained weights is fairly low, allowing one to generate easily new pre-trained weights for any custom model architecture or task. 

Link to PDF: [https://www.sciencedirect.com/science/article/pii/S0168169921005275](https://www.sciencedirect.com/science/article/pii/S0168169921005275){:target="_blank"}.