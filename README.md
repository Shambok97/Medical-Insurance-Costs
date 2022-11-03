# Medical-Insurance-Costs
 
 ## Introduction 
The dataset for this project was obtained from kaggle (http://kaggle.com/datasets/mirichoi0218/insurance?resource=download) and the aim was to build a model that could predict using what the insurance costs would be for non-smokers vs smokers. The dataset was comprised of 1338 observations and 7 variables, which were as follows:

* Age: Age of primary beneficiary
* Sex: Insurance contractor gender, female, male
* BMI: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
* Children: Number of children covered by health insurance / Number of dependents
* Smoker: Smoker or Non-smoker
* Region: The beneficiary's residential area in the US, northeast, southeast, southwest, northwest
* Charges: Individual medical costs billed by health insurance

## Data Cleaning and Preprocessing

The dataset was first imported into Python and using Pandas, the datafram was created. No missing value was present in the dataset which was a good sign. However, the categorical variable "Region" were not in the correct format which is why it was converted into dummy variables using the get_dummies() function. Additionally, "gender" and "smoker" were encoded into labels 1 and 0. Numpy was used to reshape the data into 2D arrays for plotting. The dataset was then split into the training and test set using the train_test_split() function. 

## Exploratory Data Analysis

The dataset was first explored using the describe() function to get a better understanding of the data. The dataset was then visualized using the seaborn library.

Furthermore, using linear regression from scikit-learn, the relationship between the variables was explored. A R^2 value of 0.75 was obtained suggesting that the model was a good fit.





