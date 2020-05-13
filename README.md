# Music_Genre_Classification

The music dataset contain ten classes.

1.blues

2.classical

3.country

4.disco

5.hiphop

6.jazz

7.metal

8.pop

9.reggae

10.rock

As we all know sound is represented in the form of an audio signal having parameters such as frequency, bandwidth, decibel etc.A typical audio signal can be expressed as a function of Amplitude and Time.Python have some great libraries for audio processing like Librosa and PyAudio.
The Dataset consist of 1000 audio clips,these clips are seperated according to there class.Each class consist of 100 files,So total 1000 files are there in the dataset.These Audio file are in .au format.

To classify our audio clips, we will choose features, i.e. Mel-Frequency Cepstral Coefficients, Spectral Centroid, Zero Crossing Rate, Chroma Frequencies, Spectral Roll-off.After extracting these freatures from audio clips,will build a classfication model for the genre classification.


























