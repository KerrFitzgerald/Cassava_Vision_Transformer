# Cassava_Vision_Transformer
Kaggle Cassava Disease Classification Competition: Vision Transformer Results

This repositiory contains my Kaggle notebooks for the Kaggle Cassava Disease Classification Competition: https://www.kaggle.com/c/cassava-leaf-disease-classification 

The aim of the challenge was to classify images of cassava leaves into four disease categories or a fifth category indicating a healthy leaf. The overall goal of the challenge was to enable farmers to quickly identify diseased plants, potentially saving their crops before they inflict irreparable damage.

PyTorch was used to enable a pre-trained (on ImageNet) Vision Transformer (ViT) network to perform single label classification of leaf images. The pre-trained model is available at: https://github.com/rwightman/pytorch-image-models

The implemented ViT network used image patch sizes of 16x16 pixels with the overall image size being set at 224x224 pixels. My team acheived 84.9% classification accuracy.

![image](https://user-images.githubusercontent.com/60627318/116540304-e0f20f00-a8e1-11eb-9cc7-f168eeda528d.png)

