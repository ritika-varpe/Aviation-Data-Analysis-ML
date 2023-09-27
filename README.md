# Aviation-Data-Analysis-ML
Aviation_analysis dataset is used and different techniques of Mahine learning are applied on it.
Firstly I have processed the data in that following steps are performed:
  1. Finding out the missing data
  2. Different statistical methods are applied mean, median, mode and standard deviation
  3. The dataset is described and info is displayed

The next is I have encoded the data that is the categorical data is converted into numerical form by using the sklearn preprocessing technique called LabelEncoder and then creating dummy variables.
Then train test is applied on the dataset with the random state 42.

The classification is used named as Bayes Classification.
In that I have applied naive bayes and imported GaussianNB.
Then predicted the dataset.

Clustering is performed in that I have applied k-means clustering using sklearn.cluster
It is shown using the graph.

![Cluster](https://github.com/ritika-varpe/Aviation-Data-Analysis-ML/assets/95220140/54390b1e-4b55-4117-93d0-03f4196bdfc3)


The last part is the decision tree. The feature columns taken are :
    (feature_cols=['totalReceived','activeGrievancesWithoutEscalation','grievancesAdditionalInfoNotProvided','grievancesWithoutFeedback'])
    
![DT](https://github.com/ritika-varpe/Aviation-Data-Analysis-ML/assets/95220140/879f15a3-0a35-4b48-8c7d-b0dd0218726f)
