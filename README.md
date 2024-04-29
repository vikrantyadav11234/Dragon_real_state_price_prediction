"# Dragon_real_state_price_prediction" 

### Problem statement
* we are given dataset of house prices with some features like no of bathrooms
  ,no of bedrooms etc.
* Our task is to create a model which will predict the price of any new house by
  looking at the features.
* While learning about machine learning it is best to actually work with real world
  data, not just artificial dataset.
* There are hundreds of open datasets to choose from.

### Gatting started
* The first question i should ask to the client that what is the businees objective 
  and goal? How will dragon real estate benifit from the model?
* Client tell me that Dragon real estates will use this model to predict house
  prices in the given area and will invest in the area if its undervalued.
* Next question i should ask to the client is that how does the current solution look
  like? The answer is: Manual expert who analyze the features.
* The prediction made by so called "experts" are not very good( error rate is 25%)
  which is why dragon real estates pvt. ltd is counting on me

### Finding the type of model to built
* Supervised, unsupervised or reinforcement learning?- supervised
  bcoz we have target variable
* classification task or regression task?
  regression--bcoz target variable is quantitative
* batch learning or online learning techniques?
  batch learning- you already have data and you build a model on that data
  online learning- you have made a pipeline you are getting data continuously(on the fly)
  so its a batch learning. We already have data.

### Selecting a performence measure
* A typical performence measure for regression problem is root mean square error(RMSE)
* RMSE is generally the prefered performence measure for regression task,
  so we choose it for the perticular problem we are solving for Dragon real 
  estate Pvt. Ltd
* other performence measures include MAE,Manhattan norm, etc we will use RMSE 
  for this problem

### Checking the assumption
* it is very important to me to check for assumptions, I might have made and
  correct them before launching the ml system.
* For Example, I should make sure that team needs the price and not the 
  categories like expensive,cheap etc.
* If latter is the case, formulating the problem as a regression task will be
  counted as big mistake.
* i have talked to the dragon real estates team member and ensured that i am
  aware of all the assumptions.
