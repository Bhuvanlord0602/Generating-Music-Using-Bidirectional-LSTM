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

## 🎼 Dataset

All models were trained using the MIDI files from the following dataset:  
📂 **Classical Music MIDI**  
🔗 [Available on Kaggle](https://www.kaggle.com/datasets/soumikrakshit/classical-music-midi)

---

## 🚀 How to Run the Notebooks

To run the evaluation notebooks:

1. **Clone the repository** (or download the files manually):
    ```bash
    git clone https://github.com/yourusername/ai-composer-series.git
    cd ai-composer-series
    ```

2. **Install the required libraries**:  
    Create a virtual environment (optional but recommended), then install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. **Launch Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```
    Open the notebook for your desired composer (e.g., `BI-mozart.ipynb`) in the browser.

4. **Run All Cells**:  
    Inside the notebook, click on `Kernel > Restart & Run All` to evaluate the model and generate outputs.

5. **Optional – MIDI to WAV Conversion**:
    To convert generated MIDI files to `.wav`, use:
    ```bash
    timidity output.mid -Ow -o output.wav
    ```
    or with `fluidsynth`:
    ```bash
    fluidsynth -ni soundfont.sf2 output.mid -F output.wav -r 44100
    ```

> 🎧 *Make sure you have `timidity` or `fluidsynth` installed on your system if you want to listen to audio output.*

---

## 📁 Folder Structure

```
project-root/
├── BI-Albeniz.ipynb
├── BI-bach.ipynb
├── BI-brahms.ipynb
├── ...
├── samples/              # Optional folder for audio outputs
└── README.md             # You're reading it!
```

---

## 👤 Author


Blending code with composition 🎹  
*Exploring the frontiers of generative art and sound.*
