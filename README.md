**AI-Powered Multilingual Video Subtitle Generator**

# 🎥 AI-Powered Multilingual Video Subtitle Generator

This mini-project is an AI-driven video subtitle generation tool that uses OpenAI's Whisper model to perform speech recognition and translation from any language to English, generating `.srt` subtitle files and embedding them directly into videos using FFmpeg.

---

## 📌 Features

- 🎙️ **Speech Recognition** — Converts speech from video files into text.
- 🌍 **Multilingual Translation** — Automatically translates recognized speech to English.
- 🎞️ **Subtitle File Generation** — Creates `.srt` subtitle files with proper timestamps.
- 📺 **Subtitles Burn-in** — Embeds subtitles directly into the video.
- 📤 **Easy File Upload & Download** — Upload videos and download processed outputs seamlessly in Google Colab.

---

## 📦 Dependencies

- [OpenAI Whisper](https://github.com/openai/whisper)
- [FFmpeg](https://ffmpeg.org/)
- `ffmpeg-python`
- `google.colab` (for file upload/download)

---

## 📥 Installation

Run the following in your Google Colab notebook:

```bash
!pip install -q git+https://github.com/openai/whisper.git
!pip install -q ffmpeg-python
!sudo apt-get install -y ffmpeg
````

---

## 📌 How It Works

1. 📤 Upload your video file.
2. 📑 The Whisper model transcribes and translates the audio.
3. 📃 Subtitles are saved in `.srt` format.
4. 🎬 Subtitles are burned into the video using FFmpeg.
5. 📥 Download your final video and subtitle file.

---

## 📂 Project Structure

```
subtitles.ipynb        # Colab notebook with all code
output_subs.srt        # Generated subtitles (after run)
final_output.mp4       # Video with burned-in subtitles (after run)
README.md              # Project documentation
```

---

## 🎛️ Usage Instructions

* Open the Colab notebook.
* Run all cells sequentially.
* Upload your video file when prompted.
* Wait for transcription, translation, and subtitle generation.
* Download the final video and subtitle file.

---

## 📊 Sample Output

* **Input Video**: `sample_video.mp4`
* **Output Subtitle File**: `output_subs.srt`
* **Subtitled Video**: `final_output.mp4`

---

## 📜 License

This project is for educational purposes only.

---

## ✨ Acknowledgments

* [OpenAI Whisper](https://github.com/openai/whisper)
* [FFmpeg](https://ffmpeg.org/)

---

## 📧 Contact

**Developer**: P. Yaswanth Kumar
**gmail**: yashyaswanth714@gmail.com
**Project**: AI-Powered Multilingual Video Subtitle Generator

```

