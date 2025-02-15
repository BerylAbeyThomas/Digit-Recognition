# Handwritten Digit Recognition using Machine Learning

## Overview
This project focuses on **Handwritten Digit Recognition**, aiming to classify digits (0-9) using various **machine learning algorithms**. The dataset used was **self-collected**, inspired by the MNIST dataset. Multiple classification models were trained and evaluated to determine the best-performing algorithm.

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
The dataset consists of 1500 images of handwritten digits. Each image was converted into a **28x28 pixel grayscale representation**, resulting in **784 numerical features** per sample. A CSV file was created with these pixel values and their corresponding digit labels.

## Installation
To run this project, ensure you have the following dependencies installed:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/handwritten-digit-recognition.git
   cd handwritten-digit-recognition
   ```
2. Run the training script:
   ```bash
   python train.py
   ```
3. To make predictions on new images:
   ```bash
   python predict.py --image path/to/image.png
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
- Implement **Deep Learning (CNNs)** for improved performance.
- Extend the project to support **multiple languages/scripts**.
- Deploy as a **web or mobile application**.

## Contributors
- **Beryl Abey Thomas**
- **Pujala Akhila**
- **Shalini Banerjee**

## License
This project is licensed under the **MIT License**.
