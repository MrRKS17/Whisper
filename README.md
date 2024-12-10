# Whisper

## Introduction

Whisper is a sentiment analysis project designed to analyze the mood conveyed by your spoken sentences. By leveraging advanced natural language processing techniques, the model can determine your emotional state based on your input.

## Features

- **Google's BERT Model**: Utilizes Google's BERT model from Hugging Face, fine-tuned specifically for mood classification.
- **FastAPI Application**: Includes a FastAPI application that captures your voice input and provides a simple sentiment analysis once your prompt is complete.

## Requirements

To run this project, you will need:

- Python
- FastAPI
- TensorFlow
- Hugging Face API

## Installation

Follow these steps to install and set up the project:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/whisper.git
    cd whisper
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install fastapi uvicorn tensorflow transformers
    ```

## Usage

Once the installation is complete, you can use the project as follows:

1. Start the FastAPI application:
    ```bash
    uvicorn main:app --reload
    ```

2. Open your web browser and navigate to `http://127.0.0.1:8000`.

3. Use the application to speak sentences into the model. The sentiment analysis results will be displayed after each prompt.

## Conclusion

Whisper provides an intuitive and efficient way to analyze sentiments based on spoken sentences. By integrating advanced NLP models and a user-friendly FastAPI application, this project offers a seamless experience for mood classification.
