# Project4-Job-Recommender

# Overview:

Utilizing NLP and tools to build a job recommender system. Data from kaggle will be used and can be found here. 

Notebooks:
Project4_Job_Recommender.ipynb - contains the code for modeling and developing a recommender system. 
Project4_mongo.ipynb - contains the code for grabbing the data from mongodb that has been uploaded to AWS

# Introduction:

Job searching can be a tedious process. It takes a lot of time to look through each job posting and then reading through the job description. Many times after reading the job description, one can find out that the job is not actually what they want. By looking through each job posting and screening them, one has wasted valuable time on reading irrelevant job postings/descriptions.  

To speed up the job searching process, I decided to build a recommender system that will take user input (some job description) and will return a posting that is currently available. This will speed up the job searching process significantly as one will not have to screen through a vast amount of jobs.  

# Methodology:

By utilizing NLP and modeling tools, we are able to break down each job posting into topics and find out which words are most important in each topic. In the notebook you will find that I used multiple modeling systems to find the optimal topics and word distribution for each topic.  

# Conclusion:

The final recommender system uses LDA to determine topics of documents and cosine similarity to find the most relevant jobs the user wants. 

