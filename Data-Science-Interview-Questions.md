### What does one understand by the term Data Science?
An interdisciplinary field that constitutes various scientific processes, algorithms, tools, and machine learning techniques working to help find common patterns and gather sensible insights from the given raw input data using statistical and mathematical analysis is called Data Science.
- It starts with gathering the business requirements and relevant data.
- Once the data is acquired, it is maintained by performing data cleaning, data warehousing, data staging, and data architecture.
- Data processing does the task of exploring the data, mining it, analyzing it which can be finally used to generate the summary of the insights extracted from the data.
- Once the exploratory steps are completed, the cleansed data is subjected to various algorithms like predictive analysis, regression, text mining, recognition patterns, etc depending on the requirements.
- In the final stage, the results are communicated to the business in a visually appealing manner. This is where the skill of data visualization, reporting, and different business intelligence tools come into the picture.

### What are some of the techniques used for sampling? What is the main advantage of sampling?
Data analysis can not be done on a whole volume of data at a time especially when it involves larger datasets. It becomes crucial to take some data samples that can be used for representing the whole population and then perform analysis on it. While doing this, it is very much necessary to carefully take sample data out of the huge data that truly represents the entire dataset.
There are majorly two categories of sampling techniques based on the usage of statistics, they are:
- **Probability Sampling techniques:** Clustered sampling, Simple random sampling, Stratified sampling.
- **Non-Probability Sampling techniques:** Quota sampling, Convenience sampling, snowball sampling, etc.

### List down the conditions for Overfitting and Underfitting.
- **Overfitting:** The model performs well only for the sample training data. If any new data is given as input to the model, it fails to provide any result. These conditions occur due to low bias and high variance in the model. Decision trees are more prone to overfitting.
- **Underfitting:** Here, the model is so simple that it is not able to identify the correct relationship in the data, and hence it does not perform well even on the test data. This can happen due to high bias and low variance. Linear regression is more prone to Underfitting.

###  What is Collaborative filtering?
Collaborative filtering used to search for correct patterns by collaborating viewpoints, multiple data sources, and various agents.

### State the difference between the expected value and mean value?
There are not many differences between these two, but it is to be noted that these are used in different contexts. The mean value generally refers to the probability distribution whereas the expected value is referred to in the contexts involving random variables.

### What is a Linear Regression?
Linear regression is a statistical programming method where the score of a variable ‘X’ is predicted from the score of a second variable ‘Y’. Y is referred to as the predictor variable and X as the criterion variable.

### Name three disadvantages of using a linear model
Three disadvantages of the linear model are:
1. The assumption of linearity of the errors.
2. You can’t use this model for binary or count outcomes
3. There are plenty of overfitting problems that it can’t solve

### What is logistic regression in Data Science?
Logistic Regression is also called as the logit model. It is a method to forecast the binary outcome from a linear combination of predictor variables.

### Difference between Regression and Classification?
The major difference between Regression and Classification is that Regression results in a continuous quantitative value while Classification is predicting the discrete labels.
However, there is no clear line that draws the difference between the two. We have a few properties of both Regression and Classification. 
These are as follows:

**Regression**
- Regression predicts the quantity.
- We can have discrete as well as continuous values as input for regression.
- If input data are ordered with respect to the time it becomes time series forecasting.

**Classification**
- The Classification problem for two classes is known as Binary Classification.
- Classification can be split into Multi- Class Classification or Multi-Label Classification.
- We focus more on accuracy in Classification while we focus more on the error term in Regression.

### When is resampling done?
Resampling is a methodology used to sample data for improving accuracy and quantify the uncertainty of population parameters. It is done to ensure the model is good enough by training the model on different patterns of a dataset to ensure variations are handled. It is also done in the cases where models need to be validated using random subsets or when substituting labels on data points while performing tests.

### Why do you need to perform resampling?
Resampling is done in below-given cases:
- Estimating the accuracy of sample statistics by drawing randomly with replacement from a set of the data point or using as subsets of accessible data
- Substituting labels on data points when performing necessary tests
- Validating models by using random subsets

### What is Power Analysis?
The power analysis is an integral part of the experimental design. It helps you to determine the sample size requires to find out the effect of a given size from a cause with a specific level of assurance. It also allows you to deploy a particular probability in a sample size constraint.

### What is bias?
Bias is an error introduced in your model because of the oversimplification of a machine learning algorithm.” It can lead to underfitting.

### What is ‘Naive’ in a Naive Bayes algorithm?
The Naive Bayes Algorithm model is based on the Bayes Theorem. It describes the probability of an event. It is based on prior knowledge of conditions which might be related to that specific event.

### Name three types of biases that can occur during sampling
In the sampling process, there are three types of biases, which are:
1. Selection bias
2. Under coverage bias
3. Survivorship bias

### Explain cluster sampling technique in Data science
A cluster sampling method is used when it is challenging to study the target population spread across, and simple random sampling can’t be applied.

### Explain why Data Cleansing is essential and which method you use to maintain clean data
Dirty data often leads to the incorrect inside, which can damage the prospect of any organization. For example, if you want to run a targeted marketing campaign. However, our data incorrectly tell you that a specific product will be in-demand with your target audience; the campaign will fail.

### When underfitting occurs in a static model?
Underfitting occurs when a statistical model or machine learning algorithm not able to capture the underlying trend of the data.

### What is Decision Tree algorithm?
A decision tree is a popular supervised machine learning algorithm. It is mainly used for Regression and Classification. It allows breaks down a dataset into smaller subsets. The decision tree can able to handle both categorical and numerical data.

### Define the term cross-validation
Cross-validation is a validation technique for evaluating how the outcomes of statistical analysis will generalize for an Independent dataset. This method is used in backgrounds where the objective is forecast, and one needs to estimate how accurately a model will accomplish.

###  What is a Random Forest?
Random forest is a machine learning method which helps you to perform all types of regression and classification tasks. It is also used for treating missing values and outlier values.

### What is the K-means clustering method?
K-means clustering is an important unsupervised learning method. It is the technique of classifying data using a certain set of clusters which is called K clusters. It is deployed for grouping to find out the similarity in the data.

### What is reinforcement learning?
Reinforcement Learning is a learning mechanism about how to map situations to actions. The end result should help you to increase the binary reward signal. In this method, a learner is not told which action to take but instead must discover which action offers a maximum reward. As this method based on the reward/penalty mechanism.

### What is Back Propagation?
Back-propagation is the essence of neural net training. It is the method of tuning the weights of a neural net depend upon the error rate obtained in the previous epoch. Proper tuning of the helps you to reduce error rates and to make the model reliable by increasing its generalization.

### Explain the benefits of using statistics by Data Scientists
Statistics help Data scientist to get a better idea of customer’s expectation. Using the statistic method Data Scientists can get knowledge regarding consumer interest, behavior, engagement, retention, etc. It also helps you to build powerful data models to validate certain inferences and predictions.

### What is Normal Distribution?
A normal distribution is a set of a continuous variable spread across a normal curve or in the shape of a bell curve. You can consider it as a continuous probability distribution which is useful in statistics. It is useful to analyze the variables and their relationships when we are using the normal distribution curve.

### What is p-value?
When you conduct a hypothesis test in statistics, a p-value allows you to determine the strength of your results. It is a numerical number between 0 and 1. Based on the value it will help you to denote the strength of the specific result.

### What is skewed Distribution & uniform distribution?
Skewed distribution occurs when if data is distributed on any one side of the plot whereas uniform distribution is identified when the data is spread is equal in the range.

### What is precision?
Precision is the most commonly used error metric is n classification mechanism. Its range is from 0 to 1, where 1 represents 100%.

### State the difference between a Validation Set and a Test Set
A Validation set mostly considered as a part of the training set as it is used for parameter selection which helps you to avoid overfitting of the model being built.
While a Test Set is used for testing or evaluating the performance of a trained machine learning model.

### What is the term Binomial Probability Formula?
The binomial distribution contains the probabilities of every possible success on N trials for independent events that have a probability of π of occurring.

###  Is it possible to capture the correlation between continuous and categorical variable?
Yes, we can use analysis of covariance technique to capture the association between continuous and categorical variables.

###  What are the Eigenvalue and Eigenvector?
Eigenvectors are for understanding linear transformations. Data scientist need to calculate the eigenvectors for a covariance matrix or correlation. Eigenvalues are the directions along using specific linear transformation acts by compressing, flipping, or stretching.

