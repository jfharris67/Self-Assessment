# Self-Assessment

## Cohesive Written Analysis:

### Database Setup

My responsibility was to setup the database via Amazon Web Services also known as AWS. The setup of the AWS database was an important part of our project as it served as our data source. I added the necessary tables and data to assist our needs for handling flight data. This included tables for Flights, arrival airports, departure airports, and airlines.

### Machine Learning Model Setup

My secondary role was as a Data Analyst, where I built and tested three classification models, including Logistic Regression, Random Forest, and Gradient Boosting Classifiers. My main contribution was tuning the models to reach high accuracy, precision, recall, and F1-Score. The challenge here was to balance these metrics to design a model that is not just accurate but also reliable. After testing different settings and feature combinations, we determined that the Gradient Boosting Classifier was the best model for our project.

## Challenges

One of the most significant challenges I faced was creating the machine learning model. I went through several iterations to identify the most accurate model for our project. While or model was very accurate overall, there was a gap between each class (ontime and delayed) for the precision, recall, and F1-Score.  I beleive the model was fine tuned very well.  The issue was lack of needed features such as weather and other viaraibles that could cause delays.  I can say the model predicted delays fairly well, but additional data would have helped thin the gap.

## Cohesive Written Summary

I made significant contributions to these areas through team discussions and team reviews. I provided insights into the kind of features that could be useful based on the understanding of the data I gained while setting up the database. 

In the machine learning model evaluation phase, I contributed to our discussions around the performance metrics and interpreting the results. I also suggested using weighted averages for precision, recall, and F1-Score to ensure that our models were evaluated and balanced considering all classes of our target variable.

Although my primary roles were setting up the database and working on model building, I contributed to all stages of the project through active participation in team discussions and team reviews and providing insights based on my understanding of the data and the project's goal.

## Project and Team Summary

Our team embarked on a project to predict and analyze flight delays, utilizing a detailed dataset with various columns. After the testing phase, we decided Gradient Boosting classifiers would be the model of choice. We built a model that predicted flight delays with 93.21% testing accuracy, which provided a delicate balance between precision, recall, and F1-score. Our success was mainly attributable to the robust AWS-hosted database, which I set up and managed, and which was visualized via ER diagrams to aid comprehension. Our team relied on regular meetings, Slack communications, and GitHub collaborations to overcome the challenge of living in different cities. Future projects could benefit from a project management tool for better task delegation and accountability.

We combined diverse expertise, especially in database management and machine learning techniques, crucial in AWS database setup and model tuning. A valuable lesson to upcoming students is the importance of thorough exploratory data analysis before embarking on the modeling phase, which can significantly enhance feature engineering and model selection. Our efforts produced a beneficial model capable of predicting flight delays, however more features could have been added from other data sources to more accurately predict the delay class, such as weather data.  With additional features, this could be an invaluable tool for airlines and passengers.
