# Speaker-Identification-One-Shot-Learning
This ipython notebook contains the siamese type neural network implementation which calcaulates the similarity scores for a pair of voices.
The similarity score is high if the voices belongs to same speaker while score is less for that pair which has voices belonging to 
different speakers.

The model has been trained on Librispeech dataset and it first converts the audio to spectrogram images and then it compares 
them using convolutional neural network.
This notebook has been created in Google Colab and hence contains linux commands and cannot be executed in anaconda ipython
notebook normally.
