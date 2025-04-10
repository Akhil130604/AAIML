# 🕉️ Devanagari Handwritten Character Recognition

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to recognize handwritten **Devanagari characters**, which include both **alphabets and numerals** used in languages like Hindi, Sanskrit, Marathi, and Nepali.

---

## 📂 Dataset

The dataset used is the [Devanagari Handwritten Character Dataset (DHCD)](https://www.kaggle.com/datasets/sachinpatel21/devanagari-character-dataset), which includes:

- **46 classes**: 36 consonants + 10 numerals
- **92,000 images** in total (2000 per class)
- **Image size**: 32x32 grayscale PNGs

---

## 🧠 Model Overview

The CNN model is built using `tensorflow.keras`, with layers including:

- **Conv2D**
- **MaxPooling2D**
- **Flatten**
- **Dense**
- **Dropout**

It uses the **Adam optimizer** and **categorical crossentropy** loss for multi-class classification.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/devanagari-character-recognition.git
cd devanagari-character-recognition
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the Script
Use jupyter notebook to run the script
