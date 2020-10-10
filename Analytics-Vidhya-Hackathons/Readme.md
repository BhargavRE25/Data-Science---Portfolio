# Janatha Hack : Machine Learning in Agriculture


### Problem Statement
Though, many of us don't appreciate much, but a farmer's job is real test of endurance and determination. Once the seeds are sown, he works days and nights to make sure that he cultivates a good harvest at the end of season. A good harvest is ensured by several factors such as availability of water, soil fertility, protecting crops from rodents, timely use of pesticides & other useful chemicals and nature. While a lot of these factors are difficult to control for, the amount and frequency of pesticides is something the farmer can control.

Pesticides are also special, because while they protect the crop with the right dosage. But, if you add more than required, they may spoil the entire harvest. A high level of pesticide can deem the crop dead / unsuitable for consumption among many outcomes. This data is based on crops harvested by various farmers at the end of harvest season. To simplify the problem, you can assume that all other factors like variations in farming techniques have been controlled for.

You need to daetermine the outcome of the harvest season, i.e. whether the crop would be healthy (alive), damaged by pesticides or damaged by other reasons.

### Data
**Training Data** : It is the data on which ou model needs to be trained. [Training Dataset](https://github.com/BhargavRE25/DataScience-Portfolio/blob/master/Analytics-Vidhya-Hackathons/Data/train.csv)

**Test Dataset** : It is the unknown data which the model has to show good performance. [Testing Dataset](https://github.com/BhargavRE25/DataScience-Portfolio/blob/master/Analytics-Vidhya-Hackathons/Data/test.csv)

### Approach to Solve this Problem

By exploring the Farm data values, the machine learning algorithm can learn the relationship between the agriculture related parameters and changes in crop to the historical crop damage data in order to predict crop damamges in the future. Since our Target variable has 3 classes, ou problem is to solve what category of crop damage will the farm predict in future. This is clearly a problem of Multi Classification problem where you have to predict the class.

### Steps involved in Solving this Problem
* Data Importing
* Exploratory Data Analysis
* Handling Null Values
* Handling Outliers
* Splitting the Dataset into Train, Validation and Test Sets
* Training Multiple Models
* Predicting the Target Valriable
* Optimize the ML model by tuning the Hyperparameters.
* Submit the Output





