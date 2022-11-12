![email-spam-Logo](https://user-images.githubusercontent.com/108679625/200128657-a2d7dffd-1917-498b-9a7c-c60806141abe.png)


With the increase in online consumption of products and services, consumers are facing a huge problem of abundance of spam message in their inbox which are either promotional based aur frauds. But due to this the messages/Email which are of much importance are squashed under the spam messages.

Here we are going to create an Streamlit app to predict whether an SMS is spam or not using Machine learning algorithms and Natural Language Processing(NLP). 

## Data Source
- [Kaggle SMS Spam Dataset](https://www.kaggle.com/datasets/tmehul/spamcsv)

## Methods

- Gathering and loading Data

- Data Cleaning

- Exploratory Data Analysis

- Data Preprocessing -- Vectorization, stemming, removing stop words

- Building a Model

- Evaluate the Model

- Improve the Model

- Convert to a website

- Deployment on Heroku

## Tech Stack

- Python (refer to requirement.txt for the packages used in this project)
- Streamlit (interface for the model)
- Heroku (model storage)

## Explore the Notebook

- check the notebook [here](https://github.com/Sarathns05/SMS-Spam-Detector/blob/main/sms_spam_classification.ipynb)


## Deployment on streamlit

To deploy this project on streamlit, follow these steps:

  - first, make sure you upload your files on Github, including a requirements.txt file
  - Go to streamlit share and login with Github, Google, etc.
  - By using Streamlit create user interface
  - Finally deployed the entire application on Heroku by adding - Procfile (informs Heroku that which application is to be run first), Requirements
    (notifies Heroku about the libraries that needs to be installed before deploying or running our application)
  - Find the Deployed website [here](https://sms-spam-finder.herokuapp.com/)


![Screenshot from 2022-10-18 11-10-05](https://user-images.githubusercontent.com/108679625/197694106-3ee33b32-2709-4e7f-845c-57d6b787a006.png)




