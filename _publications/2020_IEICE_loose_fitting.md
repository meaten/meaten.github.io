---
title: "Human Pose Annotation Using a Motion Capture System for Loose-Fitting Clothes"
collection: publications
permalink: /publication/2020_IEICE_loose_fitting
excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2020-06-01
venue: '2020 IEICE Transactions on Information and Systems 103 (6), 1257-1264'
citation: 'Takuya Matsumoto, Kodai Shimosato, Takahiro Maeda, Tatsuya Murakami, Koji Murakoso, Kazuhiko Mino, Norimichi Ukita. IEICE Transactions on Information and Systems 2020.'
---
This paper proposes a framework for automatically annotating the keypoints of a human body in images for learning 2D pose
estimation models. Ground-truth annotations for supervised learning are
difficult and cumbersome in most machine vision tasks. While considerable contributions in the community provide us a huge number of poseannotated images, all of them mainly focus on people wearing common
clothes, which are relatively easy to annotate the body keypoints. This paper, on the other hand, focuses on annotating people wearing loose-fitting
clothes (e.g., Japanese Kimono) that occlude many body keypoints. In order to automatically and correctly annotate these people, we divert the 3D
coordinates of the keypoints observed without loose-fitting clothes, which
can be captured by a motion capture system (MoCap). These 3D keypoints
are projected to an image where the body pose under loose-fitting clothes
is similar to the one captured by the MoCap. Pose similarity between bodies with and without loose-fitting clothes is evaluated with 3D geometric
configurations of MoCap markers that are visible even with loose-fitting
clothes (e.g., markers on the head, wrists, and ankles). Experimental results validate the effectiveness of our proposed framework for human pose
estimation.

[Download paper here](https://www.jstage.jst.go.jp/article/transinf/E103.D/6/E103.D_2019MVP0007/_pdf)
