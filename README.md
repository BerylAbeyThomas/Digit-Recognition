# Handwritten Digit Recognition using Machine Learning

## Overview
This project focuses on Handwritten Digit Recognition, aiming to classify digits (0-9) using various machine learning algorithms. The dataset used was self-collected, inspired by the MNIST dataset. Multiple classification models were trained and evaluated to determine the best-performing algorithm.

## Workflow
![image](https://github.com/user-attachments/assets/fa072264-2f70-4a60-9e30-930f09b827d3)


## Features
- **Custom Dataset**: Collected and preprocessed 1500 handwritten digit images.
- **Machine Learning Models**:
  - Logistic Regression
  - Random Forest (Entropy & Gini Index)
  - k-Nearest Neighbours (k-NN)
  - Support Vector Machines (SVM)
  - Ensemble Methods (Bagging, XGBoost, AdaBoost)
- **Preprocessing Steps**:
  - Image resizing (28x28 pixels)
  - Binarization & grayscale conversion
  - Data augmentation for better generalization
- **Performance Evaluation**:
  - Accuracy, Precision, Recall, and F1-Score
  - **Best model: SVM with Polynomial Kernel (94.33% accuracy)**

## Dataset
The dataset consists of 1500 images of handwritten digits. Each image was converted into a 28x28 pixel grayscale representation, resulting in 784 numerical features per sample. A CSV file was created with these pixel values and their corresponding digit labels.

#### 1. Sample digit
![image](https://github.com/user-attachments/assets/0a3f6d96-4792-497a-9e5a-ddd3828074b5)

#### 2. Extracting pixels
![image](https://github.com/user-attachments/assets/4e27758a-5d3a-44b4-be72-7e5301d7fe72)

#### 3. Coverting pixels to comma separated strings
![image](https://github.com/user-attachments/assets/f7228260-c01b-4f55-ad0d-ad54af30964c)

#### 4. Loading the .csv file
![image](https://github.com/user-attachments/assets/db1c0576-694f-4602-a07c-e9379ac3f92b)

## Installation
To run this project, ensure you have the following dependencies installed:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Results
| Model | Accuracy |
|--------|------------|
| k-NN (k=3) | 94.16% |
| SVM (Poly Kernel) | 94.33% |
| MLP (Logistic Activation) | 92.00% |
| Bagging with KNN | 92.91% |
| XGBoost | 92.83% |

## Future Improvements
- Implement Deep Learning (CNNs) for improved performance.
- Extend the project to support multiple languages/scripts.
- Deploy as a web or mobile application.

## Contributors
- **Beryl Abey Thomas**
- **Pujala Akhila**
- **Shalini Banerjee**
