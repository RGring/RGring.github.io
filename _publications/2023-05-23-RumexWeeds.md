---
title: "RumexWeeds: A Grassland Dataset for Agricultural Robotics"
collection: publications
permalink: /publication/2023-05-23-RumexWeeds
#excerpt: 'We present a system to train neural-network policies for local planners, explicitly accounting for humans navigating the space.'
date: 2023-05-23
venue: 'Journal of Field Robotics, 2023'
authors: Ronja Güldenring, Frits van Evert, Lazaros Nalpantidis.
# citation: 
---
Abstract: Computer vision can lead towards more sustainable agricultural production by enabling robotic precision agriculture. Vision-equipped robots are being deployed in the fields to take care of crops and control weeds. However, publicly available agricultural datasets containing both image data as well as data from navigational robot sensors are scarce.
Our real-world dataset RumexWeeds targets the detection of the grassland weeds: *Rumex obtusifolius L.* and *Rumex crispus L.*. RumexWeeds includes whole image sequences instead of individual static images, which is rare for computer vision image datasets, yet crucial for robotic applications. It allows for more robust object detection, incorporating temporal aspects and considering different viewpoints of the same object. Furthermore, RumexWeeds includes data from additional navigational robot sensors --- GNSS, IMU and odometry --- which can increase robustness, when additionally fed to detection models. In total the dataset includes 5,510 images with 15,519 manual bounding box annotations collected at 3 different farms and 4 different days in summer and autumn 2021. Additionally, RumexWeeds includes a subset of 340 ground truth pixels-wise annotations. The dataset is publicly available at [https://dtu-pas.github.io/RumexWeeds/](https://dtu-pas.github.io/RumexWeeds/){:target="_blank"}. In this paper we also use RumexWeeds to provide baseline weed detection results considering a state-of-the-art object detector; in this way we are elucidating interesting characteristics of the dataset.

Link to PDF: [https://onlinelibrary.wiley.com/doi/full/10.1002/rob.22196](https://onlinelibrary.wiley.com/doi/full/10.1002/rob.22196){:target="_blank"}.

Link to dataset: [https://dtu-pas.github.io/RumexWeeds/](https://dtu-pas.github.io/RumexWeeds/){:target="_blank"}