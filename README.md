# Number of sunspots
This repository in included a machine learning project related to number of sunspots during almost 200 years. 

What is ***Sunspot*** ? 
> Sunspots are temporary phenomena on the Sun's photosphere that appear as spots darker than the surrounding areas. They are regions of reduced surface temperature caused by concentrations of magnetic field flux that inhibit convection. Sunspots usually appear in pairs of opposite magnetic polarity. (From Wiki) 

In order to be familiar with sunspots, I have provided you a picture of those.  


![Left-The-SOHO-MDI-satellite-image-of-the-solar-disk-Right-the-McIntosh-Sunspot](/img/Left-The-SOHO-MDI-satellite-image-of-the-solar-disk-Right-the-McIntosh-Sunspot.png)

Datasets of this project have been downloaded form the [Kaggle website](https://kaggle.com).  The `.csv` contains some columns which are divided into features and label data in order to train a model in machine learning. I have set the `Number of Sunspots` as our label data and built several models such as  
- LinearRegression
- RidgeRegression
- DecisionTreeRegressor
- RandomForestRegressor

to predict `Number of Sunspots`. Furthermore, you can find some analysis in this project that shows the changes in the `Number of Sunspots` during the last 200 years as also 2018 as a special case.  
Aforementioned models results almost high in **Mean Absolute error (MAE)**. In order to solve this problem, I have used `GridsearchCV` in `scikit-learn` and tuned the `hyperparameter`. 


If you have any questions or suggestions, please [contact](mailto:m.reza.ebrahimi1995@gmail.com) me. 
