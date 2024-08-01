# Audio Recorder using Python

## Description
This project records audio from your microphone and saves it as WAV files. It uses the `sounddevice` library to capture audio and `scipy` and `wavio` libraries to save the audio data into WAV format.

## Installation
To run this project, you need to install the following libraries:
- `sounddevice`
- `scipy`
- `wavio`

You can install them using pip:
```bash
pip install sounddevice scipy wavio

-------------------------------------------
Code Explanation

Sampling Frequency: The number of samples per second (in Hz). In this project, it is set to 44100 Hz.
Recording Duration: The length of the recording in seconds. In this project, it is set to 5 seconds.
Recording: The audio is recorded using the sounddevice library and saved into a NumPy array.
Saving Audio: The recorded audio is saved into two WAV files using scipy.io.wavfile.write and wavio.write.

-----------------------------
Output
When you run the script, it will create two WAV files in the current directory:

recording0.wav
recording1.wav
These files contain the recorded audio from your microphone for the specified duration.
