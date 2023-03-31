# REPRODUCING: NATURAL TTS SYNTHESIS BY CONDITIONING WAVENET ON MEL SPECTROGRAM PREDICTIONS

_Chandra Shekhar Pandey, Priyanka Bose_

This project validates some of the qualitative claims made in the paper

> J. Shen et al., "Natural TTS Synthesis by Conditioning Wavenet on MEL Spectrogram Predictions," 2018 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Calgary, AB, Canada, 2018, pp. 4779-4783, doi: 10.1109/ICASSP.2018.8461368.

which describes Tacotron2, a neural network for predicting mel spectograms from text, which can then be used with a vocoder to synthesize speech.

To reproduce this work:

* Use the `Colab_Chameleon_Ubuntu.ipynb` notebook to reserve a server on Chameleon, configure it with the required software and libraries, and set up an SSH tunnel between your local system and this server.
* Then, open the `Tacotron2_validation.ipynb` notebook on Colab: [Tacotron2 validation](https://colab.research.google.com/github/indianspeedster/ML_Project_Tacotron2/blob/main/Tacotron2_validation.ipynb).
* In the top-right part of the interface, click on the ▼ next to the word "Connect". Select "Connect to a local runtime." Then paste the URL of your JupyterHub server from the first notebook.
* You may then run the Tacotron2 notebook on Colab. 