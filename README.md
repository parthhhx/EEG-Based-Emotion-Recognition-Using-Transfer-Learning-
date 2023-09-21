# EEG-Based-Emotion-Recognition-Using-Transfer-Learning-
EEG based emotion recognition using Transfer Learning and CNN model on SEED-IV.

Feature Extraction is important when it comes to claassifying EEG signals in one of the classes. Traditional methods do not consider spatial relationships among eeg channels which plays a crucical part in final classification.

I have used transer learning method for feature extraction using Image classification pretrained model to get feature vectors. Then feature vectors are arranged in 8*9 map to represent spatial locations. 

CNN model takes spatial feature map and extracts spatial relations between eeg channels and classifies them.

To use this repo for classifying SEED-IV:
1. dataset can be downloaded from: https://bcmi.sjtu.edu.cn/home/seed/ , with dataset owner's permission (you will have to mail dataset owner with License Agreement signed and they will provide you links to download). 
2. There are two .ipynb files, one for featue extraction and one for training CNN from extracted features. First run the feature extraction code and you will be having extracted feratures persisted somewhere on disk.
4. use these features to train CNN and get classification done.
