# speech-to-text
Using DeepSpeech2 - End -to-End Speech Recognition

## How to install

### 1. Clone the repo
git clone <>
### 2. Get inside the folder
cd models/research/deep_speech

### 3. Set PYTHONPATH to the models folder
export PYTHONPATH="$PYTHONPATH:<path to>/models"
  
### 4. Download the training and evaluation dataset.
python3 data/download.py

### 5. Train the model
python3 deep_speech.py
