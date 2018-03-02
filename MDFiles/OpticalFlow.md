## Optical Flow
- [FlowNet: Learning Optical Flow with Convolutional Networks](https://arxiv.org/abs/1504.06852): First paper to estimate optical flow using deep learning. Not so great results.

- [FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks](https://arxiv.org/abs/1612.01925):  Improvement of FlowNet paper. Amazing results especially at the boundaries.

- [Optical Flow Estimation using a Spatial Pyramid Network](https://arxiv.org/abs/1611.00850): Super tiny network which gives reasonable optical flow.

- [Fast Optical Flow using Dense Inverse Search](https://arxiv.org/abs/1704.07813): Can control the output quality based on desired speed of algorithm. Traditional optimization without any deep learning.

- [Devon: Deformable Volume Network for Learning Optical Flow](https://arxiv.org/abs/1802.07351): Super small network, results better than SpyNet.

- [PWC-Net: CNNs for Optical Flow Using Pyramid, Warping, and Cost Volume](https://arxiv.org/abs/1709.02371) NVIDIA's amazing deep learning based optical flow. Spectacular results which are better than FlowNet2 and can run at 35fps on a 1024x436 image.
- [Correlation Flow: Robust Optical Flow Using Kernel Cross-Correlators](https://arxiv.org/abs/1802.07078) Impressive results for a frequency based optical flow algorithm which is a one-to-one replacement for the PX4Flow sensor. Can provide linear velocities and yaw rate. Can be used for odometry on a quadrotor.
