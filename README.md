# Brain MRI Image Segmentation with U-Net
This network architecture in this project is based on the original U-Net publication [U-Net: ConvolutionalNetworks for Biomedical Image Segmentation](https://arxiv.org/pdf/1505.04597.pdf). The codes in this repo are mainly developed in Python and GoogleColab.

## Table of contents

<!--ts-->
   * [Introduction](#Introfuction)
   * [Requirements](#Requirements)
   * [Results](#Results)
   * [Acknowledgements](#Acknowledgements)
<!--te-->


## Introduction
The U-Net architecture of this project consists of an encoder and a decoder part that together givethe network an U-shaped form. The encoder part follows a traditional architecture of aconvolutional network. Each layer consists of a repeated 3x3 padded double convolutions, followed by batch normalization and a rectifier linear units (ReLU) activation.  The output feature map is stored as a skip connection which will later be concatenated to the decoder part. Moving downwardsthrough the network, a down sampling is performed by a 2x2 max pooling operation with a stride of2, which doubles the number of feature channels.

## Requirements
- Python  3.9.1
- PyTorch 1.8.1
- CUDA toolkit 10.2
- Albumentations

## Results


<!-- CONTACT -->
## Contact

Chieh-Ju Wu (Jeremy) - jeremy.cjwukth@gmail.com
Fredrik Mazur - fredrik@mazur.se
Niclas Määttä - niclas.maatta@hotmail.com
Daniel Grönås - daniel.gronas@hotmail.com
