# Assignment_7_Veronica
Model Training from Coqui TTS

In this Repo you will find 3 colab notebooks:

1) A Coqui TTS demo to try pre-trained models available --> coqui_test.ipynb

2) A Coqui TTS demo to train a model on LJspeech dataset - this notebook is intented to show the code used for training --> 

3) A Coqui TTS demo to train a model on a custom dataset - the Dataset is called ab_dataset and it has been built by me based on the voice of Alessandro Barbero, an italian professor. I took inspiration from this video https://www.youtube.com/watch?v=6QAGk_rHipE

The original audio file used to create the samples for the dataset has been downloaded from this video https://www.youtube.com/watch?v=zlqqCAPqMMw&t=1111s
I manipulated the audio file with ffmeg (conversion from .mp3 to .wav) and Audacity to split the audio based on silence. Then I converted the samples from stereo to mono with a samplerate of 22050 with the help of https://github.com/xiph/rnnoise.git

In the relative directory on this Repo wavs files and metadata.csv have been uploaded.

Note: I am aware that even if the original audio is of public domain, its usage could be limited.
