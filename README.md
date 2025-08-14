# Kideny-Disease-Classification
This project aims to classify kidney disease using machine learning techniques. The model is trained on a dataset containing medical image data related to kidney disease, helping in early detection and treatment planning. The project demonstrates the process of data preprocessing, model selection, and evaluation to achieve high accuracy in disease classification.

# Data 
https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone

# Introduction
Kidney disease is a significant public health issue globally, and early detection is crucial for effective treatment. This project utilizes machine learning algorithms to predict Kidney disease using a dataset of patient records. The goal is to assist healthcare professionals in early diagnosis and improve patient outcomes.
Each person have two kidneys, each about the size of your fist. They are near the middle of your back, just below the rib cage. Inside each kidney there are about a million tiny structures called nephrons. They filter your blood. They remove wastes and extra water, which become urine. The urine flows through tubes called ureters. It goes to your bladder, which stores the urine until you go to the bathroom.
In this project we will classify three kinds of Kidney disease (Cysts, Stones, Tumor)
Kidney cysts are round pouches of fluid that form on or in the kidneys. Kidney cysts can occur with disorders that may impair kidney function. But more often, kidney cysts are a type called simple kidney cysts. Simple kidney cysts aren't cancer and rarely cause problems
Kidney stones (also called renal calculi, nephrolithiasis or urolithiasis) are hard deposits made of minerals and salts that form inside your kidneys. Diet, excess body weight, some medical conditions, and certain supplements and medications are among the many causes of kidney stones
Kidney tumors (also called renal tumors) are growths in the kidneys that can be benign or cancerous. Most do not cause symptoms and are discovered unexpectedly when you are being diagnosed and treated for another condition.

# Model
Several models have been explored for text generation, including:

* CNN (Convolutional Neural Network)
* InceptionV3 Transfer Learning
* DenseNet121 Transfer Learning
* MobileNet Transfer Learning
* Xception Transfer Learning
* ResNet50 Transfer Learning

# Installation
```bash
git clone https://github.com/Osama-Anmar/Kideny-Disease-Classification.git
cd Kideny-Disease-Classification
pip install -r requirements.txt
```

# Usage
```bash
jupyter notebook KidenyDiseaseClassification.ipynb
```
for Prediction : in **predict_image** section insert the image and select the model

# Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
