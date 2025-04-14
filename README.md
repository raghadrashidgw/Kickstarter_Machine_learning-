# Kickstarter_Machine_learning-
<div style="text-align: center;">
    <img src="https://media.gq.com/photos/59f0aa1cf964810d9a9b8f23/4:3/w_1024%2Cc_limit/1025-KickStarterMenswear_16x9.gif" width="500"/>
</div>
A machine learning model developed to predict the amount of pledge of a project in Kickstarter 


## Machine learning to predict the amount of pledge 
The model selected features:
features = ['subcategory', 'location', 'goal', 'backers', 'updates_per_day']   
target = "pledged"

RandomForestRegressor algorithim was used because it has many chances of true and false, the predict amount has a variance of R2: 0.76.
