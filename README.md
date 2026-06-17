# Opening Line — Whisper demo

This repository contains a minimal demo that transcribes short English audio using OpenAI's Whisper models locally or in Google Colab.

**Live demo (Colab / drive link):** https://drive.google.com/file/d/1um05V5EFp30OSxEItmkznjqAS8lKUK1i/view?usp=sharing
- Click this link and in the top right corner click "Open in Co-Lab". You should be able to see a Jupyter Notebook run entirely in Google Colab

**Quick overview**
- **Upload**: Run the upload cell in the Colab notebook and choose an audio file.
- **Record**: Or use the built-in browser recorder transcribe immediately.

**Run in Google Colab**
1. Open the notebook in Colab or use the provided link above.
2. Run the first cell to install dependencies (`openai-whisper`, `ffmpeg-python`).
3. Use the upload cell or the recorder cell (click "Record 5s" and allow mic access).
4. After transcription, a `.txt` file will be saved and (when possible) auto-downloaded.
