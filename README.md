# 🎵 LyricsRetranscript (AI Lyrics Studio)

**LyricsRetranscript** is a desktop application that automatically transcribes and translates song lyrics from audio files using AI.

The project demonstrates how modern speech recognition models can be used locally to process music while preserving user privacy.

---

## 🚀 Features

- **Lyrics Transcription**  
  Uses OpenAI Whisper to extract lyrics from audio files.

- **Translation**  
  Translates generated lyrics into a selected language.

- **Offline Processing**  
  Runs locally without sending user data to external servers.

- **Desktop Interface**  
  Simple GUI built with PyQt6.

- **Export Options**  
  Save results as TXT, SRT, or LRC files.

---

## 🛠️ Technologies Used

- Python  
- PyQt6 (GUI)  
- OpenAI Whisper (speech recognition)  
- FFmpeg (audio processing)  
- Deep Translator (translation)

---

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/[your-username]/LyricsRetranscript.git
cd LyricsRetranscript

2. Create environment (recommended)
conda create -n lyrics_app python=3.10 -y
conda activate lyrics_app

3. Install dependencies
conda create -n whisper_app python=3.10 -y 
conda activate whisper_app 
conda update -n base -c defaults conda -y 
pip install --upgrade pip 
conda install pytorch torchvision torchaudio pytorch-cuda=12.4 -c pytorch -c nvidia 
python -c "import torch; print(f'PyTorch version: {torch.__version__}'); print(f'Is CUDA available: {torch.cuda.is_available()}')"
conda install -c conda-forge ffmpeg -y 
pip install -U openai-whisper 
pip install PyQt6
pip install pygame

▶️ Running the Application
python main.py

📂 Project Structure
LyricsRetranscript/
│── .gitignore
│── base.ipynb
│── EnvSetup
│── lyricx_studio
│── main.ipynb
│── README.md
│── setup.ipynb (optional)

🔄 Git Workflow

Pull on another machine

git clone https... 
cd lyrics... 
git checkout dev 
git pull

Work on development branch

git checkout dev

Save changes

git add .
git commit -m "message"
git push

📊 Project Context

This project focuses on:
 
. Lyrics transcription from audio
. Translation for accessibility and learning
. Offline AI usage for privacy

It is designed for:

. Music listeners
. Language learners
. Beginner musicians

⚖️ Limitations

. Transcription accuracy may vary with complex music
. Performance depends on hardware
. Translation may require manual verification

📚 Research Basis

This project is based on research in:

. Speech recognition for singing
. Multilingual transcription models
. Whisper-based systems

👤 Author

Name
Final Year Project – Computer Science




