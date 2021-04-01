# final-project-zengtian-deng
final-project-zengtian-deng created by GitHub Classroom

This is the github repository for the pancreas segmentation project using Attn-UNet.

## Setup
The dataset used by the model is from Medical Segmentation Decathlon. The link to get the dataset is

https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2

The above is a google drive link. Please download the ```Task07_Pancreas.tar``` file. Once downloaded, extract the zip file to the directory of your interest, and make sure to change the variable ```dataset_path``` to the extracted directory of the dataset. All notebooks are coded to be used in google colab setting, but can be easily generalized to general setting in Linux systems. Shell commands in Windows system are not supported.

## Training
For UNet training, please run the ```UNet.ipynb``` notebook, for Attention UNet, please run the ```Attn_UNet.ipynb``` notebook. 

Please be noted that the notebook uses Cache dataset which requires very large RAM. Make sure to adjust ```cache_rate``` parameter according to the availible RAM.

## Inference

Similarly, run ```UNet_Inf.ipynb``` for U-Net inference and run ```Attn_UNet_Inf.ipynb``` for Attention U-Net inference

## Pre-trained Model

Due to the size of the model checkpoint, the pretrained model are accessible through the link below:

Attention UNet with (64,128,256,512,1024) channel:

https://drive.google.com/file/d/1tD74Hg7kwRFHqIfM_5vyJKS2A4HcS1g8/view?usp=sharing

UNet with (64,128,256,512,1024) channel:

https://drive.google.com/file/d/1gxRkeXIrSvNAdBVp4fFYFDVAMOnhs03N/view?usp=sharing
