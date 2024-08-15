# 📊 Social Media Sentiment Analysis

This project focuses on analyzing sentiment in social media comments and categorizing them as **positive**, **negative**, or **neutral**. The analysis is performed using deep learning models like MLP and LSTM, and the project also includes an API that allows users to input a comment and receive a sentiment classification in real-time.
(Using Indonesian language).

---

## 🚀 Project Overview

### Project Goals
- Build a robust model to classify social media comments based on sentiment.
- Develop an API that can take a comment as input and return its sentiment classification.
- Implement preprocessing steps to filter out special characters, excessive punctuation, and slang.

### Features
- **Sentiment Analysis Models**: Trained using MLP and LSTM for accurate classification.
- **Real-time Sentiment Prediction**: API that returns sentiment (positive, negative, or neutral) when given a comment.
- **Text Preprocessing**: Handles slang, emojis, and other social media-specific language nuances.

### 📄 File Descriptions
- **train_preprocess.tsv**: Original dataset containing social media comments
- **new_kamusalay.csv**: For data cleansing needs.
- **NN_MLP.ipynb**: Jupyter notebook for training MLP model.
- **LSTM.ipynb**: Jupyter notebook for training LSTM model.
- **app.py**: Flask API for predicting sentiment based on input comment.
- **model_mlp.p**: Saved MLP model.
- **model_lstm.h5**: Saved LSTM model.
- **Others**: Required libraries and dependencies.

---

## 🚀 Note on Running the API

### This repository requires this following softwares and dependencies to work:

- Python3 (version 3.11)
- Pandas
- Regex Python
- Sqlite3
- Flask
- Flassger
- Sckit Learn
- Tensorflow (version 2.13.1)

### To make work well, install all dependencies first.

Before run the API, please download all models resources in this: 
`https://drive.google.com/drive/folders/1edkciZgfV-t2yhLWEo12vCQWPiJ1z5S5?usp=drive_link`

Put the resources on directory `/modeling`

### How to run API
python app.py

---

## 📬 Contact
If you have any questions or feedback, feel free to reach out at ayudwindap@gmail.com.
