# TP1: Conversion of Sampling Frequency and STFT

*By Daniel Jorge Deutsch, Kevin Kuhl and Santiago Velandia (25/09/2020)*
</br>


## Code Setup

### Windows

1. Make sure you have python >=3.6 installed
2. Create a virtual environment and activate it
    ``` 
    pip install virtualenv
    virtualenv venv 
    .\venv\scripts\activate.bat
    ```
3. Install the dependencies of the code listed in the file requirements.txt
    ```
    pip install -r requirements.txt
    ```
4. Create the input folder manually and place there the file named "caravan_48khz.wav":
    ```
    mkdir .\inputs
    ```
5. Create the output folders manually:
    ```
    mkdir .\outputs\figures
    mkdir .\outputs\sounds
    ```
6. Enjoy the code :)

Obs: if pyaudio doesn't work at first you might have to do the following:

```
pip install pipwin
pipwin install pyaudio
```