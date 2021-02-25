# Skier-Ability-Prediction

Each row of csv contains data from a skier’s run. It has the following
columns:
(m1, m2 m3 ..., m14) which are a selection of metrics that characterise skiing technique after the completion of a run.
An example of one of these metrics is the average of the max edge angles from the outside ski for each turn in the run.

ability is a label of skiing ability (beginner, intermediate, advanced, expert).

Tasks:
Load the dataset into your notebook, and find which metrics do not have normal distributions.
Train and evaluate an interpretable machine learning model, making sure to select the features that are best at discerning ability.
Evaluate which features are most important to your interpretable model.
It is important that the model is interpretable so that we can explain to our users why they are classed as a certain ability and to help them learn how to improve their technique.
Save the best model to disk. 
