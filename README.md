# ELE489_MachineLearning_HW2
This project implements a Decision Tree classifier to detect counterfeit banknotes for the Banknote Authentication 
Dataset from the UCI Machine Learning Repository.

Some of my key findings from this project are like following:
Achieved 98.2% accuracy with optimal depth=4
Most important feature: Variance (57% importance)
Shallow trees (depth 3-4) provide best balance of accuracy and interpretability.

This repository includes a Jupyter Notebook (decision_tree.ipynb) file and this Readme.md file. 
In Jupyter Notebook file you can find my codes related with this project. 
As outcome of this code you can see data analysis, Decision Tree implementation
with differet parameters (different values for max_depth, min_samples_split, and criterion ("gini" vs "entropy").) 
Accuracy vs. depth analysis, Feature importance evaluation and more.


Dependencies:
Python 3.8+
pandas, numpy, matplotlib, seaborn
scikit-learn

NOTE:To access the data set in the code, you need to download the data 
file from the link below and copy it to the required file path. 
I also added a section containing the data link as a comment to the code so that you can run the code without the file.
You can also run the code using this section.

LINK:https://archive.ics.uci.edu/dataset/267/banknote+authentication
