# Text-Based Emotion Tracking and Monitoring System Using Bi-Directional LSTM

This project was developed as part of my Final Year Project for the Bachelor of Computer Science (Artificial Intelligence) at Universiti Teknikal Malaysia Melaka (UTeM). The system aims to help individuals monitor and track their emotions based on the text they input into a web-based application.

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

## 📷 Screenshots (Optional)

If available, include:
- Architecture diagram
- Website UI mockup
- Emotion prediction chart

## 🧑‍⚕️ Target Users

- Individuals monitoring their own emotions
- Potential future use by mental health professionals

## 📄 Final Report

You can read the full technical and research write-up in the [`report`](./report/PSM1_B032010378_NURSYUHADABINTIAZHAR.pdf) folder.

---

*Developed by Nur Syuhada Binti Azhar — 2023*
