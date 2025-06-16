# Gemini Real-Time Translator - Team 2  
A multimodal translator using Google Gemini's generative models for real-time translation in four modes: text-to-text, text-to-speech, speech-to-text, and speech-to-speech.

---

## 🌐 Overview  
This project implements an interactive translation tool capable of identifying and converting spoken or written language into a translated text or audio response. The following modes are supported:

- Text-to-Text Translation (ttt)
- Text-to-Speech Translation (tts)
- Speech-to-Text Translation (stt)
- Speech-to-Speech Translation (sts)

---

## 🎯 Features

- **Multimodal Translation**: Supports both text and audio inputs
- **Language Detection**: Automatically detects input language using `langdetect`
- **Translation with Gemini**: Uses `gemini-2.0-flash` and `gemini-2.5-flash-preview-tts` models
- **Speech Synthesis**: Generates translated audio using prebuilt Gemini voices
- **File Upload**: Accepts `.wav` audio files for speech-based translation
- **Colab-Ready**: Runs entirely in Google Colab with minimal setup

---

## 📦 Required Dependencies

- `google-generativeai`
- `langdetect`
- `iso639`
- `wave`
- `google.colab`
- `pathlib`

Install with:

```bash
!pip install langdetect pathlib iso639