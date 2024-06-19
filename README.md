# NLP Course Exam Project

## Sentiment Analysis with GoEmotions Dataset

This project involves sentiment analysis using the GoEmotions dataset, which is split into 3 and 6 emotion classes. The project implements several models to analyze the dataset and predict emotions.

## Instructions
To change emotion classification group (3 or 7 emotions) please see cell #11 and modify accordingly. Then run all cells.
For simple models:
1. Run all cells
2. Cancel model training cells
3. Run inference

For BERT:
1. Run last 2 cells

## Models Used
- Naive Bayes
- Multi-layer Perceptron
- K-Nearest Neighbors
- Finetuned BERT
  - [7 emotions](https://www.dropbox.com/scl/fi/soluzvdt7lz5xywq6bv89/bert_model_weights_7label.pth?rlkey=t6hyymrqnaol0yudckwcxyw6k&st=wafgh068&dl=0)
  - [28 emotions](https://www.dropbox.com/scl/fi/5q1lpgqtrks8j2vfrwb4s/bert_model_weights_28label.pth?rlkey=fvnigkehdtvcjp3grp0vgv50g&st=ubfco31v&dl=0)

## Dataset
The dataset used in this project is the [GoEmotions dataset](https://github.com/google-research/google-research/tree/master/goemotions), introduced by Demszky et al. (2020).
