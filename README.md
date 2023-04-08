# Transfer Learning Object Detection Framework for IndoorEnvironments

Research study conducted using ResNet50 based models for Transfer Learning.

**Layman Abstract**: With the growing interest in creating self-driving robots, it's important to teach them how to see and recognize objects like humans do. However, current object detection technology is not perfect and can make mistakes when it comes to things like color, texture, and view. To improve this, researchers developed a new dataset that includes different types of objects in various indoor environments. They used this dataset to train a computer program called ResNet50 to better detect and categorize objects like doors, chairs, and tables. When they tested the program, it was more accurate than other object detection systems currently in use. This new method can be used to train future object detection technology and improve its accuracy.


**Abstract**: The recent increase in interest in building autonomous mobile robots has made detecting and recognizing objects a very important task. Object detectors aim to mimic the function of the human eye; however, they are limited by their visual acuity. In complex indoor environments, object detectors remain prone to classification and localization errors as they frequently fail to account for different variations in color, texture, occlusions, and viewpoints in objects; thus, they are unable to provide a consistently reliable cue. Leading object detectors leverage recent progress in Convolutional Neural Networks (CNNs) to simultaneously detect and categorize objects of interest in dynamic scenes. We developed a novel classification and localization dataset compiled from eight open-source datasets. An additional real-world dataset was created using 5,000 crowdsourced images obtained from over 30 freelance volunteers. Different strategies to train ResNet50-based models were explored to achieve better object detection accuracy (mAP) using five classes - doors, door handles, chairs, tables, and extraneous objects. The architectures were trained using the developed classification and object localization dataset consisting of over 80k images. To quantify the robustness of the model, cross-validation was performed on test set images, and model robustness tests (image corruptions) were used as performance indexes. Experimentation demonstrated a 22% lift (mAP) as compared to industry standard object detectors for the ResNet50 pre-trained on ImageNet and fine-tuned with our developed classification set. Ultimately, the method described can be implemented to train future object detectors for specific tasks while achieving better accuracy results.


Images and other relevant code present in research paper!





*All content in this document, including text, images, and other media, is protected by copyright laws and is the property of the author. This document is intended for personal and non-commercial use only, and may be used for reading and inspirational purposes. You are not authorized to copy, modify, distribute, or sell any part of this document for any purpose without the express written consent of the author. This document is not to be copyrighted by any other individual or entity. Unauthorized use may result in legal action.*
