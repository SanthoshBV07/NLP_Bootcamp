## 🔹 Overview
This repository contains the **first NLP Bootcamp assignment**, applying text preprocessing and word embedding techniques on **Yelp customer reviews**.

## 📂 Dataset
- **Source:** [Yelp Open Dataset](https://business.yelp.com/data/resources/open-dataset/)  
- **Content Used:** Customer review text column  

> ⚠️ **Note:** To run the code, update the dataset path in the Jupyter notebook to match your local installation.
# 📝 Assignment 1

## ✨ Preprocessing
- Lowercasing  
- Regex-based cleaning (punctuation, digits, URLs, emojis)  
- Stopword removal  
- Stemming and lemmatization  

## 💡 Feature Extraction & Embeddings
- **Bag of Words (BoW)**  
- **TF-IDF**  
- **One-Hot Encoding**  
- **Word2Vec (CBOW)**

- # 📝 Assignment 2: Sentiment Analysis with Feedforward Neural Network

This assignment implements a **feedforward neural network (FFNN)** for **sentiment analysis** on a subset of the **Yelp review dataset**.

## 🔹 Key Features

- ⚡ Built using **PyTorch** (`nn.Module`) for flexible model architecture  
- 🏃‍♂️ Trained with **Stochastic Gradient Descent (SGD)** optimizer  
- 💧 Tested **dropout** at various rates to study its effect on model performance  
- 📄 Input: **Bag-of-Words vectors** from preprocessed Yelp reviews  
- 🎯 Output: **Multi-class sentiment prediction**

## 🎯 Purpose

To explore the impact of **dropout regularization** and **SGD optimization** on FFNN performance for text classification tasks.
