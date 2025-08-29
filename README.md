# Implementation of Univariate Linear Regression
## AIM:
To implement univariate Linear Regression to fit a straight line using least squares.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Get the independent variable X and dependent variable Y.
2. Calculate the mean of the X -values and the mean of the Y -values.
3. Find the slope m of the line of best fit using the formula. 
<img width="231" alt="image" src="https://user-images.githubusercontent.com/93026020/192078527-b3b5ee3e-992f-46c4-865b-3b7ce4ac54ad.png">
4. Compute the y -intercept of the line by using the formula:
<img width="148" alt="image" src="https://user-images.githubusercontent.com/93026020/192078545-79d70b90-7e9d-4b85-9f8b-9d7548a4c5a4.png">
5. Use the slope m and the y -intercept to form the equation of the line.
6. Obtain the straight line equation Y=mX+b and plot the scatterplot.

## Program:
```
/*
import numpy as np
import matplotlib.pyplot as plt
X=np.array([3.6,4.8,7.2,6.9,10.7,6.1,7.9,9.5,12.7])
Y=np.array([9.3,10.2,11.5,12,13.6,13.2,10.8,22.7,-1.5])
Xmean=np.mean(X)
Ymean=np.mean(Y)
num=0
denom=0
for i in range(len(X)):
    num+=(X[i]-Xmean)*(Y[i]-Ymean)
denom+=(X[i]-Xmean)**2
m=num/denom
b=Ymean-m*Xmean
print("Name: SANJAY KUMAR B")
print("Register No: 212224230242")
print("Slope:",m)
print("Y intercept:",b)
ypred=m*X+b
print("Predicted Values:",ypred)
plt.scatter(X,Y)
plt.plot(X,ypred,color='green')
plt.show()
Developed by: SANJAY KUMAR B
RegisterNumber:  212224230242
*/
```

## Output:
<img width="1150" height="741" alt="image" src="https://github.com/user-attachments/assets/2ce8050e-72e4-4138-b0b8-808dec7d7e04" />



## Result:
Thus the univariate Linear Regression was implemented to fit a straight line using least squares using python programming.
