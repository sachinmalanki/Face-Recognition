# Face-Recognition
Performs Face Recognition using Open CV - Python.
Packages needed -
Scikit-learn, Numpy, imutil, opencv-python

Create the same directory structure as given.

1 - python extract_embeddings.py --dataset dataset --embeddings output/embeddings.pickle --detector face_detection_model --embed
ding-model openface_nn4.small2.v1.t7

2 - python train_model.py --embeddings output/embeddings.pickle --recognizer output/recognizer.pickle --le output/le.pickle

3 - python recognize.py --embedding-model openface_nn4.small2.v1.t7 --recognizer output/recognizer.pickle --le output/le.pickle
--image images/adrian.jpg




