# Data Science MAsters (Data Aaylyst)
1. Working With Ptyhon
2. Exploring Pandas dataframe
3. Working with numpy
4. Visualization (matplotlib, seaborn, plotly)
     

# Scrapping IMDB movies (Top 250) 
- Scrapping IMDB website to collect the informations like ratings, movie name, movie year, 
- movie rankings of top 250 by IMDB and dumping these feature in an excel sheet.
- Click: [Check](Scapping_IMDB_MOVIES)
     
# Lets understand the concept of EDA in very simple language, so when ever a data analyst gets a data set, 
the main role is to find out the insights and then help the product manager or sales maanger of the particular company 
to make appropriate decissions, her ecomes the concept of EDA (Exploratory data analysis) where the data scientist/analyst analysis 
features of the raw data in all possible ways, visualises it using matplotlib and seaborn to make more clear insights and 
conclusions for company that ll help them in decision making.

* Also before the emplementation of ML model the EDA is performed using various feature engineering and  statistical engineering techniques
* inorder to handle the raw data in such a way that no biasness occurs in the model.
* 
# Some of the ways are: 
  * Handling missing values
  * Balancing the imbalanced data
  * standarization 
  * feature extracton

# EDA in 5 minutes 
- Exploratory data analysis of any data set within just few minutes by help of 
     Pandas profiling report, and saving the report into .html
     
  visit here: Visit here [toview](https://drive.google.com/drive/u/0/folders/1XLHedq8OwXl-LS9ugY4f0s-jj-gw6m9m) Report.


# EDA OF US-Accidents data with 3M data points
The main aim behind analysing this huge data set is to get hand on industry level expirence of how 
working on such a big data set looks like and what are the real time challenges faced by an data anylyst in order to do that,
by using various feature engineerng & statistical enfineering techniques inorder to handel unbalanced data by 
     upsampling technique preventing our ML model getting baised, and handling missing values to avoid 
     loss of huge amount of data by varoius imputation techniques.
     At the end giving the ensights of the features analysed using graphs and summury-conclusions.
      
 Data overview from kaggle:
            
            
 ![Data_set overview kaggle](https://user-images.githubusercontent.com/117031012/227447300-fc412b38-775b-4172-9836-ef1b4fbaaf66.png)



      Modelling:
      In python on jupiter notebook, file in repository.
      
      
   # EDA of Wine_Quality_Check:
      Data Set Information:

The two datasets are related to red and white variants of the Portuguese 
"Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) 
and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced 
(e.g. there are many more normal wines than excellent or poor ones). 
Outlier detection algorithms could be used to detect the few excellent or poor wines. 
Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

Attribute Information:

Input variables (based on physicochemical tests):

* fixed acidity
*  volatile acidity
* citric acid
* residual sugar
*  chlorides
* free sulfur dioxide
* total sulfur dioxide
* density
* pH
* sulphates
* alcohol

Output variable (based on sensory data):

** - quality (score between 0 and 10)



  # EDA OFSTUDENT PERFORMANCE INDICATOR (from kaggle)
 1) Problem statement
This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.
2) Data Collection
        View: [Dataset Source](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977) here.
The data consists of 8 column and 1000 rows.
* Dataset Information
* gender : sex of students -> (Male/female)
* race/ethnicity : ethnicity of students -> (Group A, B,C, D,E)
* parental level of education : parents' final education ->(bachelor's degree,some college,master's degree,associate's degree,high school)
* lunch : having lunch before test (standard or free/reduced)
* test preparation course : complete or not complete before test
* math score
* reading score
* writing score


# Data Checks to perform:
 
 * Check Missing values
 * Check Duplicates
 * Check data type
 * Check the number of unique values of each column
 * Check statistics of data set
 * Check various categories present in the different categorical column

# Web scraping-Flipkart:
Coming up with my 1st Data Science Project 😀 "Web Scraping" In Python(Core App) & Flask(API).

- Very first let me brief you about web scarping, It is the process of extracting data from any websites using automated tools or software. The data is usually in the form of HTML, which is the markup language used to create websites. Web scraping involves parsing the HTML code of a website and then extracting specific data from it. The data can be structured or unstructured, and it can include text, images, videos, links, and other types of content.

- In this project I have scraped Flipkart for the customers feedback on various products such as rating, comments, product name, customer name & comment heading.

- The idea behind this project is to extracting the raw data(that is not human friendly to understand) by inspecting the website stepwise, and then beautifying it by using python Beautiful soup, and then structuring the collected data into a list to display in table format at
the review page/result page.

- Also I have Tried to dump the fetched details into a MongoDB database.

**Overview**
![Alt text](1.png)
![Alt text](2.png)
![Alt text]("C:\Users\risha\OneDrive\Pictures\Screenshots\Screenshot 2023-03-26 000402.png")