# Transfer-Learning-on-Pytorch
* This repository contains notebooks where I have employed Transfer Learning Technique on PyTorch using different network architectures such as Resnets, GoogLe Net, Inception Net, DenseNets to classify high resolution images which will other wise take thousand of GPU hours to train.
* The Resnet, GoogLenet and DenseNet121 model used here were trained on 1 million images of imagenet database and the trained parameters were downloaded from torchvision datasets library.
* Originally these models were trained to classify among 1000 classes but I have modified the softmax layers of these to classify on two classes.
* only the softmax layer was retrained on our development set by freezing all other layers.
* The classification accuracy of more than 99% was achieved by training the model just for a few minutes on my local machine.
