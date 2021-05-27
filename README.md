# mltask1
creat a marks predictor ML model
import numpy
import pandas as pd
from sklearn.linear_model import LinearRegression
data=pd.read_csv('marks.csv')
y=data['score']
x=data['hrs']
x=x.values.reshape(4,1)
model=LinearRegression()
p=int(input("enter hr to get marks:  ")
value=model.predict([[p]])
print(value)
