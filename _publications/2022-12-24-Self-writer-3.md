---
title: "Self-Writer: Clusterable Embedding Based Self-Supervised Writer Recognition from Unlabeled Data"
collection: publications
category: manuscripts
permalink: /publication/2022-12-24-self-writer
excerpt: "This paper presents a self-supervised approach for writer recognition using clusterable embeddings."
date: 2022-12-24
venue: "Mathematics, Vol. 10, Issue 24"
slidesurl: ""
paperurl: "https://doi.org/10.3390/math10244796"
citation: 'Zabir Mohammad, Muhammad Mohsin Kabir, Muhammad Mostafa Monowar. (2022). "Self-Writer: Clusterable Embedding Based Self-Supervised Writer Recognition from Unlabeled Data." <i>Mathematics</i>.'
---

Abstract: Writer recognition based on a small amount of handwritten text is one of the most challenging deep learning problems because of the implicit characteristics of handwriting styles. In a deep convolutional neural network, writer recognition based on supervised learning has shown great success. These supervised methods typically require a lot of annotated data. However, collecting annotated data is expensive. Although unsupervised writer recognition methods may address data annotation issues significantly, they often fail to capture sufficient feature relationships and usually perform less efficiently than supervised learning methods. Self-supervised learning may solve the unlabeled dataset issue and train the unsupervised datasets in a supervised manner. This paper introduces Self-Writer, a self-supervised writer recognition approach dealing with unlabeled data. The proposed scheme generates clusterable embeddings from a small fixed-length image frame such as a text block. The training strategy presumes that a small image frame of handwritten text should include the writer’s handwriting characteristics. We construct pairwise constraints and nongenerative augmentation to train Siamese architecture to generate embeddings depending on such an assumption. Self-Writer is evaluated on the two most widely used datasets, IAM and CVL, on pairwise and triplet architecture. We find Self-Writer to be convincing in achieving satisfactory performance using pairwise architectures.
