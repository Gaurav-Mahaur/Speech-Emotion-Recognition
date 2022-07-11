# Speech-Emotion-Recognition

This study aims to investigate and implement an Artificial Intelligence (AI) algorithm that will analyze an audio file in real-time, identify and present 
the expressed emotion within it.

Emotions are important part of understanding human interactions. Research is going into finding methods that can at the very least mimic human ability 
to recognise emotions displayed in the form of facial expressions, changes in tone while speaking, etc. Speech Emotion Recognition (SER) is one of such fields.
Using deep learning and machine learning algorithms with the help of Ravdess and TESS dataset we aim to design an automatic emotion recognition system.

**Feature set information**

For this task, the dataset is built using 2800 samples from:
* the [Toronto emotional speech set (TESS) ](https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess)

This sample include:

* 2800 files from TESS. A set of 200 target words were spoken in the carrier phrase "Say the word _____' by two actresses (aged 26 and 64 years) and recordings 
were made of the set portraying each of seven emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral). There are 2800 stimuli in total.
Two actresses were recruited from the Toronto area. Both actresses speak English as their first language, are university educated, and have musical training. Audiometric 
testing indicated that both actresses have thresholds within the normal range.

# Feature Extraction

Feature extraction is the main part of the speech emotion recognition system. It is basically accomplished by changing the speech waveform to a form of parametric 
representation at a relatively lesser data rate.

In this repository, we have used the most used features that are available in librosa library including:
* [MFCC](https://en.wikipedia.org/wiki/Mel-frequency_cepstrum)
* Chromagram
* MEL Spectrogram Frequency (mel)




## Flowcharts And Results

*Flowchart*

![img](https://user-images.githubusercontent.com/93429968/178201079-afb90706-445a-428e-92f6-067b1d8580f3.png)

*Model*


![flowchart](https://user-images.githubusercontent.com/93429968/178201314-8f59d534-1abd-49b0-88c5-74384596e069.jpg)

*Accurracy And Loss plots*


![acc](https://user-images.githubusercontent.com/93429968/178201712-d108d98f-72b5-49f6-9c3f-b4d025233ae5.png)
![loss](https://user-images.githubusercontent.com/93429968/178201742-a6a6466d-afe5-4dc1-aab9-ae6aa93d1c8c.png)

*Confusion Metrix*

![cf](https://user-images.githubusercontent.com/93429968/178202341-453c8ed4-dc4b-4262-ba75-76ea4077b6ff.png)

Results had shown an accuracy of 96.64% of emotional recognition from speech.
