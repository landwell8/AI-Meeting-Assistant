# 🤖 AI Meeting Assistant

**The open-source, privacy-first alternative to Otter.ai**  
🎙️ Real-time meeting transcription, summaries, and action items – **100% offline**.

![Demo](https://user-images.githubusercontent.com/.../demo.gif)  
*(Example: Live transcription with speaker identification)*

## Why This Exists
Commercial tools like Otter.ai or Fireflies:
- Upload your conversations to the cloud ☁️  
- Charge $20+/month for basic features 💸  
- Lock you into their ecosystems 🔒  

This tool runs **entirely on your device** with optional self-hosting.

## Key Features
- **Offline Transcription**: Whisper.cpp-based (no internet needed)  
- **Auto-Summary**: LLM-generated bullet points (local Llama 3 or cloud API)  
- **Action Items**: Detects decisions ("We'll migrate by Friday")  
- **Plugins**:  
  - ✅ Zoom/Teams auto-join  
  - ✅ Jira/Trello task creation  
  - ✅ Export to Obsidian/Notion  

## Get Started
```bash
# Install (Linux/macOS)
git clone https://github.com/yourusername/ai-meeting-assistant.git
cd ai-meeting-assistant
pip install -r requirements.txt

# Run with default mic
python main.py --device 0
