# Offline Translator 

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

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
```

## 2️⃣ Set up a virtual environment
python -m venv venv

## 3️⃣ Activate the virtual environment
venv\Scripts\activate

## 4️⃣ Install dependencies
pip install -r requirements.txt

## 5️⃣ Run the application
python translator.py
✅ The first run will download the models (Hindi ≈ 300MB, Kannada ≈ 2.5GB).
✅ After the first run, the application works fully offline.

![Image](https://github.com/user-attachments/assets/346bc9af-519a-4159-bddc-61e744758f98)

## 📦 Requirements
<pre>torch
transformers
sentencepiece
tk
</pre>

# 📸 Screenshots & Snapshots
The resultant Screenshorts 
### English to Hindi
![Image](https://github.com/user-attachments/assets/04e1822d-89b1-4e70-a1dd-a253678484ec)
![Image](https://github.com/user-attachments/assets/84820830-593a-45f5-b4d5-14e470011603)

### English to Kannada 
![Image](https://github.com/user-attachments/assets/dbb749ee-e6ad-45b4-b49c-5f4e1987ba99)
![Image](https://github.com/user-attachments/assets/19205113-9e9a-4adf-b396-5ccaf979ffef)

### 🙌 Credits
Developed by Amrutha M and Anagha S K
Under the guidance of Ms. S. Sandhya, CM (IT), Aircraft Division, HAL

Based on the internship report at HAL, Bengaluru.
