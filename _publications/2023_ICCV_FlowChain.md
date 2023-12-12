---
title: "Fast Inference and Update of Probabilistic Density Estimation on Trajectory Prediction"
collection: publications
permalink: /publication/2023_ICCV_FlowChain
excerpt: "We proposed FlowChain: fast and accurate probability density estimation on time-series data based on Normalizing Flow." 
date: 2023-10-04
venue: 'Proceedings of the IEEE/CVF International Conference on Computer Vision.'
citation: 'T. Maeda and N. Ukita, "Fast Inference and Update of Probabilistic Density Estimation on Trajectory Prediction" ICCV2023'
---
Safety-critical applications such as autonomous vehicles and social robots require fast computation and accurate probability density estimation on trajectory prediction. To address both requirements, this paper presents a new normalizing flow-based trajectory prediction model named FlowChain. FlowChain is a stack of conditional continuously-indexed flows (CIFs) that are expressive and allow analytical probability density computation. This analytical computation is faster than the generative models that need additional approximations such as kernel density estimation. Moreover, FlowChain is more accurate than the Gaussian mixture-based models due to fewer assumptions on the estimated density. FlowChain also allows a rapid update of estimated probability densities. This update is achieved by adopting the newest observed position and reusing the flow transformations and its log-det-jacobians that represent the motion trend. This update is completed in less than one millisecond because this reuse greatly omits the computational cost. Experimental results showed our FlowChain achieved state-of-the-art trajectory prediction accuracy compared to previous methods. Furthermore, our FlowChain demonstrated superiority in the accuracy and speed of density estimation.

![Method Overview](/images/overview_FlowChain_iccv2023.png)

[Paper](https://arxiv.org/abs/2308.08824)

[Code is available here](https://github.com/meaten/FlowChain-ICCV2023)