# BrainCancer-Detection-Using-Matlab
Classification of Brain MRI scan volumes into chronological age of participants using image processing and deep learning in MATLAB.

We have used brain MRI dataset that is publicly available for our project. We will use this to classify the brain volumes into 3 categories, Ages 3-5, Ages 7-12, Adults. Firstly, we have preprocessed our dataset using many methods available in the Image Processing Toolbox. Pre-processing steps include applying skull stripping, random rotation and image resizing. We then use this augmented dataset for classification. We have used ResNet-18 to extract features from the brain volumes and use the extracted features to train a classification model. The ResNet-18 model is taken from the Deep Learning Toolbox provided by MATLAB. After training the classification model, we will use it to evaluate its predictions on random images from the dataset.

## Architecture of the model

![Model Architecture](https://github.com/Abhishek-Aditya-bs/BrainCancer-Detection-Using-Matlab/blob/main/output-images/5.JPG)

## Output Screenshots

![](https://github.com/Abhishek-Aditya-bs/BrainCancer-Detection-Using-Matlab/blob/main/output-images/1.png)

![](https://github.com/Abhishek-Aditya-bs/BrainCancer-Detection-Using-Matlab/blob/main/output-images/2.JPG)

![](https://github.com/Abhishek-Aditya-bs/BrainCancer-Detection-Using-Matlab/blob/main/output-images/3.JPG)

![](https://github.com/Abhishek-Aditya-bs/BrainCancer-Detection-Using-Matlab/blob/main/output-images/6.JPG)

![](https://github.com/Abhishek-Aditya-bs/BrainCancer-Detection-Using-Matlab/blob/main/output-images/7.JPG)

![](https://github.com/Abhishek-Aditya-bs/BrainCancer-Detection-Using-Matlab/blob/main/output-images/8.JPG)

![](https://github.com/Abhishek-Aditya-bs/BrainCancer-Detection-Using-Matlab/blob/main/output-images/9.JPG)

![](https://github.com/Abhishek-Aditya-bs/BrainCancer-Detection-Using-Matlab/blob/main/output-images/10.JPG)
