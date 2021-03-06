## Multi-view Geometry using Deep Learning
- [Convolutional neural network architecture for geometric matching](https://www.di.ens.fr/~josef/publications/Rocco17.pdf): Implements TPS in a network.

- [Unsupervised Deep Visual-Inertial Odometry with Online Error Correction for RGB-D Imagery](https://ieeexplore.ieee.org/document/8691513): Presents an approach called VIOLearner which fuses RGB-D and IMU data for absolute trajectory estimation. A great PAMI paper with a lot of comparisons and studies of robustness including fog.

- [DeepVIO: Self-supervised Deep Learning of Monocular Visual Inertial Odometry using 3D Geometric Constraints](https://arxiv.org/abs/1906.11435): Performs IMU pre-integration in a network and then fuses it with depth and pose network. 

- [VINet: Visual-Inertial Odometry as a Sequence-to-Sequence Learning Problem](https://arxiv.org/abs/1701.08376): Fuses Camera and IMU in a Neural Network. CNN for Vision which runs at 10Hz on a Tesla K80 and LSTM for IMU 200Hz on a Tesla K80.

- [PoseNet: A Convolutional Network for Real-Time 6-DOF Camera Relocalization](https://arxiv.org/abs/1505.07427): Uses a naive loss function to regress 6DOF pose from an input RGB image. Needs excessive parameter tuning.

- [Geometric Loss Functions for Camera Pose Regression with Deep Learning](https://arxiv.org/abs/1704.00390):  Improvement of the PoseNet paper with better results a new theoretical loss functions based on multi-view geometry.

- [SfM-Net: Learning of Structure and Motion from Video](https://arxiv.org/abs/1704.07804): Outputs 3D scene depth, 6DOF camera pose between 2 images.

- [Unsupervised Learning of Depth and Ego-Motion from Video AKA SFMLearner](https://arxiv.org/abs/1704.07813): David Lowe's paper with Google to estimate depth from a single image and multi-view 6DOF pose.

- [UnDeepVO: Monocular Visual Odometry through Unsupervised Deep Learning](https://arxiv.org/abs/1709.06841): Monocular VO, estimates depth and 6DOF pose. Performs better than SfMLearner.

- [Alex Kendall's Blog](https://alexgkendall.com/computer_vision/Reprojection_losses_geometry_computer_vision/) Awesome curated list of papers which use deep learning to solve multi-view geometry problems.

- [LIFT: Learned Invariant Feature Transform](https://arxiv.org/abs/1603.09114) SIFT like matching using deep learning. Super robust and does not need RANSAC.

- [Unsupervised Deep Homography: A Fast and Robust Homography Estimation Model](https://arxiv.org/abs/1709.03966) Estimate robust homography using deep learning. Steven's and Shreas' paper.

- [End-to-End Learning of Geometry and Context for Deep Stereo Regression](https://arxiv.org/abs/1703.04309) Alex Kendall and Skidio's paper on obtaining stereo disparity using CNN. Takes 0.90s per pass. [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://github.com/Jiankai-Sun/GC-Net) 

- [Pyramid Stereo Matching Network](https://arxiv.org/abs/1803.08669) Stereo disparity from CNN. Impressive results. Takes 0.41s per pass. [<img src="../README/images/logo/pytorch.jpg" width="24" height="24" />](https://github.com/JiaRenChang/PSMNet) .

- [Spherical CNNs](https://arxiv.org/abs/1801.10130) First paper on Spherical CNN.  [<img src="../README/images/logo/pytorch.jpg" width="24" height="24" />](https://github.com/jonas-koehler/s2cnn). 

- [Learning Spherical Convolution for Fast Features from 360° Imagery](https://arxiv.org/abs/1708.00919) Feature extraction on 360° Imagery. 

- [Spherical convolutions and their application in molecular modelling](https://papers.nips.cc/paper/6935-spherical-convolutions-and-their-application-in-molecular-modelling)


- [DSAC - Differentiable RANSAC for Camera Localization](https://arxiv.org/abs/1611.05705) Implements RANSAC in a neural network.


- [Modelling and unsupervised learning of symmetric deformable object categories](http://papers.nips.cc/paper/8040-modelling-and-unsupervised-learning-of-symmetric-deformable-object-categories.pdf)


- [From Motion Blur to Motion Flow: a Deep Learning Solution for
Removing Heterogeneous Motion Blur](https://arxiv.org/abs/1612.02583) Generates Motion Flow (Optical Flow) from a Blurred Image. 

- [Removing Camera Shake from a Single Photograph](https://cs.nyu.edu/~fergus/papers/deblur_fergus.pdf) Removing Motion blur using an MAP method.

- [SuperDepth: Self-Supervised, Super-Resolved Monocular Depth Estimation](https://arxiv.org/abs/1810.01849)

- [How do neural networks see depth in single images?](https://arxiv.org/abs/1905.07005)

- [Self-Supervised deep homography estimation with invertibility constraints](https://www.sciencedirect.com/science/article/abs/pii/S0167865519302673)

- [SuperPoint: Self-Supervised Interest Point Detection and Description](https://arxiv.org/abs/1712.07629) Feature point detector and descriptor using a neural network running at 70 FPS on a Titan X from MagicLeap. [<img src="../README/images/logo/document.png" width="24" height="24" />](../PaperSummaries/GeometricDL/SuperPointSummary.pdf) [<img src="../README/images/logo/pytorch.jpg" width="24" height="24" />](https://github.com/MagicLeapResearch/SuperPointPretrainedNetwork)  [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://github.com/rpautrat/SuperPoint).

- [UnsuperPoint: End-to-end Unsupervised Interest Point Detector and Descriptor](https://arxiv.org/abs/1907.04011) Feature point detector and descriptor using a neural network running at 323 FPS on a Titan X trained completely in an unsupervised manner. This is the unsupervised version of SuperPoint. [<img src="../README/images/logo/document.png" width="24" height="24" />](../PaperSummaries/GeometricDL/UnsuperpointSummary.pdf)
