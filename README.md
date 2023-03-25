# Image Classification Using Custom CNN Model

## Contributors:
---
Author: Masood Ahmed <br>
Email: masood20@connect.hku.hk<br>

---

## Description:

E-commerce has changed the business world and the way we purchase items.
One common problem faced by the e-commerce owner/platform is to tag appropriate
labels with images of products so that those products can pop out when
a relevant query is entered. Unfortunately, human annotation is expensive and
error-prone. Thus, an automated solution that can identify the tags of images
is needed. The goal of this project is to create a classifier that can identify the label
of a fashion product image using CNN and iterative improve the performance
of your model by image augmentation and tunning of Hyper-parameters.

### Link to the dataset:
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small

The test.cv and train.csv can also be found in this repository.

## Explanation on Part 1:

In part one, we create a basic CNN model that can identify if
an image is related to the following 13 subcategories: Topwear, Bottomwear,
Innerwear, Bags, Watches, Jewellery, Eyewear, Wallets, Shoes, Sandal, Makeup,
Fragrance, Others. More specially, we are given a dataset containing 44,441
fashion product images. we are also given two files, i.e., train.csv and test.csv
containing the meta-data (image id, label, productDisplayName) related to each
image.

## Explanation on Part 2:

In part two, we create two enhanced models, leveraging the following two methods:

- Tuning one hyper-parameter and explain why this is worth to tune.
- Data augmentation, i.e., generating more images for training.



*Thank you for reading. Stay happy and stay safe :)*