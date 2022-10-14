# AWS-Health-AI-Hackathon

## About Us

Welcome, We are egabi Solutions' AI team, we have worked on many different AI Projects like NLP, Speech recognition, and Computer Vision domains

## What inspired you

* Our inspiration was based on the motto “Do not google your symptoms”. In fact, most people in Egypt tend to diagnose themselves or turn to google their symptoms without seeking professional advice because sometimes it may be expensive.

* Almost all of these people end up underestimating or overestimating their medical condition but these kinds of results could make them avoid the doctor because they don’t want to hear bad news or they’ll worry so much that it leads to other harmful consequences.

* We wanted to help these people by using Amazon Medical Comprehend to build a more reliable model that is intended for informational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment.

* The problem statement is Helping the patients to have some sort of understanding of what their medical symptoms could mean, and providing them with trusted information about their diagnosis.

## Pipeline

![My Image](https://github.com/muhammadayman97/AWS-Health-AI-Hackathon/blob/main/images/pipeline.jpg)

## Step By Step

* Classification model was trained using a Disease Prediction dataset.
* Amazon Medical Comprehend is used to extract patient’s medical information from medical text.
* A semantic similarity method is used to measure the similarity between the medical information and some predefined features which represent medical symptoms.
* Only the medical symptoms with similarity above a specific threshold are taken into consideration.
* The classification model takes the chosen features as input and predicts the best diagnosis.


## Future Extension

Our solution can be extended by integrating it with chatbots that can ask the patients questions to give a more reliable result. Also, hospitals in Egypt have doctors that one of their tasks is to do an initial diagnosis on patients when they arrive to direct them to the right clinic, our solution can be extended to replace those doctors in this particular task.

