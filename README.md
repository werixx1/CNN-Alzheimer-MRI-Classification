# MRI-Alzheimer-Stages-Detection-CNN
academic project that aims to teach how to optimize cnn networks and understand the impact of various training parameters on model performance :)

### OPTIMIZED MODEL:

| Structure | Img size | Samples | Augmentation | Normalization | Accelerator | Transfer learning | Dropout | Batch size | Epochs |
|-----------|----------|---------|--------------|---------------|-------------|-------------------|---------|------------|--------|
| MobileNet | 224x224  | 12200   | YES          | YES           | GPU         | YES               | NO      | 32         | 16     |

<p align="center">
  <img height="300" width="500" src="https://github.com/user-attachments/assets/107da92c-9c67-4138-adab-23fcd1f059f2" />
  <img height="300" width="500" src="https://github.com/user-attachments/assets/cd9a615e-53ad-4438-a43b-72da3654429b" />
</p>

## 
dataset: https://www.kaggle.com/datasets/uraninjo/augmented-alzheimer-mri-dataset/data 
</br>
(im using non augmented version because of project requirements) \
models raports are on 'project' branch (in polish)

## >Assigned instructions for the project:
#### 1. Prepare a dataset for image classification (binary or multiclass). ✅
#### 2. Train a model using the ResNet50 architecture from scratch (without transfer learning) on CPU. ✅
- The obtained results (training time and accuracy) will serve as a baseline for subsequent experiments. 
#### 3. To optimize training speed, apply:
a. GPU acceleration – prepare a comparative report showing training times with and without GPU. ✅\
b. Transfer learning – prepare a comparative report with and without transfer learning; we are particularly interested in reaching a certain accuracy level, e.g., 80%. ✅
#### 4. To optimize accuracy, apply: 
a. Normalization – prepare a comparative report with and without data normalization. ✅\
b. Data augmentation – prepare a comparative report with and without augmentation, including details of the transformations used. ✅\
c. Dropout – prepare a comparative report with and without applying dropout. ✅\
d. Data extension – prepare a comparative report with and without adding a new batch of data. ✅\
e. Different input sizes (e.g., 96x96, 160x160, 224x224) – prepare a comparative report for each size. ✅\
f. Different batch sizes (e.g., 32, 64, 128) – prepare a comparative report for each size. ✅\
g. Different network architectures (e.g., VGG16, ResNet101, InceptionV3, MobileNet) – prepare a comparative report for each architecture (at least 4). ✅

##
todo
- change dataset to regular not augmented and train again :( ✅
- check variables names ✅

##
todo in the future
- !! get rid of code redundancy !! (make functions that automatically change images input sizes, batch sizes, models etc)

## 
- https://www.geeksforgeeks.org/image-classification-using-resnet/ 
- https://miroslawmamczur.pl/jak-dzialaja-konwolucyjne-sieci-neuronowe-cnn/
- https://www.youtube.com/watch?v=OxYGhiUDJYQ
