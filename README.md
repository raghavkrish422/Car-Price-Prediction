# Car Price Prediction

Note: The coding part of the project was equally shared and contributed by all the 3 team members stated below
1. Venkataraman B (20BCE1499)
2. Rohit Madhavan S (20BCE1150)
3. Raghav K (20BCE1468)

This can also be seen in the right hand side of the main section --> Contributors

# Objective and Problem Statement
The main aim of this project is to predict the price of used cars using the various Machine Learning (ML) models. This can enable the customers to make decisions baesd on different inputs or factors namely

1. Brand or Type of the car one prefers like Ford, Hyundai etc
2. Model of the car namely Ford Figo, Hyundai Creta
3. Location like Delhi, Chennai, Mumbai
4. Year of manufacturing like 2020, 2021 etc
5. Type of fuel namely Petrol, Diesel
6. Price range or Budget
7. Type of transmission which the customer prefers like Automatic or Manual
8. Mileage

They are a few characterisitic features required by the customer. The project Car Price Prediction deals with providing the solution to these problems. Through this project, we will get to know which of the factors are significant and tell us how they affect the car's worth in the market

# Dataset
https://www.kaggle.com/austinreese/craigslist-carstrucks-data

# Details about the dataset
The dataset has 26 columns which has details of

 1. Unique ID, where no two cars can have same ID
 2. Region where the car is available
 3. Price of the car which also includes the price range
 4. Year of manufacture like 2020, 2021 etc
 5. Brand or Type of the car
 6. Name of the manufacturer
 7. Model of the car

These are the primary needs the customer looks into before buying a second hand car. We can also add some additional features that can enhance the chances of the customer and also helps in the sales of the cars

# Model used
Multiple linear regression model is used which is characterized by more than 1 independent variables.

# Tasks to perform on the dataset
The tasks that are to be done in this project are divided into various categories namely

# Data exploration and understanding
![image](https://github.com/user-attachments/assets/69b62a34-1886-4e6d-a5c1-19da2f7da776)

The dataset has 205 rows and 26 columns. All the columns except "Price" are independent factors or variables. We again subdivide independent variables as "Categorical" and "Numerical" variables

# Some of the "Numerical" variables include
1. wheelbase
2. carlength
3. carwidth
4. carheight
5. curbweight
6. enginesize
7. boreratio
8. stroke
9. compressionratio
10. horsepower
11. peakrpm
12. citympg
13. highwaympg

# Some of the "Categorical" variables include
1. symboling
2. fueltype
3. aspiration
4. doornumber
5. carbody
6. drivewheel
7. enginelocation
8. enginetype
9. cylindernumber
10. fuelsystem
11. car_name

# Data Cleaning
There are no missing values in the dataset and also all the columns in the dataset are in the correct format except for Symboling which is a Categorical value. Also Data Preprocessing has been done on CarName and have created a new factor or variable instead of former and called it car_company

# Data Preparation
1. Firstly, we need to prepare data for building the model, which requires us to split the data into X and Y as shown in the figure
2. Secondly, create dummy variables for the independent variables
3. Split the dataset into train and test
4. Model Building involves building the model with all necessary features using Linear Regression. We find out that the value as r-squared as 83%
5. Decide and choose the features for building the model. One such way for choosing the features is to plot no of features in the model to the value of r-squared as shown in the figure below
   ![image](https://github.com/user-attachments/assets/4e014d08-34f1-4b2f-a4cd-9e05c36fab17)


# Building the suitable model and evaluating it
After deciding upon the data preparation, we finally come to the model building part wherein the final model is built using 6 different features as shown in the figure and we get the value of r2-squared to be 0.8851 which tends the model to have accuracy of 88.51%
![image](https://github.com/user-attachments/assets/0908f261-5fba-4442-a93f-eea60b450a2c)

# Evaluating the final model
In the model, we must ensure to test that the error terms are always normally distributed having mean equal to zero, with less correlation with the predictors and lastly, the variance of the error terms must be constant. We then plot the error terms. Thus, we come to know that the conclusion that final predictors have high value of correlation
![image](https://github.com/user-attachments/assets/c9adfe74-dfd5-4c3f-bae4-833cbadf2399)










