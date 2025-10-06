# Details
One can find the slides of lecture 4 `Lecture 4.pdf`.
 
Below one can find the first exercises for the Digital Signal Processing part of Introduction to Smart Systems Engineering course at the Hanze University of Applied Sciences.


# Exercises

1. Create timeseries data, then using FFT, create a spectrum plot (= frequency domain graph) in which aliasing is present.

1. Download and load the following:  https://bigsoundbank.com/UPLOAD/wav/1064.wav, in Python. Now decimate the signal by a power of 3 (= keep every third datapoint). Play the original sound, then play the decimated sound. What has happened?

1. Plot an FFT of the original and the decimated sound. Does this confirm what you previously noticed?

1. Challenge: Plot a spectrogram of sound data of your liking using https://docs.scipy.org/doc/scipy/reference/generated/scipy.signal.spectrogram.html
    - Super challenge: Can you try out different windows and analyze the difference? What could be the cause of the difference?

1. Alternative challenge: When the $x[n]$ is a pure sine wave, there is the possibility where $frac{1}{2} f_s = f_{Nyquist}$ is not enough to recreate the frequency of the input sine wave. Can you find this?

