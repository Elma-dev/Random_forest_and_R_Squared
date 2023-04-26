# Random_forest_and_R_Squared
Random Forest and R squared meaning
# <center>**Random Forest Intuition**</center>
**step1:** Pick at random K data points from the training set.\
**step2:** Build the Decision Tree associated to these K data points.\
**step3:** Choose the number Ntree of trees you want to build and repeat **step1 & step2**.\
**step4:** For a new data point, make each one of your Ntree tree predict the value of Y to for the data in question, and assign the new data point the average across all of the predict Y values.\
![image](https://user-images.githubusercontent.com/67378945/234571224-79bc90dc-4dd8-475a-a228-796c2cda083c.png)

# R squared
```math
R^{2}=1-\frac{\sum_{i}(y_{i}-\hat{y_{i}})^2}{\sum_{i}(y_{i}-y_{avg})^2}
```

![image](https://user-images.githubusercontent.com/67378945/234576124-27749f27-cb18-4b71-acc8-b61994b107fb.png)
![image](https://user-images.githubusercontent.com/67378945/234576217-b4ca26b8-3bb3-49f9-b0bf-e72494069e19.png)

* 1.0  = Perfect fit
* 0.9  = Very good
* <0.7 = Not great
* <0.4 = Terrible
* <0   = Model makes no sense for this data

