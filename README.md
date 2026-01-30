# Multimodal Executive Function Reproducibility Package

This repository provides full code and preprocessed feature support
for reproducibility of the paper:

"A Multimodal Fusion and Deep Learning Framework for Executive Function Assessment"

Raw child audio/video data are not redistributed due to ethical constraints.
Instead, extracted features, labels, splits, and full training code are released.

## Run
pip install -r requirements.txt
cd code
python extract_audio_features.py
python split_data.py
python train.py
