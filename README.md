# Neural Network Charity Analysis

## Overview

* Using machine learning (Deep Neural Networks) to assess if funding from Alphabet Soup would help applicants succeed

## Results

### Data Preprocessing

* The variable "IS_SUCCESSFUL" was the target for this model
* The features "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT" were considered for this model
* The categorical columns "EIN" and "NAME" were removed from the dataset because they were not target or features

### Compiling, Training, and Evaluating the Model

* There are two neural hidden layers. The first layer has 80 neurons and the second layer has 30 neurons. The activation of the first layer is "relu" and the activation of the second layer is "sigmoid"
* An accuracy of 75% was not reached and the model accuracy stayed at approximately 73% after extensive testing.
* Testing included:
    - Additional epochs
    - Additional hidden layers (3 total)
    - Random Forest Classifier was utilized 

## Summary 

* The accuracy of 75% was not met, instead 73% was achieved. It is likely that the implementation of different activation methods might increase this accuracy percentage. The use of the Random Forest Classifier is recommended because of it's ability to handle binary data with high accuracy.


## Questions

* You can contact me via email or GitHub!

    * Email: emilyporter920@gmail.com
    * GitHub Profile: Emily Porter || github.com/emilyporter920
