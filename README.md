# Neural_Network_Charity_Analysis
---
### Purpose
##### The purpose of this project was to explore neural networks. For the project, we help a funding company called Alphabet Soup create a binary classifier that is capable of predicting whether applicants will be successful if funded by the company.
##### We received a CSV file containing more than 34,000 organizations that have received funding from Alphabet Soup over the years as our data to train, fit, and test.
---
### Results
#### **Data-Preprocessing:
##### The CSV contained many elements that were preprocessed and sorted by significance for the scope of the project.
##### 1. The target for the model was:
            - IS_SUCCESSFUL : which indicates whether the particular organization was used successfully/effectively. 
            1 being successful, 0 being unsuccessful.
##### 2. The features for the model were (these features were encoded and scaled for the model to run successfully):
            - Status
            - Ask_Amt
            - Application_Tyoe
            - Income_Amount
            - Special_Considerations
            - Organization_Type
            - Use_Case
##### 3. The variables that were neither targets nor features and removed from the data were:
            - EIN
            - Name
#### **Compiling, Training, and Evaluating the model:
##### The original model had 80 neurons in the first hidden layer and 30 in the second hidden layer. The activation functions were relu for the hidden layers and sigmoid for the outer layer. The model ran 50 epochs and produced around a 73% accuracy.
![](https://github.com/yfaulkne/Neural_Network_Charity_Analysis/blob/main/Resources/images/compile_train_evaluate.png)
![](https://github.com/yfaulkne/Neural_Network_Charity_Analysis/blob/main/Resources/images/accuracy.png)
##### The model was run three times after the initial run to try and improve optimaztion to above 75%. 
##### 1. Optimization 1 was run with less neurons in each layer and increased the epochs to 100. The accuracy yielded  %
![](https://github.com/yfaulkne/Neural_Network_Charity_Analysis/blob/main/Resources/images/optimazation1.png)
![](https://github.com/yfaulkne/Neural_Network_Charity_Analysis/blob/main/Resources/images/optimization1_accuracy.png)
##### 2. Optimaztion 2 was run with even less neurons in each hidden layer and the epochs remained at 100. The accuracy yielded almost 73%
![](https://github.com/yfaulkne/Neural_Network_Charity_Analysis/blob/main/Resources/images/optimization2.png)
![](https://github.com/yfaulkne/Neural_Network_Charity_Analysis/blob/main/Resources/images/optimization2_accuracy.png)
##### 3. Optimaztion 3 was run with even less neurons in each hidden layer and the epochs remained at 100. The accuracy yielded almost 73%
![](https://github.com/yfaulkne/Neural_Network_Charity_Analysis/blob/main/Resources/images/optimization3.png)
![](https://github.com/yfaulkne/Neural_Network_Charity_Analysis/blob/main/Resources/images/optimization3_accuracy.png)
            
