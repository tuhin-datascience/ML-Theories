#### **Confusion Metrics**

![Confusion Metrics](https://github.com/tuhin-datascience/images/blob/main/CM.PNG)

**True Positives (TP)** - These are the correctly predicted positive values which means that the value of the actual class is yes and the value of the predicted class is also yes. E.g. if the actual class value indicates that this passenger survived and the predicted class tells you the same thing.

**True Negatives (TN)** - These are the correctly predicted negative values which means that the value of the actual class is no and value of predicted class is also no. E.g. if the actual class says this passenger did not survive and the predicted class tells you the same thing.
False positives and false negatives, these values occur when your actual class contradicts the predicted class.

**False Positives (FP)** – When the actual class is no and the predicted class is yes. E.g. if the actual class says this passenger did not survive but the predicted class tells you that this passenger will survive.

**False Negatives (FN)** – When the actual class is yes but predicted class is no. E.g. if the actual class value indicates that this passenger survived and the predicted class tells you that the passenger will die.

Once you understand these four parameters then we can calculate Accuracy, Precision, Recall and F1 score.

**Accuracy**
Accuracy is the most intuitive performance measure and it is simply a ratio of correctly predicted observation to the total observations. One may think that, if we have high accuracy then our model is best. Yes, accuracy is a great measure but only when you have symmetric datasets where values of false positive and false negatives are almost the same. Therefore, you have to look at other parameters to evaluate the performance of your model. 

![Confusion Metrics](https://github.com/tuhin-datascience/images/blob/main/accuracy.PNG)

**Precision**
 Precision is the ratio of correctly predicted positive observations to the total predicted positive observations. The question that this metric answers is of all passengers that are labeled as survived, how many actually survived? High precision relates to the low false positive rate.

![Precision](https://github.com/tuhin-datascience/images/blob/main/precision.PNG)

**Recall (Sensitivity)**
Recall is the ratio of correctly predicted positive observations to all observations in the actual class. 

![Recall](https://github.com/tuhin-datascience/images/blob/main/recall.PNG)

**F1 score**
F1 Score is the weighted average of Precision and Recall. Therefore, this score takes both false positives and false negatives into account. Intuitively it is not as easy to understand as accuracy, but F1 is usually more useful than accuracy, especially if you have an uneven class distribution. Accuracy works best if false positives and false negatives have similar cost. If the cost of false positives and false negatives are very different, it’s better to look at both Precision and Recall. 

![F1 Score](https://github.com/tuhin-datascience/images/blob/main/f1score.PNG)


