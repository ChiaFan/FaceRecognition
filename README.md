# FaceRecognition

Face Recognition with dlib

This project implements a face recognition system using the dlib library in Python. It detects faces in images, extracts 128-dimensional feature vectors using a pre-trained ResNet model, and compares them to determine if two images depict the same person based on Euclidean distance.

Features
* Detects faces in images using dlib's frontal face detector.
* Extracts 68 facial landmarks using a pre-trained shape predictor.
* Computes 128D face descriptors using dlib's face recognition model.
* Compares two images to determine if they show the same person by calculating the Euclidean distance between feature vectors.
* Supports multiple platforms (Cloud, PC) with configurable file paths.

Requirements
* Python 3.6+
* dlib
* numpy
* Pre-trained models:
  shape_predictor_68_face_landmarks.dat (for facial landmark detection)
  dlib_face_recognition_resnet_model_v1.dat (for face recognition)
