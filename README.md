# Breast_Cancer_Detection
Breast Cancer Detection using Decision Tree and GridSearchCV


Data:
Data for this is downloaded from: https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(original) 

Data Description: 

Number of Instances: 699

Number of Attributes: 10 plus the class attribute

Attribute Information: (class attribute has been moved to last column)

   #  Attribute                     Domain
   -- -----------------------------------------
   1. Sample code number            id number
   2. Clump Thickness               1 - 10
   3. Uniformity of Cell Size       1 - 10
   4. Uniformity of Cell Shape      1 - 10
   5. Marginal Adhesion             1 - 10
   6. Single Epithelial Cell Size   1 - 10
   7. Bare Nuclei                   1 - 10
   8. Bland Chromatin               1 - 10
   9. Normal Nucleoli               1 - 10
  10. Mitoses                       1 - 10
  11. Class:                        (benign, malignant)

Missing attribute values: 16


Libraries: 
1. Pandas : It is used for performing operations related to dataframe.  A dataframe will be created once we load the data from csv file. 
			DataFrames allow you to store and manipulate tabular data in rows of observations and columns of variables.
2. NumPy:  NumPy is a python library used for working with arrays.
3. Matplotlib: It is used for plotting.
4. sklearn: sklearn is a machine learning library which contains various algorithms and it supports various Python numerical and scientific libraries.
5. Seaborn: Seaborn is a Python data visualization library based on matplotlib.
8. Kfold: Split dataset into k consecutive folds (without shuffling by default). Each fold is then used once as a validation while the k - 1 remaining folds form the training set.
9. Graphviz: Graphviz is open source graph visualization software. Graph visualization is a way of representing structural information as diagrams of abstract graphs and networks.

