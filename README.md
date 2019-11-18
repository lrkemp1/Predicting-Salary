# Predicting Salary
## Determine Industry factors that are most important in Predicting Salary using NLP

This data set was scraped from Seek.com.au on 30.10.2019. The scrape was based on roles advertised in Australia related to the 
Job Title 'Data Analyst' and 'Data Scientist'.

- I used a model to predict if the salary would be above or below the median value based on the Job Description.
- I also used a model to predict if the Role was a 'Data Scientist' or 'Data Analyst' based on the Job Description.
- As expected with NLP, Multinomial Naive Bayes Model performed the best.

Methods & Models Used:

NLP:
- TF-IDF vectorization
- Count vectorization

Models:
- Logistic Regression
- Random Forest Classifier
- Multinomial Naive Bayes

Other Methods:
- Word Clouds
- Scoring based on ROC AUC
- Cross Validation

Any feedback or constructive criticism welcome :) 
