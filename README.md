# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>
get the independent variable XX and depenedent variable Y
### Step2
<br>
import pandas as np and  also import linear_model from sklearn module
### Step3
<br>
read the CSV file which should be attached to the code runner
### Step4
<br>
give the command to print
### Step5
<br>
end te program
## Program:

```
import pandas as pd
from sklearn import linear model
df=pd.read_csv('/content/drive/My Drive/car (1).csv')
x-df[['weight','Volume']]
y=df[['coz']]
regr=linear_model.linearRegression()
regr.fit(x,y)
print('coefficient:',regr.coef_)
print('Intercept:',regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))
```
## Output:
![image](https://github.com/23008859/Multivariate-Linear-Regression/assets/139117979/7da18817-671e-4d13-a7bd-41ade1b2ec3f)

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
