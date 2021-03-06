# SC1015 Project - Saving Mall X

## Mall X
Mall X is one of the oldest most established malls in Singapore who has constantly been ranked as Singapore's highest earning shopping mall. 
However, when the pandemic struck, sales plummeted and Mall X was overtaken by its rival, Mall Y. Seeking to reclaim its title of highest earning shopping mall, the marketing team was tasked to devise strategies to increase its sales.

Taking on the role of data analysts in the marketing team, we decided to enhance existing advertisements to attract greater sales without incurring too much additional costs. To do this, we performed a customer segmentation analysis on the mall's existing customer data.


<br>

## Our roles
@Isaachzj - Data Preparation, Exploratory Data Analysis, Machine Learning (Clustering)

@yankailim - Analytic Visualisation, Machine Learning (Clustering)

@seah_js - Exploratory Data Analysis, Advertisement Design Strategisation.


<br>

## The "Marketing Campaign" Dataset
Uploaded by Rodolfo Saldanha, this Kaggle dataset contains the profile of the customers visiting a certain mall. It contains key information such as Age, Income, Education Status and Marital Status of the customers. Apart from this, it also contains data such as the amount spent by the customer on various products sold at the mall (Wine, Fruits, Meat, Fish, Gold) and number of purchases made on the various purchasing platforms (Physical Stores, Website, Catalogue).

This dataset can be accessed via this link: https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign


<br>

## Project Folder
This folder contains the two Jupyter Notebooks for our project. Here is a description of our work in each of the notebooks.

### "Part 1"
This notebook consists of the Problem Introduction, Data Preparation, Exploratory Data Analysis and Machine Learning steps in the Data Science Pipeline.

We began by giving a short introduction of the problem and a basic description of the project. Thereafter, we proceded to clean and prepare the data by droppping irrelevant columns, rows with null values and forming new columns to aid our analysis etcetra. Following this, we carried out an Exploratory Data Analysis thorugh uni-variate and bi-variate analysis of the various variables. Lastly, we clustered the data using K-Prototypes and serialised the results into 'dataFile' in "Data Folder". 

### "Part 2" 
In this notebook, we analysed the profile of the customers in each of the clusters formed. Using insights derived from the process, we gave suggestions on how existing Advertisements could be improved ethically.



### "group8_dsf3_slides"
Here are our presentation slides in pdf format.



<br>

## Data Folder
This folder contains the csv file of our dataset as well as the data file containing our clustering results.

**marketing_campaign.csv** - this is our dataset

**dataFile** - this file contains the serialized results of our clustering model.


<br>

## References
Aprilliant, A. (2022, March 31). The K-prototype as clustering algorithm for mixed data type (categorical and numerical). Medium. Retrieved April 22, 2022, from https://towardsdatascience.com/the-k-prototype-as-clustering-algorithm-for-mixed-data-type-categorical-and-numerical-fe7c50538ebb 

Elbow method???. Elbow Method - Yellowbrick v1.4 documentation. (n.d.). Retrieved April 22, 2022, from https://www.scikit-yb.org/en/latest/api/cluster/elbow.html#:~:text=If%20the%20line%20chart%20looks,fits%20best%20at%20that%20point. 

How to use knee point detection in K means clustering. Practical Data Science. (2021, March 12). Retrieved April 22, 2022, from https://practicaldatascience.co.uk/machine-learning/how-to-use-knee-point-detection-in-k-means-clustering 

Imputation techniques: What are the types of imputation techniques. Analytics Vidhya. (2021, June 30). Retrieved April 22, 2022, from https://www.analyticsvidhya.com/blog/2021/06/defining-analysing-and-implementing-imputation-techniques/ 

Saldanha, R. (2020, May 8). Marketing campaign. Kaggle. Retrieved April 24, 2022, from https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign 

Zazueta, Z. (2020, October 1). Data transformation in ML???-???standardization vs normalization. Medium. Retrieved April 22, 2022, from https://zachary-a-zazueta.medium.com/data-transformation-in-ml-standardization-vs-normalization-70ba26de9060 

Zazueta, Z. (2021, August 7). K-prototypes clustering???-???for when you're clustering continuous and categorical data. Medium. Retrieved April 23, 2022, from https://zachary-a-zazueta.medium.com/k-prototypes-clustering-for-when-youre-clustering-continuous-and-categorical-data-6ea42c2ab2b9 

