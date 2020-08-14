# DEEP ADVERSARIAL ACTIVE LEARNING WITH MODEL UNCERTAINTY FOR IMAGE CLASSIFICATION
By Zheng Zhu(zzhu@cqu.edu.cn), Hongxing Wang

## Introduction

This is a [PyTorch](https://pytorch.org/) implementation for the paper ["Deep Adversarial Active Learning with Model Uncertainty for Image Classification"] in ICIP2020. It brings the AL models trained on the [CIFAR10/100](https://www.cs.toronto.edu/~kriz/cifar.html),[SVHN](http://ufldl.stanford.edu/housenumbers/) and [Caltech256](http://www.vision.caltech.edu/Image_Datasets/Caltech256/).

<img src="https://github.com/zzzzZZZZ777/AALU-ICIP2020/blob/master/Reference/method.png" width=500 alt="introfig">


## Abstract
Active learning aims at selecting and labeling as few samples as possible to train a good task model. Most existing methods rely on various heuristics to iteratively select a single sample in each active learning loop, thus cannot tackle large datasets effciently. In this paper, we propose a new batchmode active learning method, which can plug model prediction uncertainty into adversarial batch selection to ensure the selected samples are representative in unlabeled data, complementary to labeled data, and beneficial for model training. Experiments on four benchmark image datasets validate the effectiveness and effciency of the proposed method for active image classification in comparison with the state-of-theart methods.

## Citation

If you think this code is useful in your research or wish to refer to the baseline results published in our paper, please use the following BibTeX entry.

```
@article{activeUncertainty2020Zheng,
    author={Zheng Zhu,Hongxing Wang},
    title={Deep Adversarial Active Learning with Model Uncertainty for Image Classification},
    journal={ICIP},
    year={2020}
}
```

## Requirements

  * Python >= 3.5
  * PyTorch ==1.1.0
  * torchvision ==0.3.0
  * numpy==1.16.4
  * scikit-learn==0.21.1
  * scipy==1.2.1

## Environment

The code is developed and tested under 
  * OS: Debian GNU/Linux 9.12 (stretch) x86_64
  * CPU:Intel Xeon E5-2650 v4 (48) @ 2.9GHz
  * GPU:1 NVIDIA TITAN V  cards 
  * CUDA:V10.0.130
  * cuDNN:7.6.4.

## Getting Start
in preparation ...

## IEEE-copyright
© 2020 IEEE. Personal use of this material is permitted. Permission from IEEE must be obtained for all other uses, in any current or future media, including reprinting/republishing this material for advertising or promotional purposes, creating new collective works, for resale or redistribution to servers or lists, or reuse of any copyrighted component of this work in other works.
