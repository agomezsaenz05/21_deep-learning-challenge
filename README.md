# 21_deep-learning-challenge

## Report on the Neural Network Model

### Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis is to use what we learned in class about Pandas and scikit-learn’s StandardScaler() to preprocess the dataset and compile, train, and evaluate the neural network model.

### Results: Using bulleted lists and images to support your answers, address the following questions:
Data Preprocessing

- What variable(s) are the target(s) for your model? X & Y were the targets for the model (based on if it was successfull or not successful)
- What variable(s) are the features for your model? The variables used were Application_type and Classification
- What variable(s) should be removed from the input data because they are neither targets nor features? We dropped EID and NAME

Compiling, Training, and Evaluating the Model

- Were you able to achieve the target model performance? Yes, on the second optimization I was able to achieve 79.9% accuracy.
- What steps did you take in your attempts to increase model performance? I dropped fewer columns, only the EID. I created more bins for rare occurrences in columns, using Name and Classification. I also modified the number of values for each bin.

#### Optimization 1
![image](https://github.com/agomezsaenz05/21_deep-learning-challenge/assets/120424668/578ad385-18cb-4df3-a774-6149aab4cbd8)
![image](https://github.com/agomezsaenz05/21_deep-learning-challenge/assets/120424668/a93b0fba-ea57-4abf-9466-88d845265feb)

#### Optimization 2
![image](https://github.com/agomezsaenz05/21_deep-learning-challenge/assets/120424668/16301b38-602a-44a9-85ca-ac7fd439e777)
![image](https://github.com/agomezsaenz05/21_deep-learning-challenge/assets/120424668/3e9c0115-9859-4264-b9d1-146fa5420d0a)

### Summary
The first model was still pretty accurate at 74.5%, however I would recommend the company to use the second model to start and they could further optimize it by modifying hidden-layers or adding more. 
