
# Deep Descriptor Transforming (DDT) for Object Co-localisation

![DDT Example](https://github.com/tonyscan6003/etivities/blob/main/etivity3_assignment_img.JPG?raw=true)

## Introduction
This project focuses on object co-localisation using the Deep Descriptor Transforming (DDT) Technique. Object co-localisation involves identifying objects of the same class across various images. This technique showcases that spatial information is retained within Deep Neural Networks trained for classification. This data can be used to create region proposals or for direct object detection.

## Deep Descriptor Transforming (DDT)
The DDT Technique allows for object co-localisation in an unsupervised manner, utilizing the feature map outputs of a pre-trained network. This approach is advantageous as it negates the need for bounding box information to adjust the pre-trained network for localisation. More details can be found in the [original DDT paper](https://arxiv.org/pdf/1707.06397.pdf).

## Notebook Structure
1. **Initial Setup**: Cloning necessary repositories and importing required packages.
2. **Import Dataset**: Retrieving the Stanford Dogs dataset.
3. **Data Preprocessing**: Creating training and test splits, and scaling images.
4. **VGG Model Setup**: Importing and setting up the VGG-16 model.
5. **Feature Map Extraction**: Extracting output feature maps from the VGG model.
6. **DDT Algorithm**: Implementation of the DDT algorithm for object co-localisation.

## Potential Applications
The DDT technique's ability to identify objects across various images has several practical applications, including:
- **Image Search Engines**: Enhancing search results by identifying similar objects across a wide range of images.
- **Surveillance**: Tracking specific objects across various camera feeds.
- **E-commerce**: Identifying similar products across different listings.


