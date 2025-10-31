# ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism

## 📘 Overview
This repository presents a deep learning-based approach for **Isolated Sign Language Recognition (ISLR)** using **pose landmarks** extracted from videos.  
A **BiLSTM (Bidirectional LSTM)** network combined with an **Attention Mechanism** is implemented to learn spatial-temporal dependencies effectively.

---

## 🧠 Key Features
- Utilizes **MediaPipe Holistic** for extracting hand, face, and body landmarks.
- Implements **BiLSTM with Attention** for temporal modeling.
- Supports **multiple class configurations** (e.g., 100 or 300 classes).
- Provides complete **training and inference pipelines**.
- Modular and well-structured source code under `src/`.

---

## 🏗️ Project Structure
```plaintext
ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism/
│
├── src/
│   ├── landmarks_Extraction.ipynb     # Extracts pose landmarks using MediaPipe
│   ├── training_100 Classes.ipynb     # Training notebook for 100-class dataset
│   └── training_300 Classes.ipynb     # Training notebook for 300-class dataset
│
├── data/                              # Dataset folder (optional, ignored by .gitignore)
├── requirements.txt                   # Dependencies list
├── .gitignore                         # Ignore unnecessary files
└── README.md                          # Project documentation
```
---

## ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com/Muhammad-Huzifa/ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism.git
cd ISLR-Landmarks-using-BiLSTM-with-Attention-Mechanism

# Create and activate a virtual environment (optional)
python -m venv venv
venv\Scripts\activate  # On Windows

# Install dependencies
pip install -r requirements.txt


