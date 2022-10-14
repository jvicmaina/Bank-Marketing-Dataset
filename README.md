# Bank-Marketing-Dataset
How banks target potential customers

 THE PROBLEM UNDERSTANDING PHASE
We begin with the Problem Understanding Phase, in order to make sure that the
ladder we are working so hard to climb is not leaning against the wrong wall.
3.2.1 Clearly Enunciate the Project Objectives
The objectives of this analysis are as follows:
1. Learn about our potential customers. That is, learn the characteristics of those
who choose to bank with us, as well as those who do not.
2. Develop a profitable method of identifying likely positive responders, so that
we may save time and money. That is, develop a model or models that will
identify likely positive responders. Quantify the expected profit from using
these models.
3.2.2 Translate These Objectives into a Data Science Problem
How shall we use data science to accomplish the project objectives?
1. There are many ways to learn about our potential customers.
a. Use Exploratory Data Analysis to express some simple graphic relationships among the variables. For example, use a histogram of age overlain
with information about the response yes/no to visualize whether age has a
bearing on customer response.
b. Use Clustering to determine whether there are natural groupings within
our potential customers, for example, younger/more‐educated vs older/
less‐educated. Then, see if these clusters differ with respect to their
response to the marketing.
c. Use Association Rules to see whether there are useful relationships among
subsets of the records. For example, suppose the rule, “If cell phone, then
response = yes” has good support and high confidence. This would allow
our marketing people to develop a targeted campaign to cellphone users,
independent of the results of our overall modeling.
2. We can develop a powerful suite of data science models to identify likely
positive responders. Note that, since the response (yes/no) is categorical, we
can use classification models but not estimation models.
a. Develop the best classification model we can, using the following
algorithms:
i. Decision Trees
ii. Random Forests
iii. Naïve Bayes Classification
iv. Neural Networks
v. Logistic Regression
b. Evaluate each model based on predetermined model evaluation criteria,
such as misclassification costs. Construct a table of the best models and
their costs.
c. Consult with management regarding the best model or models with which
to move forward to the deployment phase.
Thus, we have (i) clearly enunciated our objectives and (ii) translated these
objectives into a set of data science tasks to be implemented. Thus, Phase One:
Problem Understanding Phase is complete.
 DATA PREPARAT ION PHASE
Next, we turn to the Data Preparation Phase, where the data are cleaned and prepped
for analysis. A complete guide to data preparation would require much more space
than we have here. (The reader is encouraged to see Data Mining and Predictive
Analytics3
 for much more on data preparation.) Every data set has its own requisite
data prep tasks. In this chapter we will focus on the following data preparation
tasks:
• Adding an index field
• Changing misleading field values
• Reexpressing categorical data as numeric data
• Standardizing the numeric fields
• Identifying outliers.
