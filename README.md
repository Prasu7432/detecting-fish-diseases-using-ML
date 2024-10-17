**A MACHINE LEARNING APPROACH FOR EARLY DETECTION OF FISH DISEASES BY ANALYZING WATER QUALITY **

**ABSTRACT:**

Fish diseases in aquaculture constitute a significant hazard to nutriment security. Identification of infected fishes in aquaculture remains challenging to find out at the early stage due to the dearth of necessary infrastructure. The identification of infected fish timely is an obligatory step to thwart the spreading disease. In this work, we want to find out the salmon fish disease in aquaculture, as salmon aquaculture is the fastest-growing food production system globally, accounting for 70 percent (2.5 million tons) of the market. In the alliance of flawless image processing and machine learning mechanisms, we identify the infected fishes caused by the various pathogens. This work is divided into two portions. In the rudimentary portion, image pre-processing and segmentation have been applied to reduce noise and exaggerate the image, respectively. In the second portion, we extract the involved features to classify the diseases with the help of the Support Vector Machine (SVM) algorithm of machine learning with a kernel function. The processed images of the first portion have passed through this (SVM) model. Then we harmonize a comprehensive experiment with the proposed combination of techniques on the salmon fish image dataset used to examine the fish disease. We have conveyed this work on a novel dataset compromising with and without image augmentation. The results have brought a judgment of how our applied SVM performs notably with 91.42 and 94.12 percent of accuracy, respectively, with and without augmentation.

**EXISTING SYSTEM:**

Some works focused on only some basic image processing techniques for the identification of fish disease. Shaveta et al. [22] proposed an image-based detection technique where firstly applies image segmentation as an edge detection with Canny, Prewitt, and Sobel. However, they did not specify the exact technique that was used for feature extraction. In feature extraction, they applied Histogram of Gradient (HOG) and Features from Accelerated Segment Test (FAST) for classification with a combination of both techniques. They tried to discover a better classification with a combination instead of applying a specific method with less exactness. Another technique Lyubchenko et al. [21] proposed a structure called the clustering of objects in the image that obliged diverse image segmentation actions based on a scale of various clusters. Here, they chose markers for individual objects and objects encountered with a specific marker. Finally, they calculated the proportion of an object in the image and the proportion of infected area to the fish body to identify fish disease. However, individual marking of an object is time-consuming and not effective.
There are some approaches focused on the consolidation of image processing and machine learning. Malik et al. [23] proposed a specific fish disease called Epizootic Ulcerative Syndrome (EUS) detection approach. Aphanomyces invadans, a fungal pathogen, cause this disease. Here, they approached combination styles that combine the Principal Component Analysis (PCA) and Histogram of Oriented Gradients (HOG) with Features from Accelerated Segment Test (FAST) feature detector and then classify over a machine learning algorithm (neural network). The sequence of FAST-PCANN gives 86 percent accuracy through the classifier, and HOG-PCA-NN gives 65.8 percent accuracy, which is less than the previous combination.

**Drawbacks of the Existing System:**

1.Fish diseases in aquaculture constitute a significant hazard to nutriment security.
2.The identification of infected fish timely is an obligatory step to thwart the spreading disease. In this work, we want to find out the salmon fish disease in aquaculture, as salmon aquaculture is the fastest-growing food production system globally, accounting for 70 percent (2.5 million tons) of the market.
3.In the alliance of flawless image processing and machine learning mechanism, we identify the infected fishes caused by the various pathogen.

**PROPOSED SYSTEM:**

One of the most popular supervised machine learning techniques, support vector machine (SVM), has brought convenient solutions for many classification problems in various fields. It is a powerful classification tool that brings out quality predictions for unlabeled data. In [19] Authors built an SVM model based on three kernel functions to differentiate dengue human infected blood sera and healthy sera. For image classification, another SVM architecture has been proposed in [3] where they emulate the architecture by combining convolutional neural networks (CNN) with SVM. SVM provides remarkable accuracy in many contexts.

**Advantages of Proposed System:**

1.Fish diseases in aquaculture constitute a significant hazard to nutriment security.
2.Identification of infected fishes in aquaculture remains challenging to find out at the early stage due to the dearth of necessary infrastructure.
3.The identification of infected fish timely is an obligatory step to thwart the spread of disease. In this work, we want to find out the salmon fish disease in aquaculture, as salmon aquaculture is the fastest-growing food production system globally, accounting for 70 percent (2.5 million tons) of the market.

**SYSTEM REQUIREMENTS:**

**HARDWARE REQUIREMENTS:
**
● System     :  MINIMUM i3

● Hard Disk  :  40GB

● Ram      :  4GB

● Key Board   :  Standard Window Keyboard

● Mouse    :  Two or Three Button Mouse


**SOFTWARE REQUIREMENTS:**

● Operating System  :  Windows 8 (upto 11)

● Coding Language  :  Python 3.7.0
