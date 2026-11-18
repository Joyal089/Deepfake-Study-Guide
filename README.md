# Deepfake Generator: Face and Voice Manipulation (Study Guide)

A study project on how deepfake videos are made: swapping faces and changing or synthesising voices. It is a **written guide and research notes, not a working generator**. The only code is a small error-logging helper.

## Contents

| File | What it is |
|---|---|
| `Guide.txt` | Step-by-step outline: environment setup, datasets, training face and voice models, combining them, post-processing |
| `Debugging and logging snippet.py` | Template for logging errors with tracebacks in a Python pipeline |

## Tools covered in the guide

- **Face swapping:** DeepFaceLab, OpenCV
- **Voice:** Tacotron2, WaveGlow, praat-parselmouth, librosa
- **Frameworks:** Python 3, PyTorch, TensorFlow
- **Datasets:** CelebA (faces), VoxCeleb / VCTK (voices)
- **Post-processing:** Audacity, DaVinci Resolve, Adobe Premiere Pro

## Responsible use

Deepfakes can cause real harm. Only use these techniques with the clear consent of anyone whose face or voice is used, label synthetic media as synthetic, and follow the law where you live. This repository is for learning about the technology, including how to recognise it.
