Download Link: https://assignmentchef.com/product/solved-cse551-hw1-electricity-demand-prediction
<br>



The goal of this homework is to develop a method to predict the electricity load demand of 3 individual users. For each user, you are given following 2 datasets which cover 1 calendar year:

・ Energy usage history (in kW) with 30-minute or 1-minute interval

・ Weather history with 1-hour interval




Your objective is to create models that predict the future electricity consumption of these customers. Use the data from January 1st to November 30th as the training set and predict the energy usage in December precisely as much as possible. Note that you need to predict for two different intervals:

・ 1-hour interval: 12/1 0:00 am, 12/1 1:00 am, …, 12/31 11:00 pm.  ・1-day interval:   12/1 0:00 am, 12/2 0:00 am, …, 12/21 0:00 am.




The accuracy of your predictions needs to be measured by the Mean Absolute Error (MAE) [1]. Your model should return a smaller MAE than the Naïve method prediction [2], which simply uses the last observed value as the prediction for all steps into the future. You might need to take into account following factors: cycling patterns (e.g., daily, weekly or seasons) and sudden pattern change (e.g., holidays or vacation). Please submit a report to Blackboard. You can submit your source code too, but it won’t be graded. In your report, please discuss following points in detail: ・Methods: data preparation and parameter tuning.

・Results: prediction accuracy, visualization and report clarity.







<strong>References: </strong>

<ul>

 <li><u>https://en.wikipedia.org/wiki/Mean_absolute_error</u></li>

 <li><u>https://en.wikipedia.org/wiki/Forecasting#Naïve_approach</u></li>

</ul>