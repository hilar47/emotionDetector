# Emotion Detector

**Project Name:** Emotion Detector  

AI-based Emotion Detection Web Application using Watson NLP and Flask.

## Project Description

This is the final project for the IBM course **Developing AI Applications with Python and Flask** on Coursera.

The application analyzes text input and detects five emotions:
- Anger
- Disgust
- Fear
- Joy
- Sadness

It returns the confidence score for each emotion and identifies the **dominant emotion**.

The application is packaged as a Python module, unit-tested, and deployed as a web service using **Flask**.

## Project Structure

```
emotionDetector/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── static/
│   └── mywebscript.js
├── server.py
├── test_emotion_detection.py
├── requirements.txt
└── README.md
```

## Features

- Emotion detection using Watson NLP library
- Formatted output with dominant emotion
- Flask web deployment
- Error handling for blank/invalid input
- Unit tests
- Static code analysis with pylint

## How to Run

1. Install dependencies:  
   `pip install -r requirements.txt`

2. Start the Flask server:  
   `python server.py`

3. Open the application in a browser:  
   `http://localhost:5000`

## Author

Created as part of the IBM / Coursera final project submission.
