# 🔊 Sound Classification

A project that recognizes sounds (dog bark, siren, rain, clapping...) from audio files.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/souharached9-droid/classification-sons/blob/main/Classification_Sons.ipynb)

## What it does

You give the program a 5-second sound, and it tells you what kind of sound it is.

## Dataset

[ESC-50](https://github.com/karoldvl/ESC-50): 2,000 short audio clips in 50 categories. The notebook downloads it automatically.

## How it works

1. **Prepare the audio**: mono, 22,050 Hz, 5 seconds
2. **Model 1 (SVM)**: uses MFCC features of the sound
3. **Model 2 (CNN)**: uses a Mel-spectrogram (an image of the sound)
4. **Evaluation**: 5-fold cross-validation
5. **Web app**: built with Gradio, you upload a sound and see the prediction

## Results

| Model | Accuracy |
|-------|----------|
| SVM | XX % |
| CNN | XX % |

## How to run

1. Click the **Open in Colab** button above
2. Click **Runtime → Run all**

## Tools used

Python, librosa, scikit-learn, TensorFlow/Keras, Gradio

## Author

souharached9-droid
