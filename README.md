# PneumoDetect Pro
(Project during AI for Healhcare - Udacity)

## Objective:
Quickly and effectively identify positive pneumonia cases from radiological images (DICOM) using a machine learning model. ​

## Key Steps:
Data Preprocessing: Verify DICOM data and generate ground truth for 14 common thoracic pathologies using NLP. ​
Data Augmentation: Normalize and split data into validation and training sets. ​
Model Building: Use a pre-trained model, adjust parameters, and build a custom model. ​
Training and Optimization: Compile the model, train with callbacks, and save the best weights. ​
Validation and Deployment: Evaluate performance, make predictions, and save the final model. ​

## Key Results:
Classification Threshold: Set at 0.40 to maximize true positives. ​
Performance Metrics: ​

Accuracy: 0.452 ​
Precision: 0.310 ​
Recall: 0.692 ​
F1 Score: 0.429 ​


The model prioritizes high recall to capture as many positive pneumonia cases as possible, sacrificing precision. ​

This project emphasizes detecting pneumonia cases with a focus on minimizing false negatives. 

See the report for more details.​

![image](https://github.com/user-attachments/assets/2b734222-bbf1-4087-b3f1-7fe5a74258bc)


![image](https://github.com/user-attachments/assets/6ab6870c-69f6-48e1-940c-2dbf811f7d1c)
