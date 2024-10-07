# Summarize text from Youtube or from a Website
This is a Streamlit-based web app that summarizes content from YouTube videos and websites using the Groq API and the Gemma-7b-It model. The app allows users to input a URL and generates a concise summary, whether it’s a webpage or a YouTube video, with the help of natural language processing.

## Features
- Summarize YouTube Videos: Extract and summarize content directly from YouTube.
- Summarize Websites: Provide a URL of any website to generate a summary.
- Real-time Results: Instant summarization once the URL is processed.
- Groq API Integration: Utilizes the Gemma-7b-It model via Groq API for efficient content summarization.

## Installation
1. Install the required dependencies: 
  ```bash
     pip install -r requirements.txt 
  ```

2. Set up your `Groq API key` by creating your own account in [Groq.com](https://groq.com/). This will be required within the Streamlit app to access the summarization model.

## Usage
1. Check the streamlit app:
2. Enter your Groq API key in the sidebar.
3. Provide a YouTube URL or Website URL.
4. Click the Summarize button to generate a summary.

## Example
Here’s a screenshot of the app in action:
![image](https://github.com/user-attachments/assets/13cfc04e-0f3e-4e0d-82dd-02037997a33f)

## Future Enhancements
- Enhance summarization options with custom word limits.
- Include translation features for multi-language support.
