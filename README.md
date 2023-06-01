# Speakeasy GPT

Speakeasy GPT is a Jupyter notebook that utilizes several natural language processing utilities to provide a seamless and low-latency speech interface to ChatGPT and other large language models.

Voice prompts are transcribed using OpenAI's whisper model, run locally on CPU or GPU. The transcription is sent as a prompt to the OpenAI gpt-3.5.turbo API. The response is synthesized into speech by several text to speech engines, including ElevenLabs' API, Mimic 3, and Coqui TTS.

## Installation and Dependencies

- Mount Drive: Mount the Google Drive to access the notebook files.
- Installs: Install the required dependencies and packages, including espeak, ElevenLabs, Mimic 3 TTS, TTS, ffmpeg-python, pydub, and OpenAI.
- Imports: Import the necessary libraries and modules for audio processing, natural language processing, and TTS.

## Usage

1. Mount Drive: Mount the Google Drive to access the notebook files.
2. Installation: Install the required dependencies and packages by running the provided installation commands.
3. Imports: Import the necessary libraries and modules for audio processing, natural language processing, and TTS.
4. Check CUDA: Check if CUDA is available for GPU acceleration.
5. Load Whisper: Load the whisper model for speech-to-text transcription using OpenAI's whisper model.
6. Load Mimic TTS: Load the Mimic 3 Text-to-Speech System for generating speech using the Mimic 3 TTS engine.
7. Load Coqui TTS: Load the Coqui TTS engine for generating speech using the Coqui TTS model.
8. Load ElevenLabs: Load the ElevenLabs API for generating speech using the ElevenLabs TTS model.
9. Load ChatGPT: Set up the OpenAI API for ChatGPT and define the initial system message.
10. Record prompt from microphone: Record audio prompts from the microphone and save them as WAV files.
11. Transcribe prompt audio to text prompt: Transcribe the audio prompts to text using the whisper model.
12. Prompt ChatGPT: Send the text prompts to the ChatGPT model for generating responses.
13. Generate response audio: Generate speech audio for the ChatGPT responses using the selected TTS engine.
14. Full loop - ElevenLabs TTS: Perform the full loop of transcription, ChatGPT prompt, and response audio generation using the ElevenLabs TTS engine.
15. Full loop - Coqui TTS: Perform the full loop of transcription, ChatGPT prompt, and response audio generation using the Coqui TTS engine.
16. Full loop - Mimic TTS: Perform the full loop of transcription, ChatGPT prompt, and response audio generation using the Mimic 3 TTS engine.

Note: Modify the code and parameters as needed for your specific use case.

## License
This code is licensed under the Creative Commons Attribution-NonCommercial (CC BY-NC) license, allowing for non-commercial use and modification with proper attribution.
See the license here:  https://creativecommons.org/licenses/by-nc/2.0/

