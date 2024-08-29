Blood Cancer and Pancreatic Cancer Classifier using CNN
Overview
This project is focused on developing a robust machine learning model for the early detection and classification of blood cancers and pancreatic cancer. The model leverages Convolutional Neural Networks (CNNs) for image classification and integrates statistical analysis of blood samples to enhance diagnostic accuracy.

Project Goals
The primary objective is to create a reliable system capable of identifying and categorizing blood cancers based on microscopic images of blood samples. The model is designed to classify images into one of the following four categories:

PreB - Pre-B lymphoblasts.
Early PreB - Early Pre-B lymphoblasts.
PostB - Post-B lymphocytes.
Benign - Non-cancerous cells.
In addition, the model is extended to incorporate statistical data from blood samples, which plays a crucial role in diagnosing pancreatic cancer. This two-pronged approach ensures that the model is not only effective in identifying blood cancer types but also in assessing the likelihood of pancreatic cancer, providing a comprehensive diagnostic tool.

Methodology
1. Data Collection and Preprocessing
Blood Sample Images: The dataset consists of labeled blood sample images, categorized into the four mentioned groups. The images undergo preprocessing steps such as normalization, resizing, and augmentation to improve model generalization.
Statistical Data: Relevant statistical data from blood tests is collected, normalized, and integrated into the model pipeline for pancreatic cancer classification.
2. Model Architecture
CNN Design: A Convolutional Neural Network (CNN) is designed and trained to classify the blood sample images. The architecture includes multiple convolutional layers, pooling layers, and fully connected layers, optimized for image recognition tasks.
Integration with Statistical Data: The model also takes statistical data as input, which is processed through dense layers and then merged with the CNN output to make the final prediction. This combined approach enhances the model’s ability to detect pancreatic cancer.
3. Training and Evaluation
The model is trained using a labeled dataset with split training and validation sets to monitor performance and prevent overfitting.
Evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess the model’s performance on the test set.
4. Deployment
The trained model is packaged and deployed in a user-friendly interface, where medical practitioners can upload blood sample images and input statistical data to receive a diagnostic classification.
Blood cancer Dataset - https://www.kaggle.com/datasets/jayaprakashpondy/blood-cancer-dataset
