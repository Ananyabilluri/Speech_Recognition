# Speech Recognition
This repository contains a Python script for converting speech to text using speech recognition, compatible with Pyodide for browser execution.

## Overview
The script uses the speech_recognition library to capture audio from a microphone, adjust for ambient noise, and convert it to text using Google's speech recognition API.

## Requirements
- Python 3.x
- speechrecognition
- pyaudio (for desktop use)

## Installation
```bash
pip install speechrecognition pyaudio
```

## Usage
Run the script to convert speech to text:
```bash
python speech_recognition.py
```

## Output
- Recognized text from the audio input

## Note
For browser use with Pyodide, ensure compatibility by avoiding local file I/O. Test with a real microphone for desktop execution.