# ML_codebasics
Simple tasks on Machine Learning algorithms
## Content
### 1. linear regression
Using *canada_per_capita_income.csv* file build a regression model and predict the per capita income for canadian citizens in year 2020

### 2. multivariate linear regression
File *hiring.csv* contains hiring statics for a firm such as experience of candidate, his written test score and personal interview score. Based on these 3 factors, HR will decide the salary. Given this data, you need to build a machine learning model for HR department that can help them decide salaries for future candidates. Using this predict salaries for following candidates:
* 2 yr experience, 9 test score, 6 interview score
* 12 yr experience, 10 test score, 10 interview score

### 3. gradient descent
Being given *test_scores.csv* file with Mathematical and Computer Science student's test scores you are to find out the correlation between scores of these subjects.
* For test scores in .csv file, run gradient descent algorithm to find out value of m, b and appropriate learning rate
* On each iteration, compare previous cost with current cost. Stop when costs are similar (use *math.isclose* function with *1e-20* threshold)
* Now using sklearn.linear_model find coefficient (i.e. m) and intercept (i.e. b). Compare them with m, b generated by your gradient descent algorithm

### 4. one hot encoding
The *carprices.csv* file has car sell prices for 3 different models. First plot data points on a scatter plot chart to see if linear regression model can be applied. If yes, then build a model that can answer following questions:
* Predict price of a mercedez benz that is 4 yr old with mileage 45000
* Predict price of a BMW X5 that is 7 yr old with mileage 86000
* Tell the score (accuracy) of your model (hint: use LinearRegression().score())
