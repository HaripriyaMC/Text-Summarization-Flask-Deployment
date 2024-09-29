## Text-Summarization-Flask-Deployment

This is a demo project to demonstrate how a text summarization model can be deployed using a Flask API. The model is based on `PegasusForConditionalGeneration` from Hugging Face's Transformers library and generates a concise summary of the input text.

### Prerequisites

To run this project, you must have the following Python libraries installed:
- Flask
- Transformers (Hugging Face)
- Torch (PyTorch)

Install the required libraries using:
```bash
pip install Flask transformers torch
```

### Project Structure

The project has the following components:

1. **app.py**  
   This is the main Flask application file. It loads the Pegasus model and tokenizer, handles incoming text summarization requests, and renders the web pages.

2. **templates/**  
   This directory contains the HTML templates:
   - **index.html**: The home page where users input text for summarization.
   - **output.html**: The result page displaying the summarized text.


### Running the Project

Start the Flask application by running:
```bash
python app.py
```
