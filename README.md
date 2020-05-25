# Office_Store_Capstone_Columbia_Emeritus
#### This Capstone Project was a part of the Post Graduate Diploma for Applied Machine Learning 

##### The original dataset consists 16173 customers information who have been a target of a marketing campaign of an office supplies company.


### Steps:

#### 1. Data Cleaning and converting the categorical variables to dummy variables for model predictions

#### 2. Data Exploration

#### 3. Creating two models :
   ##### - Model I : Grid Search CV with XG Boost Classifier was created to predict whether a customer makes a purchase during campaign or not.
   ##### - Model II:   XGBoost Regressor was used to identify the most important features that affect the sales volume ($ Transaction Size) and to predict sales volume and estimate profit

#### 4. Analysis and Creation of Presentation for client


### Background:

##### An office supply store tests a telemarketing campaign to its existing business customers. The company targeted approximately 16,000 customers for the campaign. Assume you are a consultant brought on board to help the company leverage and use the findings from the tests to its advantage. Refer to the accompanying spreadsheet, which contains the results of the tests. 

### Project objectives:

#####  - Profile the customers that responded to the campaign to make the company aware of who its typical customer is.
##### - Develop models that will allow the company to use the results of the campaign to target future, similar campaigns.
##### - Show the financial value of your models.

### Expected deliverables:
##### A deck that details your findings and the models (must include a clear gains chart showing the financial contribution of your results) and the percent of the base that can be profitably targeted for the next campaign.

### Relevant financials:

#### - Gross margin on sales: 22%
#### - Campaign cost: $45.65 per business contacted
#### - Transaction cost: $8.40 per transaction

### DataSheets
2 datasheets were provide but those have not been shared here due to copyrights

### Methodology:

#### - Create model and validation sets
#### - Develop a model to estimate the probability of responding to this campaign
#### - Develop a model to estimate the size ($) of the transaction
#### - Calculate the expected profit resulting from each target; use the formula below:

#### E(Profit)=.22*Prob(Sale)*Est(Transaction Size)-$8.40*Prob(Sale)-$45.65

#### - Illustrate the contribution to profitability associated with your models versus random targeting
#### - Create a presentation for your client


### Description of jupyter notebooks and files provided
#### 1. Data Cleaning
In this notebook the initial data has been cleaned and dummy encoded for carrying out analysis.

#### 2. EDA
In this notebook, the initial data exploration is done.

#### 3. Final Analysis
After EDA, this is the main notebook in which models are created and data is analysed. 

#### 4. Analysis Slideshow
This file has all the analysis charts. It can be viewed using nbviewer by putting the github link of html file (Analysis_slideshow slides.html) on nbviewer here: https://nbviewer.jupyter.org/

#### 5. Office Corp Presentation
The final presentation deck created for the client. All the results of analysis are summarized here.

### Concluding Remarks:

##### It is recommended that this model be used for future Marketing Campaigns. Introducing this model could increase ROI to 450 %, from original ROI of -31% (baseline) by targeting selected customers instead of all.
##### A high lift in our model means that during the Marketing Campaign,  targeting those customers suggested by our Predictive Model would likely get 3.5 times buying response as compared to targeting customers at random.
##### The cumulative Gains chart here shows that by the time we covered 27% of the population, we identified 75% of the buyers.


### Future Recommendations:
Other regression models could be tried to find if any other model gives a better performance.





