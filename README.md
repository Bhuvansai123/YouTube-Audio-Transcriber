# 🎥 **Video Processing Project**  
## 🎙️ **Deepgram & ElevenLabs Integration**  


## 📝 **Overview**  
This project facilitates the **download, audio extraction, transcription, and text-to-speech generation** from YouTube videos. It utilizes **Deepgram** for transcription and **ElevenLabs** for generating speech from text, streamlining the process of creating audio content from video sources.

---

## ✨ **Key Features**  
1. **Video Downloading**:  
   - Downloads YouTube videos in **MP4** format.  

2. **Audio Extraction**:  
   - Converts downloaded video files to **WAV** format for transcription.  

3. **Transcription**:  
   - Utilizes **Deepgram's API** to convert audio to text.  

4. **Text-to-Speech Generation**:  
   - Generates audio files from text using **ElevenLabs' API**, providing a smooth audio output experience.

---

## 📂 **Directory Structure**  
D:/Video-Processing-Project/
│
├── video_processing.py     # Main script for processing videos
├── downloads_dir/          # Directory where videos are downloaded
├── audio_dir/              # Directory for extracted audio files
└── requirements.txt        # List of dependencies

---

## 🚀 **Run the Application**  

1. **Prerequisites**  
   - Install [Python](https://www.python.org/downloads/).  
   - Install the necessary dependencies:  
     ```bash
     pip install pytubefix requests
     ```

2. **Set Up Your API Keys**  
   - Replace `YOUR_DEEPGRAM_API_KEY` and `YOUR_ELEVENLABS_API_KEY` in the script with your actual API keys.  
   - Specify your voice ID in the script as well.

3. **Run the Script**  
   - Execute the script to download a video, extract audio, transcribe it, and generate audio from the transcription:  
     ```bash
     python video_processing.py
     ```

---

## 💬 **Example Usage**  
To use the script, simply specify a YouTube video URL in the `video_processing.py` file. Upon execution, it will perform the following:

1. Download the video.
2. Extract audio from the video.
3. Transcribe the audio to text.
4. Generate an audio file from the transcribed text.

---

## 🛠️ **Key Functions**  
- **`download_video(video_url)`**:  
  Downloads a YouTube video and returns the file path.  
- **`extract_audio(video_file_path)`**:  
  Extracts audio from the video file and returns the audio file path.  
- **`transcribe_audio(audio_path, deepgram_api_key)`**:  
  Transcribes audio to text using Deepgram's API.  
- **`generate_audio(text, elevenlabs_api_key, voice_id)`**:  
  Generates audio from text using ElevenLabs' API.

---

## 🤝 **Contributing**  
We appreciate your interest! However, we are still finalizing the contribution process.  
In the meantime, feel free to fork the repository and experiment with the code. We plan to introduce formal contribution guidelines soon.

---

## 📄 **License**  
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## 📧 **Contact**  
For any inquiries, feel free to reach out via:  
- **Email**: bhuvansai62@gmail.com 
- **LinkedIn**: [Anusuri Bhuvan Sai](https://www.linkedin.com/in/bhuvansai62/)

---

Enjoy processing videos with this **Deepgram & ElevenLabs Integration** project! 🎉
