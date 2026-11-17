# 📝 AI Text Summarizer using T5 Transformer

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=for-the-badge&logo=pytorch)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi)

> An AI-powered text summarization application using a fine-tuned T5-Small Transformer model to convert lengthy conversations into concise, meaningful summaries.

</div>

---

## 🎯 Project Overview

This project implements **Abstractive Text Summarization** using the T5-Small Transformer model.

The model is fine-tuned on the **SAMSum Dialogue Summarization Dataset** and integrated with FastAPI to provide an interactive web application.

## 🖥️ Application Preview

<div align="center">
      
![AI Text Summarizer](images/homepage.png)

</div>

Users can paste lengthy conversations and generate concise summaries through a clean and interactive interface.

## ✨ Features

- Fine-tuned T5-Small Transformer model
- Dialogue summarization using Samsum dataset
- Text preprocessing using Regex
- T5 Tokenizer for text tokenization
- Beam Search decoding
- FastAPI backend integration
- Interactive HTML, CSS and JavaScript interface
- GPU / CPU support

## 🧠 Model Workflow

```text
Input Dialogue
      ↓
Text Preprocessing (Regex)
      ↓
T5 Tokenizer
      ↓
Fine-Tuned T5-Small
      ↓
Beam Search Decoding
      ↓
Generated Summary
      ↓
FastAPI Web Application
```

## 📊 Training Configuration

| Parameter | Value |
|---|---|
| Model | T5-Small |
| Dataset | SAMSum |
| Epochs | 6 |
| Batch Size | 8 |
| Weight Decay | 0.01 |
| Warmup Steps | 500 |
| Max Input Length | 512 |
| Max Summary Length | 150 |
| Beam Search | 4 Beams |
| Framework | PyTorch |

## 📈 Training Results

| Metric | Result |
|---|---:|
| Total Epochs | 6 |
| Total Training Steps | 3,750 |
| Final Training Loss | 0.881289 |
| Training Runtime | 1,494 seconds |
| Training Time | 24 min 54 sec |

The model was fine-tuned for six epochs using the SAMSum dataset. The final training loss was approximately **0.8813**.

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- T5-Small
- T5 Tokenizer
- Regex
- FastAPI
- HTML, CSS, JavaScript
- SAMSum Dataset

## 📂 Project Structure

```text
AI-Text-Summarizer/
│
├── images/
│   └── homepage.png
│
├── saved_summary_model/
│
├── app.py
├── index.html
├── Text_summerizer.ipynb
├── requirements.txt
└── README.md
```

## ⚙️ Run Locally

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd AI-Text-Summarizer
```

**2. Install dependencies**

```bash
pip install -r requirements.txt
```

**3. Start the application**

```bash
uvicorn app:app --reload --port 8000
```

**4. Open in browser**

```text
http://127.0.0.1:8000
```

## 📚 Learning Outcomes

- Transformer Architecture
- Encoder-Decoder Models
- Transfer Learning and Fine-Tuning
- NLP and Text Summarization
- Tokenization and Text Preprocessing
- Beam Search Decoding
- Model Saving and Loading
- FastAPI Backend Development
- End-to-End AI Application Development

## 🔮 Future Improvements

- PDF and DOCX summarization
- Multilingual summarization
- Batch text summarization
- Model quantization
- Cloud deployment

## 👨‍💻 Author

**Sumit Gaikwad**

AI/ML Engineer | Deep Learning | NLP | Generative AI

[![GitHub](https://img.shields.io/badge/GitHub-Sumit_Gaikwad-181717?style=for-the-badge&logo=github)](https://github.com/gaikwadsumitsudhakar-cpu)

---

<div align="center">

⭐ If you like this project, don't forget to give it a star!

**Built with ❤️ using Python, PyTorch & Hugging Face Transformers.**

</div>
