# Text-Based Emotion Tracking and Monitoring System Using Bi-Directional LSTM

This project was developed as part of my Final Year Project for the Bachelor of Computer Science (Artificial Intelligence) at Universiti Teknikal Malaysia Melaka (UTeM). The system aims to help individuals monitor and track their emotions based on the text they input into a web-based application.

> ⚠️ **Note**: The original source code is not included in this repository due to loss of code source. SSSSSSIINNNNNNNNIIIII  
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
*(Replace this with your actual diagram from the report)*

![System Architecture](screenshots/system_architecture.png)

## 💻 User Interface
*(Replace these with your actual UI screenshots)*
- Emotion journal input page
- Predicted emotion display
- Emotion trend visualization

Example:  
![UI Example](screenshots/ui_example.png)

## 📈 Results & Evaluation
*(Replace this with your result charts from the report)*  
The trained model achieved an accuracy of **XX%** and effectively predicted emotions across the five target categories.

![Results Chart](screenshots/results_chart.png)

## 🧑‍⚕️ Target Users

- Individuals monitoring their own emotions
- Potential future use by mental health professionals

## 📄 Final Report

You can read the full technical and research write-up in the [`report`](./report/PSM1_B032010378_NURSYUHADABINTIAZHAR.pdf) folder.

---

*Developed by Nur Syuhada Binti Azhar*

Bachelor of Computer Science (Artificial Intelligence)  

Universiti Teknikal Malaysia Melaka (UTeM) — 2023

