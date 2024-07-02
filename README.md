#  **neural-network-challenge-2**
### By: Kyle Kerner

In this program we assume we are tasked with creating a neural network that HR can use to predict whether employees are likely to leave the company.  In addition, HR believes that some employees may be better suited to other departments, so we are also tasked with predicting the department that best fits each employee.  

Starting with the data we determine the number of unique values in each of the columns.  Next we determined that department and attrition would be the target variables.  Selecting 10 of the remaining columns we split the data and converted all of the columns to numeric data types.  After scaling the data we tranformed the training and testing data of both the department and attrition columns using OneHotEncoder.

Next, we determined the number of columns in the training data and created an input later, two shared laters, and branched the department and target columsn using one hidden layer and one output layer. With the layers and branches we created, compiled, summarized and trained the model using the preprocessed data.  Lastly we evaluted the model with the testing data and printed the accuracy for both department and attrition.

# Sources
Source code provided in class as well as the use of Chat GPT to help with code direction was used in the making of the program.  