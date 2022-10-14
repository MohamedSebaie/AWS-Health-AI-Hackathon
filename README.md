# AWS-Health-AI-Hackathon

## About Us

* Welcome, We are egabi Solutions' AI team, we have worked on many different AI Projects like NLP, Speech recognition, and Computer Vision domains

## Problem Statement 

* Helping the patients to have some sort of understanding of what their medical symptoms could mean, and providing them with trusted information about their diagnosis.

## Step By Step

![My Image]([https://raw.githubusercontent.com/muhammadayman97/AWS-Health-AI-Hackathon/main/images/pipeline.jpg](https://github.com/muhammadayman97/AWS-Health-AI-Hackathon/blob/main/images/pipeline.jpg))

* Classification model was trained using a Disease Prediction dataset.
* Amazon Medical Comprehend is used to extract patient’s medical information from medical text.
* A semantic similarity method is used to measure the similarity between the medical information and some predefined features which represent medical symptoms.
* Only the medical symptoms with similarity above a specific threshold are taken into consideration.
* The classification model takes the chosen features as input and predicts the best diagnosis.
