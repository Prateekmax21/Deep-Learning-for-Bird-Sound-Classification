# Bird Species Classification Using CNNs

This project applies Convolutional Neural Networks (CNNs) to classify bird species based on audio recordings. The goal is to identify bird calls using spectrograms generated from mp3 sound clips.

## Project Overview

- **Binary Classification**: Classify between American Crow and Spotted Towhee.
- **Multi-class Classification**: Predict among 12 Seattle-area bird species.
- **External Evaluation**: Test the trained model on mystery bird audio clips.

## Technologies Used

- Python
- TensorFlow / Keras
- Librosa
- Matplotlib / Seaborn
- Scikit-learn

## Files

- `final_test.ipynb`: Full model training, evaluation, and testing notebook.
- `bird_spectrograms.hdf5`: Preprocessed spectrogram dataset (not included here).
- `test_clips/`: Contains three mystery test audio files.

## How to Run

1. Clone the repo and open the notebook.
2. Ensure you have required dependencies installed.
3. Run all cells in order to preprocess data, train models, and evaluate predictions.

---

*This work is submitted for academic purposes as part of the DATA 5322 course.*
