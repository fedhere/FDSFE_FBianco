  # READING: 
No reading this week

# ASSIGNMENT: 
follow the [notebook instructions in this folder ](https://github.com/fedhere/FDSFE_FBianco/blob/main/HW4/ExamScore_linear_regression.ipynb)

- add captions to the figures and tables of the notebook done in class

- Linear Regression tips: 

the notebook from the class with the linear regression examples is [here](https://github.com/fedhere/FDSFE_FBianco/blob/main/CodeExamples/Walking_Speed_linear_regression_in_detail.ipynb):
look at the **sklearn** part, that is the way I recommand you do it

tip: used a dataframe as input variable. 
- when you need to do a univariate linear regression make a dataframe with one column: e.g. `df[["Attendance"]]` : NOTE THE DOUBLE PARENTHESIS! `df[["Attendance"]]` a dataframe, it can be used as input to LinearRegression(); 
`df["Attendance"]` is a series, LinearRegression() would give an error that the dimension of the input is not correct

- when you do multivariate linear regression, your X variable will look for example `df[["Attendance", "Hours_Studied"]]`


- note: I am asking for a different plot than the plots done in the linear regression class. In class you were showing the dependent variable (y) vs the independent variable VS the prediction for y agains the independent variable. here you are showing  the prediction VS the dependent variable. if the prediction was perfect, the points would align along the diagonal of the plot. The code should look like:
  
```
y_prediction = model.predict(X)
plt.plot(y_prediction, y, '.') #this makes the scatter plot
plt.plot(y, y, "-") #this plots a diagonal line
```

## NOTE : FROM THIS WEEK ON you will be penalized if your Github repo has the wrong structure (e.g. missing folders for homeworks) and if your HW folder misses the README file

The readme file needs to state  in your own work

- what the homework was about 

- what you learned (one or two may take home points _for you_ from doing the exercise. Can be the analytical aspects or some practical method to do things)

- who you worked with

- what you contributed specifically into the group work (if this assignment was hard for you and you do not feel like you were leading any aspects of it that is ok! I am asking you to state this to ensure you do some introspection and check your progress throughout the course)
