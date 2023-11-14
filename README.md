# OpeninApp
The objective of the give task by OpeninApp is to demonstrate the skills in creating an AI model that is proficient in lip-syncing i.e. synchronizing an audio file with a video file. The task is to ensure the model is accurately matching the lip movements of the characters in the given video file with the corresponding audio file.
The link to google colab notebook :
The input files used are: https://colab.research.google.com/drive/18tKguAcugTcPihg4TtthgDyWUGuX4evh?usp=sharing
* Vedio:https://openinapp.co/5cwva
* Audio:https://openinapp.co/o9vuj
Used Wav2Lip to lipsync using pretrained model downloaded using https://github.com/Rudrabha/Wav2Lip and https://colab.research.google.com/github/justinjohn0306/Wav2Lip/blob/master/Wav2Lip_simplified_v5.ipynb#scrollTo=Qgo-oaI3JU2u
Prerequisites:

- **Python Version:** Python 3.6

- **Install necessary packages using pip:**
  - `pip install -r requirements.txt`

- **Installed Packages:**
  - `librosa==0.8.0`
  - `numpy==1.17.1`
  - `--upgrade pip`
  - `opencv-python`
  - `opencv-contrib-python`
  - `torch==1.1.0`
  - `torchvision==0.3.0`
  - `tqdm==4.45.0`
  - `numba==0.48`
Lip-syncing videos using the pre-trained models (Inference) and two other files in detailed explanation : The result is saved in output/output_voice.mp4.

The link to google colab notebook : https://colab.research.google.com/drive/18tKguAcugTcPihg4TtthgDyWUGuX4evh?usp=sharing
