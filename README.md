# Dog Breed Classifier with PyTorch

## Project Overview

Hello there !

This project is to showcase the use of Deep Learning with a pretrained VGG16 Deep Neural Network for the classification of dog breeds from dog images using PyTorch.

This project was developed as capstone project for the Machine Learning NanoDegree offered by Udacity.

Artificial Neural Networks have rapidly growing applications in the area of image-based classification problems. Moreover, recent advances in the ANN technology allows for the use/reuse of pre-trained Deep Artificial Neural Networks (e.g. AlexNet, Resnet, VGG, and others) that were trained to recognize thousands of different categories by sifting through millions of high resolution images. This re-utilization of pretrained Deep Neural Networks belongs to a field of Machine Learning called “Transfer Learning” where these pre-built models can be repurposed to be utilized in numerous applications of image recognition and classification.

Recognizing the breeds of dogs is certainly a challenging task. The estimated number of known dog breeds ranges between 200 and 350 different breeds, making the task of telling “which breed a dog belongs to” a very challenging task. This task gets more difficult when the breeds are visually similar and cannot be easily distinguished.

## Project Instructions

1. Clone the repository and navigate to the downloaded folder.
```	
git clone https://github.com/kurdi1mans/Dog_Breed_Classifier_with_PyTorch.git
cd dog-project
```

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.

3. Before you proceed, you need to check the integrity of the data as it may contain corrupted files. You may use the script in `verify_images.ipynb` to verify the integrity of the image files. If you find one corrupt image, you may deleted it. If you find more, you have to re-download the data as it may have been corrupted during download.

4. In order for the data to be ready for processing, the data folders in dogImages need to be renamed to a numerical encoding by the script in `Rename_data_folders.ipynb`. This script will also provide a JSON output containing the mapping between the numerical encodings and the names of the dog breeds.

5. Open the notebook.
```
jupyter notebook Dog_Breed_Classifier_with_Pytorch.ipynb
```

## Project Report

For an easy read on the work done in this project, you may read the `Project Report.pdf` to walk you through the main steps of building and training a deep neural net for dog breed recognition.