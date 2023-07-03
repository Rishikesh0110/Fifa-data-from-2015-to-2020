
# Exploratory Data Analysis of FIFA data for 2020

The datasets provided include the players data for the Career Mode from FIFA 20 ("players_20.csv"). The data allows multiple comparison of the same players across the version of the videogame. So derived EDA to gain insights from this dataset.

## About Data
DataSetInformation: https://www.kaggle.com/datasets/stefanoleone992/fifa-20-complete-player-dataset 
Updated dataset available here: https://www.kaggle.com/stefanoleone992/fifa-21-complete-player-dataset


## Used Tool and Techniques
1. Used tools and techniques to perform this EDA
For withdraw insights from the data ,we must have the following python liberies installed to analyse data deeply.

2. Numpy: NumPy (Numerical Python) . https://numpy.org/doc/stable/user/absolute_beginners.html

3. Pandas: https://pandas.pydata.org/docs/

4. Seaborn: https://seaborn.pydata.org/

5. Matplotlib: https://matplotlib.org/

6. Sklearn: Simple and efficient tools for predictive data analysis https://scikit-learn.org/stable/

7. Google Analytics Colab
## Questions that derived
1. Which of player get most payment to play?
2. Which country has highest number of players belong?
3. Which player is most aged and which player has highest weight? 
4. Average age of players playing FIFA 2020.
5. Top shooters, Top defenders, Which club is able to make most number of passes?
simier kind of some questions has been drawn inside the notebook. 
## Techniques to performed EDA
1. **Loaded the required libraries**
Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn

2. **Load the dataset**
By help of pandas as pd.read_filetype("Path_name"),load the dataset.

3. **Checked to understood the data**
Reat the first 5 rows and last 5 rows by help of head() and tail() functions.

4. **Checked information of data**
info() fuctions checked the information such as how many column are there and what is the lenghts.

5. **Stistical analysis of data**
1. After checking lenght and columns of dataset i did the Stistical analysis by help of describe() function for both numerical and categorical columns which give 5 point analysis.

6. **Used wordclouds**
As this data has some columns such as clubs , countries, Player names so use wordclouds to show a imahge of words. Which works on the mode technique and number of repititions.

2. Than checked shape of data to get the actual lengh of rows and columns

3. Than Checked stistical analysis for string or categorical columns bu df.describe(include="O")

4. Than also returns the each column names and stored as list seperatly as categorical columns and numerical colums.

6. **Exploratory data analysis**
1. So after extracting the structure of data, Now i started the EDA part to mining the data by visualization of each columns.

2. Ananlysis of each numerical columns and categorical columns to derive insights by using diffrents pandas and numpy functions, which able to give us the different usefull insights.
We have more than 100 number of columns the dataset is very huge.

3. Statistical anlysis of each numerical columns and after ,By help of Histogram, Distribution plot , Box plot 

4. After combining numerical and categorical columns by help of bar diagrame, scatter plot, line plot, successfully extracted insights from data.

5. Visualiing those insights to make it interactive by diffrent techniques of Seaborn and Matplotlib by charts such as Histogram,Distribution plot ,Box plots for each nuerical columns and countplots for each categorical colums.

6. Sucessfully derive all the possible insights from the data with multiple trends ,that how the bbuisiness is going and how we can improve in functions.

7. Tried to derived correlation b/w some of columns to find relationships by using Heatmaps and regplots. Whether columns and other values effects the quality of wine.

#Data wranggling 
1. **Handled mssing values**
2. Removing np.nan values of missing values by replecing with specific mean or median of the column.
3. **Dropping duplicates**
4. Than checked for duplicates by trying to find the shape of dataset again after applied drop_duplicates()
4. **Outliers handling** 
5. Than handled outliers for each numerical columns the make the data more accurate and need to set the column to represent by their mean. #Standrization 
6. **Standrization**
 of each categorical and numeical columns that can help us in model building part. 20. Handling columns of Standrization of each numerical and categorical columns

Than handled categorical columns by One hot encoding pd.get_dummies() and numerical columns by minmax scaler and stadard scaler to standarize numerical columns.
## Conclusion
So, we can easily meke Conclusion after analyzing the data that the average age of players are around 27 years,
We found out about top shooters ,defeners, passers, Highest salary,Who is the oldest youngest
We also found out how many players belonged from which country and many more
