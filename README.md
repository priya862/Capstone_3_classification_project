# Capstone_3_classification_project
Mobile price range prediction

# PROBLEM STATEMENT
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.


### *Data Description -*
* *Battery_power* - Total energy a battery can store in one time measured in mAh
* *Blue* - Has bluetooth or not
* **Clock_speed** - speed at which microprocessor executes instructions
* **Dual_sim** - Has dual sim support or not
* **Fc** - Front Camera mega pixels
* **Four_g** - Has 4G or not
* **Int_memory** - Internal Memory in Gigabytes
* **M_dep** - Mobile Depth in cm
* **Mobile_wt** - Weight of mobile phone
* **N_cores** - Number of cores of processor
* **Pc** - Primary Camera mega pixels
* **Px_height** - Pixel Resolution Height
* **Px_width** - Pixel Resolution Width
* **Ram** - Random Access Memory in Mega Bytes
* **Sc_h** - Screen Height of mobile in cm
* **Sc_w** - Screen Width of mobile in cm
* **Talk_time** - longest time that a single battery charge will last when you are
* **Three_g** - Has 3G or not
* **Touch_screen** - Has touch screen or not
* **Wifi** - Has wifi or not
* **Price_range** - This is the target variable with value of 
* 0(low cost), 
* 1(medium cost),
* 2(high cost) and
* 3(very high cost).
* Thus our target variable has 4 categories so basically it is a Multiclass classification problem.


# Conclusion
* here in the dataset there is no any null value,no duplicate values.
* EDA Conclusion
1. there is equal number of observation for each category.
2. half the devices have bluetooth and don't have.
3. Ram has continuous increase with the price range.
4. 76.2 % supported 3g and 23.8% not.
5. 52% mobile supported 4g and 48% not.
6. got 12 important feature for our model .
* applied four classification models
1. Decision tree classifier
2. Gradient Boosting Classifier
3. XGBoost Classifier
4. SVM 
* And got to know that SVM is the best suitable model for our dataset
