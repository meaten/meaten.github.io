---
title: "Data Augmentation for Human Motion Prediction"
collection: publications
permalink: /publication/2021_MVA_data_augmentation
excerpt: "We proposed two data augmentation approaches using VAE and IK, and a motion refinement using Imitation Learning for Motion Prediciton" 
date: 2021-06-01
venue: '2021 17th International Conference on Machine Vision Applications (MVA)'
citation: 'T. Maeda and N. Ukita, "Data Augmentation for Human Motion Prediction," 2021 17th International Conference on Machine Vision and Applications (MVA), 2021, pp. 1-5, doi: 10.23919/MVA51890.2021.9511368.'
---
Human motion prediction is seldom deployed to real-world tasks due to difficulty in collecting a huge amount of motion data.
We propose two motion data augmentation approaches using Variational AutoEncoder (VAE) and Inverse Kinematics (IK).
Our VAE-based generative model with adversarial training and sampling near samples generates various motions even with insufficient original motion data. 
Our IK-based augmentation scheme allows us to semi-automatically generate a variety of motions.
Furthermore, we correct unrealistic artifacts in the augmented motions.
As a result, our method outperforms previous motion augmentation methods.

![Method Overview](/images/MVA_2021_overview.png)

[Youtube link for presentation](https://www.youtube.com/watch?v=9H0DqRYYwCY)

Results
<video muted autoplay width="480" height="320" loop>
  <source src="/images/mva2021.mp4" type="video/mp4">
  <p>Your browser does not support the video element.</p>
</video>

[Download paper here](http://www.mva-org.jp/Proceedings/2021/papers/O2-2-2.pdf)