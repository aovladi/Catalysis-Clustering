# Catalysis-Clustering
This repository contains code for 2020 paper "Catalysis Clustering with GAN by Incorporating Domain Knowledge"

## Catalysis generation with GAN

WGAN training procedure follows [this repo](https://github.com/PacktPublishing/Advanced-Deep-Learning-with-Keras/tree/master)

The main code for this stage is the following:
-  `lib` folder contains model builders and utility functions
-  `wgan-luad.py` contains training and generation procedures for lung somatic mutation profiles
-  `wgan-ov.py` contains training and generation procedures for ovarian somatic mutation profiles
-  `requirements.txt` contains the list of requirements for this code
    - You can install requirements all together with: `pip install -r requirements.txt` 

## Evaluation
