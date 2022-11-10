# Assignment_7_Veronica
Model Training from Coqui TTS -- original Repo --> https://github.com/coqui-ai/TTS

In this Repo you will find 3 colab notebooks:

1) A Coqui TTS demo to try pre-trained models available --> Coqui_test.ipynb (this is the one to open to have fun with different models)

2) A Coqui TTS demo to train a glow-tts model on LJspeech dataset for Italian - this notebook is intented to show the code used for training --> Assignment7_Veronica.ipynb

IMPORTANT: the training took a long since the dataset is massive, but if you want to see the output you can try with a lower number of epochs

3) A Coqui TTS demo to train glow-tts model on a custom dataset --> Assignment7_Veronica_ab.ipynb

and the python file used for training on ab_dataset--> train_glowtts_ab.py

you need to upload this file to your drive if you to want to give it a try.

for the original recipe go here --> https://github.com/coqui-ai/TTS/tree/dev/recipes/ljspeech/glow_tts

the Dataset is called ab_dataset and it has been built by me based on the voice of Alessandro Barbero, an italian professor. I took inspiration from this video https://www.youtube.com/watch?v=6QAGk_rHipE

The original audio file used to create the samples for the dataset has been downloaded from this video https://www.youtube.com/watch?v=zlqqCAPqMMw&t=1111s
I manipulated the audio file with ffmeg (conversion from .mp3 to .wav) and Audacity to split the audio based on silence. Then I converted the samples from stereo to mono with a samplerate of 22050 with the help of https://github.com/xiph/rnnoise.git

Link to download ab_dataset --> https://drive.google.com/drive/folders/1-Eexb1kB0zQUhnBpaQaIxEc7pTnwX61g?usp=share_link

Dataset has been constructed following LJspeech formatter as per this guideline https://tts.readthedocs.io/en/latest/formatting_your_dataset.html#formatting-your-dataset

but unfortunately I still get an index error, I guess it's due to the metadata.csv, so the notebook is here to have a look but the work it's still in progress.

Note: I am aware that even if the original audio is of public domain, its usage could be limited.

I am available for any question!
