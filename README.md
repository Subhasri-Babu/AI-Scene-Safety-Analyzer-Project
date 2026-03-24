# 🚀 AI Scene Safety Analyzer

An advanced AI-powered application that analyzes images and determines safety levels using computer vision and large language models.

## 📌 Overview

The **AI Scene Safety Analyzer** automatically detects safety risks in images and classifies them into:

- ✅ Safe
- ⚠️ Warning
- 🔴 Dangerous

It also provides:
- Risk Score (0–100)
- Detailed explanation
- Recommended safety actions

---

## 🧠 How It Works

1. Image is uploaded via UI
2. **BLIP Model** generates image caption
3. Caption is sent to **LLaMA 3.3-70B (via Groq API)**
4. AI analyzes and returns:
   - Safety Label
   - Risk Score
   - Reason

---

## ✨ Features

- 🔍 AI-powered image safety analysis
- 🎯 Risk scoring system (0–100)
- 🌍 Multi-language support (7 languages)
- 🔊 Voice output (Text-to-Speech)
- 📊 Safety charts (Bar & Pie)
- 🖼️ Heatmap overlay on images
- 📄 Export reports:
  - PDF
  - CSV
  - Excel
- 💻 Beautiful UI using Gradio

---

## 🛠️ Technologies Used

- Python 3.12
- BLIP (Image Captioning Model)
- LLaMA 3.3-70B (via Groq API)
- Gradio (UI)
- PyTorch
- Pandas
- Matplotlib
- gTTS (Voice)
- deep-translator

---

## 🖥️ Project Structure

project/
│── app.py
│── project.ipynb
│── requirements.txt
│── README.md
