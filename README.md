# Big-mart-sales-prediction 💰💰


### Project Link ->  https://big-mart-sales-prediction1.herokuapp.com/ 🌐🌐

![enter image description here](https://cdn-images-1.medium.com/max/480/1*JADDaOLHMZ4ZhQinzmScRQ.png)

This Repository is on the BigMart’s sale prediction proposed by Analytics Vidhya.According to the information provided, Bigmart is a big supermarket chain, with stores all around the country and its current board set out a challenge to all Data Scientist out there to help them create a model that can predict the sales, per product, for each store. BigMart has collected sales data from the year 2013, for 1559 products across 10 stores in different cities. With this information the corporation hopes we can identify the products and stores which play a key role in their sales and use that information to take the correct measures to ensure success of their business.


**Project Link** - ***https://cartpriceprediction.herokuapp.com/***




![enter image description here](https://miro.medium.com/max/875/1*DjdHeBOiO0-Pv-8-ylqHaA.png)

 ## Flowchart
![enter image description here](https://github.com/ritik-sys/Big-mart-sales-prediction/blob/main/Blank%20diagram.png)

## Data Exploration🚀
In this phase useful information about the data has been extracted from the
dataset. That is trying to identify the information from hypotheses vs available
data. Which shows that the attributes Outlet size and Item weight face the
problem of missing values, also the minimum value of Item Visibility is zero
which is not actually practically possible. Establishment year of Outlet varies
from 1985 to 2009. These values may not be appropriate in this form. So, there is a 
need to convert them into how old a particular outlet is. There are 1559 unique
products, as well as 10 unique outlets, present in the dataset. The attribute
Item type contains 16 unique values. Where as two types of Item Fat Content
are there but some of them are misspelled as regular instead of ’Regular’ and
low fat, LF instead of Low Fat. It was found that the response
variable i.e. Item Outlet Sales was positively skewed. So, to remove the skewness
of response variable a log operation was performed on Item Outlet Sales

## Data Cleaning 🚀
It was observed from the previous section that the attributes Outlet Size and
Item Weight has missing values. In our work in case of Outlet Size missing
A Comparative Study of Big Mart Sales Prediction .Univariate distribution of target variable Item outlet sales. The Target variable
is positively skewed towards the higher sales.
value we replace it by the mode of that attribute and for the Item Weight
missing values we replace by mean of that particular attribute. The missing
attributes are numerical where the replacement by mean and mode diminishes
the correlation among imputed attributes. For our model we are assuming that
there is no relationship between the measured attribute and imputed attribute

 ## Methodology
![enter image description here](https://github.com/ritik-sys/Big-mart-sales-prediction/blob/main/Blank%20diagram(1).png)

## Model Building 🚀
After completing the previous phases, the dataset is now ready to build proposed
model. Once the model is build it is used as predictive model to forecast sales
of Big Mart. In our work, we propose a model using Xgboost algorithm and
compare it with other machine learning techniques like Linear regression, Ridge
regression , Decision tree etc.

 ## UI/UX
 ### Screenshot-1![enter image description here](https://raw.githubusercontent.com/ritik-sys/Big-mart-sales-prediction/main/1.jpeg)
 ### Screenshot-2![enter image description here](https://raw.githubusercontent.com/ritik-sys/Big-mart-sales-prediction/main/2.jpeg)
 ### Screenshot-3![enter image description here](https://raw.githubusercontent.com/ritik-sys/Big-mart-sales-prediction/main/3.jpeg)
## Tech Stack and Tools 💻

 - [Python]
 - [Google Colab]
 - [Anaconda]
 - [Flask]
 - [Keras]

## Installation :zap:

 
 **1. Now start the  server  by running the following command :-**
 ```bash
 python app.py
 ```
 
 **2.** **🎉  Open your browser and go to  `https://localhost:3000`**
 
## Contributors 🤝
 - [**Gagandeep Singh**](https://github.com/)  

 


