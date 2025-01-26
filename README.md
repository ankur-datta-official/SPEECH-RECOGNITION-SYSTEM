**Company**: CODTECH IT SOLUTIONS PVT.LTD

**Name**: Ankur Datta

**Intern ID**: CT08JSJ

**Domain**: Artificial Intelligence

**Batch Duration**: January 5th, 2025 to February 5th, 2025

**Mentor Name**: Neela Santhosh 

# Speech Recognition System

This Python script implements a basic speech-to-text system using the `speech_recognition` and `pydub` libraries. It is capable of transcribing short audio clips into text.

## Functionality

The script defines a function `transcribe_audio` that takes an audio file path as input. It performs the following steps:

1. **Loads the audio file:** Reads the audio file using `pydub` and converts it to WAV format if necessary.
2. **Initializes the recognizer:** Creates an instance of the `Recognizer` class from `speech_recognition`.
3. **Records audio data:** Reads the audio data from the WAV file.
4. **Transcribes audio:** Uses the Google Speech Recognition API to transcribe the audio data.
5. **Returns the transcription:** If successful, returns the transcribed text; otherwise, returns an error message.

## Usage

1. **Install dependencies:** Make sure you have `speech_recognition` and `pydub` installed. You can install them using `pip`:
2. **Replace audio file path:** Update the `audio_file_path` variable with the path to your audio file.
3. **Run the script:** Execute the Python script.

The transcribed text will be printed to the console.

## Example
python audio_file_path = "audio.mp3" # Replace with your audio file path result = transcribe_audio(audio_file_path) print("Transcription:\n", result)

## Notes

- The script uses the Google Speech Recognition API, which requires an internet connection.
- The accuracy of the transcription may vary depending on the quality of the audio and the speaker's accent.
- For longer audio files, consider splitting them into smaller segments for better performance.
