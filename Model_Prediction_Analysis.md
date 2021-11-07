# Predicting the Model
A machine leanring model widely depends upon the data and the final goal that we are trying to achieve
after having a look at the data, which is a very large sample of data ( 12180 rows × 93 columns) and the fact that we are looking to predict a 
category and not a quantity it will be better to go with RandomForest model over logistic regression model. 

# Before Scaling Analyis 
After fitting the models and testing them out it was clear that even though RandomForest performed slighlty better on the test data 
compared to Logistic Regression model, it also seem to be overfitting the data.As can be ssen belowin the images 
![logreg](https://user-images.githubusercontent.com/85182090/140656540-5e72d6d3-63ca-4b70-9460-d2b74c6a9a65.JPG)
![ranfor](https://user-images.githubusercontent.com/85182090/140656541-fd13b9c0-8c50-4a34-bd90-63009c87b8ee.JPG)

In conclusion both the model don't seem to be the 
best choice for this type of data 

# After Scaling Data 
Even after scaling the data there doesn't seem to be much difference in the results.Hence reenforcing the previous analyis.
 
