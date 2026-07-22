# 🩺 Chest X-ray Disease Classification using CNN & DenseNet121

A Deep Learning project that classifies chest X-ray images into **COVID-19**, **Pneumonia**, and **Normal** categories using **Custom CNN** and **DenseNet121 (Transfer Learning)**. The project compares both models based on their classification performance and demonstrates the use of transfer learning for medical image analysis.



## 📌 Project Overview

Chest X-ray imaging is widely used for diagnosing lung diseases. This project aims to develop an automated image classification system capable of detecting three categories:

- 🦠 COVID-19
- 🫁 Pneumonia
- ✅ Normal

Two different deep learning models were implemented and compared:

- **Custom Convolutional Neural Network (CNN)**
- **DenseNet121 (Transfer Learning)**


## 📂 Dataset

**Source:** Kaggle

### Dataset Statistics

| Class | Number of Images |
|--------|-----------------:|
| COVID | 2,313 |
| Normal | 2,313 |
| Pneumonia | 2,313 |
| **Total Images** | **6,939** |

- Image Size: **224 × 224**
- Number of Classes: **3**



## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- OpenCV
- Jupyter Notebook
- Streamlit



## 🧠 Models Used

### 1. Custom CNN
A Convolutional Neural Network built from scratch using:
- Conv2D
- MaxPooling2D
- Dropout
- Dense Layers
- Softmax Output Layer

### 2. DenseNet121
Transfer Learning model using:
- ImageNet Pre-trained Weights
- Global Average Pooling
- Dense Layers
- Dropout
- Softmax Classifier



## 🔄 Project Workflow


                                             Chest X-ray Images
                                                      │
                                                      ▼
                                              Data Preprocessing
                                                      │
                                                      ▼
                                               Data Augmentation
                                                      │
                                                |──────────────|
                                                ▼              ▼
                                          Custom CNN     DenseNet121
                                                │              │
                                                ▼              ▼
                                           Training      Transfer Learning
                                                │              │
                                                └──────┬───────┘
                                                       ▼
                                                Model Evaluation
               ▼
     Performance Comparison
               ▼
      Best Model Selection
               ▼
     Prediction on New Images


## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report



## 📁 Project Structure


Chest-Xray-Disease-Classification/
│
├── notebooks/
│   ├── 01_Data_Preprocessing.ipynb
│   ├── 02_Custom_CNN.ipynb
│   ├── 03_DenseNet121.ipynb
│   └── 04_Model_Comparison.ipynb
│
├── models/
│   ├── cnn_model.keras
│   └── densenet121.keras
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE


## 🚀 Features

- Chest X-ray Disease Classification
- Custom CNN Implementation
- DenseNet121 Transfer Learning
- Data Augmentation
- Model Performance Comparison
- Confusion Matrix
- Classification Report
- Prediction on New Images
- Streamlit Web Application



## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/SHIVAM0505ai/Chest-Xray-Disease-Classification.git
```

Go to the project directory:

```bash
cd Chest-Xray-Disease-Classification
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```



## 📈 Future Improvements

- Add ResNet50 and EfficientNetB0 for comparison
- Implement Grad-CAM for model interpretability
- Hyperparameter tuning
- Deploy the application on the cloud
- Dockerize the application



## 👨‍💻 Author

**Shivam Jha**

- 🎓 B.Tech CSE (Data Science)
- 💻 Aspiring AI/ML Engineer

**GitHub:** https://github.com/SHIVAM0505ai

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
