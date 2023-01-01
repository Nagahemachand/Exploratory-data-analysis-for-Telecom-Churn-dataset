# Exploratory-data-analysis-for-Telecom-Churn-dataset
The Telecom operator has a dataset inclusive of various attributes and churn labels. This repository has focused on exploratory data analysis of the data considering various measures and methods of data mining.
We'll address the following questions to make more sense for analysis. The code and the analysis is in the Exlporatory data analysis.ipynb file.

Instructions to execute:

Download the dataset and ipynb file. Suppose if you are using Jupyter notebook. Upload the dataset and the ipynb file into one folder and execute the ipynb file to see the code, analysis and results.

Datasets for experimentation: telecom_churn.csv
In this experiment, we will do exploratory data analysis to understand the data better. The dataset contains the record of telecom customers along with the label "churn". Churn = "true" signifies that the customer has left the company, and churn = "false" signifies that the customer is still loyal to the company.

Answer the following questions:

**1.** How many records are there in the dataset?

**2.** How many features are there? Name each feature and assign it as binary, discrete, or continuous.

**3.** As a data scientist, your job is to build a model that identifies customers intending to leave your company. To do that, we prepare our data for the machine learning model. We can have the most advanced algorithm, but our results will be poor if our training data is terrible. According to your intuition, which features are irrelevant? Briefly explain your reasoning.

**4.** Are there any missing values in the data?

**5.** What are the average, median, maximum, minimum, and standard deviation values for the continuous features?

**6.** What is the average number of customer service calls a customer makes to the company?

**7.** In our dataset, data comes from how many states?

**8.** What's the distribution of the "Churn" feature? Is this feature skewed?

**9.** What are the customers' highest and lowest "total day charge"? If we sort the dataset in ascending and descending order by "total day charge", what observation can you make regarding the connection between "total day charge" and "churn" rate?

**10.** What's the average number of customer service calls made by the user who has churned out of the company? Compare and contrast it with the average number of customer service calls made by the user who is still with the company.

**11.** Compare and contrast the average values of numerical features for churned and non-churned users. As a data scientist, what strategy will you recommend to the company to retain more customers?

**12.** Assume you have devised a model which states that if "international plan" = 'no', then the customer will not churn (i.e., "churn" = False). Report accuracy, precision, and recall concerning the "churned" class.

**13.** Calculate P (churn = True | international plan = ‘yes’), P (churn = False | international plan = ‘yes’), P (churn= True | international plan = ‘no’), P (churn = False | international plan = ‘no’). For a customer who has churned, what are the probabilities that the customer has opted/not opted for the international plan? Similarly, given that the customer has not churned, what are the probabilities that the customer has opted/not opted for the international plan?

**14.** Calculate the probability of customers leaving the company, given that he has not made any customer service call. Compare and contrast it with the customer making 1,2,3,4,5,6,7,8,9 customer service calls. Plot the probability of customers leaving the company as customer service calls increase.

**15.** Assume you have devised a model which states that if "international plan" = 'yes' and the number of calls to the service center is greater than 3, then the customer will churn (i.e., "churn" = True). Report accuracy, precision, and recall concerning the "churned" class.
