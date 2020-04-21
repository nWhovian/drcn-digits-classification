# Domain Adaptation for Digits Classification
#### train on SVHN dataset, test on MNIST
For the domain adaptation I use the **Deep Reconstruction-Classification Network (DRCN)**.
![](https://imgur.com/5Ggxr8D.png)

The model is based on a convolutional architecture that has two pipelines with a shared encoding representation. First pipeline is a convolutional network for label prediction based on the source data, second pipeline is a convolutional autoencoder for target data reconstruction. Including the reconstruction of target data among with a standard label classifier helps to implement the domain adaptation.
The model is based on a [paper](https://arxiv.org/pdf/1607.03516.pdf) and a [code](https://github.com/fungtion/DRCN).

##Results
![](https://imgur.com/fsKTJcR.png)
