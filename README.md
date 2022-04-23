# SC1015 Project - Saving Mall X
## Mall X
Mall X is one of the oldest most established malls in Singapore who has constantly been ranked as Singapore's highest earning shopping mall. 
However, when the pandemic struck, sales plummeted and Mall X was overtaken by its rival, Mall Y. Seeking to reclaim its title of highest earning shopping mall, the marketing team was tasked to devise strategies to increase sales.

Taking on the role of data analysts in the marketing team, we decided to enhance existing advertisements to attract greater sales without incuring too much additional costs. To do this, we performed a customer segmentation analysis on the mall's existing customer data.


## Our roles
@Isaachzj - Data Preparation, Exploratory Data Analysis, Cluster Analysis

@yankailim - Analytic Visualisation, Cluster Analysis

@seah_js - Exploratory Data Analysis, Advertisement Design Strategisation.


## Project Folder
This folder contains the two Jupyter Notebooks for our project. Here is a description of our work in each of the notebooks.

### Part 1
We began by giving a short introduction of the problem. After cleaning and preparing the data, we did an Exploratory Data Analysis thorugh uni-variate and bi-variate analysis of the various variables. Thereafter, we clustered the data using K-Prototypes and serialised the results in 'dataFile' in "Data Folder". 

### Part 2 
For this notebook, we first analysed the profile of the customers in each of the clusters formed. Using the insights derived from the process, we gave suggestions on how existing Advertisements could be improved.


## Data Folder
This folder contains the csv file of our dataset, as well as the data file containing our clustering results.

**marketing_campaign.csv** - this is our dataset

**dataFile** - this file contains the serialized results of our clustering model.


## References
Aprilliant, A. (2022, March 31). The K-prototype as clustering algorithm for mixed data type (categorical and numerical). Medium. Retrieved April 22, 2022, from https://towardsdatascience.com/the-k-prototype-as-clustering-algorithm-for-mixed-data-type-categorical-and-numerical-fe7c50538ebb

Elbow method. Elbow Method - Yellowbrick v1.4 documentation. (n.d.). Retrieved April 22, 2022, from https://www.scikit-yb.org/en/latest/api/cluster/elbow.html#:~:text=If%20the%20line%20chart%20looks,fits%20best%20at%20that%20point.

How to use knee point detection in K means clustering. Practical Data Science. (2021, March 12). Retrieved April 22, 2022, from https://practicaldatascience.co.uk/machine-learning/how-to-use-knee-point-detection-in-k-means-clustering

Imputation techniques: What are the types of imputation techniques. Analytics Vidhya. (2021, June 30). Retrieved April 22, 2022, from https://www.analyticsvidhya.com/blog/2021/06/defining-analysing-and-implementing-imputation-techniques/

Zazueta, Z. (2020, October 1). Data transformation in ML - standardization vs normalization. Medium. Retrieved April 22, 2022, from https://zachary-a-zazueta.medium.com/data-transformation-in-ml-standardization-vs-normalization-70ba26de9060

Zazueta, Z. (2021, August 7). K-prototypes clustering - for when you're clustering continuous and categorical data. Medium. Retrieved April 23, 2022, from https://zachary-a-zazueta.medium.com/k-prototypes-clustering-for-when-youre-clustering-continuous-and-categorical-data-6ea42c2ab2b9

