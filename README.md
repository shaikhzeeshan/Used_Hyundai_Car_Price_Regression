# Used-car-price-Prediction

 <img src= "https://cdn.dribbble.com/users/1239720/screenshots/3506944/car_mg.gif" > 

Predicting  the  price of a used cars has been studied extensively in various  researches.Car price prediction is somehow an interesting and popular problem.Accurate car price prediction involves expert knowledge, because price  usually depends on many  distinctive  features  and factors.Typically, the most signiﬁcant ones are present price , brand and model,  age, mileage etc. The fuel type used in the car as well as fuel consumption  per mile highly affect the price of a car due to a frequent changes in the  price of a fuel.
Different features like  Transmission, tax, Mileage per gallon (mpg), engine size , etc. will also inﬂuence the car price.







<br>
<br>
<!-- <p align="center"><a><img src="https://forthebadge.com/images/badges/built-with-love.svg"><img src="https://user-images.githubusercontent.com/106439762/181936448-9314e858-4251-46d6-b4d1-35a4c29e9c19.svg"><img src="https://forthebadge.com/images/badges/made-with-python.svg"></a></p> -->

##  <img src="https://user-images.githubusercontent.com/106439762/181935629-b3c47bd3-77fb-4431-a11c-ff8ba0942b63.gif" width="48" height="48"> **User's Manual**
| Files/Folder| Description |
| ------------- | ------------- |
| **Investment Advisor IPYNB** | This file contains the ipynb code for the  project. |
| **Project PPT Files**  | This file provides the powerpoint presentation which contains all the major insights and conclusions.  |
| **Hyundi.csv**  | This folder provides the raw data for the analysis .  |


<p align="center"><img src="https://cdn.rentechdigital.com/common_files/blogs/machine-learning-swipecart-blog-img-01-31-08-2022.gif" width="600" ></p>


##  DataSet
The Dataset consists of 9 columns which are:

    1. The model column which gives the name of the car model
    
    2. Year column Which include year from 2000 to 2020 details of different car sold in UK.
    
    3. Price column shows the price at which the car has been sold in the market.
    
    4. Transmission shows weather the car is automatic or manual.
    
    5. Mileage shows the KM driven .
    
    6. Fuel Type states weather it is petrol or diesel.
    
    7. MPG shows the miles per gallon.
    
    8.Tax and engine size are basically the tax paid by the individual and the power of each engine.








.







    
    

##  <img src=https://user-images.githubusercontent.com/106439762/178428775-03d67679-9aa4-4b08-91e9-6eb6ed8faf66.gif  width="48" height="48"> **Analysis**

    o       Analysed the data, performed univarient and bivarient analysis . 
    
    o	Found out the correlation between various variables by using Pearson Correlation coefficient and also plotted heatmap of it.
           
            Eg: PCC of Year and Price 
            
            Pearson Correlation coefficient :  0.58

     
    o	Created different machine learning models such as Linear Regression, Decision Tree,Random Forest,Support Vector  Machine .
  
    o	Random forest with hyper parameter tuned using grid search cv gives the maximum accuracy of 92.3%. 
    
    o	Most of the regression models gives good predictions

    
    
##  💻 Tools Used:

    o       Scikit-Learn
    
    o	Pandas
     
    o	Numpy 
    
    o       Python    
    
    o	Matplotlib
     
    o	Seaborn 
       
    
    
    
   

## <img src="https://user-images.githubusercontent.com/106439762/181937125-2a4b22a3-f8a9-4226-bbd3-df972f9dbbc4.gif" width="48" height="48" > Quick Start

    1. Imported the data into python dataframe.
    
    2. Performed Exploratory Data Analysis.
    
    3. The data consists of nearly about 4200 car data.
    
    4. Performed univarient and bivarient analysis.
    
    5. Ploted the  necessary graphs.
    
    6. Created different Machine Learning Models.
    
    7. Calculated the accuracy using rmse,r2 score etc .
    
    8. The random forest model gave an accuracy of 92.3%.
    
    9. Created a powerpoint presentation with all the insights and conclusions listed with the indepth analysis.
    
**Predictions**
| ML Model| R2 Score |
| ------------- | ------------- |
| **Linear Regression** | 88.73 %. |
| **Decision Tree**  | 88.00 %  |
| **Random Forest**  | 91.5 %   | 
| **Grid search CV** | 92.5 %  |
| **Polynomial Regression(dregree=2)** | 93.1 % |
  
# <img src="https://www.getcloudapp.com/wp-content/uploads/2021/03/5aebb952e4867ce13f4d308f_laptop_gif_trans.gif" > Screenshots


**This graph shows the correlation between all the columns in the datasets.For a perfect ML model their shouldn't be multicollinearity.** 

![image](https://user-images.githubusercontent.com/82110840/235917343-6197b1f0-af30-4c3a-829f-10a34167ae05.png)

**This is a mulitivarient analysis containing different pairplots of all the columns in the dataset.It aims to understand the relationships, patterns, and interactions among multiple variables and how they collectively influence an outcome or phenomenon.**
![image](https://user-images.githubusercontent.com/82110840/235917392-0c946d40-09a9-43a4-87ca-cb2d6711d171.png)

**The Graph shown below is the univarient analysis which shows the number of cars using different transmission and we can conclude that Manual cars are sold wiedly in the market.**

![image](https://user-images.githubusercontent.com/82110840/235917422-b3c5bba4-c0b2-4c7d-a1a5-4caeea899259.png)

**The graph gives us an idea of the fuel type of majority number of car which id petrol cars are widely used in UK.It focuses on examining the characteristics, patterns, and distribution of a single variable without considering the relationship with other variables.**

![image](https://user-images.githubusercontent.com/82110840/235917444-964b77b1-1b2f-4e79-b88e-b78840aba98a.png)
# Challenges
We Have Faced challenges while tuning the hyperparameter for the model to find the best parameters which give the maximum output.
The polynomial regression which helped the model to attain its best performance was a new learning for the project.

# Conclusions

The developed machine learning model demonstrates a high level of accuracy and performance in predicting used car prices in the UK. It has undergone rigorous training and evaluation, achieving reliable results.

Extensive data preprocessing techniques were applied, including handling missing values, encoding categorical variables, and feature scaling. These steps ensured the quality and consistency of the input data, leading to improved model performance.

The developed model exhibits robustness and generalization capabilities, successfully handling unseen data and outperforming traditional methods of used car price estimation. It has the potential to be deployed in real-world scenarios, supporting decision-making processes in the automotive industry.

The model's design and implementation consider scalability and efficiency, enabling it to handle large datasets and accommodate future growth in the used car market. It is capable of processing data quickly, facilitating timely decision-making and enhancing operational efficiency
