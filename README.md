# Mortality-Prediction-Challenge

To be, or not to be? Mortality Prediction Challenge

The main question of this challenge is: How to predict the survival of a patient given his or her medical record? More specifically, you will have to predict whether or not the patients died during their stay at the hospital.

Background

Everyday, doctors and nurses collect a lot of information about patients by asking questions and using adapted tools (stethoscope, syringe, sensors, etc.). This data is very useful to monitor health state, diagnose and choose treatments.

It can also be used for statistical predictive analysis.

Data

The training dataset contains information about 80,000 patients, represented by categorical, binary and numerical features (also named "variables"). Those features are for instance age, gender, ethnicity, marital status, as well as medical data such as blood pressure rate or glucose rate. There are a total of 342 variables.

The class (or label) to be predicted is a binary variable telling if the patient died or not during while in the hospital. Fortunately, most of them don't:

Which leads to an imbalanced classification problem. In the above graphic, 0 means "DIDN'T DIE" and 1 means "DIED".

Task

The task is to create a model able to learns from the data and make predictions on unseen data. This is called supervised learning, because the algorithm learns from labeled data. Each data (each patient) has a label telling if he died or not during his stay at the hospital. It is possible to learn a link between data and labels and use it to make predictions: automatically label unseen data.

Link_of_Datasets

https://competitions.codalab.org/competitions/19365#learn_the_details-get_starting_kit

