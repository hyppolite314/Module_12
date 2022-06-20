# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

For this analysis, we were provided with historical lending data from a peer-to-peer lending group. The historical lending data included information about the borrowers such as their income, loan size, and the number of accounts they had open. Based on this data, we used a logistic regression model to 'learn' the trends or behavior of the data in order to make predictions of future high-risk loans.

Two logistic regression models were used. The first model was formed around the data as provided; the data set was imbalanced. During this exercise, the imbalance inherent in the data set was accounted for in the second regression model by implementing an over-sampling.

The key take away was that the second model was better at predicting high-risk loans based on an increased recall metric. The increased recall metric, did come at a relatively small expense of the precision metric for the high-risk loan category.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1
  <br>
  Accuracy(Balanced): 0.952
  <br>
  Precision: For "0" = 1.00 ; For "1" = 0.85
  <br>
  Recall scores: For "0" = 0.99 ; For "1" = 0.91


![Screenshot of Plot](https://github.com/hyppolite314/Module_12/blob/main/screen_model_1.png)


* Machine Learning Model 2:
  * Description of Model 2
  <br>
  Accuracy(Balanced): 0.994
  <br>
  Precision: For "0" = 1.00 ; For "1" = 0.84
  <br>
  Recall scores: For "0" = 0.99 ; For "1" = 0.99
  
![Screenshot of Plot](https://github.com/hyppolite314/Module_12/blob/main/screen_model_2.png)

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

The key take away was that the second model was better at predicting high-risk loans based on an increased recall metric. The increased recall metric, did come at a relatively small expense of the precision metric for the high-risk loan category.

If the goal and imperative is to better predict high-risk loans or loans which will likely default, then model 2 is the recommended regression model.

## Contributors

Reginald Hyppolite
https://www.linkedin.com/in/reginald-hyppolite-nyc/

BIG THANKS to all the great TAs and Professor Vinicio DeSola

---

## License

N/A -- Free open.ware for a better world.