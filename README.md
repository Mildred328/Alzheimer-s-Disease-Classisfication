#  Alzheimer’s Disease Classification using MRI Images

##  Project Overview

Alzheimer’s Disease (AD) is a progressive neurological disorder that affects memory, thinking, and behavior. Early detection and proper classification of Alzheimer’s stages are critical for effective patient care and treatment planning.

This project focuses on **classifying Alzheimer’s disease stages using brain MRI images**. It is part of the **20 Days Data Project Challenge** and demonstrates how data analysts and data scientists can explore medical image data using **exploratory data analysis (EDA), traditional machine learning, and visualization tools**.

The dataset used is a **multi-class MRI image dataset** containing four Alzheimer’s disease stages, with balanced classes achieved through data augmentation.


## Objectives

* Explore and understand MRI image data related to Alzheimer’s disease
* Perform **EDA** to analyze class distribution and image characteristics
* Extract image features using **Histogram of Oriented Gradients (HOG)**
* Build a **Support Vector Machine (SVM)** classification model
* Evaluate model performance using accuracy, confusion matrix, and classification report
* Visualize insights using **Power BI dashboards**


## Dataset Description

The dataset consists of MRI brain scan images categorized into four classes:

* **Non-Demented** – No signs of Alzheimer’s
* **Very Mild Demented** – Early-stage symptoms
* **Mild Demented** – Noticeable cognitive decline
* **Moderate Demented** – Advanced stage of Alzheimer’s

The dataset is balanced using data augmentation techniques to ensure fair model evaluation.


## Exploratory Data Analysis (EDA)

EDA was performed to better understand the dataset and included:

* Class distribution analysis
* Visual inspection of MRI images
* Image consistency and quality checks
* Feature extraction preparation

These steps helped identify patterns and challenges, especially in distinguishing early-stage dementia.


## Machine Learning Approach

* **Feature Extraction**: Histogram of Oriented Gradients (HOG)
* **Model Used**: Support Vector Machine (SVM)
* **Evaluation Metrics**:

  * Accuracy
  * Confusion Matrix
  * Classification Report (Precision, Recall, F1-score)


## Model Performance

* **Model Accuracy**: **0.716875**
* Best performance observed for **Moderate Demented** cases
* Early-stage classes (**Very Mild Demented vs Non-Demented**) were more difficult to classify due to visual similarity

The results show that the HOG + SVM model provides a solid baseline for Alzheimer’s disease classification.


## Visualization

Power BI was used to create interactive dashboards, including:

* Class distribution charts
* Comparative analysis of Alzheimer’s stages
* Interactive filtering for better insight exploration


## Tools & Technologies

* Python
* NumPy, OpenCV, scikit-learn
* Jupyter Notebook
* Power BI
* Kaggle (Alzheimer’s Multi-Class Dataset)


## Target Audience

* Data analysts exploring image-based datasets
* Beginners in machine learning and healthcare analytics
* Data scientists interested in medical imaging projects


## Conclusion

This project demonstrates an end-to-end workflow for Alzheimer’s disease classification using traditional machine learning techniques. While early-stage detection remains challenging, the model achieves reasonable performance and provides a strong foundation for future improvements using deep learning models such as CNNs.


## Future Improvements

* Apply deep learning models (CNNs, Transfer Learning)
* Improve early-stage classification accuracy
* Experiment with advanced feature extraction techniques
* Hyperparameter tuning for better convergence.


## Author

**Mildred Okonye**  
Data Analyst | Data Scientist  
Interested in Healthcare Analytics, Machine Learning, and AI-driven solutions for real-world problems.
