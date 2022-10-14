# AWS-Health-AI-Hackathon

## About Us
<p align="center">
    <img width="200" src="https://github.com/muhammadayman97/AWS-Health-AI-Hackathon/blob/main/images/egabi.png" alt="Material Bread logo">
</p>

Welcome, We are egabi Solutions' AI team, we have worked on many different AI Projects like NLP, Speech recognition, and Computer Vision domains

## What inspired us

* Our inspiration was based on the motto “Do not google your symptoms”. It’s a world-wide problem that people google their symptoms searching for quick cheap diagnosis which may lead to underestimating / overestimating their medical conditions.

* But these kinds of results could make them avoid the doctor because they don’t want to hear bad news or they’ll worry so much that it leads to other harmful consequences.

* We wanted to help these people by using Amazon Medical Comprehend to build a reliable model that is intended for informational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment.


## Solution

* Building an AI Model that can help the patients to have some sort of understanding of what their medical symptoms could mean, and provide them with an initial diagnosis for their symptoms, that would be more reliable than googling them.

* The patient will write a text explaining his/her symptoms and the model will diagnose the patient’s medical condition.


## Pipeline

![My Image](https://github.com/muhammadayman97/AWS-Health-AI-Hackathon/blob/main/images/pipeline.jpg)


## Step By Step

* Classification model was trained using a Disease Prediction dataset.
* Amazon Medical Comprehend is used to extract patient’s medical information from medical text.
* A semantic similarity method is used to measure the similarity between the medical information and some predefined features which represent medical symptoms.
* Only the medical symptoms with similarity above a specific threshold are taken into consideration.
* The classification model takes the chosen features as input and predicts the best diagnosis.

## Team Members

Muhammad Ayman 


