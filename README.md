# Mercedes-Benz-Greener-Manufacturing

## Project Overview

The goal of this project is to minimize the time a Mercedes-Benz spends on the test bench during the testing phase. By leveraging advanced algorithmic approaches, the aim is to enhance the efficiency of the testing system while dealing with the complexity of various feature combinations found in Mercedes-Benz vehicles.

### Problem Statement

Mercedes-Benz is synonymous with innovation and excellence in the premium car industry. Ensuring the safety and reliability of each unique vehicle configuration is critical before these cars are released onto the market. The challenge lies in optimizing the testing process to handle a myriad of feature permutations without compromising the brand's high standards of safety and efficiency.

### Objective

The primary objective is to reduce the testing time for cars on the bench, thereby decreasing carbon dioxide emissions without undermining the quality standards of Mercedes-Benz.

### Methodology

1. **Data Preprocessing**:
   - Removal of any features with zero variance as they do not contribute to the predictive model.
   - Identification and handling of null values in the test and train datasets.
   - Application of label encoding to transform non-numerical labels into numerical labels.

2. **Dimensionality Reduction**:
   - Implementation of dimensionality reduction techniques to improve model performance and reduce computational cost.

3. **Model Training and Prediction**:
   - Utilization of the XGBoost algorithm to train the model and predict the test bench time for various car configurations.

## Instructions for Use

- Follow the Jupyter notebook for step-by-step instructions on preprocessing, training, and prediction.

