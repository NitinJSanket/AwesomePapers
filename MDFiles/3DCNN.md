## 3D Neural Networks
- [Beam Search for Learning a Deep Convolutional Neural Network of 3D Shapes](https://arxiv.org/abs/1612.04774): Paper presents methods to fine-tune architecture by adding or removing neurons for 3D object recognition using Voxel Grids (useful for changing architecture to start adding layers to grow the network to account for new classes).

- [Learning to Generate Chairs, Tables and Cars with Convolutional Networks](https://arxiv.org/abs/1411.5928): Paper presents a method to take input as class, view and transformation parameters to generate images of chairs with segmentation masks (good to derive ideas on priming the latent space). Note that this paper does not use a GAN but only a CNN.   [<img src="../README/images/logo/document.png" width="24" height="24" />](../PaperSummaries/3DCNN/GeneratingChairCNNSummary.txt)

- [Learning a Probabilistic Latent Space of Object Shapes via 3D Generative-Adversarial Modeling](https://arxiv.org/abs/1610.07584): Paper presents a method to generate single object class from a latent space (useful starting point for single class).  [<img src="../README/images/logo/document.png" width="24" height="24" />](../PaperSummaries/3DCNN/GAN3DLatentSpaceArithmetic.txt) [<img src="../README/images/logo/torch.png" width="24" height="24" />](https://github.com/zck119/3dgan-release) [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://github.com/meetshah1995/tf-3dgan)(../PaperSummaries/3DCNN/GAN3DLatentSpaceArithmetic.txt)


- [3DMatch: Learning Local Geometric Descriptors from RGB-D Reconstructions](https://arxiv.org/abs/1603.08182): Paper presents a feature extractor to match shapes in 3D voxel grids (useful to get a score metric of how close shapes are). [<img src="../README/images/logo/matlab-Logo.png" width="24" height="24" />](https://github.com/andyzeng/3dmatch-toolbox)

- [A Point Set Generation Network for 3D Object Reconstruction from a Single Image](https://arxiv.org/abs/1612.00603): Paper presents a method to obtain 3D point set from a single image which is an alternative repesentation to voxel grids (less lossy than voxel grids and can be useful for us). [<img src="../README/images/logo/document.png" width="24" height="24" />](../PaperSummaries/3DCNN/GuibasImageTo3DSummary.txt)

