# Signal-Processor
<img width="1255" alt="FirstPanel" src="https://user-images.githubusercontent.com/52253824/229042686-6f5287a3-59f3-4c4e-b66f-b35ececed10c.png">
<img width="1256" alt="SecondPanel" src="https://user-images.githubusercontent.com/52253824/229042684-0ab4caa2-3de9-482e-ab5d-aead88e70dfd.png">
<img width="1255" alt="ThirdPanel" src="https://user-images.githubusercontent.com/52253824/229042676-c671b75b-7a40-4a6a-a857-85a0f2304b31.png">

## Aims
This MATLAB application algorithmically suppresses noise and isolates frequencies in audio files using finite impulse response filtering. It also provides visualisation for the frequency spectrum and lissijous plots for both the processed and unprocessed files alongside playback. The generated filter attributes such as amplitude response, phase response, basic filter response and filter coefficients are also visualised in the GUI. The user may also A/B the filter by using the toggle filter button during playback to compare the audio.

## Features
- High pass, Low pass, Band pass and Band stop filters
- Hanning, Hamming and Blackman window functions
- Support for mono, stereo and files with arbitrary channel numbers
- Synchronised frequency response visualisation
- Synchronised lissijous figure generation

The user has control over the following parameters :
- Cutoff frequency
- Bandwidth (for band pass and band stop filters)
- Filter type
- Window Function
- Window Size (and by extension filter Q)
- Playback position

## Dependencies
This program requires **one** of the following MATLAB add-ons:
- Audio Toolbox
- Communications Toolbox
- DSP System Toolbox
- Signal Processing Toolbox
- Wavelet Toolbox
