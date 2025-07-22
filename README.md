# SYRIATEL COMMUNICATION  PREDICTION OF CHURNERS AND NON-CHURNERS
## 1.0 Project Overview
This project is about analysis of the syriatel commucation company churning rate. The analysis involves Data cleaning,Exploratory Data Analysis(EDA),preparing dataset for machine learning in an effort to find predictable pattens for customers who will stay or stop doing business with the syrial Tel communication company.
## 2.0 Business Understanding
Telcom companies mostly face high risks of customer churn rate which are likely to lead to high revenue loss and high acquisition cost.Therefore its in the best interest for the syrial Tel communication company to retain its customers
## 3.0 Data sources
  The analysis utilizes syriaTel communication from Kaggle dataset
### 3.1 Stakeholders Needs
 -The main stakeholder is syrial Tel company and its needs are as below
 - Minimize risk of churning which may lead to companys revenue loss
 - Maintaining the non-churners since acquisition cost is expensive
### 3.2 Key Business Questions
  - Can we predict the number of the customers likely to churn?
  - Can we predict the number of the customers who are non-churners?
  - what business insights can be provided to syrial Tel communication?
  - What measures should be put in place to minimize the risk of churning/retention?
## 4.0 Data Understanding
### 4.1 : Data cleaning, EDA, Model training, Evaluation, Deployment.
- The variable that determines whether a customer stays with syrialTel communicatio is the churn and contain unique  values of True and False
- phone number as a feature does not influence the customer staying or not since its not unique and therefore dropped among the features
-The variables the dataset are then cleaaned by aligning the names and binary conversion of the target variable and features with yes and no
Lastly the state is encoded to convert it to numerical for machine learning and modelling

## 5.0 KEY VISUALIZATION
Below we have different viasualization that gives insights into the syriaTel communication data;
  1. confusion matrix summarizing the classification report
  2. Visualization showing the simple decision tree
  3. Visualization showing the hypertuned decision tree
  ## 6.0 CONCLUSION
  ### 6.1 Findings
  - 2,284 did not churn, 382 did churn
  - If customer service call > 3.5 there is high churn rate especially if day minutes are high
  - If a customer has an international plan it is associated with high churn rate
  - If day minutes are > 173.5 there is a high likelihood of churning
  - If customer voice mail messages > 6.5 there is a less like hood of churning
  - If customer day charge > 44.8 high spending customers are more likely to churn
  ### 6.2 Business Recommendations
  - Identify customers with frequent service calls or high usage for proactive retention.
  - Improve customer support for high-touch customers.
  - Target international plan users with loyalty offers.
  - Encourage voicemail plan usage to improve retention.
  - Offer waiver packages for frequent callers so as to retain them
  ## 7.0 Tools Used in Analysis
   > Python for  analysis
   > Pandas and Numpy for manipulation, calculations and analysis of the datasets
   > Matplotlib  for visualization
   > Logistic regression and Decision tree for modelling
   > Confusion matrix and accuracy for evaluating the models