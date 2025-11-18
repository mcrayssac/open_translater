# open_translater
## Commands (MacOS)
```bash
# Find Python
which python3

# Initialize Python venv
python3 -m venv venv

# Activate venv
source venv/bin/activate

# Install dependencies
python3 -m pip install -r requirements.txt
# or with full features
python3 -m pip install yt-dlp
python3 -m pip install git+https://github.com/openai/whisper.git

# MP3 downloading from YouTube
yt-dlp -x --audio-format mp3 "https://www.youtube.com/watch?v=example"

# Transcription using whisper from OpenAI
whisper "example.mp3" --model medium --language en