# Health-Insurance-Cost-Predicition
The data is collected by a US Health Insurance Company. The Dataset is based on US citizens. The dataset is comprised of 1338 records with 6 attributes.Attributes are as follow age, sex, bmi,
children, smoker and charges. The data was in structured format
and was stores in a csv file. In a dataset not every attribute has
an impact on the prediction. Whereas some attributes even
decline the accuracy, so it becomes necessary to remove these
attributes from the features of the code. Removing such
attributes not only help in improving accuracy but also the
overall performance and speed.


# Data Description
<ul>
<li>Age: Age is the attribute of the citizen in Years.</li>

<li>Sex: Sex is the gender of the particular person, [female, male]</li>

<li>BMI: Body mass index is a value derived from the mass and height of a person,
providing an understanding of body, weights that are relatively high or low relative
to height, objective index of body weight (kg / m ^ 2) using the ratio of height to
weight, ideally 18.5 to 24.9</li>

<li>Children: number of children covered by health insurance / Number of dependents</li>

<li>Smoker: This Attribute or feature of the dataset describes if a person smokes or not
in [yes, no].</li>

<li>Region: the beneficiary’s residential area in the US, [northeast, southeast,
southwest, northwest]</li>

<li>Charges: Individual medical costs billed by health insurance.</li>

</ul>


# Approach 

 🡪<b>Linear Regression<b/>
It comes under usage when we want to predict a single output depending
upon multiple input or we can say that the predicted value of a variable is
based upon the value of two or more different variables. The predicted
variable or the variable we want to predict is called the dependent variable
(or sometimes, the outcome, target or criterion variable) and the variables
being used in predict of the value of the dependent variable are called the
independent variables (or sometimes, the prediction, explanatory or
regression variables).  

🡪<b>Decision tree regression using Decision Tree Regressor<b/>
Regression or classification models in decision tree regression builds in the
form of a tree structure. The dataset is divided or segmented into smaller
and smaller subsets while at the same time an associated decision tree is
incrementally developed. A decision tree with decision nodes and leaf nodes
is obtained as a final result. These decision nodes have two or more
branches, each representing values for the attribute tested. Decision on the
numerical target is represented by leaf node. The topmost decision node
corresponds to the best predictor in the tree called root node. Numerical
data along with categorical data can be handled by decision tress.


🡪<b> Gradient Boosting Regression<b/>
This algorithm for Boosting Trees came from the application of boosting
methods to regression trees. The basic idea behind this is to compute a
sequence of simple trees, where each successive tree is built for the
prediction residuals of the preceding tree. For predictive models, gradient
boosting is considered as one of the most powerful techniques.


# Visualizations

![image](https://github.com/moremnitesh47/Health-Insurance-Cost-Predicition/assets/144453984/7d42a7db-1cbf-4ec2-8cba-29b9da10dab8)


![image](https://github.com/moremnitesh47/Health-Insurance-Cost-Predicition/assets/144453984/c31142a6-ee1c-406b-8ec0-f71fb9760401)



# Conclusion

As the Root square Score of both train and test data is 0.75, we can conclude
that the model shows negligible signs of overfitting.
In this project, three regression models are evaluated for individual health
insurance data. The health insurance data was used to develop the three
regression models, and the predicted premiums from these models were
compared with actual premiums to compare the accuracies of these models. It
has been found that Gradient Boosting Regression model which is built upon
decision tree is the best performing model.
Various factors were used and their effect on predicted amount was examined. It
was observed that a person’s age and smoking status affects the prediction most
in every algorithm applied. Attributes which had no effect on the prediction were
removed from the features.
The effect of various independent variables on the premium amount was also
checked. The attributes also in combination were checked for better accuracy
results.
Premium amount prediction focuses on persons own health rather than other
company’s insurance terms and conditions. The models can be applied to the
data collected in coming years to predict the premium. This can help not only
people but also insurance companies to work in tandem for better and more
health centric insurance amount.
