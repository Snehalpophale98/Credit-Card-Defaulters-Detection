# Credit-Card-Defaulters-Detection

# IMPORTANT :
In this repository I haven't added the data set file becuase it is of 158 MB. But I have added the file which contains names of columns and their description which
are in the data set. The data set conatains 30K rows and 122 columns.
Also I have made two files one contains EDA and one contain model building becuase my local host went out of memory to run the whole project in one go. 

# About the Project:
This project aims to predict credit card defaults using machine learning algorithms. The dataset used in this project is sourced from Kaggle 
The objective of this project is to predict whether a credit card holder will default or not based on the features provided in the dataset.The project uses 
different machine learning algorithms such as logistic regression, decision tree, random forest, and XGBoost to predict credit card defaults.
The project also includes data exploration and data visualization techniques to better understand the relationship between different features and credit card defaults.

# Requirements
The following libraries are required to run the project:

Pandas ,  NumPy ,Scikit-learn , Matplotlib , Seaborn, XGBoost , Random Forest Classifier, Decision Tree Classifier , Logistic Regreesion, CATBoost

# Exploratory Data Analysis (EDA) :
The data exploration section of the Notebook includes basic statistical analysis, such as mean, standard deviation, minimum, and maximum, for each column in the dataset. 
It also includes data visualization techniques such as histograms, count plots, and heatmaps to better understand the relationship between different features and 
credit card defaults.
Detecting and Handling the ouliers , Correlation beetwin the features , drawing inferences from the plots.

I have written the insights in the Jupyter Notebook itself.

### Data Preprocessing : 
The data preprocessing section of the Notebook includes techniques such as handling missing values, scaling, and encoding categorical variables. 
The data is split into training and testing sets using a 80-20 split.

### Model Selection : 
The model selection section of the Notebook includes different machine learning algorithms such as logistic regression, decision tree, random forest, and XGBoost. 
The models are trained on the training set and evaluated on the testing set using different evaluation metrics such as accuracy, precision, recall, and F1-score.

### Model Evaluation :
This step involves evaluating the performance of the model using various metrics such as accuracy, precision, recall, and F1 score.
It also involves analyzing the confusion matrix and ROC curve. So my XGBoost Model gave me 92% accuracy.







