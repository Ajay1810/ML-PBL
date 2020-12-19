# ML-PBL
# Catching Crooks in Sea

The following program combines the predictive power of Random Forests – a powerful machine learning algorithm – with the open source, web application builder “R Shiny”. This decision support tool allows users to select a test fishing vessel with set parameters, and predict its probability of engaging in illegal fishing. Users can also create their own series of parameters and make a prediction on the probability of a ship engaging in illegal fishing.

Random Forests works by way of decision trees (i.e. a souped-up series of conditional “if” / “then” statements) to make predictions on a target variable. It creates those conditional statements by “learning” the relationships between the target variable (here, illegal fishing) and the predictor variables (the variables we want to use to predict the target – see table above).  Using the data simulated we used the “Illegal” column as our target variable – in other words, we were interested in predicting if a ship was engaged in illegal activity based on the other columns (owner, country, etc…).

We used a cross-validation technique to ensure the model was predicting our data well.  In this case, the Random Forests model we used had an accuracy of 74% – that means that it correctly guessed if a ship was engaged in illegal fishing (or not), 74% of the time. This value could be vastly improved through tuning of the model (e.g. tuning of hyperparameters, use of ensemble models, deep learning methodology, or other techniques).  I purposefully programmed “noise” in our dataset to ensure that we didn’t achieve a perfect model. The goal of this is to demonstrate how the proposed system could work as opposed to perfecting the model.

Using them to combat illegal fishing will automate decision-making in a transparent way that can be scaled from local to global solutions. Furthermore, data integrity can be secured through centralized databases with specifically designed access.

There is still much work to be done to develop these tools in a way that is agreed upon by the global community, but we are at a stage now to begin the process
