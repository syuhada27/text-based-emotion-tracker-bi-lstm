# Text-Based Emotion Tracking and Monitoring System Using Bi-Directional LSTM

This project was developed as part of my Final Year Project for the Bachelor of Computer Science (Artificial Intelligence) at Universiti Teknikal Malaysia Melaka (UTeM). The system aims to help individuals monitor and track their emotions based on the text they input into a web-based application.

> ⚠️ **Note**: The original source code is not included in this repository due to file loss. 
> This repo contains documentation, screenshots, and the full technical report.

## 📌 Objective

- To explore emotion recognition techniques based on text.
- To build a recognition model to predict emotions using deep learning.
- To develop a web application that allows users to track and visualize their emotional patterns.


## 🧠 Methodology

The system was developed following the **Agile methodology**, enabling iterative development, continuous feedback, and flexible improvements to both the AI model and the web application.

The system uses a **Bi-Directional Long Short-Term Memory (Bi-LSTM)** deep learning model to predict the emotional tone of user-inputted text. Data pre-processing includes:
- Stopword removal
- Lemmatization
- Tokenization
- Label encoding

The model was integrated into a web application using **Flask**, where users could:
- Submit their daily emotion journal
- View predicted emotion
- Visualize emotional trends over time

## 📊 Dataset

- Source: Public dataset from GitHub
- Size: ~55,000 tweets
- Original classes: 13 emotions
- Final classes used: 5 emotions (`neutral`, `happy`, `sad`, `anger`, `love`)

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook & Google Colab
- Flask (for web deployment)
- TensorFlow / Keras (for model training)
- SQLite (for saving emotion logs)

## 📁 Project Files

- `report/`: Contains the full final year project report.
- `README.md`: Project overview (this file).
- *(Code not available due to file loss, but full project flow is detailed in the report.)*

## 🖼️ System Architecture

The system architecture of this project:

![system_architecture](https://github.com/user-attachments/assets/f2e88968-8387-4249-bccf-9120e630867c)

## 💻 User Interface

Main page of the web application:

<img width="599" height="281" alt="homepage" src="https://github.com/user-attachments/assets/7978126f-1ed5-4af2-bfdd-235ae86f8342" />


When user enter text, the "intensity" options are available to choose:

<img width="544" height="465" alt="emotion prediction" src="https://github.com/user-attachments/assets/8a54fd01-97f5-43b7-8a9a-ccf627fe857c" />

## 📈 Results & Evaluation

The trained model achieved an accuracy of **93%** and effectively predicted emotions across the five target categories:

<img width="451" height="220" alt="Picture12" src="https://github.com/user-attachments/assets/5792d941-47f0-4b0e-8409-15b13c3b3e3d" />

## 🧑‍⚕️ Target Users

- Individuals monitoring their own emotions
- Potential future use by mental health professionals

## 📄 Final Report

You can read the full technical and research write-up in the [`report`](./report) folder.

---

*Developed by Nur Syuhada Binti Azhar*

Bachelor of Computer Science (Artificial Intelligence)  

Universiti Teknikal Malaysia Melaka (UTeM) — 2023

