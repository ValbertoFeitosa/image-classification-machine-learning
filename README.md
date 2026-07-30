# 🖼️ Image Classification using Machine Learning and Deep Feature Extraction

## 📌 Overview

This project presents a complete Computer Vision pipeline for image classification using classical Machine Learning algorithms and deep feature extraction techniques.

Unlike many image classification projects that rely exclusively on benchmark datasets, this work includes the creation of a **custom image dataset**, assembled specifically for this study.

The project covers the entire workflow of a Computer Vision application, including data collection, dataset construction, image preprocessing, feature extraction, model training, and performance evaluation.

Two different approaches are explored:

- Image classification using classical Machine Learning algorithms.
- Image classification using deep feature extraction with EfficientNet.

The objective is to compare different classification strategies while reproducing a realistic Computer Vision development process.

---

# 🎯 Objectives

The main objectives of this project are:

- Build a custom image dataset.
- Organize images into predefined classes.
- Preprocess image data.
- Extract image features.
- Compare Machine Learning classifiers.
- Evaluate model performance.
- Explore Transfer Learning using EfficientNet.

---

# 💡 Project Contributions

This project goes beyond simply training Machine Learning models.

The work involved the complete development of a Computer Vision pipeline, including:

- Definition of the classification problem;
- Research and collection of images;
- Construction of a custom dataset;
- Image preprocessing;
- Feature extraction;
- Model training;
- Model comparison;
- Performance evaluation.

The goal was to simulate a real-world Computer Vision project, where collecting and preparing data is often one of the most important stages of the entire pipeline.

---

# 📂 Dataset

Unlike many Computer Vision projects that use publicly available benchmark datasets, this project uses a **custom-built image dataset**.

The dataset was created specifically for this study through the following process:

- Research and selection of publicly available images from Internet sources;
- Manual organization of the images into predefined classes;
- Image preprocessing and quality verification;
- Construction of a structured dataset for Machine Learning experiments.

Creating the dataset was an important part of this project because it reproduces a common real-world scenario in Computer Vision, where data collection and organization are often necessary before model development.

### Expected Dataset Structure

```
data/
│
├── Class_01/
├── Class_02/
├── Class_03/
├── ...
└── Class_N/
```

---

# ⚠️ Dataset Availability

The original image dataset is **not included** in this repository.

The images used in this project were collected from publicly available Internet sources exclusively for educational and research purposes. Since many of these images may still be protected by copyright or subject to their respective licenses, they are **not redistributed** in this repository.

Only the source code, notebook, and documentation are made available.

Researchers, students, and practitioners interested in reproducing the experiments are encouraged to create their own dataset following the methodology described in this project.

---

# 🧹 Image Preprocessing

Before training the models, the following preprocessing steps were performed:

- Image loading
- Image resizing
- Image normalization
- Feature vector generation
- Dataset organization
- Train/Test split

---

# 🤖 Machine Learning Models

The following Machine Learning algorithms were evaluated:

- Gaussian Naive Bayes
- Logistic Regression
- Random Forest
- K-Nearest Neighbors (KNN)
- SGD Classifier
- XGBoost

The notebook allows the comparison of different classifiers using the same dataset.

---

# 🧠 Deep Feature Extraction

Besides traditional Machine Learning approaches, the project also explores Transfer Learning through deep feature extraction.

The following architecture was used:

- EfficientNet-B2

Instead of training a Convolutional Neural Network from scratch, EfficientNet is used as a feature extractor. The generated embeddings are then used as input for classical Machine Learning algorithms.

This approach combines the representational power of Deep Learning with the simplicity and efficiency of traditional Machine Learning classifiers.

---

# 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Confusion Matrix
- Cross Validation
- Classification Report

These metrics provide a comprehensive comparison of classifier performance.

---

# 🛠 Technologies

- Python
- NumPy
- Pandas
- OpenCV
- Scikit-learn
- TensorFlow
- Keras
- Matplotlib
- Google Colab

---

# 📁 Repository Structure

```
image-classification-machine-learning/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── image_classification_machine_learning.ipynb
├── data/
│   └── README.md
└── images/
    └── README.md
```

---

# 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-user/image-classification-machine-learning.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Build your own dataset following the folder structure described in this README.

4. Update the dataset path inside the notebook if necessary.

5. Run the notebook.

---

# 📚 Project Highlights

- ✔ Custom image dataset construction
- ✔ Image preprocessing
- ✔ Feature extraction
- ✔ Classical Machine Learning
- ✔ Transfer Learning
- ✔ Model comparison
- ✔ Performance evaluation
- ✔ Complete Computer Vision workflow

---

# 🔮 Future Improvements

Possible future improvements include:

- Convolutional Neural Networks (CNNs)
- Data Augmentation
- Hyperparameter Optimization
- Larger image datasets
- Additional image categories
- Explainable AI techniques (Grad-CAM)

---

# ⚠️ Disclaimer

This repository is intended exclusively for educational and research purposes.

The original images used during the experiments are **not distributed** with this repository. All image rights remain with their respective copyright holders.

---

# 👨‍🏫 Author

**Valberto Feitosa**

Professor • Data Scientist • Machine Learning • Computer Vision • Artificial Intelligence

---

If you found this project useful, consider giving it a ⭐ on GitHub.
