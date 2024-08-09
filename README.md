# Video Summarization Project

## Project Description
This project is a Python-based tool for summarizing video content. It takes a video URL as input, downloads the audio, transcribes it using OpenAI's Whisper model, and then generates a concise summary using a pre-trained language model. The project is particularly useful for quickly understanding the content of long videos without watching them in full.

## Table of Contents
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact Information](#contact-information)

## Installation Instructions

1. Clone the Repository:
   ```bash
   git clone https://github.com/yourusername/your-repository.git
   cd your-repository
   
2. Set Up the Environment:

  It’s recommended to use a virtual environment.
  
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install Required Libraries:

  Install the necessary Python packages using pip:
  
    pip install yt-dlp ffmpeg-python openai-whisper torch transformers pyttsx3 tqdm pydub

4. Install FFmpeg:

  Ensure FFmpeg is installed on your system. You can download it from FFmpeg's official website and add it to your system's PATH.

## Usage
  1. Run the Jupyter Notebook:
    - Launch Jupyter Notebook:
    ```bash

    jupyter notebook
    
  - Open Video_Summarization.ipynb and follow the steps provided in the notebook.
      
  2. Input Video URL:
     - The notebook prompts you to input a YouTube video URL. The audio from this video will be extracted for summarization.
  3. Transcribe and Summarize:
     - The notebook uses OpenAI's Whisper model to transcribe the audio and a pre-trained language model to generate a summary of the transcription.
    
##  Features
Download Audio: Extract audio from YouTube videos using yt-dlp.
Transcribe Audio: Use OpenAI's Whisper model for high-quality transcription.
Summarize Text: Summarize the transcription using Hugging Face's models.
Text-to-Speech: Option to read the summary aloud using pyttsx3.

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork this repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes with clear messages.
4. Push to your fork and submit a pull request.

## Acknowledgments
OpenAI Whisper for transcription.
Hugging Face Transformers for text summarization.
yt-dlp for downloading audio from YouTube.
FFmpeg for audio processing.

## Contact Information
For questions, suggestions, or contributions, please contact:

Name: Dingyi Duan

Email: dingyiduan7@gmail.com

GitHub: dingyiduan7
