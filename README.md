# MRI-Alzheimer-Stages-Detection-CNN
dataset: https://www.kaggle.com/datasets/uraninjo/augmented-alzheimer-mri-dataset/data 
##
academic project that aims to teach how to optimize cnn networks and understand the impact of various training parameters on model performance :) (not really focusing on performance here)

## >Assigned instructions for the project:
#### 1. Prepare a dataset for image classification (binary or multiclass). ✅
#### 2. Train a model using the ResNet50 architecture from scratch (without transfer learning) on CPU. ✅
- The obtained results (training time and accuracy) will serve as a baseline for subsequent experiments. 
#### 3. To optimize training speed, apply:
a. GPU acceleration – prepare a comparative report showing training times with and without GPU. ✅\
b. Transfer learning – prepare a comparative report with and without transfer learning; we are particularly interested in reaching a certain accuracy level, e.g., 80%. ✅
#### 4. To optimize accuracy, apply: 
a. Normalization – prepare a comparative report with and without data normalization. \
b. Data augmentation – prepare a comparative report with and without augmentation, including details of the transformations used. \
c. Dropout – prepare a comparative report with and without applying dropout. \
d. Data extension – prepare a comparative report with and without adding a new batch of data. \
e. Different input sizes (e.g., 96x96, 160x160, 224x224) – prepare a comparative report for each size. \
f. Different batch sizes (e.g., 32, 64, 128) – prepare a comparative report for each size. \
g. Different network architectures (e.g., VGG16, ResNet101, InceptionV3, MobileNet) – prepare a comparative report for each architecture (at least 4). 

##
todo
- change dataset to regular not augmented and train again :(
- check variables names 

## 
- https://www.geeksforgeeks.org/image-classification-using-resnet/ 
- https://miroslawmamczur.pl/jak-dzialaja-konwolucyjne-sieci-neuronowe-cnn/
