# Wine Quality Project
Use multiple machine learning algorithms to predict the wine quality.

Team Members: Tian (Luke) Qi, Ran Huang, Randy Ma, Anna Zeng.

## Goal
This project is the final project of MSDS621 Introduction to Machine Learning. In this project we used Decision Tree, Random Forest, Support Vector Classifier, KNN to predict wine quality. In the presentation slides, we showed our models' performance on the test data.

The learning outcome of this project is to understand the concept of some machine learning algorithms and implementation of them.

## Description of Data
The dataset we will be analyzing in this study is from the [UCI Machine Learning Repository Wine Data](https://archive.ics.uci.edu/ml/datasets/wine+quality)

The data includes information about red and white vinho verde wine samples, from the north of Portugal, with their 11 features: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol.

## Result
After resampling, the random forest model has 73% accuracy on the test data, and it performs pretty well on the good and low quality group wine, however, it sacrifices too much accuracy on the medium group. The SVM, which has 78% accuracy on the test data, is like a balanced model, it doesn't performs as well as Random Forest on the low and good group, but it improves their accuracy compare to svm without resampling, and it does not lose too much accuracy on the medium wine. Based on the business idea, the company could use either model to classify their wine quality.

## Deliverables
The [**presentation_slides**](https://github.com/tqi2/Wine_Quality_Project/blob/master/presentation_slides.pdf) shows the complete workflow of the project.

The [**project.ipynb**](https://github.com/tqi2/Wine_Quality_Project/blob/master/project.ipynb) shows the corresponding code of our project
