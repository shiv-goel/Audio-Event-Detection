# Audio Event Detection
It is an audio classification problem, technically known as "Audio Event Detection".\
Each audio file corresponds to an event class, e.g., children-playing, dog-barking, drilling, etc. The folder "audio_train_1ch/" in "Training Data" contains the mono audio files (1761 wav files) and the file "labels_train.csv" contains the class labels.\
There are 2 tasks to be performed:\
TASK 1: Given an audio file corresponds to a single event, find out that event.\
Evaluation: Accuracy\
TASK 2: Given an audio file contains a sequence of events occurring one after the other, find out that sequence of events. A sequence can contain at least 1 and at most 5 events.\
Evaluation: Edit distance\
    • Return sequence of classes separated by hyphen "-".\ 
        ◦ E.g. street_music-dog_bark-engine_idling \
    • Labels would not repeat consecutively, e.g., street_music-dog_bark-dog_bark will be labeled as street_music-dog_bark\

The "README.docx" file contains the complete problem statement.\

