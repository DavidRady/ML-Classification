# README Machine Learning Classification
## Comparision of various Classification ML models

### by: David Rady

The purpose of this project is to train and compare different machine learning models on different data sets. 
An in depth analysis of the results can be found in the `Analysis.pdf`

Classification Algorithms used: 

-   Logistic regression
-   Support Vector 
-   Decision Tree 
-   Random Forest 
-   K-Nearest Neighbours
-   AdaBoost 
-   Gaussian Naive Bayes 
-   Neural Network 

## Dependencies (Third-party Libraries)
- numpy
- matplotlib
- pandas
- sklearn

### Run the following command to install all dependencies:

pip:
    
    python -m pip install numpy pandas matplotlib sklearn 

## File Structure
The code is organized by different tasks

- `ML-Classification`                                         -- root folder
    - `./data`                        -- contains datasets that are being classified
    - `./ClassificationPipeline.py`   -- contains script to run classification pipeline on all datasets
    - `./ClassificationPipelineNotebook.ipynb`   -- jupyter notebook as an option to run the classification pipeline
    - `./PipelineFunctionsClassification.py` -- contains helper functions for running the classifications
    - `./plots/` -- contains plots from the classification experiments
        - `./plots/adult/`                        -- contains output plots / figures from adult data set
        - `./plots/breast_cancer/`                -- contains output plots / figures from breast cancer data set
        - `./plots/default_credit/`               -- contains output plots / figures from default credit data set
        - `./plots/diabetic_retinopathy/`         -- contains output plots / figures from diabetic retinopathy data set
        - `./plots/seismic_bumps/`                -- contains output plots / figures from seismic bumps data set
        - `./plots/statlog_german/`               -- contains output plots / figures from statlog german credit data set
        - `./plots/thoracic_surgery/`             -- contains output plots / figures from thoracic surgery data set
        - `./plots/yeast/`                        -- contains output plots / figures from yeast data set
        - `./plots/zoo_animal/`                   -- contains output plots / figures from zoo animals data set
    

## How To Run
There are 2 options to run and test the program.

### Jupyter Notebook
- Open up jupyter notebook
- Navigate to the root project folder
- Run the notebook
    - `./ClassificationPipelineNotebook.ipynb` 
### Regular Python program
- run `python3 ClassificationPipeline.py`
## Datasets

### UCI
- the various datasets can be downloaded here:
    - https://archive.ics.uci.edu/ml/datasets/Diabetic+Retinopathy+Debrecen+Data+Set
    - https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients
    - https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
    - https://archive.ics.uci.edu/ml/datasets/Statlog+(German+Credit+Data)
    - https://archive.ics.uci.edu/ml/datasets/adult
    - https://archive.ics.uci.edu/ml/datasets/Yeast
    - https://archive.ics.uci.edu/ml/datasets/Thoracic+Surgery+Data
    - https://archive.ics.uci.edu/ml/datasets/seismic-bumps
    
### Kaggle
- https://www.kaggle.com/uciml/zoo-animal-classification?select=zoo.csv
