# TP1: Conversion of Sampling Frequency and STFT

*By Daniel Jorge Deutsch, Kevin Kuhl and Santiago Velandia (25/09/2020)*
</br>


## Code Setup

### Windows

1. Make sure you have python >=3.6 installed
2. Create a virtual environment and activate it
    2.1 pip install virtualenv
    2.2 virtualenv venv 
    2.3 .\venv\scripts\activate.bat
3. Install the dependencies of the code listed in the file requirements.txt
    3.1 pip install -r requirements.txt
4. Create the input folder manually and place there the file named "caravan_48khz.wav":
    4.1 ./inputs/caravan_48khz.wav
5. Create the output folders manually:
    5.1 ./outputs/figures
    5.2 ./outputs/sounds
6. Enjoy the code :)

Obs: if pyaudio doesn't work at first you might have to do the following:

1. pip install pipwin
2. pipwin install pyaudio