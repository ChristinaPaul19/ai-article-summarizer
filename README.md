# AI-Powered Article Summarizer

## About
A Python web application that uses Google's Gemini API to convert long articles into concise summaries.

## Features
- Enter an article directly into a text box.
- Upload an article as a `.txt` file.
- Generate AI-powered summaries.
- Choose short, medium, or detailed summaries.
- Download the generated summary.
- Handle empty input and API errors.

## Technologies Used
- Python
- Google Gemini API
- Google GenAI Python SDK
- Streamlit
- Git and GitHub

## Installation

1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install the required libraries:

   `python -m pip install -r requirements.txt`

4. Configure your `GEMINI_API_KEY` environment variable.
5. Start the application:

   `streamlit run app.py`

## API Key
Obtain a Gemini API key through [Google AI Studio](https://aistudio.google.com/). Keep your key private and never commit it to GitHub.

## Usage
Paste an article or upload a `.txt` file, select a summary length, and click **Summarize Article**. View and download the result.

## Author
Christina Paul

## Future Improvements
- Support more document formats.
- Add additional AI providers.
- Improve the interface and summary customization.
