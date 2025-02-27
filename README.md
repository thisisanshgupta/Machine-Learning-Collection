# Machine Learning Collection
In this repository you will find tutorials and projects related to Machine Learning. I try to make the code as clear as possible, and the goal is be to used as a learning resource and a way to lookup problems to solve specific problems. For most I have also done video explanations on YouTube if you want a walkthrough for the code. If you got any questions or suggestions for future videos I prefer if you ask it on [YouTube](https://www.youtube.com/c/AladdinPersson). This repository is contribution friendly, so if you feel you want to add something then I'd happily merge a PR :smiley:

## Table Of Contents
- [Machine Learning Algorithms](#machine-learning)
- [PyTorch Tutorials](#pytorch-tutorials)
	- [Basics](#basics)
	- [More Advanced](#more-advanced)
    - [Object Detection](#Object-Detection)
	- [Generative Adversarial Networks](#Generative-Adversarial-Networks)
	- [Architectures](#architectures)

## Machine Learning
* [![Youtube Link][logo]](https://youtu.be/pCCUnoes1Po) &nbsp; [Linear Regression](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/algorithms/linearregression/linear_regression_gradient_descent.py) **- With Gradient Descent** :white_check_mark: 
* [![Youtube Link][logo]](https://youtu.be/DQ6xfe75CDk) &nbsp; [Linear Regression](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/algorithms/linearregression/linear_regression_normal_equation.py) **- With Normal Equation** :white_check_mark:
* [![Youtube Link][logo]](https://youtu.be/x1ez9vi611I) &nbsp; [Logistic Regression](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/algorithms/logisticregression/logistic_regression.py)
* [![Youtube Link][logo]](https://youtu.be/3trW5Lig7BU) &nbsp; [Naive Bayes](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/algorithms/naivebayes/naivebayes.py) **- Gaussian Naive Bayes**
* [![Youtube Link][logo]](https://youtu.be/QzAaRuDskyc) &nbsp; [K-nearest neighbors](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/algorithms/knn/knn.py)
* [![Youtube Link][logo]](https://youtu.be/W4fSRHeafMo) &nbsp; [K-means clustering](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/algorithms/kmeans/kmeansclustering.py) 
* [![Youtube Link][logo]](https://youtu.be/gBTtR0bs-1k) &nbsp; [Support Vector Machine](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/algorithms/svm/svm.py) **- Using CVXOPT**
* [![Youtube Link][logo]](https://youtu.be/NJvojeoTnNM) &nbsp; [Neural Network](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/algorithms/neuralnetwork/NN.py)
* [Decision Tree](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/algorithms/decisiontree/decision_tree.py)

## PyTorch Tutorials
If you have any specific video suggestion please make a comment on YouTube :)

### Basics
* [![Youtube Link][logo]](https://youtu.be/x9JiIFvlUwk) &nbsp; [Tensor Basics](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_tensorbasics.py)
* [![Youtube Link][logo]](https://youtu.be/Jy4wM2X21u0) &nbsp; [Feedforward Neural Network](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_simple_fullynet.py)
* [![Youtube Link][logo]](https://youtu.be/wnK3uWv_WkU) &nbsp; [Convolutional Neural Network](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_simple_CNN.py)
* [![Youtube Link][logo]](https://youtu.be/Gl2WXLIMvKA) &nbsp; [Recurrent Neural Network](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_rnn_gru_lstm.py)
* [![Youtube Link][logo]](https://youtu.be/jGst43P-TJA) &nbsp; [Bidirectional Recurrent Neural Network](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_bidirectional_lstm.py)
* [![Youtube Link][logo]](https://youtu.be/g6kQl_EFn84) &nbsp; [Loading and saving model](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_loadsave.py)
* [![Youtube Link][logo]](https://youtu.be/ZoZHd0Zm3RY) &nbsp; [Custom Dataset (Images)](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/Basics/custom_dataset)
* [![Youtube Link][logo]](https://youtu.be/9sHcLvVXsns) &nbsp; [Custom Dataset (Text)](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/Basics/custom_dataset_txt)
* [![Youtube Link][logo]](https://youtu.be/qaDe0qQZ5AQ) &nbsp; [Transfer Learning and finetuning](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_pretrain_finetune.py)
* [![Youtube Link][logo]](https://youtu.be/Zvd276j9sZ8) &nbsp; [Data augmentation using Torchvision](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_transforms.py)
* [![Youtube Link][logo]](https://youtu.be/rAdLwKJBvPM) &nbsp; [Data augmentation using Albumentations](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/Basics/albumentations_tutorial)
* [![Youtube Link][logo]](https://youtu.be/RLqsxWaQdHE) &nbsp; [TensorBoard Example](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_tensorboard_.py)
* [![Youtube Link][logo]](https://youtu.be/y6IEcEBRZks) &nbsp; [Calculate Mean and STD of Images](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_std_mean.py)
* [![Youtube Link][logo]](https://youtu.be/RKHopFfbPao) &nbsp; [Simple Progress bar](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_progress_bar.py)
* [![Youtube Link][logo]](https://youtu.be/1SZocGaCAr8) &nbsp; [Deterministic Behavior](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/set_deterministic_behavior/pytorch_set_seeds.py)
* [![Youtube Link][logo]](https://youtu.be/P31hB37g4Ak) &nbsp; [Learning Rate Scheduler](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_lr_ratescheduler.py) 
* [![Youtube Link][logo]](https://youtu.be/xWQ-p_o0Uik) &nbsp; [Initialization of weights](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/Basics/pytorch_init_weights.py)


### More Advanced
* [![Youtube Link][logo]](https://youtu.be/WujVlF_6h5A) &nbsp; [Text Generating LSTM](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Projects/text_generation_babynames/generating_names.py)
* [![Youtube Link][logo]](https://youtu.be/IHq1t7NxS8k) &nbsp; [Semantic Segmentation w. U-NET](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/image_segmentation/semantic_segmentation_unet)
* [![Youtube Link][logo]](https://youtu.be/y2BaTt1fxJU) &nbsp; [Image Captioning](https://github.com/AladdinPerzon/Machine-Learning-Collection/tree/master/ML/Pytorch/more_advanced/image_captioning)
* [![Youtube Link][logo]](https://youtu.be/imX4kSKDY7s) &nbsp; [Neural Style Transfer](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Pytorch/more_advanced/neuralstyle/nst.py)
* [![Youtube Link][logo]](https://www.youtube.com/playlist?list=PLhhyoLH6IjfzxdlsLrclcCTsS8kIcfWJb) &nbsp; [Torchtext [1]](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Pytorch/more_advanced/torchtext/torchtext_tutorial1.py) [Torchtext [2]](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Pytorch/more_advanced/torchtext/torchtext_tutorial2.py) [Torchtext [3]](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Pytorch/more_advanced/torchtext/torchtext_tutorial3.py)
* [![Youtube Link][logo]](https://youtu.be/EoGUlvhRYpk) &nbsp; [Seq2Seq](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Pytorch/more_advanced/Seq2Seq/seq2seq.py) **- Sequence to Sequence (LSTM)**
* [![Youtube Link][logo]](https://youtu.be/sQUqQddQtB4) &nbsp; [Seq2Seq + Attention](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Pytorch/more_advanced/Seq2Seq_attention/seq2seq_attention.py) **- Sequence to Sequence with Attention (LSTM)**
* [![Youtube Link][logo]](https://youtu.be/M6adRGJe5cQ) &nbsp; [Seq2Seq Transformers](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Pytorch/more_advanced/seq2seq_transformer/seq2seq_transformer.py) **- Sequence to Sequence with Transformers**
* [![Youtube Link][logo]](https://youtu.be/U0s0f995w14) &nbsp; [Transformers from scratch](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Pytorch/more_advanced/transformer_from_scratch/transformer_from_scratch.py) **- Attention Is All You Need**

### Object Detection
[Object Detection Playlist](https://youtube.com/playlist?list=PLhhyoLH6Ijfw0TpCTVTNk42NN08H6UvNq)
* [![Youtube Link][logo]](https://youtu.be/XXYG5ZWtjj0) &nbsp; [Intersection over Union](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/object_detection/metrics/iou.py) 
* [![Youtube Link][logo]](https://youtu.be/YDkjWEN8jNA) &nbsp; [Non-Max Suppression](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/object_detection/metrics/nms.py)
* [![Youtube Link][logo]](https://youtu.be/FppOzcDvaDI) &nbsp; [Mean Average Precision](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/object_detection/metrics/mean_avg_precision.py)
* [![Youtube Link][logo]](https://youtu.be/n9_XyCGr-MI) &nbsp; [YOLOv1 from scratch](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/object_detection/YOLO)
* [![Youtube Link][logo]](https://youtu.be/Grir6TZbc1M) &nbsp; [YOLOv3 from scratch](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/object_detection/YOLOv3)

### Generative Adversarial Networks
[GAN Playlist](https://youtube.com/playlist?list=PLhhyoLH6IjfwIp8bZnzX8QR30TRcHO8Va)

* [![Youtube Link][logo]](https://youtu.be/OljTVUVzPpM) &nbsp; [Simple FC GAN](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/GANs/1.%20SimpleGAN/fc_gan.py)
* [![Youtube Link][logo]](https://youtu.be/IZtv9s_Wx9I) &nbsp; [DCGAN](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/GANs/2.%20DCGAN)
* [![Youtube Link][logo]](https://youtu.be/pG0QZ7OddX4) &nbsp; [WGAN](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/GANs/3.%20WGAN)
* [![Youtube Link][logo]](https://youtu.be/pG0QZ7OddX4) &nbsp; [WGAN-GP](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/GANs/4.%20WGAN-GP)
* [![Youtube Link][logo]](https://youtu.be/SuddDSqGRzg) &nbsp; [Pix2Pix](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/GANs/Pix2Pix)
* [![Youtube Link][logo]](https://youtu.be/4LktBHGCNfw) &nbsp; [CycleGAN](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/GANs/CycleGAN)
* [![Youtube Link][logo]](https://youtu.be/nkQHASviYac) &nbsp; [ProGAN](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/GANs/ProGAN)
* [SRGAN](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/GANs/SRGAN)
* [ESRGAN](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/GANs/ESRGAN)
* [StyleGAN](https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/GANs/StyleGAN) - NOTE: NOT DONE



### Architectures
* [![Youtube Link][logo]](https://youtu.be/fcOW-Zyb5Bo) &nbsp; [LeNet5](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/79f2e1928906f3cccbae6c024f3f79fd05262cd1/ML/Pytorch/CNN_architectures/lenet5_pytorch.py#L15-L35) **- CNN architecture**
* [![Youtube Link][logo]](https://youtu.be/ACmuBbuXn20) &nbsp; [VGG](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/79f2e1928906f3cccbae6c024f3f79fd05262cd1/ML/Pytorch/CNN_architectures/pytorch_vgg_implementation.py#L16-L62) **- CNN architecture**
* [![Youtube Link][logo]](https://youtu.be/uQc4Fs7yx5I) &nbsp; [Inception v1](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Pytorch/CNN_architectures/pytorch_inceptionet.py) **- CNN architecture**
* [![Youtube Link][logo]](https://youtu.be/DkNIBBBvcPs) &nbsp; [ResNet](https://github.com/AladdinPerzon/Machine-Learning-Collection/blob/master/ML/Pytorch/CNN_architectures/pytorch_resnet.py) **- CNN architecture**
* [![Youtube Link][logo]](https://youtu.be/fR_0o25kigM) &nbsp; [EfficientNet](https://github.com/aladdinpersson/Machine-Learning-Collection/blob/master/ML/Pytorch/CNN_architectures/pytorch_efficientnet.py) **- CNN architecture**
