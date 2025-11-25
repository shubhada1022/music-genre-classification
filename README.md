# music-genre-classification
I created this project as part of my data science coursework to build a complete ETL (Extract, Transform, Load) pipeline for music genre classification. I used the GTZAN dataset and extracted audio features like MFCCs to train a machine learning model using Random Forest. 
readme_content = """# 🎵 Music Genre Classification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Librosa](https://img.shields.io/badge/Librosa-Audio_Features-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow)
![License](https://img.shields.io/badge/License-None-lightgrey)
![Colab](https://img.shields.io/badge/Platform-Google_Colab-green?logo=googlecolab)

---

## 📌 Project Overview

This project implements a complete **ETL (Extract, Transform, Load)** pipeline for audio data to perform **music genre classification** using machine learning. The model is trained on the GTZAN music dataset using a Random Forest classifier, and predictions can be made on new `.wav` files.

## 🎯 Features
- **Extract** audio features (MFCC) using `librosa`.
- **Transform** and store features in a structured DataFrame.
- **Load** features into a CSV file for training.
- Train a machine learning model using `RandomForestClassifier`.
- Save and load the model and label encoder for reuse.
- Classify new music files uploaded by the user.
- Visualize the ETL pipeline and classification results.

## 📂 Dataset
- **Name:** GTZAN Genre Collection  
- **Source:** [Kaggle - carlthome/gtzan-genre-collection](https://www.kaggle.com/datasets/carlthome/gtzan-genre-collection)  
- **Genres:** Classical, Pop, Rock, Jazz, Blues, Reggae, Disco, Country, Hiphop, Metal

## 🧪 Libraries Used
- Python 3.11
- `librosa`
- `scikit-learn`
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `joblib`
- `graphviz`

## 🔍 ETL Pipeline Flowchart

![ETL Pipeline](etl_pipeline.png)

## 📊 Confusion Matrix
The following matrix shows the performance of the classifier on the test set:

> (This will display in the notebook / output cell using `seaborn`.)

## 🚀 Usage Instructions
1. Clone the repo or run the notebook in Google Colab.
2. Upload your `kaggle.json` file.
3. Download the dataset using Kaggle CLI.
4. Run the ETL, model training, and prediction steps.
5. Upload a new `.wav` file to classify its genre.

## 📁 Folder Structure

## 📌 Disclaimer
This project is intended for educational and research purposes only. The dataset is used under fair use for academic work.

