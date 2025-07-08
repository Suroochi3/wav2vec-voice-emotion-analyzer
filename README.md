# 🔊 Wav2Vec-Based Voice Emotion Analyzer

This repository contains a Wav2Vec 2.0 model developed for detecting emotions from speech signals. It is trained as part of the **AI Powered Smart Cognitive Tracker** — a multimodal system designed to identify early signs of mental health issues in adolescents.

---

## 🎯 Project Context

Human speech carries emotional cues like tone, pace, and stress. The Wav2Vec model in this project learns to interpret these cues and classify emotional states (e.g., sad, anxious, neutral, happy), contributing to a broader AI-based mental health assessment system.

---

## 🧠 Model Overview

| Component       | Details                                      |
|----------------|----------------------------------------------|
| Model           | Wav2Vec 2.0 (Facebook AI pretrained)         |
| Task            | Voice Emotion Classification                |
| Framework       | PyTorch, torchaudio                         |
| Data Source     | Public/custom speech emotion dataset        |
| Project Context | Part of "AI Powered Smart Cognitive Tracker" |

---

## 📂 Files Included

- `WAV2VEC MODEL TRAINING.ipynb`  
  → Complete Colab notebook for loading audio, preprocessing, training Wav2Vec, and evaluating performance.

- `data/`  
  → Sample `.wav` or `.csv` files if used.

---

## 🚀 Run on Google Colab

Click below to run this notebook instantly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Suroochi3/wav2vec-voice-emotion-analyzer/blob/main/WAV2VEC%20MODEL%20TRAINING.ipynb)

---

## 📦 Requirements

```bash
pip install torchaudio librosa transformers
