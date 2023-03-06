# Women Techsters Fellowship-MachineLearning-MobileClassification

# Machine Learning Project- Mobile Classification
## by Sara Osama Kilany


## Dataset

Bob has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.

He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.

Bob wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solve this problem.

In this problem you do not have to predict actual price but a price range indicating how high the price is.

Link to this Kaggle Dataset is [here](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification).

Data Fields :

battery_power : Total energy a battery can store in one time measured in mAh
blue : Has bluetooth or not
clock_speed : speed at which microprocessor executes instructions
dual_sim : Has dual sim support or not
fc : Front Camera mega pixels
four_g : Has 4G or not
int_memory : Internal Memory in Gigabytes
m_dep : Mobile Depth in cm
mobile_wt : Weight of mobile phone
n_cores : Number of cores of processor
pc : Primary Camera mega pixels
px_height : Pixel Resolution Height
px_width : Pixel Resolution Width
ram : Random Access Memory in Mega Bytes
sc_h : Screen Height of mobile in cm
sc_w : Screen Width of mobile in cm
talk_time : longest time that a single battery charge will last when you are
three_g : Has 3G or not
touch_screen : Has touch screen or not
wifi : Has wifi or not
price_range : This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost)


## Summary of Findings

Both logistic regression and SVM have the best performance for our dataset.

Class 2 and class 1 have the worst f1 score and the largest numbers of mis-classified points.

XGBoost and Random Forest and KNN have good score for the test data but they overfit the training data causing the exclusion of their use.

Naive Bayes has low performance - 0.84 f1 score and accuracy. Causing its exclusion.

Not only does Decision Tree overfits, but it has the lowest performance in terms of f1 score and accuracy compared to all the other models.

