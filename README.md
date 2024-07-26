
---

# Speech Recognition System 🗣️

This project is a Speech Recognition System that includes two main functionalities: Speech-to-Text and Speech-to-Web. The system uses Python libraries for speech recognition and text-to-speech conversion, enabling users to interact with their computer using voice commands.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

The Speech Recognition System is designed to allow users to convert spoken words into text and to open websites using voice commands. By leveraging the capabilities of the `speech_recognition` and `pyttsx3` libraries, this system provides a hands-free experience for interacting with a computer.

## Features

- **Speech-to-Text**: Converts spoken words into text using Google's speech recognition API.
- **Speech-to-Web**: Opens websites based on voice commands.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/speech_recognition_system.git
   cd speech_recognition_system
   ```

2. Create a virtual environment and activate it:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install SpeechRecognition pyttsx3 pipwin
   pipwin install pyaudio
   ```

## Usage

### Speech-to-Text

The Speech-to-Text functionality converts spoken words into text and then reads the text back to the user.

1. Run the `speech_to_text.py` script:
   ```bash
   python speech_to_text.py
   ```

2. Follow the prompts to speak into the microphone.

### Speech-to-Web

The Speech-to-Web functionality listens for a website name and opens the specified website in the default web browser.

1. Run the `speech_to_web.py` script:
   ```bash
   python speech_to_web.py
   ```

2. Follow the prompts to speak into the microphone and specify the website to open.

## Project Structure

```plaintext
speech_recognition_system/
├── speech_to_text.py     # Script for Speech-to-Text functionality
├── speech_to_web.py      # Script for Speech-to-Web functionality
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgements

- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/) for providing the speech recognition API.
- [pyttsx3](https://pypi.org/project/pyttsx3/) for text-to-speech conversion.
- [PyAudio](https://people.csail.mit.edu/hubert/pyaudio/) for accessing the microphone input.

---
