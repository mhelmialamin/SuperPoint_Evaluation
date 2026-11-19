**Evaluation of SuperPoint for Feature Point Detection and Matching**
**Independently Developed by Muhammad Helmi Al Amin**

This research presents a self-supervised interest point detection and description (SuperPoint) evaluation in detecting and matching feature points.

By using this machine learning method, this project experiments with how interest point detection can outperform available hand crafted algorithms.

It shows both quantitatively and qualitatively that SuperPoint can constantly detect more keypoints than the original pre-adapted model and any other classical corner detector (FAST, Harris and Shi-Tomasi). While ORB obtains the highest repeatability, the SuperPoint demonstrates better homography estimation results on HPatches and outperforms SIFT, LIFT and ORB in descriptor matching.

Subsequently, we develop a simple sparse optical flow visualisation for evaluating the SuperPoint network to compute points and descriptors and match them across video sequences, showing that the feature matching performance of SuperPoint significantly depends on the number of trained datasets.
