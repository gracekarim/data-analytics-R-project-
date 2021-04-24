# data-analytics-R-project-
image classifier model 
•	Use the images file to build a matrix of 3 columns consisting of the medians of the pixels intensities x1:red,x2:gren,x3:blue. 
•	Create a matrix of 0 and 1 based on the fact that the image is an outdoor or not. 
•	Combine both matrices, to create a data frame for the LDA methods 
•	Build a training and a testing data set 
•	Build a glm model for the logistics regression models and the lda model for the linear regression analysis based on the training data set 
•	Predict each model based on the testing data set , and use the cut-off of 0.5 predict if it is an outdoor or not . 
•	Find the ROC curve and the AUC to see how we improve how model based on the sensitivity and the specificity. A classification rule is sensitive if it predicts 1 for most y=1, and it is specific if it predicts 0 for all y=0. Sensitivity is the proportion of observed positive classified correctly and specificity is the proportion of observed negative classified correctly. The ROC curve is the plot of sensitivity against specificity. We want it to be attractive to the top-left corner of the graph, with a very fast rise to the upper horizontal line at 1 and a large area under the curve. Basically, we want a large sensitivity. W want also a large AUC , around 0.8 
•	Compute the misclassification errors rates 
•	Compare both methods to make inference.  
