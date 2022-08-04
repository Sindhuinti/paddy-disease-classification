# Paddy disease detection 🌾

> A Deep learning model build to classify paddy diseases.It is a fine tuned model of RestNet50.

## Problem statement

Rice (Oryza sativa) is one of the staple foods worldwide. Paddy, the raw grain before removal of husk, is cultivated in tropical climates, mainly in Asian countries. Paddy cultivation requires consistent supervision because several diseases and pests might affect the paddy crops, leading to up to 70% yield loss. Expert supervision is usually necessary to mitigate these diseases and prevent crop loss. With the limited availability of crop protection experts, manual disease diagnosis is tedious and expensive. Thus, it is increasingly important to automate the disease identification process by leveraging computer vision-based techniques that achieved promising results in various domains.

## Objective
The main objective of this competition is to develop a machine or deep learning-based model to classify the given paddy leaf images accurately. We provide a training dataset of 10,407 (75%) labeled images across ten classes (nine disease categories and normal leaf). Moreover, we also provide additional metadata for each image, such as the paddy variety and age. Your task is to classify each paddy image in the given test dataset of 3,469 (25%) images into one of the nine disease categories or a normal leaf.

## Libraries used
- Tensorflow
- Keras 
- pandas
- seaborn
- matplotlib

## Model 

![image](https://storage.googleapis.com/kaggle-script-versions/101455916/output/model.png?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=databundle-worker-v2%40kaggle-161607.iam.gserviceaccount.com%2F20220804%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20220804T033327Z&X-Goog-Expires=345599&X-Goog-SignedHeaders=host&X-Goog-Signature=b545b00b180bb4bd8fae8cc8a249f1ee2a8c067efee446852d81219c807b12e21ea66e5d611c9cc6e23d60b1dc9d233a6bcc59337b0d4ff93681e5f41c2e04524dc142b1b901b81eeac65c5da90f5676f5972334415c1fd1247950a5415e37c3835d487cfbffdb4109af4b4d51639206f71b75c12aadd389fa58b928239e4fd522d8f637461482b5f1e2b9105bf2854828f513ebae8cf52a3841a908fcbf2d215ada7808641f433e875a96206764991ce1fae6afd633cb5da3e034d2789551bf27ece4ffa88a500334d1ec2a4fe16f56a13c4f2bfed8ea002b30b7854070b389551564dd1776b62e11e891da348e4bce01f1df2d220369c387467b116dcfa6c0)

## Dataset 

API command for dataset
```
kaggle competitions download -c paddy-disease-classification
```
