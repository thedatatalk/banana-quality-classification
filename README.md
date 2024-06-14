# Banana Quality Prediction
Doing the Exploratory Data analysis for Banana Quality and Predicting the Bad and Good quality bananas

# Requirements
Python 3.8+ Jupyter Notebook - Kaggle Notebook is preferrable.

# Dataset
Movie Dataset : https://www.kaggle.com/datasets/l3llff/banana

# How to Run The Notebook.
1. Login to Kaggle.com
2. Visit https://www.kaggle.com/datasets/l3llff/banana
3. Click on "New Notebook" Option Available on the top of the screen.
4. Download the ".ipynb" File attached in the current repository, select the right version
5. Upload On the New Notebook place by clicking on Import Notebook option.
6. Run The Notebook program

# Run the program in virtual envrionment python
1. Create virtual environment
2. Activate virtual environment
3. Install requirements.txt 
4. Run jupyter notebook and Open the .ipynb notebook file on the localhost:8888

# Key Data Insights
1. We analyzed the correlation among features and found that the quality of bananas appears to depend most on the harvest time.
2. The data was normalized and underwent the necessary preprocessing steps to prepare for predicting the quality of bananas.
3. Several models were fitted to the dataset, and their ROC accuracy scores were evaluated:
    * The Random Forest classifier performed well on the training set but overfitted the test set.
    * Consequently, the HistGradientBoostingClassifier was chosen for its balanced performance on both the training and testing sets.
4. Upon further evaluation, it was observed that the model tended to predict bad quality bananas as good. To minimize this issue, the MLPClassifier was selected, which reduced the false positive rate for bad bananas predicted as good.
5. Additional preprocessing steps included handling missing values and encoding categorical variables to ensure the models received a clean and well-structured dataset.
6. Cross-validation was used throughout the model evaluation process to ensure robustness and to avoid overfitting, leading to a more reliable assessment of model performance.
