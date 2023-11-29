# CARDIOVISION: REAL-TIME ECG IMAGE-BASED HEART DISEASE DETECTION USING DEEP LEARNING
Dataset ECG: https://data.mendeley.com/datasets/gwbz3fsgp8/2 
save it in folder name as : "ECG_data"
# Introduction
Cardiovascular diseases (CVD) are global health concerns that can be reduced through early prevention and improved patient risk assessment and treatment. 
Early detection of CVD is critical for saving lives and reducing mortality rates. This project is primarily focused on introducing an innovative approach to CVD detection deep learning techniques for image analysis. 
A widely available dataset from Mendeley was utilized for model training, aiming to enhance the precision of heart disease detection.
# Dataset Source: Mendeley provided a globally available dataset used for model training.
•	Categories for Classification: The ECG images were categorized into four classes:
1.	Normal
2.	Myocardial Infarction
3.	Abnormal Heartbeat
4.	History of Myocardial Infarction
•	Total Images: 16,704 images were extracted from the Mendeley dataset.
•	Training Data: 9,600 images (80%) were allocated for training the model.
•	Testing Data: 2,400 images (20%) were reserved for testing the model.

# Data Preprocessing and Lead Segmentation
•	Resizing and cropping ECG images for standardization.
•	Background removal using grayscale conversion, thresholding, and morphological operations.
•	Extraction of 12 leads (I, II, III, aVR, aVL, aVF, V1-V6) and their negative versions.
•	Logical progression in pixel coordinates for consistent and accurate segmentation.

# CNN Architecture
•	Development of Convolutional Neural Network (CNN) for feature extraction.
•	Utilization of Conv2D, MaxPooling2D, and Dense layers for pattern recognition.
•	Optimization with Adam optimizer, sparse categorical cross-entropy loss, and class balancing.

# Outcomes:
•	The aim of this study to proposed a Deep Learning CNN-based model for the detection of heart diseases.
•	The CNN architecture performs well, achieving an accuracy of 89% with a loss of 42%
•	The findings of this study can be used as a foundation for the advanced detection of different heart diseases.


