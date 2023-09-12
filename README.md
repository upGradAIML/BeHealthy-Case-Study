# Welcome to Syntactic Processing Assignment:

BeHealthy has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.

So, companies like ‘BeHealthy’ are providing medical services, prescriptions and online consultations and generating huge data day by day.

You need to understand that each word in the dataset is provided in a single line. So, first, you need to club all these words together to form the sentences. Moreover, there are blank lines given in the dataset that have been highlighted in the image given above. These blank lines indicate that a new sentence is starting from the next line onwards to the next blank line.

## What is required?

In this assignment, you need to perform the following broad steps:

- You need to process and modify the data into sentence format. This step has to be done for the 'train_sent' and ‘train_label’ datasets and for test datasets as well.
- After that, you need to define the features to build the CRF model.
- Then, you need to apply these features in each sentence of the train and the test dataset to get the feature values.
- Once the features are computed, you need to define the target variable and then build the CRF model.
- Then, you need to perform the evaluation using a test data set.
- After that, you need to create a dictionary in which diseases are keys and treatments are values.
- There are a total of 5 folders as mentioned below:

## Expected Tasks

There are eight major tasks that you need to perform to complete the assignment. They are as follows:

1. **Data preprocessing**
2. **Concept identification**
3. **Defining the features for CRF**
4. **Getting the features words and sentences**
5. **Defining input and target variables**
6. **Building the model**
7. **Evaluating the model**
8. **Identifying the diseass and predicted treatment using a custom NER**
