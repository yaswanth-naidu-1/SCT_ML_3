# 🐘🦁 Elephants vs Lions Image Classification using SVM

This repository contains a Python-based implementation of a *Support Vector Machine (SVM)* model to classify images of *elephants* and *lions. The dataset is sourced from **Kaggle*, and the goal is to build a simple image classifier for wildlife recognition using traditional machine learning.

---

## 📂 Dataset

- *Dataset*: Elephants and Lions Image Dataset from [Kaggle](https://www.kaggle.com/)
- *Data Format*: .jpg images labeled as either elephant or lion
- *Folder Structure*:

dataset/ ├── elephant/ │   ├── elephant_1.jpg │   ├── ... ├── lion/ │   ├── lion_1.jpg │   ├── ...

> ⚠ You need to manually download and extract the dataset from Kaggle into the dataset/ directory.

---

## 📌 Features

- Image Preprocessing: resize, grayscale conversion, flattening
- Feature Extraction: raw pixel intensities
- Model: *Support Vector Machine (SVM)* using scikit-learn
- Binary Classification: Elephant vs Lion
- Train-Test split and Accuracy Evaluation

---

## 🚀 Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/your-username/elephants-vs-lions-svm.git
cd elephants-vs-lions-svm

2. Install required Python libraries

pip install -r requirements.txt

3. Prepare the dataset

Place the elephant/ and lion/ folders inside the dataset/ directory.

4. Run the model

python svm_classifier.py


---

🧠 Model Details

Algorithm: Support Vector Machine (SVM)

Library: scikit-learn

Kernel: Linear (can be changed to RBF or Polynomial)

Input: Resized grayscale image (e.g., 64x64)

Output: 0 = Elephant, 1 = Lion



---

🖼 Sample Output

Loaded 1000 images (500 elephants, 500 lions)
Training Accuracy: 91%
Test Accuracy: 87.4%


---

✅ Requirements

Python 3.7+

numpy

opencv-python

scikit-learn

matplotlib (optional)


Install with:

pip install numpy opencv-python scikit-learn matplotlib


---

🧠 Use Cases

Wildlife image classification

Zoology or animal behavior projects

Low-resource animal recognition systems using classical ML



---
