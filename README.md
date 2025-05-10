# Offline Translator 🇮🇳

An **offline desktop translator app** that converts English text into Hindi or Kannada using Hugging Face Transformers and Tkinter.  
Built as part of an internship project at **Hindustan Aeronautics Limited (HAL)** 🚀

---

## ✨ Features

✅ Translate English → Hindi (`Helsinki-NLP/opus-mt-en-hi`)  
✅ Translate English → Kannada (`facebook/nllb-200-distilled-600M`)  
✅ Simple GUI using Tkinter  
✅ Fully offline after first-time model download  
✅ Font customization for Hindi (`Nirmala UI`) and Kannada (`Noto Sans Kannada`)  
✅ Error handling for empty inputs and translation failures

---

## 💻 Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/AmruthaMalik/offline-translator.git
cd offline-translator

##2️⃣ Set up a virtual environment
python -m venv venv

##3️⃣ Activate the virtual environment
venv\Scripts\activate

##4️⃣ Install dependencies
pip install -r requirements.txt

##5️⃣ Run the application
python translator.py
✅ The first run will download the models (Hindi ≈ 300MB, Kannada ≈ 2.5GB).
✅ After the first run, the application works fully offline.

image url

##📦 Requirements
torch
transformers
sentencepiece
tk

#📸 Screenshots & Snapshots




###🙌 Credits
Developed by Amrutha M and Anagha S K
Under the guidance of Ms. S. Sandhya, CM (IT), Aircraft Division, HAL

Based on the internship report at HAL, Bengaluru.
