# Health Insurance Cross Sell

Identifying health insurance customers who would be interested in vehicle insurance.

![Health](https://cdn.pixabay.com/photo/2017/02/20/14/18/health-2082630_960_720.jpg?raw=true)

## Description

In this project, a series of methods are used to identify cross sell opportunities within a data set of a company’s existing health insurance customers. Whether or not the customer is interested in vehicle insurance is known. The goal of the analysis is to be able to identify whether or not a customer would be interested in vehicle insurance for a new data set in which this information was not known. The methods described include customer segmentation based on grouping known information about the customer through exploratory data analysis, predictive modeling, and customer segmentation based on probabilities given by the predictive models. For predictive modeling, a wide range of algorithms are used including, but not limited to, Light Gradient Boosting Machine and densely connected neural networks. In identifying customers who are interested in vehicle insurance, the project aims to reduce the number of customers the company would have to solicit the additional product to and provide information needed to create a more targeted communication strategy.

## Data

[Kaggle Dataset](https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction)

## Contents

Data  
* Interest by Category Data - tables analyzing vehicle interest by grouping values for each variable
* Kaggle Data - raw Kaggle datasets

Exploratory Data Analysis  
* Excel Plots.xlsx - visualizations made in Excel for presentation deck
* Exploratory Data Analysis.ipynb - exploratory data analysis notebook
* HealthInsuranceCrossSell_ProfileReport.html - PyCaret profiling report for comprehensive exploratory analysis
* Power BI Charts - bullet charts to visualize interest rates by category

Predictive Modeling  
* Predictive Modeling with PyCaret.ipynb - initial predictive modeling using several ML models
* Initial Modeling with Keras.ipynb - initial neural networks trained
* Final Modeling with Keras.ipynb - final neural networks trained
* Probability Plots.xlsx - customer segmentation using model prediction probabilities
* Weighted_NN_model.h5 - final neural network model

Papers  
* Proposal - Health Insurance Cross Sell.pdf
* Project Draft - Health Insurance Cross Sell.pdf
* Report - Health Insurance Cross Sell.pdf

Presentation Deck - Health Insurance Cross Sell.pptx - deck used to aid [presentation](https://drive.google.com/file/d/1D_pe_VaUB9i7SbPsLxOOPh9DT-LaXdR6/view?usp=sharing)

## Tools
* Python
* PyCaret
* Keras
* TensorFlow
* SMOTE
* SKLearn
* PowerBI
* MatPlotLib


## Author

Samuel Sears @ssears219

## Acknowledgments

* [Health Insurance Cross Sell Kaggle Competition](https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction/)
* [Cross Sell Article by Goose Digital](https://goosedigital.com/media-types/articles/executing-a-successful-cross-sell-strategy/)
* [Cross Sell Case Study by Xpanse AI](https://xpanse.ai/case-studies/predictive-analytics-in-marketing-case-study-2-cross-sell-for-insurance/)
* [PyCaret](https://pycaret.org/compare=models/)
* Deep Learning with Python by Francois Chollet
* [TensorFlow Unbalanced Data Tutorial](https://www.tensorflow.org/tutorials/structured_data/imbalanced_data)
* [SMOTE Example](https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/)
* [Article on Confusion Matrix Visualization](https://medium.com/@dtuk81/confusion-matrix-visualization-fc31e3f30fea)
