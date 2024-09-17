# BrainTumor_ML
CNN-driven Model for Brain Tumor Identification

## 1. Image Classification Task. 
The central nervous system (comprising the brain and spinal cord) oversees numerous biological 
functions, including coordination, analysis, decision-making, command issuance, and synthesis 
. The realm of medical imaging holds paramount significance in the timely identification and 
diagnosis of brain tumors. Yet, the arduous task of manually deciphering MRI scans in search of 
these elusive tumors not only consumes valuable time but also leaves room for human fallibility, 
casting shadows of doubt upon the accuracy of the interpretation. 
It is critical to provide healthcare professionals with an automated and accurate system that can 
detect and classify brain tumors in MRI images in order to aid in early detection and diagnosis. 
The objective of this project is to build a CNN-based system that performs binary classification on 
MRI brain images to detect the presence of tumors. In the early detection and diagnosis of brain 
tumors, it improves patient outcomes and treatment planning. 
## 2. Dataset Selection. 
In this project, the integration of two distinct brain tumor datasets significantly contributes to 
advance the research and development endeavors. These datasets, namely the ["Brian Tumor 
Dataset"](https://www.kaggle.com/preetviradiya), and ["Br35H:: Brain Tumor Detection"](https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection), both offer valuable resources for analysis 
and model training. 
The "Brian Tumor Dataset" comprises 4514 images, among which 2087 depict tumor presence 
and 2427 depict tumor absence. On the other hand,  "Br35H:: Brain Tumor Detection" dataset 
includes three folders: "yes," "no," and "pred," containing a total of 3060 Brain MRI Images. 
However, for our project, we focus solely on the "yes" and "no" folders. 
The merged dataset contains a total of 7198 images, 3576 of them are healthy brain images, and 
3622 are MRI scans depicting tumor within the brain, and all images has 3 channels, we 
preprocessed the images by converting them to RGB format, resizing them to a standardized 
dimension of 128x128 pixels. 
## 3.Model selection and Parameter Tuning. 
we concentrated on adjusting the crucial learning rate hyperparameter to enhance model convergence and performance during training. Through manual tuning, we explored various learning rate values, including 1e-4, alongside adjusting the dropout rate to 0.4 to prevent overfitting. Monitoring metrics like accuracy, precision, recall, and F1-score on the validation set aided in pinpointing the optimal learning rate for improved overall performance. Additionally, we assessed alternative CNN architectures like MobileNet and ResNet50 to gauge their performance relative to our baseline model, emphasizing performance metrics such as accuracy, sensitivity, specificity, and area under the ROC curve throughout the process. The goal was to craft a reliable tumor detection model capable of accurately classifying brain MRI images by fine-tuning hyperparameters and evaluating model performance iteratively.
## 4.Results.
CNN Accuracy: 98%, MobileNet Accuracy: 77%, ResNet Acuuracy: 52%.




