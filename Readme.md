# 🖼️ Image Captioning with CNN + LSTM  

This project implements an **image captioning system** using a **CNN encoder (Xception)** to extract image features and an **LSTM decoder** to generate natural language captions.  
The model is trained on the **Flickr8k dataset**.

---

## 📌 Features
- Extracts image features using **Xception (pretrained on ImageNet)**  
- Preprocesses and cleans text captions  
- Builds a vocabulary and tokenizer  
- Trains a CNN–LSTM model for caption generation  
- Supports saving/loading features, tokenizer, and trained models  

---

## ⚙️ Requirements
Make sure you have **Python 3.9–3.11** installed.  
Install dependencies using:

```bash
pip install -r requirements.txt

