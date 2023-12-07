# Music-Genre-Classification
Music Genre Classification using AST(Audio Spectrogram Transformer) and MIDI format Classifier

## MIDI format feature
*Rhythmic Patterns*
Repeating patterns that define the rhythm of the piece
*Harmony & Chord Progressions*
Represents the sequences of the chords used in the MIDI file
*Tempo*
A critical feature for classification, distinguishing between different genres
*Pitch & Velocity*
Information  about specific notes being played and corresponding loudness i.e how hard a note is played

## Audio Spectrogram Model (AST)
Reference: https://github.com/YuanGongND/ast

*Architecture Diagram*
![ast_architecture_diagram](https://github.com/yadgire7/Music-Genre-Classification/assets/47882001/1f7fc7ff-036b-43a6-a34e-174f656f5fbf)

## Dataset Used
GTZAN Dataset for Music Genre Classification
Download link: https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

## MIDI Implementation
- Mention input directory path and output directory path
- Create a CSV file using the generated MIDI files
- Read the created CSV file to implement the
- Execute the classification code

## AST Implementation
- Run the ast_gtzan_clf.ipynb
- Mention the file path of the test file from the GTZAN dataset
