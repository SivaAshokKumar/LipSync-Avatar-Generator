# AvatarSync Pro: AI-Powered Lip-Sync Video Generator (CPU-Only)

✨ **Steve Avatar** is a lightweight, CPU-compatible implementation of the powerful [Wav2Lip](https://github.com/Rudrabha/Wav2Lip) model that generates lip-synced avatar videos using just an image and an audio file. Perfect for creating talking-head videos, virtual characters, and personalized content — even on low-resource machines like Google Colab CPU.

---

## 🚀 Demo Preview

https://youtube.com/shorts/CPN3XDoHJsY?feature=share

---

## 🧠 Features

- 🎙️ Generate lip-synced video from a still image and speech audio.
- 🖼️ Upload any facial photo to turn it into a talking avatar.
- 🛠️ CPU-compatible – no GPU required.
- 🪄 Automatically downloads pretrained models.
- 🧩 Fully patched for librosa and CPU-only environments.

---

## 📦 Tech Stack

- Python 3.9  
- PyTorch 1.13.1  
- OpenCV  
- Librosa 0.9.2  
- FFmpeg  
- GTTS (for Text-to-Speech, optional)

---

##  🔭 Future Work
Here’s what’s planned to enhance Steve Avatar:

🔊 Advanced TTS with Chatterbox/Resemble AI
Replace GTTS with neural voice cloning tools like Chatterbox-TTS for realistic, emotion-aware speech synthesis using custom or cloned voices.

🧠 Dynamic Head Movement with Motion Alignment
Integrate models like SadTalker or First Order Motion Model to enable head nods, eye movement, and expression tracking — making avatars feel more human and interactive.

🌐 Web-based Interface (Gradio/Streamlit)
Build a user-friendly front end so users can upload audio/images and generate videos right from a browser with no code.
---
##  🛡️ License
This project is for educational and research purposes only.
Please refer to Wav2Lip License for the original model rights.
---
##  🙌 Credits
Wav2Lip

Chatterbox TTS (Planned)
---
## 🔗 Connect with Me
🌐 LinkedIn : https://www.linkedin.com/in/siva-ashokkumar/

💻 GitHub: https://github.com/SivaAshokKumar

---

## ⚙️ Installation & Usage (Google Colab)

> Open [Google Colab](https://colab.research.google.com/) and paste the following code block step-by-step.

### 1. Install Dependencies (CPU-only)

```bash
!apt update -qq
!apt install -y ffmpeg git python3.9 > /dev/null
!pip install -q gtts opencv-python torch==1.13.1 torchvision==0.14.1 numpy==1.21.6 librosa==0.9.2

