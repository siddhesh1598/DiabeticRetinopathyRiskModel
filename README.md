# DiabeticRetinopathyRiskModel

![alt text](https://github.com/siddhesh1598/DiabeticRetinopathyRiskModel/blob/master/thumbnail.png?raw=true)

A Risk Model to detect the disease of **Diabetic Retinopathy** by using the pathent's dataset. This code uses a structures dataset having patient's attributes *(Age, Systolic_BP, Diastolic_BP, Cholesterol)*. 

## Technical Concepts
**Diabetic Retinopathy:** It is a diabetes complication that affects eyes. It's caused by damage to the blood vessels of the light-sensitive tissue at the back of the eye (retina). <br>
More information can be found [here](https://www.medicalnewstoday.com/articles/183417)

**C-Index:** The concordance index or C-index is a generalization of the area under the ROC curve (AUC) that can take into account censored data. It represents the global assessment of the model discrimination power: this is the model’s ability to correctly provide a reliable ranking of the survival times based on the individual risk scores. <br>
More information can be found [here](https://square.github.io/pysurvival/metrics/c_index.html)

**Logistic Regression:** Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist. In regression analysis, logistic regression *(or logit regression)* is estimating the parameters of a logistic model *(a form of binary regression)*. <br>
More information can be found [here](http://www.fao.org/tempref/AG/Reserved/PPLPF/ftpOUT/Gianluca/stats/Logistic%20Regression,%20A%20Self-Learning%20Text,%202Ed%20(Statistics%20For%20Biology%20And%20Health)%20(David%20G%20Kleinbaum,%20Mitchell%20Klein)%200387953973.pdf)


## Getting Started

Clone the project repository to your local machine, then follow up with the steps as required.

### Requirements

After cloning the repository, install the necessary requirements for the project.
```
pip install -r requirements.txt
```

### Training

The code implements the Risk Model from scratch. The raw data is normalized and then interactions are added to enhace the efficiency of the model. If you wish to train the model on your own dataset. You can split your dataset into *X_data.csv* and  *y_data.csv* files or you can make changes to the code itself. <br>

The **C-Index** of th model is **0.8281** <br>

![alt text](https://github.com/siddhesh1598/DiabeticRetinopathyRiskModel/blob/master/coefficients.png?raw=true)
Coefficients of the features used to make the predictions.


## Authors

* **Siddhesh Shinde** - *Initial work* - [SiddheshShinde](https://github.com/siddhesh1598)

 
