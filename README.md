Download Link: https://assignmentchef.com/product/solved-dsci552-homework-2
<br>
<h1>1.    Combined Cycle Power Plant Data Set</h1>

The dataset contains data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (EP) of the plant.

(a) Download the Combined Cycle Power Plant data<sup>1 </sup>from:

https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant (b) Exploring the data:

<ol>

 <li>How many rows are in this data set? How many columns? What do the rows and columns represent?</li>

 <li>Make pairwise scatterplots of all the varianbles in the data set including the predictors (independent variables) with the dependent variable. Describe your findings.</li>

</ol>

<ul>

 <li>What are the mean, the median, range, first and third quartiles, and interquartile ranges of each of the variables in the dataset? Summarize them in a table.</li>

 <li>For each predictor, fit a simple linear regression model to predict the response. Describe your results. In which of the models is there a statistically significant association between the predictor and the response? Create some plots to back up your assertions. Are there any outliers that you would like to remove from your data for each of these regression tasks?</li>

 <li>Fit a multiple regression model to predict the response using all of the predictors. Describe your results. For which predictors can we reject the null hypothesis <em>H</em><sub>0 </sub>: <em>β<sub>j </sub></em>= 0?</li>

 <li>How do your results from 1c compare to your results from 1d? Create a plot displaying the univariate regression coefficients from 1c on the x-axis, and the multiple regression coefficients from 1d on the y-axis. That is, each predictor is displayed as a single point in the plot. Its coefficient in a simple linear regression model is shown on the x-axis, and its coefficient estimate in the multiple linear regression model is shown on the y-axis.</li>

 <li>Is there evidence of nonlinear association between any of the predictors and the response? To answer this question, for each predictor <em>X</em>, fit a model of the form<sup>2</sup></li>

 <li>Is there evidence of association of interactions of predictors with the response? To answer this question, run a full linear regression model with all pairwise interaction terms and state whether any interaction terms are statistically significant.</li>

</ul>

<sup>1</sup>There are five sheets in the data. All of them are shuffled versions of the same dataset. Work with Sheet

<ol>

 <li>2</li>

</ol>

https://scikit-learn.org/stable/modules/preprocessing.htm#generating-polynomial-features

<ul>

 <li>Can you improve your model using possible interaction terms or nonlinear associations between the predictors and response? Train the regression model on a randomly selected 70% subset of the data with all predictors. Also, run a regression model involving all possible interaction terms and quadratic nonlinearities, and remove insignificant variables using p-values (be careful about interaction terms). Test both models on the remaining points and report your train and test MSEs.</li>

 <li>KNN Regression:</li>

</ul>

<ol>

 <li>Perform <em>k</em>-nearest neighbor regression for this dataset using both normalized and raw features. Find the value of <em>k </em>∈ {1<em>,</em>2<em>,…,</em>100} that gives you the best fit. Plot the train and test errors in terms of 1<em>/k</em>.</li>

</ol>

<ul>

 <li>Compare the results of KNN Regression with the linear regression model that has the smallest test error and provide your analysis.</li>

</ul>

<ol start="2">

 <li>ISLR: 2.4.1</li>

 <li>ISLR: 2.4.7</li>

</ol>