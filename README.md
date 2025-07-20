
# 🐱🐶 Cats vs Dogs Image Classification using SVM

This repository contains a Python implementation of a Support Vector Machine (SVM) model to classify images of cats and dogs using the *Kaggle Dogs vs Cats* dataset. The task demonstrates basic image preprocessing and supervised learning techniques for binary classification using classical machine learning.

## 📂 Dataset

- Dataset: [Kaggle lion vs elephant Dataset
- Format: .jpg images of cats and dogs
- Size: ~25,000 labeled images (12,500 cats and 12,500 dogs)

> ⚠ Note: You must download the dataset manually from Kaggle and extract it into the appropriate folder as explained below.

---

## 🛠 Features

- Image preprocessing (resizing, grayscale conversion, flattening)
- Feature extraction using raw pixel values (basic version)
- Binary classification using *SVM (Support Vector Machine)*
- Train-test split
- Accuracy evaluation
- Option to visualize sample predictions

---

## 📁 Folder Structure

cats-vs-dogs-svm/ ├── dataset/ │   ├── train/ │   │   ├── lion.0.jpg │   │   ├── elephant.0.jpg │   │   └── ... ├── svm_classifier.py ├── utils.py ├── requirements.txt └── README.md

---

## ⚙ Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/cats-vs-dogs-svm.git
cd lion-vs-elephant-svm

2. Install dependencies:



pip install -r requirements.txt

3. Download the dataset from Kaggle and extract the train folder into the dataset/ directory.




---

🧪 How to Run

python svm_classifier.py

> You can tweak parameters like image size, number of images, or SVM kernel inside the script.




---

🧠 Model Used

SVM (Support Vector Machine) from scikit-learn

Kernel: Linear (can be changed to RBF or Poly)

Input: Flattened grayscale images (resized to 64x64 or smaller)

Output: Binary classification (0 = lion, 1 = elephant)



---

📊 Sample Output

Loaded 2000 images (1000 cats, 1000 dogs)
Accuracy on test set: 85.6%


---

🖼 Visualizations

Shows random predictions with actual vs predicted labels (optional)

Helps understand classification confidence visually



---

✅ Requirements

Python 3.7+

numpy

scikit-learn

opencv-python

matplotlib (optional for visualization)


pip install numpy scikit-learn opencv-python matplotlib


---

📌 Notes

This is a basic classical ML approach. For higher accuracy, deep learning models like CNNs are preferred.

Ideal for understanding how traditional ML models perform on image data.

Useful for beginners exploring SVM and image classification without heavy compute.



---

📄 License

This project is licensed under the MIT License.


---

🤝 Contributing

Feel free to fork the repository, submit issues or pull requests.
