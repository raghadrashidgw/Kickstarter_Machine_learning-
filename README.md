# Kickstarter_Machine_learning-
<div style="text-align: center;">
    <img src="https://media.gq.com/photos/59f0aa1cf964810d9a9b8f23/4:3/w_1024%2Cc_limit/1025-KickStarterMenswear_16x9.gif" width="500"/>
</div>
------- 
Projects with a higher success rate :
 Dance
 Music
 Theater
 On a median basis,:
 these projects receive a substantial
 amount of funding and attract a
 significant number of backers.
 Launching a project in any of these categories on
 Kickstarter is highly recommended.
![](SuccessRatioPlot)
A machine learning model developed to predict the amount of pledge of a project in Kickstarter 


## Machine learning to predict the amount of pledge 
The model selected features:
features = ['subcategory', 'location', 'goal', 'backers', 'updates_per_day']   
target = "pledged"

RandomForestRegressor algorithim was used because it has many chances of true and false, the predict amount has a variance of R2: 0.76.
our model has ~76.45% of the variance in the target variable (Pledge amount)
