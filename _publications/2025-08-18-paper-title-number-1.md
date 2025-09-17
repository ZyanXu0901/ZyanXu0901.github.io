---
title: "SCEP-TI: A side-channel attack on encrypted proxy video streams for video title identification"
collection: publications
category: manuscripts
permalink: /publication/2025-08-18-paper-title-number-1
excerpt: 'This work presents SCEP-TI, a novel method that leverages side-channel features in encrypted proxy video streams to accurately identify video titles. The approach demonstrates that even encrypted traffic can leak sensitive information through traffic patterns, posing new privacy and security risks.'
date: 2025-08-18
venue: 'Computer Networks'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S1389128625005973'
citation: 'Yi Zhang, Zhenyu Xu, Xurui Ren, Hua Wu, Guang Cheng, SCEP-TI: A side-channel attack on encrypted proxy video streams for video title identification, Computer Networks, Volume 271,2025,111630, ISSN 1389-1286,https://doi.org/10.1016/j.comnet.2025.111630'
---
With the widespread use of the Internet and the continuous development of streaming media technology, video streaming has increasingly become the main body of the entire Internet traffic. Although the video is encrypted during transmission, it may still be vulnerable to side-channel attacks. However, after the video is transmitted through proxy encapsulation, the accuracy of side-channel attack is greatly reduced. In the paper, we propose a side-channel attack on encrypted proxy video streams for title identification(SCEP-TI), which is a new attack method to identify video titles in encrypted proxy traffic based on side-channel features. We extract stable video segment features from encrypted proxy traffic based on DASH and HLS protocols, and SCEP-TI utilizes a convolutional neural network (CNN) model to accurately identify video titles. This method overcomes the traffic confusion caused by encrypted proxy encapsulation, the interference of a large amount of background traffic, and the limitation of unidirectional traffic in asymmetric routing scenarios. The experimental results show that SCEP-TI has higher accuracy in both closed-world and open-world scenarios, which is superior to the existing methods. Furthermore, to protect the privacy of the user, we propose two defense mechanisms. Our code is available at https://github.com/Zzzyyzz/SCEP-TI.
