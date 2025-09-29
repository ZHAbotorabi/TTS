# TTS (Text-to-Speech) – Colab
Simple gTTS example.

## How to run (Colab)
```python
from gtts import gTTS
text = "You will hear a student booking a library room. I would like a small study room at 3 p.m."
tts = gTTS(text=text, lang='en')
tts.save("sample_listening_form_completion.mp3")
print("Audio saved as sample_listening_form_completion.mp3")
