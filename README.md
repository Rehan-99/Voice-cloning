# Text-To-Speech with Custom Voice
This project focuses on the development of a personalized voice cloning model. The primary objective of this project is to create a synthetic voice that can closely emulate a specific individual's unique vocal characteristics. The developed model will not just mimic the tone or pitch of the target speaker, but will also capture and replicate their speech patterns, pronunciation, accent, and other nuanced attributes that make each person's voice distinct.

This project utilizes the Tortoise library to convert a given text into speech using a custom voice.
## Requirements

    Python 3.x
    torch
    torchaudio
    IPython
    Tortoise

## Usage

This script prompts you to upload custom voice samples which are then used to synthesize speech from a provided text string.

1.Follow the prompts to upload your custom voice samples. They must be .wav files and between 6 to 10 seconds long. At least two audio clips are recommended for better results.

2. The script will convert the provided text into speech using your custom voice samples.

3.The resulting audio will be saved as a .wav file in the same directory and also displayed in an audio player if the script is run in an environment like Jupyter Notebook or Google Colab.
