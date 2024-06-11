# Satellite-Image-Segmentation
**Topic : Satellite Image Segmentation** <br>
**Problem Statement : Land Use Land Cover classification Using Satellite Images and Deep Learning** <br>
**Selected Pre-trained Model : VGG16** <br>
**Dataset : https://www.kaggle.com/datasets/apollo2506/eurosat-dataset/data**

## Steps :
1) Importing Libraries: 'numpy', 'pandas', 'matplotlib', 'seaborn', 'sklearn', 'keras'

2) Dataset Loading : <br>
Defined dataset folder path. <br>
Loaded training, validation, and test datasets into pandas DataFrames. <br>

3) Dataset Analysis : <br>
Computed sizes of training, validation, and test sets. <br>
Printed dataset sizes for understanding distribution. <br>

4) Image Data Preparation : <br>
Set image dimensions (64x64) and batch size (32). <br>
Created ImageDataGenerator instances for data augmentation and preprocessing. <br>

5) Model Architecture (VGG16) : <br>
Used a pre-trained VGG16 model. <br>
Convolutional layers with 3x3 filters and same padding. <br>
Max pooling layers with 2x2 pool size and stride of 2. <br>
Flattening layer to convert 3D feature maps to 1D feature vectors. <br>
Fully connected layers with ReLU activation. <br>
Softmax activation for output layer. <br>

6) Model Training : <br>
Detailed structure of the VGG16 architecture discussed, emphasizing the layers and their configurations. <br>

7) Model Summary : <br>
Provided a summary diagram of the VGG16 model architecture. <br>
