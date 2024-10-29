# Important Video Segments Generation

This Flask application allows users to upload a video file, extract audio from it, convert the audio to text, and then extract important sentences based on named entities. It also allows users to create a video that highlights specific segments based on the timestamps provided.

## Features

- Upload video files.
- Convert video to audio.
- Use Google Speech Recognition to convert audio to text.
- Extract important sentences containing entities like PERSON, ORGANIZATION (ORG), and GEOPOLITICAL ENTITY (GPE).
- Create a new video that highlights important segments based on specified timestamps.

## Requirements

To run this application, you need to have the following installed:

- Python 3.x
- Flask
- MoviePy
- SpeechRecognition
- SpaCy
- `en_core_web_sm` model for SpaCy

## Installation

1. Clone the repository or download the code files.
2. Navigate to the project directory.
3. Install the required Python packages using pip:

   ```bash
   pip install Flask moviepy SpeechRecognition spacy
4. Download the SpaCy language model:
   
      ```bash
   python -m spacy download en_core_web_sm
5 . Create directory names:

      ```bash
   mkdir uploads
      



