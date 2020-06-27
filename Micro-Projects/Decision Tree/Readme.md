# About Dataset

This datasets is related to red variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).The datasets can be viewed as classification or regression tasks. But, in this case I have considered a classification task for demonstrating my skills as a beginner. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones). But I did not consider any measures for handling the unbalanced dataset and solved applied Decision Tree Classifier algorithm on this unbalanced dataset. 

Predictor/Input variables (based on physicochemical tests):
      1 - fixed acidity
      2 - volatile acidity
      3 - citric acid
      4 - residual sugar
      5 - chlorides
      6 - free sulfur dioxide
      7 - total sulfur dioxide
      8 - density
      9 - pH
      10 - sulphates
      11 - alcohol

Target/Output variable (based on sensory data):
      12 - quality (score between 0 and 10)
      
My Intention was to Predict the Quality of Wine as ("Bad", "Average" or "Excellent") based on the "Quality" parameter.

For More Information regarding the dataset, Go to [Wine-Quality-Dataset](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009)
      
# My Steps as a beginner to Solve this Problem
* Understand the Problem Statement
* Import all the necessary Libraries
* Perform Exploratory Analysis on Data (Plot Visualizations, Look all the Stats behind the data)
* Checked if there are any Null Values in the data. Fortunately, there are no missing values in this dataset.
* Checked if there are any outliers in the dataset. (Just identified the outliers using Boxplot. I did not used any houtlier handling mechanism to deal with outliers.)
* Added a new column to the data data called "Reviews". Here, I performed some feature engnineering tasks like ("Label Encoding"). The main purpose of this column is to classify the data into 3 classes (1-'Bad', 2-'Average', 3-'Excellent')(If Quality = 1-3, it is "Bad". If Quality = 4-7, it's Average, If Quality>7, it's Excellent)
* Splitted the Data into Train and Test Sets.
* Applied Decision Tree Classifier model on the training Data
* Predicted the reviews for Test Set.
* Evaluated the Model Performance by using the Performance Metrics (Confusion Matrix, Accuracy Score)


Please do let me know for any suggestions from your side. 



Thanks

Bhargav mahesh
