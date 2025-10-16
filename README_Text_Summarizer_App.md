# 🧠 Text Summarizer App (Abstractive, Transformer-Based)

An **abstractive text summarization app** built using a **Transformer model (facebook/bart-large-cnn)**.  
This project automatically generates concise summaries from long articles using state-of-the-art NLP techniques.  
It includes a notebook for model exploration and a Streamlit-based front-end for deployment.

---

## 🧩 Project Overview

This project demonstrates how to build a complete abstractive text summarization system using Hugging Face Transformers.  
It covers everything from model loading and dataset preparation to evaluation and dashboard visualization.

The summarizer compresses text while preserving meaning — not by extracting sentences, but by generating new ones that capture the essence of the source content.

---

## ⚙️ Features

- Transformer-based abstractive summarization (`facebook/bart-large-cnn`)  
- Evaluation dashboard with readability and compression metrics  
- Interactive Streamlit app for text summarization  
- Dataset loading from Hugging Face (`cnn_dailymail`)  
- Metrics tracking (compression ratio, word count, summary quality)

---

## 🧠 Model Architecture

- **Pretrained Model:** `facebook/bart-large-cnn`  
- **Architecture:** Encoder–Decoder Transformer  
- **Tokenizer:** Byte Pair Encoding (BPE)  
- **Training Dataset:** CNN/DailyMail News Summaries  

---

## 🗂️ Project Structure

```
Text_Summarizer_App/
│
├── Text_Summarizer_App.ipynb     # Main notebook
├── app.py                        # Streamlit front-end (optional)
├── requirements.txt               # Dependencies
├── README.md                      # Documentation
└── LICENSE                        # License file
```

---

## 🧰 Tech Stack & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FF6F00?style=flat&logo=huggingface&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-D00000?style=flat&logo=huggingface&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-005C84?style=flat&logo=matplotlib&logoColor=white)

---

## 🚀 How to Run

### 1️⃣ Run on Google Colab
1. Upload `Text_Summarizer_App.ipynb` to [Google Colab](https://colab.research.google.com)  
2. Ensure GPU runtime is enabled: **Runtime → Change runtime type → GPU**  
3. Execute all cells to train and evaluate the model

### 2️⃣ Run Locally
```bash
git clone https://github.com/<your-username>/Text_Summarizer_App.git
cd Text_Summarizer_App
pip install -r requirements.txt
jupyter notebook Text_Summarizer_App.ipynb
```

### 3️⃣ Run the Streamlit App
```bash
streamlit run app.py
```

---

## 📊 Evaluation Dashboard

| Metric | Description |
|:--|:--|
| **Compression Ratio** | Original length vs summary length |
| **Readability Score** | Evaluates how easy the summary is to read |
| **Summary Length** | Word count of generated summaries |
| **ROUGE Score** | Measures overlap between generated and reference summaries |

---

## 🔍 Key Learnings

- Implementing abstractive summarization using Transformers  
- Evaluating model performance using ROUGE metrics  
- Building lightweight dashboards for NLP metric visualization  
- Deploying summarization pipelines using Streamlit  

---

## 📁 Dataset

- **Dataset Name:** CNN / DailyMail  
- **Source:** [Hugging Face Datasets](https://huggingface.co/datasets/cnn_dailymail)  
- **Description:** News articles paired with human-written summaries  

---

## 🧾 License

This project is open-source and available under the [MIT License](LICENSE).

```
MIT License

Copyright (c) 2025 Janhvi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🌟 Acknowledgments

- [Hugging Face Transformers](https://huggingface.co/transformers/) for model and dataset APIs  
- [PyTorch](https://pytorch.org/) backend for efficient computation  
- [Streamlit](https://streamlit.io/) for web app deployment  
- [CNN/DailyMail Dataset](https://huggingface.co/datasets/cnn_dailymail) for training and evaluation  

---

### 👩‍💻 Author
Developed by **Janhvi** — Data Analyst & Machine Learning Enthusiast  
Built as part of a hands-on NLP project on abstractive text summarization.

