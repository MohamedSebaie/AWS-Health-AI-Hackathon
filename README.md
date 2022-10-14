# AWS-Health-AI-Hackathon

## Step By Step

* Classification model was trained using a Disease Prediction dataset.
* Amazon Medical Comprehend is used to extract patient’s medical information from medical text.
* A semantic similarity method is used to measure the similarity between the medical information and some predefined features which represent medical symptoms.
* Only the medical symptoms with similarity above a specific threshold are taken into consideration.
* The classification model takes the chosen features as input and predicts the best diagnosis.
