# Intro to Machine Learning Project 
## Instructions
1. First, the audio wav files need to be downloaded using the tool [yt-dlp](https://www.mankier.com/1/yt-dlp). For this run [`audio_retrieval.ipynb`](https://drive.google.com/file/d/1Q4RsKFqIIkKJ_Q8shg88WK1lZbSWgClm/view?usp=share_link). Note that the each file is about 880 KB, totally upto 25.3 GB!
2. Next, generate MEL spectrograms by running `generate_spectrograms.py`. If needed, you may modify the same file to change the Short Time Fourier Transform (STFT) parameters.
3. The next step is to run the models. Please refer to the corresponding Jupyter notebooks. The deep learning based models are present in notebooks 3.1, 3.2 and 3.3. Notebooks 4 and 5 contains steps for feature extraction (run `feature_extraction.py`) and building the classifiers using `sklearn`. For futher insights please check our [code explanation videos](https://drive.google.com/drive/folders/1qnYCeY1qoTXg3zAAzAXr6-Sz5FeCICMM?usp=share_link).
