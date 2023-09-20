---
title: "Real-Time Joint-Stem Prediction for Agricultural Robots in Grasslands Using Multi-Task Learning "
collection: publications
permalink: /publication/2023-09-12-joint-stem-rumexweeds
#excerpt: 'We present a system to train neural-network policies for local planners, explicitly accounting for humans navigating the space.'
date: 2023-09-12
venue: 'MDPI Agronomy, 2023'
authors: Jiahao Li, Ronja Güldenring, Lazaros Nalpantidis.
# citation: 
---
Autonomous weeding robots need to accurately detect the joint stem of grassland weeds in order to control those weeds in an effective and energy-efficient manner. In this work, keypoints on joint stems and bounding boxes around weeds in grasslands are detected jointly using multi-task learning. We compare a two-stage, heatmap-based architecture to a single-stage, regression-based architecture—both based on the popular YOLOv5 object detector. Our results show that introducing joint-stem detection as a second task boosts the individual weed detection performance in both architectures. Furthermore, the single-stage architecture clearly outperforms its competitors with an OKS of 56.3 in joint-stem detection while also achieving real-time performance of 12.2 FPS on Nvidia Jetson NX, suitable for agricultural robots. Finally, we make the newly created joint-stem ground-truth annotations publicly available for the relevant research community.

Link to PDF: [https://www.mdpi.com/2073-4395/13/9/2365](https://www.mdpi.com/2073-4395/13/9/2365){:target="_blank"}.

Link to dataset: [https://dtu-pas.github.io/RumexWeeds/](https://dtu-pas.github.io/RumexWeeds/){:target="_blank"}