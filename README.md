# Emotion Detector

An AI-based web application for detecting emotions from text using the Watson NLP library.

## Project Overview

This project uses Watson NLP (via the Watson Embeddable AI library) to analyze text input and detect the following emotions:
- Anger
- Disgust
- Fear
- Joy
- Sadness

The application returns the dominant emotion along with scores for all five emotions.

## Project Structure

```
final_project/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Setup & Run

```bash
pip install flask requests pylint
python server.py
```

Then open `http://localhost:5000` in your browser.

## Run Tests

```bash
python -m unittest test_emotion_detection.py
```

## Static Code Analysis

```bash
pylint server.py
```
