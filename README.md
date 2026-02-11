# 🎙️ Voice-to-Text Transcription Utility (OpenAI Whisper)

This project implements a high-precision automated speech recognition (ASR) system using **OpenAI's Whisper** model. It is designed to streamline the transcription of technical notes and research audio into structured text data.

## 🚀 Overview
[cite_start]The utility leverages a Transformer-based model to transcribe audio with high accuracy in Spanish. It includes a complete pipeline from environment setup to file export, optimized for cloud execution.

## 🛠️ Tech Stack & Implementation
* [cite_start]**Language:** Python 3.x 
* [cite_start]**AI Model:** OpenAI Whisper (`small` model) 
* [cite_start]**Core Libraries:** `whisper` for inference, `google.colab` for file handling 
* [cite_start]**Infrastructure:** Linux-based environment with `ffmpeg` for robust audio processing 

## 🎯 Key Features
* [cite_start]**Automated Environment Setup:** Scripts to install dependencies like `openai-whisper` and `ffmpeg` automatically.
* [cite_start]**Interactive File Handling:** Custom upload widget for audio files (supporting formats like `.m4a`).
* [cite_start]**High-Precision Transcription:** Configured for Spanish language recognition with automatic GPU acceleration.
* [cite_start]**Export Utility:** Automatically generates and downloads a `.txt` file containing the full transcription.

## 🧪 How to Use
1.  🚀 **[Run in Google Colab](https://colab.research.google.com/drive/1yx-r5wHlNV6pDN3QUt3ldKpFzyX4a4mP?usp=sharing)**: Use GPU acceleration to transcribe your files in seconds.
2.  📂 **[View Source](./AI_Whisper_v1.ipynb)**: Review the implementation logic directly in this repository.

---
*Developed as part of my exploration in **Applied AI** and **Remote Workflow Automation**.*
