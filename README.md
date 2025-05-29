<div align="center">

<br />

<h1>🧠 DeToxy: Hate Speech Detection from Speech</h1>

<p><strong>Baseline Model - Version 1.0</strong></p>

<img src="https://img.shields.io/badge/-NLP-008080?style=for-the-badge&logo=ApacheSpark&logoColor=white" alt="NLP" />
<img src="https://img.shields.io/badge/- Transformers-FF9E0F?style=for-the-badge&logo=HuggingFace&logoColor=black" alt="Transformers" />
<img src="https://img.shields.io/badge/-Wav2Vec2-430098?style=for-the-badge&logo=OpenAI&logoColor=white" alt="Wav2Vec2" />
<img src="https://img.shields.io/badge/-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/-Emotion_Recognition-yellow?style=for-the-badge&color=ffcc00" alt="Emotion Recognition" />
<img src="https://img.shields.io/badge/-Hate_Speech-black?style=for-the-badge&color=000000" alt="Hate Speech" />
<img src="https://img.shields.io/badge/-BERT-005571?style=for-the-badge&logo=Google&logoColor=white" alt="BERT" />

<h3 align="center">A speech-based E2E system to detect and classify hate speech using audio and transcript</h3>

</div>

---

## ✅ What's Done So Far

### 📊 Datasets Used

| Dataset Name | Description                                           | Link                                                        |
| ------------ | ----------------------------------------------------- | ----------------------------------------------------------- |
| Common Voice | Multilingual speech corpus (used Version 6.1)         | [Common Voice](https://commonvoice.mozilla.org/en/datasets) |
| LJ Speech    | English speech dataset by a single speaker            | [LJ Speech](https://keithito.com/LJ-Speech-Dataset/)        |
| MELD         | Multimodal EmotionLines Dataset (raw audio extracted) | [MELD](https://affective-meld.github.io/)                   |
| VCTK         | Voice Cloning Toolkit (multi-speaker English corpus)  | [VCTK](https://datashare.ed.ac.uk/handle/10283/2950)        |

### 🛠️ System Architecture Completed

* ✅ Preprocessing/Data cleaning and preparation of audio + transcript
* ✅ Pre-trained Wav2Vec2-model fine-tuned on Detoxy Dataset for hate speech detection
* ✅ Transformer-based contextual layers for context/semantics-aware modeling
* ✅ Extracted prosodic and paralinguistic features (pitch, energy, pauses)
* ✅ Results compiled and presented in test and test-trigger environments

### 📈 Current Evaluation Results

| Epoch| System Category | Test  | Test-T  |  
| -----| --------------- | ----- | ------  | 
| 002  | E2E  :Macro F1  | 0.902 | 0.497   | 
| 002  | E2E  :Micro F1  | 0.926 | 0.988   | 

---

## 🧩 A Lot More Research Work in progress... 

---

## 🚀 Get Started with DeToxy

**Prerequisites:**

* Python 3.9+
* PyTorch
* Librosa, Transformers, Scikit-learn, etc.

```bash
# Clone this repo
https://github.com/SimoneRodriguess/DeToxy.git
cd DeToxy

# Install dependencies
pip install -r requirements.txt

#Download the datasets and their corresponding transcripts
#Prepare the data by data_prep

# Train the model
python run_iemocap-ours-meld.py 
```
<strong>...And your hate speech detection baseline model is ready!</strong>

---

Thank you for checking out DeToxy! 🌸 This is just the beginning of smarter, safer speech tech.

<p align="center">
  With love from Simone 💖
</p>
