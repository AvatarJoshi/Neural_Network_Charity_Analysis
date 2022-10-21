# Neural_Network_Charity_Analysis

## Project Overview
The purpose of this project was to use DeepLearning to create a binary classifier capable of predicting whether applicants will effectively use funds given by the company Alphabet Soup. This dataset contains over 34,000 organizations that have been funded by Alphabet Soup over the years along with data regarding the application type, affiliated sector or industry, government organization classification, use case for funding, organization type, active status, income classification, special consideration for application, and funding amount requested. In addition, the dataset contains data regarding whether or not these organizations used the funds effecitvely.

In order to create a binary classifier capable of predicting which applicants will effectivelty use funds from Alphabet soup I performed the following tasks:

- Deliverable 1: Preprocessed Data for a Neural Network Model

- Deliverable 2: Compiled, Trained, and Evaluated the Model

- Deliverable 3: Optimized the Model

## Resources
[AlphabetSoupCharity.ipynb](AlphabetSoupCharity.ipynb) - A Jupyter Notebook that contains the initial preprocessing, training, and evaluation of the neural network model.

[AlphabetSoupCharity.h5](AlphabetSoupCharity.h5) - An HDF5 file that allows the original trained model to be imported for future used.

[AlphabetSoupCharity_Optimzation.ipynb](AlphabetSoupCharity_Optimzation.ipynb) - A Jupyter Notebook where the neural network model was optimized.

[AlphabetSoupCharity_Optimized.h5](AlphabetSoupCharity_Optimized.h5) - An HDF5 file that allows the original trained model to be imported for future used.

[charity_data.csv](Resources/charity_data.csv) - Contains the raw data used to generate the model.


## Results
### Data Preprocessing
- The target for the model was the following column:
    - "IS_SUCCESSFUL": Indicates whether or not a company used funding effectively.
- The features of the model were the following columns:
    - "NAME": Indicates which organization applied for funding
    - "APPLICATION_TYPE": Indicates the type of application
    - "CLASSIFICATION": Indicates the government organization classification
    - "USE_CASE": Indicates the use case for funding
    - "ORGANIZATION": Indicates the type of organization that applied
    - "STATUS": Indicates whether the application is active or not
    - "INCOME_AMT": Indicates the income classification 
    - "SPECIAL_CONSIDERATIONS": Indicates if there was a special consideration for the application
    - "ASK_AMT": Indicates the funding amount requested


## Summary
