---
layout: post
title: Privacy-Preserving Analytics using Edge Computing
---



A recent [NSF report](http://iot.eng.wayne.edu/edge/NSF%20Edge%20Workshop%20Report.pdf) highlighted the challenges and opportunities in Edge Computing, leveraging the high processing capabilities and low latency offered at the edge of the network (IoT devices, smartphones, cloudlets) for achieving scalable yet secure and private analytics. Recently we put two papers on ArXiv, focusing on Privacy-Preserving Analytics using smartphones and constrained devices on the network (such as a Raspberry Pi). I encourage the privacy and mobile computing enthusiasts to read these papers and kindly provide us with any feedback on the analytics which can improve the research efforts in this space.  



*Seyed Ali Ossia, Ali Shahin Shamsabadi, Ali Taheri, Hamid R. Rabiee, Nic Lane, Hamed Haddadi, "A Hybrid Deep Learning Architecture for Privacy-Preserving Mobile Analytics", Available on ArXiv, March 2017. [paper](https://arxiv.org/abs/1703.02952)

**Abstract
The increasing quality of smartphone cameras and variety of photo editing applications, in addition to the rise in popularity of image-centric social media, have all led to a phenomenal growth in mobile-based photography. Advances in computer vision and machine learning techniques provide a large number of cloud-based services with the ability to provide content analysis, face recognition, and object detection facilities to third parties. These inferences and analytics might come with undesired privacy risks to the individuals. 
In this paper, we address a fundamental challenge: Can we utilize the local processing capabilities of modern smartphones efficiently to provide desired features to approved analytics services, while protecting against undesired inference attacks and preserving privacy on the cloud? We propose a hybrid architecture for a distributed deep learning model between the smartphone and the cloud. We rely on the Siamese network and machine learning approaches for providing privacy based on defined privacy constraints. We also use transfer learning techniques to evaluate the proposed method. Using the latest deep learning models for Face Recognition, Emotion Detection, and Gender Classification techniques, we demonstrate the effectiveness of our technique in providing highly accurate classification results for the desired analytics, while proving strong privacy guarantees.



*Sandra Servia-Rodriguez, Liang Wang, Jianxin R. Zhao, Richard Mortier, Hamed Haddadi, "Personal Model Training under Privacy Constraints", Available on ArXiv, March 2017. [paper](https://arxiv.org/abs/1703.00380)

**Abstract
Many current Internet services rely on inferences from models trained on user data. Commonly, both the training and inference tasks are carried out using cloud resources fed by personal data collected at scale from users. Holding and using such large collections of personal data in the cloud creates privacy risks to the data subjects, but is currently required for users to benefit from such services. We explore how to provide for model training and inference in a system where computation is moved to the data in preference to moving data to the cloud, obviating many current privacy risks. Specifically, we take an initial model learnt from a small set of users and retrain it locally using data from a single user. We evaluate on two tasks: one supervised learning task, using a neural network to recognise users' current activity from accelerometer traces; and one unsupervised learning task, identifying topics in a large set of documents. In both cases the accuracy is improved. We also demonstrate the feasibility of our approach by presenting a performance evaluation on a representative resource-constrained device (a Raspberry Pi).