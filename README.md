# Machine-Learning

This is the process by which I learnt the basics of machine learning!

1.Import libraries
2.Import dataset

3.Exploratory data analysis - provides an opportunity to become familiar with your data including distribution 
and the state of missing values. Exploratory data analysis also drives the next stage of data scrubbing and your choice of algorithm.

4.Data scrubbing - most time consuming - cleaning up the data, inspecting its value, 
making repairs, and, ultimately, knowing when to throw it out.

5.Pre-model algorithm (Optional) - optional extension of the data scrubbing process, 
unsupervised learning techniques, including k-means clustering analysis and descending dimension algorithms, 
are sometimes used in preparation for analyzing large and complex datasets.

6.Split validation - partition the data to train and test analysis. 
It’s also useful to randomize your data at this point using the shuffle feature and 
to set a random state if you want to replicate the model’s output in the future.

7.Set algorithm - As input data is variable, algorithms can produce different outputs based on the input data. 
Algorithms are also malleable in that they have hyperparameters that can be adjusted to create a more customized model.

8.Predict - predict function on test data to validate model 
generates a numeric value such as price or a numeric correlation indicator in regression problems. 
In classification, the predict function generates discrete classes, 
such as the movie category or spam/non-spam classification.

9.EVALUATE: 
In classification, the common evaluation methods are the confusion matrix, classification report, and accuracy score.
Accuracy = NumberPredictedCorrectly / ​NumberofCases 
^^ false positives and false negatives can be problematic, so we use 2 accuracy methods

A confusion matrix (good for classification models) (also known as an error matrix) is a simple table that summarizes
the model’s performance, including the exact number of false positives and false negatives.
​​
False-positives + False-negatives            12 + 29
                /                               /    = 0.1366 -> 86.34% Accuracy Score
         TotalDataPoints                       300


Classification reports.

Precision:
The ratio of correctly predicted true positives to the total of predicted positive cases. 
A high precision score translates to a low occurrence of false positives.

    NumberTruePositives
            /                    =    Precision
NumberPredictedPositiveCases

Recall:
Represents the ratio of correctly predicted true positives to actual positive cases. 
In other words, recall addresses the question of how many positive outcomes were rightly classified as positive.

    NumberTruePositives
            /                    =    Precision
NumberActualPositiveCases

F1 Score: (Generally lower score)
F1-score is a weighted average of precision and recall. 
It’s typically used as a metric for model-to-model comparison rather than for stand-alone model accuracy.

10.Optimize:
This might mean going back to modify the number of clusters or 
change the hyperparameters of a tree-based learning technique for clustering analysis techniques.

trial and error manually or automation via grid search
