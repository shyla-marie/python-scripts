# Video-to-Audio-to-Text
## File Conversion and Audio Speech Transcription

1. Input the links for the YouTube Videos you wish to transcribe.
2. Script pulls data from webpages for the links provided.
3. Script converts the video's audio data into a .wav file using FFMPEG via Homebrew.
4. Whisper API (or run locally) transcribes the audio data into a .txt file.
5. Some Google Cloud Python BS accessible via Hugging Face distinguishes between various speakers and assigns the transcribed text to its corresponding speaker label.

<br>

Further revision of the Python Script is necessary in order to generate .srt files with proper speaker labeling. To be completed at a later date.
