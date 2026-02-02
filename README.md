# Breast-Cancer-Classification-False-Negatives-comparison
Comparative analysis of four machine learning models for breast cancer classification, emphasizing accuracy and false negative detection.

## Project Overview
This project compares 4 different machine learning models to classify breast cancer tumors as malignant or benign based on medical data. The aim is to compare model performance with focus on reducing false negative predictions.

## Dataset
The dataset contains features related to tumor characteristics such as radius, texture, smoothness, and symmetry.

## Models Used
- Logistic regression  
- Random Forest
- KNN
- SVM
  
## Technologies Used
- Python  
- Jupyter Notebook  
- Scikit-learn  
- Pandas  
- NumPy  

## How It Works
The data is preprocessed and split into training and testing sets.  
Four machine learning models are trained and evaluated to compare accuracy .
In medical diagnosis, recall is specially important in order to eliminate the risks of false negative predictions.
The model then compares the accuracy and recall values of the four models.
The best model is then selcted considering both accuracy and recall value.

## Results
   ## -Confusion Matrix
  <img width="311" height="106" alt="image" src="https://github.com/user-attachments/assets/ae9225d9-8b24-49de-8d0f-fb9fa2d22c94" />
  <img width="319" height="114" alt="image" src="https://github.com/user-attachments/assets/c697ff28-d818-4a59-b47c-3d94e0b86682" />
  <img width="308" height="117" alt="image" src="https://github.com/user-attachments/assets/ad90816c-807b-4247-a77d-6c4f24f8eb68" />
  <img width="315" height="116" alt="image" src="https://github.com/user-attachments/assets/9290af50-3faf-48c9-8d53-414118a25e0e" />

   ## -Accuracy Comparison
   <img width="448" height="277" alt="image" src="https://github.com/user-attachments/assets/41cecb2c-56c2-43cb-8a9d-fa56e875e6ba" />
   
   ## -Recall Comparison 
  <img width="432" height="285" alt="image" src="https://github.com/user-attachments/assets/77c5a546-6e4d-4cbb-8bd0-1ffb3d226bc5" />

## Conclusion
Among the four models SVM prformed best in terms of both accuarcy and recall, making it the most effective model for breast cancer classification.
