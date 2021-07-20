# Attention-Mechanism-to-Traverse-the-Tree

## 01. SHORT INTRODUCTION 
This model uses Sequence-to-Sequence Attention Mechanism to Traverse the Tree.

## REQUIREMENTS 
- Flask
- NumPy
- Pandas
- Tensorflow
- Keras

## 02. TO TRAIN THE MODEL
- Run python attention_train.py --traindata path/to/traindata --loadvocab yes --model model_name.h5
- While training for first time pass --loadvocab no, This will let you to create the vocab file and--loadvocab yes loads the vocab already built.
- To Deploy the model in flask
  - Run python app.py
-  To do interface
  - Run python inference.py

## 03. RESULTS
https://user-images.githubusercontent.com/40186859/126306663-a686ac57-f6e4-4e80-9700-fcba59d95c47.mp4

