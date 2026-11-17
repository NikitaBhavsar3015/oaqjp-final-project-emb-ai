# Final Project – Emotion Detection Application

## Project Overview

This project implements an Emotion Detection application using IBM Watson Natural Language Processing (NLP) libraries.

The application analyzes a given text and identifies five emotions:

- Anger
- Disgust
- Fear
- Joy
- Sadness

It also identifies the dominant emotion expressed in the input text.

## Technologies Used

- Python 3
- IBM Watson NLP Emotion Prediction
- Flask
- HTML
- JavaScript
- Requests
- Pylint
- Unittest

## Project Structure

```text
oaqjp-final-project-emb-ai/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│
├── static/
│   └── mywebscript.js
│
├── templates/
│   └── index.html
│
├── test_emotion_detection.py
├── server.py
├── README.md
└── LICENSE
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/NikitaBhavsar3015/oaqjp-final-project-emb-ai.git
```

2. Navigate to the project directory:

```bash
cd oaqjp-final-project-emb-ai
```

3. Install the required dependencies:

```bash
python3 -m pip install requests flask pylint
```

## Running the Application

Start the Flask application:

```bash
python3 server.py
```

The application runs on port 5000.

Open the application using the Cloud IDE's Launch Application feature with port `5000`.

Enter text into the input field and click **Run Sentiment Analysis** to view the detected emotions.

## Error Handling

The application includes:

- HTTP 400 error handling for invalid requests.
- Blank input validation.
- An appropriate error message for empty input:

`Invalid text! Please try again!`

## Unit Testing

Run the unit tests using:

```bash
python3 -m unittest test_emotion_detection.py
```

## Code Quality

Static code analysis is performed using Pylint:

```bash
pylint server.py
```

The final server implementation achieved a score of **10.00/10**.

## Author

Nikita Bhavsar

## Project

IBM Skills Network – AI-Based Emotion Detection Final Project
