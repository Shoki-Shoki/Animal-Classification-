# Animal-Classification-
Team Project 
Challenge Overview
The objective of this challenge is to create a machine learning model to accurately predict the likelihood that an image contains a zebra, as opposed to an elephant. While this may be an easy task for humans, elephants, and zebras, your computer will find it a bit more difficult.

You can also have a look at the original challenge as on Zindi.

The total dataset contains 13,999 images of zebras and elephants, sampled from the Snapshot Serengeti collection of more than 6 million animals.

Your task is to predict whether a given image contains a zebra or elephant. For each unique image ID in the test set you should estimate the likelihood that the image contains a zebra or elephant, with an estimated probability value between 0 and 1. A value of 1 represents a zebra and 0 represents an elephant. These images do not contain both simultaneously. It is therefore only a binary classification task.

The dataset
You are given 13,999 photos each with a unique identifier. The data is given in jpeg format. Each photo has already been resized to 330x330 pixels. The dataset can be downloaded here.

The dataset is structured as follows:
ID 0 - 6,999 are all elephants.
ID 7,000 - 13,999 are zebras.
Training set (size: 10,000):
ID 0 - 5,000 as well as
ID 7,000 - 12,000
Validation set (size: 2,000):
ID 5,000 - 5,999 as well as
ID 12,000 - 12,999
Test set (size: 2,000):
ID 6,000 - 6,999 as well as
ID 13,000 - 13,999

The data has already been divided into the respective folders. You must write code to load the data in accordingly.
Marking Criteria
There are multiple ways one can tackle the problem. It is up to you to decide and motivate your decisions. You are not limited to using any specific methods or models.

Motivate all of your steps taken in completing the task at hand, this includes but is not limited to:

Exploring the data
Data augmentation
Preprocessing the data
Choosing the right machine learning model(s)
Tuning the model(s)
Performance assessment of the model(s)
Make sure to add your thoughts and motivations behind your decision making as well as the outcome thereof in markdown cells.

Your commentary will be more valuable than the performance of the model itself (but that's obviously important too!)
