# Signal-Processor
<img width="1255" alt="FirstPanel" src="https://user-images.githubusercontent.com/52253824/229042686-6f5287a3-59f3-4c4e-b66f-b35ececed10c.png">
<img width="1255" alt="SecondPanel" src="https://user-images.githubusercontent.com/52253824/229044251-f5550d31-0e02-4326-80d5-7922b0e066ae.png">
<img width="1254" alt="ThirdPanel" src="https://user-images.githubusercontent.com/52253824/229046050-88f9b5da-cea8-4a8d-a8a1-df0895707ce0.png">


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
