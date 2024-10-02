  # READING: 
No reading this week

# ASSIGNMENT: 
follow the notebook instructions in this folder 
- add captions to the figures and tables of the notebook done in class

- Linear Regression tips: 

the notebook from the class with the linear regression examples is [here](https://github.com/fedhere/FDSFE_FBianco/blob/main/CodeExamples/Walking_Speed_linear_regression_in_detail.ipynb):
look at the **sklearn** part, that is the way I recommand you do it

tip: used a dataframe as input variable. 
- when you need to do a univariate linear regression make a dataframe with one column: e.g. `df[["Attendance"]]` : NOTE THE DOUBLE PARENTHESIS! `df[["Attendance"]]` a dataframe, it can be used as input to LinearRegression(); 
`df["Attendance"]` is a series, LinearRegression() would give an error that the dimension of the input is not correct

- when you do multivariate linear regression, your X variable will look for example df[["Attendance", "Hours_Studied"]]


## NOTE : FROM THIS WEEK ON you will be penalized if your Github repo has the wrong structure (e.g. missing folders for homeworks) and if your HW folder misses the README file

The readme file needs to state  in your own work

- what the homework was about 

- what you learned (one or two may take home points _for you_ from doing the exercise. Can be the analytical aspects or some practical method to do things)

- who you worked with

- what you contributed specifically into the group work (if this assignment was hard for you and you do not feel like you were leading any aspects of it that is ok! I am asking you to state this to ensure you do some introspection and check your progress throughout the course)
