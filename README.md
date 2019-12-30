# Data_Analyst_Nanodegree
**Record projects completed for this Nanodegree. Skills practiced include but not limited to: Anaconda, jupyter notebook, Python, pandas, Numpy, Matplotlib, seaborn, linear/logistic regression models**

## Project 2: Investigate the Dataset of Doctor Appointments

The dataset I am analyzing for this project has recorded information from 110k medical appointments in Brazil. Each medical appointment has 14 associated variables and the most important one is the last variable called No-show which tells if the patients show-up to their appointment. We should be careful with this column, since it says "No" if the patient showed up to their appointment, and "Yes" if they didn't. Most variable names are quite self-explanatory. Particular explanations are provided:

1) "ScheduledDay" tells us on what day the patient set up their appointment.
2) "Neighborhood" indicates the location of the hospital.
3) "Scholarship" indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família. For more information, please see: https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia 
4) "SMS_received" tells us if a patient gets a message reminder about the schedule appointments or not

The main purpose of my analysis is to identify among these associated variables, what factors are important for  us to know in order to predict whether a patient will show up for the scheduled appointment.

##  Project 3: Analyze A/B Test Results

This project will assure I have mastered the subjects covered in the statistics lessons. 

### Table of Contents
- [Introduction](#intro)
- [Part I - Probability](#probability)
- [Part II - A/B Test](#ab_test)
- [Part III - Regression](#regression)


A/B tests are very commonly performed by data analysts and data scientists. For this project, I will be working to understand the results of an A/B test run by an e-commerce website. My goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

##  Project 4: Wrangle, Analyze and Visualize Tweet Archive of Twitter User WeRateDogs

This project has two parts. Firstly, I will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. 

After gather and clean WeRateDogs Twitter data, I have then obtained a well structured DataFrame containing basic tweet data for 1870 records of their original tweets with dog pictures. Four interesting insights have been produced by analyzing above information.


## Project 5: Pisa Data Exploration by Visualization and Communication with Slideshow

### Dataset

The initial Pisa dataset contains 485490 PISA assessment with 636 features (reading, math and science related), representing about 28 million 15-year-olds globally for year 2012. The original dataset can be found on Udacity host network (https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip) with feature documentation available as well (https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv).
Upon investigation, I have chosen 15 features of interest, including country, gender,students' attitude towards school and study as well as some math related variables, for deeper analysis. These extracted records have been stored in Pisa_result.csv file available on my github profile (https://github.com/Ying1002/Data_Analyst_Nanodegree/blob/master/P5_communicate_PISA_findings/Pisa_result.csv).

### Summary of Findings

In the exploration, I have mainly sought after the variables: students' sense of belonging to school and out-of-school learning time as well as what factors can possibly affect these two variables. I found out then students' attitude towards school learning and teacher-student relations have the strongest impact upon students' sense of belonging to school.No math-associated variables found to be relevant with students' sense of belonging to school, but those features are all heavily correlated with each other.

While no particular relationship could be verified between students' out-of-school learning time and sense of belonging to school or any other feature in this dataset, something interesting has been discovered upon investigating the categorical features of gender and residing country. Students from OECD countries generally report higher sense of belonging to school, but meanwhile shorter out-of-school study time, compared to their peers from Non-OECD countries.Female students in this dataset also report slightly higher sense of belonging to school and out-of-school study time than their male counterparts.

Despite of the multivariate exploration, I still couldn't find any obvious relationship between students' out-of-school learning time and any other feature in this dataset. But I have confirmed that the three variables of students' attitude towards school learning, sense of belonging to school and teacher-student relations are highly correlated with each other.

### Key Insights for Presentation

For the presentation, I focus on just the influence of students' attitude towards school learning and teacher-student relations on students' sense of belonging to achool and leave out most of the intermediate derivations. I started by analyze the distribution of every single variable of interest, followed by 2D scatter plotting to verify the strong relationship between students' sense of belonging to achool and their attitude towards school learning, teacher-student relations. It's even clear from 3D scatter plotting that as students' attitude towards school learning increases, sense of belonging to school also increases, do does teacher-student relations.

Afterwards, I used boxplot to show the finding that students from OECD countries generally report higher sense of belonging to school, but meanwhile shorter out-of-school study time, compared to their peers from Non-OECD countries.Throughout the presentation I've made sure to use different color palettes for each different variable to distinguish one from another.
