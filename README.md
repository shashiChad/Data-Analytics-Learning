# Data-Analytics-Learning
DAY:01 
1) What is Data  ? 
=> In data analytics, data refers to the raw information collected from   various sources that is processed and analyzed to extract  insights,patterns or trends that support decision making.
 Types of data:-
Structured Data :- Stored in rows and column. Ex:- transcation details,customer details
Unstructured Data :- Do not follow a specific format. Ex:- emails,social media posts,video,audio
Semi-structured data :- It has some structure. Ex:- JSON,XML

2) What is Data Analytics ?
=>  It is the process of collecting,organizing,cleaning and analyzing data.
3) What is Data Science ?
=>  It is define as the data to extract meaningful insights for decision-making using analytical, statistical, and programming techniques.

4) Difference between Data analytics and Data science ?
=>         Data analytics:- 
   Focuses on analyzing existing data to find trends, patterns, and insights.
   Primarily deals with data processing, statistical analysis, and reporting.
   Excel, SQL, Power BI, Tableau, Python (for analysis), etc.

    Data Science:-
  A field that involves extracting insights and building predictive models using data. 
   data collection, cleaning, analysis, modeling, and deployment.
   Machine Learning, Deep Learning, Predictive Modeling.
    Python, R, TensorFlow, Hadoop, Spark, SQL, etc.

5) Types of Data ?
 Structured Data :- Data organized in rows and columns. Ex:- SQL databases, spreadsheets.
Unstructured Data:- No predefined format. Ex:- social media posts, images
Semi-Structured Data:- Partially organized, not in traditional databases. Ex:- JSON, XML, HTML

6) Types of Data analytics ?
 Descriptive Analysis:- What happened?. Ex:- Monthly sales reports, website traffic summary.
 Diagnostic Analysis:- Why did it happen?. Ex:- Investigating why sales dropped last quarter
 Predictive Analysis:- What is likely to happen?. Ex:- stock price forecasting.
 Prescriptive Analysis:- What should we do?. Ex:- Recommending product pricing

7) Types of learning in AI/ML ?
Supervised Learning :- It is used for Classification & regression problems. Ex:- Email spam detection 
Unsupervised Learning:- Discover hidden patterns or groupings. Ex:- Customer segmentation
 Reinforcement Learning:- Learn a strategy to maximize cumulative reward over time. Ex:- Robotics 

8) Mean,Median & Mode in data analysis ?
Mean :- 
    Formula :- Mean=Number of values / Sum of all values​ 
     Ex:- Data = [10, 20, 30, 40]
            Mean = (10 + 20 + 30 + 40) / 4 = 25


Median:- 
           The middle value when data is arranged in order. Ex:-
                    Data = (10, 20, 30, 40, 50) → Median = 30
Mode :- 
                The value that appears most frequently in the dataset.
                 Ex:- Data = (2, 4, 4, 6, 8) → Mode = 4

DAY:- 02

1) Difference between ILOC & LOC ?
=>    ILOC :- 
Integer-based (0, 1, 2...)
Like NumPy array indexing
Boolean Not supported directly

    LOC:-
Label-based ('x', 'y', 'z')
Not like Numpy array indexing
Boolean supported directly.

2) What is zeros,ones,eye,arrange,linspace ?
=>    Zeros:- ( )
         Creates an array filled with 0s.
          Syntax:-
          numpy.zeros(shape) ex:- import numpy as np
                                                   a = np.zeros((2, 3))
                                                    print(a)
            o/p:-
             [[0. 0. 0.]
              [0. 0. 0.]]

     Ones:-
      Creates an array filled with 1s.
       Ex:-
       b = np.ones((3, 2))
       print(b)
     
      O/p:-
        [[1. 1.]
         [1. 1.]
         [1. 1.]]

EYE:-
Creates an identity matrix (diagonal elements are 1, others are 0).
 Ex:- 
c = np.eye(3)
print(c)
 O/p:-
[[1. 0. 0.]
 [0. 1. 0.]
 [0. 0. 1.]]

Arrange:-
Creates an array with values from start to end (step).Similar to Python's range() but returns a NumPy array.
Ex:- 
d = np.arange(1, 10, 2)
print(d)
 O/p:-
[1 3 5 7 9]

Linspace:-
Creates an array with evenly spaced values between start and stop.
Ex:-
e = np.linspace(0, 1, 5)
print(e)

O/p:-
[0.   0.25 0.5  0.75 1.  ]


3) If one string are present then how to convert all int into string ?
=>    If one value are string and to convert all int into string 
         Ex:- 
         df['column_name'] = df['column_name'].astype(str) (convert column into string)
          df = df.astype(str) (convert dataframe into string )


4) How to filter data type ?
=>      In data analytics, especially when working with Pandas in Python, filtering by data type is a common task—for example, selecting only numeric columns, or only object (string) columns, etc.
 Ex:- 
 #  Filter only numeric columns (int, float)
numeric_df = df.select_dtypes(include=['number'])

#  Filter only integer columns
int_df = df.select_dtypes(include=['int'])

# Filter only float columns
float_df = df.select_dtypes(include=['float'])

DAY:- 03



