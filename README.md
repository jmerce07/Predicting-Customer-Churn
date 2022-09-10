
# Music Streaming Service: Predicting Churn

## Project Motivation

For this project I was interested in predicting customer churn for a fictional music streaming company: Sparkify. Customer churn is defined as when customers stop using a service. This, of course, is not good for a business and can result in a music streaming service to go from a current service to a discontinued service. To prevent churn, companies are using machine learning to identify customers who are likely to churn before doing so. These customers are usually offered some type of incentive to stay and be retained as a customer. This project will try to use data science and PySpark to predict customer churn before it even gets to that point. This will save companies money and increase profits!

The project takes you through the ETL and Data Science process. 
> - We'll load and clean a subset (128MB) of the full dataset (12GB). 
> - Then the Exploratory Data Analysis step happens where the data and variables are observed.
> - Feature Engineering occurs next by modifying and deriving features for the model.
> - Four machine learning algorithms will be used (Logistic Regression, Linear SVC, Naive Bayes, and Random Forest) to predict churn.

## Installations

#### This project requires Python 3. Also the following Python libraries need to be installed:
> - NumPy
> - Pandas
> - Seaborn
> - Matplotlib
> - PySpark SQL
> - PySpark ML
> - Time
> - Datetime
> - Re

## File Descriptions

- **mini_sparkify_event_data.json**: If you want the data that is referred to in the code, you'll need to see go to Udacity's website.

- **Sparkify.ipynb**: This file contains all of the code to extract and transform the data and build and evaluate the model in a Jupyter Notebook. The file includes Markdown cells with commentary on the process.

## Blog Post on Medium

The communication of my findings can be found in my blog post on [Medium](https://medium.com/@jeremyamercer/cancelling-that-music-streaming-subscription-we-already-knew-a7f1be7130ee). My detailed explanation of my process is available in a form where people not to familar with machine learning r data science can understand and relate to.

## Licensing, Authors, Acknowledgements

This is project stems from the Data Scientist Nanodegree from [Udacity](https://www.udacity.com/course/data-scientist-nanodegree--nd025). I would like to thank them for the real life example and knowledge to complete this. The documentation from [Sci-Kit Learn](https://scikit-learn.org/stable/index.html) was referenced many time in the explanation of the models.
