 Urdu Handwritten Letter Recognition ✍️

This project focuses on **recognizing handwritten Urdu letters** using a **custom VGG-style Convolutional Neural Network (CNN)**.
The model is designed to achieve good accuracy while keeping the **number of parameters low**, making it efficient and suitable for limited-resource environments.

📊 Dataset
The dataset contains images of **handwritten Urdu letters** collected for classification tasks.

📥 Dataset Link:
https://drive.google.com/drive/folders/1Odk8K3ta-aoBUq2fe4SSVFCjzllIw-Wb?usp=sharing

 How to use the dataset:
1. Download the dataset from the link above
2. Extract it to your local system
3. Update the dataset path inside the notebook according to your directory structure

Example:
python
DATASET_PATH = "D:/datasets/urdu_handwriting/"

📓 Training & Testing
The complete **training and testing pipeline** is implemented in the Jupyter notebook:

📄 Notebook:
"Urdu_letter_handwriting.ipynb"

This notebook includes:

* Data loading and preprocessing
* Model architecture definition
* Model training
* Evaluation and predictions

Run the notebook cell by cell to reproduce the results.

🧠 Model Architecture
* Model Name: **Custom VGG-based CNN**
* Trained Model File:
  📦 "vgg1_urdu_custom.keras"

 Why Custom VGG?

* Inspired by **VGG architecture**
* Custom-built with **fewer parameters**
* Reduces overfitting
* Faster training compared to standard VGG16/VGG19
* Well-suited for handwritten character recognition

The architecture is optimized specifically for **Urdu handwritten letters**, considering dataset size and complexity.

⚙️ Requirements

Install required dependencies:

pip install tensorflow numpy matplotlib opencv-python

 👨‍💻 Author

Safiullah
Final Year BSCS | Artificial Intelligence & Machine Learning
GitHub: [https://github.com/Safiullah455](https://github.com/Safiullah455)

