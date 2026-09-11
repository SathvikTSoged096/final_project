# Final Project: Emotion Detection Application

A Python-based AI web application that analyzes user-provided text to detect underlying emotions using the **IBM Watson NLP EmotionPredict API** and serves results through a **Flask** web interface.

---

## 🛠️ Features

- **Watson NLP Integration:** Analyzes input text for 5 core emotions: `anger`, `disgust`, `fear`, `joy`, and `sadness`.
- **Dominant Emotion Identification:** Evaluates emotion scores to determine the primary emotional tone of the statement.
- **Robust Error Handling:** Detects blank or invalid user input and handles `400` status responses gracefully.
- **Flask Web Server:** Deploys a web interface where users can enter text and view structured results in real time.
- **Unit Tested:** Built with automated test cases using Python's `unittest` framework to ensure model accuracy.
- **PEP 8 Compliant:** Clean, readable codebase scored 10/10 on static code analysis using `pylint`.

---

## 📁 Project Structure

```text
final_project/
│
├── EmotionDetection/
│   ├── __init__.py           # Package initializer
│   └── emotion_detection.py  # Watson API connection & error handling logic
│
├── templates/
│   └── index.html            # Frontend UI
│
├── server.py                 # Flask web deployment server
├── test_emotion_detection.py # Unit tests for emotion detection
├── README.md                 # Project documentation
└── requirements.txt          # Required dependencies
