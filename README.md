# Jerome Goh

I am a first-year MS Statistics student at Arizona State University, graduating in May 2025, with strong interests in Data Science, Machine Learning, and Applied Mathematics. On this page is a collection of completed and ongoing projects throughout my academic life.

## Projects in statistics and data science

### Project 1: Missing data analysis and multiple imputation in R
This project aims to understand better how the characteristics of vehicles factor into greenhouse gas emissions based on the Environmental Protection Agency's (EPA) 2023 [data](https://www.epa.gov/compliance-and-fuel-economy-data/data-cars-used-testing-fuel-economy) on testing fuel economy. This dataset poses a unique challenge since deleting empty cells will result in the deletion of most of the data, thus calling the need for imputation to perform any analysis.

The objectives are to identify and understand missing data mechanisms, patterns of missingness, and estimate values of missing observations based on prior information from the remaining dataset. After which, we pool the imputations, calculate correlations, and deploy algorithmic variable selection models to best identify predictors for CO2 levels. 

The full repository can be viewed [here](https://github.com/jerome-goh/Multiple_Imputation)

### Project 2: Image classification with HyperModels in Python

This project explores the effect of various neural network architectures on prediction accuracy for image classification tasks with the TensorFlow API. The dataset consists of high-resolution scans of a highly varied assortment of [Poker cards](https://www.kaggle.com/datasets/gpiosenka/cards-image-datasetclassification/data). The initial exploratory analysis examines the effectiveness of pre-trained models to predict these images. However, it is likely that such cards are not factored into the pre-trained weights, due to playing cards not being a part of their training data. 

Instead of arbitrarily fitting as many pre-trained models (with transfer learning) as possible until satisfactory predictions are attained, I propose the use of hyperparameter search algorithms and hypermodels to build an effective model.

The full repository can be viewed [here](https://github.com/jerome-goh/DL_CNN), while a full written report can be found [here](https://github.com/jerome-goh/DL_CNN_PY/blob/main/STP598_FinalProject.pdf)
