## GANs and it's improvements
- [Generative Adversarial Networks](https://arxiv.org/abs/1406.2661): The original paper which proposed the concept of GANs. [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://wiseodd.github.io/techblog/2016/09/17/gan-tensorflow/)
![GAN loss](../README/images/gan.png)

- [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434): The first GAN paper which uses a deep convolutional network for generative and discriminative networks. [TensorFlowCodeTutorial](http://bamos.github.io/2016/08/09/deep-completion/) [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://github.com/carpedm20/DCGAN-tensorflow)

- [Conditional Generative Adversarial Nets](https://arxiv.org/abs/1411.1784): Talks about conditioniong latent space based on class. [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://wiseodd.github.io/techblog/2016/12/24/conditional-gan-tensorflow/) [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://github.com/wiseodd/generative-models/blob/master/GAN/conditional_gan/cgan_tensorflow.py)
![CGAN loss](../README/images/cgan.png) 

- [Wasserstein GAN](https://arxiv.org/abs/1701.07875): Improves stability by getting rid of mode collapse problem by using an alternative formulation. [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://wiseodd.github.io/techblog/2017/02/04/wasserstein-gan/) [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://github.com/wiseodd/generative-models/blob/master/GAN/wasserstein_gan/wgan_tensorflow.py)

- [InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets](https://arxiv.org/abs/1606.03657): Talks about priming latent space to learn specific functionality for specific parts of the latent space. [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://wiseodd.github.io/techblog/2017/01/29/infogan/) [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://github.com/openai/InfoGAN)
![infoGAN loss 1](../README/images/infogan1.png) 
![infoGAN loss 2](../README/images/infogan2.png) 

- [GANHacks](https://github.com/soumith/ganhacks): Some hacks by Soumith Chinthala to stabilize GAN training. 

- [Generative Adversarial Text to Image Synthesis](https://arxiv.org/abs/1605.05396): Generates realistic images from text (fine example of zero shot learning). [<img src="../README/images/logo/document.png" width="24" height="24" />](../PaperSummaries/GAN/GANTextToImageSummary.txt)  [<img src="../README/images/logo/torch.png" width="24" height="24" />](https://github.com/reedscot/icml2016) [<img src="../README/images/logo/theano.svg" width="36" height="24" />](https://github.com/paarthneekhara/text-to-image) [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://github.com/zsdonghao/text-to-image)

- [Plug & Play Generative Networks: Conditional Iterative Generation of Images in Latent Space](https://arxiv.org/abs/1612.00005):  This paper introduces an additional prior on the latent code, improving both sample quality and sample diversity, leading to a state-of-the-art generative model that produces high quality images at higher resolutions. [<img src="../README/images/logo/caffe-logo.png" width="48" height="16" />](https://github.com/Evolving-AI-Lab/ppgn)

- [Stabilizing Adversarial Nets With Prediction Methods](https://arxiv.org/abs/1705.07364): Stabilizes GAN training using PDHG methods. 

- [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/abs/1703.10593): Amazing paper on unpaired image to image translation.  [<img src="../README/images/logo/torch.png" width="24" height="24" />](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) [<img src="../README/images/logo/torch.png" width="24" height="24" />](https://github.com/junyanz/CycleGAN)

- [Deep Metric Learning using Triplet Network](https://arxiv.org/abs/1412.6622): Talks about using Triplet loss to learn useful metrics. [<img src="../README/images/logo/torch.png" width="24" height="24" />](https://github.com/eladhoffer/TripletNet)

- [Deep Supervised Hashing with Triplet Labels](http://www.cs.cmu.edu/~kkitani/pdf/WSK-ACCV16.pdf): Concept of using Triplet loss for hashing in neural nets. [<img src="../README/images/logo/matlab-Logo.png" width="24" height="24" />](https://github.com/Minione/DTSH) 

#### TODO
- [ ] Add papers regarding alternative representations to voxels (surfles and so on).
- [ ] Add papers regarding OctTree and QuadTree based repsentations in neural nets for object recognition.

***
