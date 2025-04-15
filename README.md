# 🎼 AI Composer Series: Classical Music Model Evaluations

> *A deep dive into AI-generated music trained on compositions by classical legends.*

---

## 🏷️ Tags

`#MachineLearning` `#DeepLearning` `#MusicGeneration` `#MIDI` `#AIArt`  
`#ClassicalMusic` `#MusicAI` `#JupyterNotebook` `#ModelEvaluation` `#Python`

---

## 📌 Overview

This project is a curated collection of Jupyter notebooks, each focused on evaluating a neural network model trained to generate music in the style of a specific classical composer.

Each notebook showcases:
- 🎹 Generated melodies
- 📉 Learning curves
- 🎧 Audio samples (converted from MIDI)
- 🧠 Model evaluation

---

## 📚 Composer Notebooks

| Composer               | Notebook Name           |
|------------------------|-------------------------|
| Isaac Albéniz          | `BI-Albeniz.ipynb`      |
| Johann S. Bach         | `BI-bach.ipynb`         |
| Johannes Brahms        | `BI-brahms.ipynb`       |
| Friedrich Burgmüller   | `BI-burgm.ipynb`        |
| Claude Debussy         | `BI-debussy.ipynb`      |
| Enrique Granados       | `BI-granados.ipynb`     |
| Edvard Grieg           | `BI-grieg.ipynb`        |
| Joseph Haydn           | `BI-haydn.ipynb`        |
| Franz Liszt            | `BI-liszt.ipynb`        |
| Felix Mendelssohn      | `BI-mendelssohn.ipynb`  |
| Wolfgang A. Mozart     | `BI-mozart.ipynb`       |
| Robert Schumann        | `BI-schumann.ipynb`     |
| Pyotr I. Tchaikovsky   | `BI-tschai.ipynb`       |

---

## 🛠️ Libraries Used

All notebooks rely on the following libraries and tools:

### 📦 Core Libraries
- `numpy`
- `matplotlib`
- `pandas`
- `seaborn`

### 🎵 Music & Audio Processing
- `pretty_midi`
- `mido`
- `music21` *(optional)*
- `librosa` *(for waveform analysis)*

### 🧠 ML & Deep Learning
- `tensorflow` or `torch` (depending on model)
- `scikit-learn` (for metrics/visualization)

### 📁 File Handling
- `os`, `glob`
- `IPython.display` *(for inline audio playback)*

### 🎧 Audio Tools (optional, for WAV conversion)
- `fluidsynth`
- `timidity`
- `ffmpeg`

---

## 🔊 Audio Evaluation

Each notebook references generated MIDI files, with `.wav` conversions for easier listening.

> 🎧 MIDI files can be tricky to play in-browser; `.wav` files are better for evaluation.

---

## 🧠 Why This Project?

Exploring music generation across composers helps us understand:
- How different musical styles impact learning
- How models internalize rhythm, harmony, and structure
- The creative potential of AI in the arts

---

## 📁 Folder Structure

```
project-root/
│
├── BI-Albeniz.ipynb
├── BI-bach.ipynb
├── BI-brahms.ipynb
├── ...
├── samples/           # Optional folder for audio outputs
└── README.md          # You're reading it!
```

---

## 👤 Author

**Bhuvan**  
Blending code with composition 🎹  
*Exploring the frontiers of generative art and sound.*


---

## 🎼 Dataset

All models were trained using the MIDI files from the following dataset:  
📂 **Classical Music MIDI**  
🔗 [Available on Kaggle](https://www.kaggle.com/datasets/soumikrakshit/classical-music-midi)

This dataset includes a rich collection of MIDI files from various classical composers — ideal for training music generation models.

