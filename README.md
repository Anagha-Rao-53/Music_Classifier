# Music Genre Classification 

This project implements a music genre classifier using a Dilated 1D Convolutional Neural Network (DCNN) built with PyTorch. The model is trained to classify audio clips into one of five genres based on their Mel-Frequency Cepstral Coefficient (MFCC) features.

Following the model training, Principal Component Analysis (PCA) is used as a visualization tool to analyze the feature representations learned by the network's convolutional layers.

---

## Dataset

The dataset consists of audio samples from **5 music genres**:
* Blues
* Classical
* Hiphop
* Metal
* Pop

Each genre contains 100 audio samples, for a total of 500 samples in the dataset.

---
# used 5 categories
## Requirements

You will need Python 3 and the following libraries to run the notebook:

* `torch`
* `librosa`
* `numpy`
* `scikit-learn`
* `matplotlib`

You can install them using pip:
```bash
pip install torch librosa numpy scikit-learn matplotlib
