---
title: "MotionAug: Augmentation with Physical Correction for Human Motion Prediction"
collection: publications
permalink: /publications/2022_CVPR_MotionAug
excerpt: "This paper presents a motion data augmentation scheme incorporating motion synthesis encouraging diversity and motion correction imposing physical plausibility." 
date: 2022-06-19
venue: 'In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition'
citation: 'T. Maeda and N. Ukita, "MotionAug: Augmentation with Physical Correction for Human Motion Prediction" CVPR2022'
---
This paper presents a motion data augmentation scheme incorporating motion synthesis encouraging diversity and motion correction imposing physical plausibility. This motion synthesis consists of our modified Variational AutoEncoder (VAE) and Inverse Kinematics (IK). In this VAE, our proposed sampling-near-samples method generates various valid motions even with insufficient training motion data. Our IK-based motion synthesis method allows us to generate a variety of motions semi-automatically. Since these two schemes generate unrealistic artifacts in the synthesized motions, our motion correction rectifies them. This motion correction scheme consists of imitation learning with physics simulation and subsequent motion debiasing. For this imitation learning, we propose the PD-residual force that significantly accelerates the training process. Furthermore, our motion debiasing successfully offsets the motion bias induced by imitation learning to maximize the effect of augmentation. As a result, our method outperforms previous noise-based motion augmentation methods by a large margin on both Recurrent Neural Network-based and Graph Convolutional Network-based human motion prediction models.

![Method Overview](/images/overview_MotionAug_cvpr2022.png)

Results
<video muted autoplay width="480" height="320" loop>
  <source src="/images/MotionAug_cvpr2022_resize.mp4" type="video/mp4">
  <p>Your browser does not support the video element.</p>
</video>

[Paper](https://arxiv.org/abs/2203.09116)

[Code is available here](https://github.com/meaten/MotionAug-CVPR2022)