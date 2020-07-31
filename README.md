# Implementación de CNN para clasificación y/o identificación de materias primas

 Dataset

This repository contains the dataset that we collected. The dataset spans six classes: glass, paper, cardboard, plastic, metal, and trash. Currently, the dataset consists of 2527 images:

    501 glass
    594 paper
    403 cardboard
    482 plastic
    410 metal

The pictures were taken by placing the object on a white posterboard and using sunlight and/or room lighting. The pictures have been resized down to 512 x 384, which can be changed in data/constants.py (resizing them involves going through step 1 in usage). The devices used were Apple iPhone 7 Plus, Apple iPhone 5S, and Apple iPhone SE.

The size of the original dataset, ~3.5GB, exceeds the git-lfs maximum size so it has been uploaded to Google Drive. If you are planning on using the Python code to preprocess the original dataset, then download dataset-original.zip from the link below and place the unzipped folder inside of the data folder.

If you are using the dataset, please give a citation of this repository. The dataset can be downloaded here.
