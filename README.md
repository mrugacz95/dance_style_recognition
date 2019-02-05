### Dance style recognition

Ballroom dance style recognition based on audio file, using CNNs.

We used MFCC for extracting spectrogram. Then we put to use convolution neural networks.

Finally we achieved 69,85 accuracy.

There is also script for data exploration showing that SVM can predict styles based on song bpm. 

Important: to download dataset you have to run `getExtendedBallroomDataset.py` with python2.7

## Model 

![image](https://user-images.githubusercontent.com/12548284/52310785-e41d1f80-29a4-11e9-9bc4-4e63c23db1f9.png)

## Presentation

[Google presentation](https://docs.google.com/presentation/d/1c5SNKTdiALrbNW_w_yPHm2h-IP14VhVwYf7p6RItM7M/edit?usp=sharing)

## Libraries

```
matplotlib
numpy
librosa
sklearn
tensorflow
soundfile
scipy
scikit-learn
```

## Dataset 

[Source](http://anasynth.ircam.fr/home/media/ExtendedBallroom)

> U. Marchand, G. Peeters, "The Extended Ballroom Dataset", in ISMIR 2016 Late-Breaking Session, New-York, USA.

