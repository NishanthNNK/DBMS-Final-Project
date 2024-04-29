# DBMS-Final-Project

## Project Title
Authenticity in Sentiment: Machine Learning Approach to Differentiating Genuine from Malicious Yelp Reviews

## Project Type
Our project is a multifaceted endeavor that encompasses elements of both Database Translation and a Custom Project.

Database Translation Component: Initially, the project focused on translating the Yelp dataset from its original, denormalized JSON format into a structured relational database schema suitable for SQL storage. This translation was essential to facilitate subsequent data manipulation, analysis, and model training processes. By restructuring the data, we significantly enhanced its accessibility and usability for complex queries and analytical tasks.

Custom Project Component: After restructuring the dataset, we expanded the project's scope to include the development and implementation of natural language processing (NLP) and machine learning techniques. The primary objective of this phase was to create a sophisticated model capable of distinguishing between genuine and malicious reviews effectively. Key elements of this phase included:

Feature Engineering: We crafted and selected relevant features from the dataset that could provide significant insights into the behaviors and characteristics of review text and user patterns.

Sentiment Analysis: We employed sentiment analysis to understand the emotional tone behind reviews, which helped in identifying extremity and bias in the sentiments expressed.

Topic Modeling: By analyzing the common topics discussed in reviews, we gained a deeper understanding of the content and context, which assisted in distinguishing between typical and atypical review patterns.

User Behavior Analysis: Analyzing patterns in user activity and reviewing habits contributed to identifying outliers and potential fraudulent behaviors.

Predictive Modeling: We developed and trained a machine learning model using the features engineered from our analyses. The model was designed to predict the likelihood of a review being genuine or malicious.

Real-time Model Deployment: The final step involved deploying this model into a real-time environment, where it could process incoming review data and provide assessments in real time.

## Overview of Notebooks

### Notebook 1 - Database Initialization and Analysis
Focuses on efficient data manipulation and analysis of the Yelp dataset using Pandas and SQLAlchemy. It involves reading data from CSV files into DataFrames, encompassing Yelp’s businesses, reviews, users, tips, and check-ins. The notebook demonstrates how to create PostgreSQL tables specifically for Illinois data, facilitating localized analysis.

Key functionalities demonstrated:

- Creation of PostgreSQL tables for localized data from Illinois, enabling focused analysis.
- Database backup using pg_dump for security purposes.
- Integration of TextBlob for sentiment analysis and basic machine learning techniques to enrich the dataset with insights into user sentiment and trends, illustrating advanced data processing capabilities within a database management framework.

### Notebook 2 - Machine Learning and Demo
Notebook 2 establishes a comprehensive analysis pipeline to identify likely fake reviews. It leverages Python for data preprocessing, utilizes machine learning models including RandomForest and LSTM for text analysis, and visualizes results effectively.

Key features include:

- Preprocessing routines such as tokenization and sentiment analysis to prepare data for modeling.
- Machine Learning Integration with RandomForest and LSTM models to analyze text and predict fake reviews.
- A Demo section where users can input review text and use the trained model to assess its authenticity. This interactive feature demonstrates the model's practicality by displaying classification metrics, confusion matrices, and word clouds from reviews flagged as fake.

### Notebook 3 - Working File Yelp
Notebook 3 was used in the initial stages of our project as part of Deliverable 02 - Git Repository setup. It likely contains preliminary explorations and configurations necessary for the subsequent development of the project's data processing and machine learning components.

## Team Members - GitHub IDs
Nishanth Nandakumar - NishanthNNK

Jongkyu Lee -  jonakyu

Dinesh Raja Natarajan - dineshrajagithub

## Dataset Description

Our project utilizes the Yelp dataset, which is a collection of data from Yelp's businesses, reviews, and user interactions. The dataset offers a real-world glimpse into the dynamics of customer feedback across various metropolitan areas in the United States and Canada. 

Yelp Reviews Dataset Utilization:
The dataset includes a comprehensive collection of 6,990,280 reviews, offering valuable insights into customer experiences and sentiments. Our project will leverage this vast repository of user-generated content to differentiate genuine reviews from potentially malicious ones. By focusing solely on the textual content of these reviews, we aim to apply natural language processing techniques and machine learning models to discern authentic feedback from deceptive entries.

### Source Link
Access to the Yelp data is available on Kaggle: [Yelp Dataset Reviews](https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset).
