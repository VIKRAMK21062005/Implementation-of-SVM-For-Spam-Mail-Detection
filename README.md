# Implementation-of-SVM-For-Spam-Mail-Detection

## AIM:
To write a program to implement the SVM For Spam Mail Detection.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import the required packages.

2.Import the dataset to operate on.

3.Split the dataset.

4.Predict the required output.

5.End the program.

## Program:
```
/*
Program to implement the SVM For Spam Mail Detection..
Developed by: VIKRAM K
RegisterNumber:  212222040180
*/
```
```
/*
import pandas as pd
data=pd.read_csv("spam.csv",encoding='latin-1')
data.head()
data.info()data.isnull().sum

x=data["v1"].values
y=data["v2"].values

from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)

from sklearn.feature_extraction.text import CountVectorizer
cv=CountVectorizer()

x_train=cv.fit_transform(x_train)
x_test=cv.transform(x_test)

from sklearn.svm import SVC
svc=SVC()
svc.fit(x_train,y_train)
y_pred=svc.predict(x_test)
y_pred

from sklearn import metrics
accuracy=metrics.accuracy_score(y_test,y_pred)
accuracy
*/
```
## Output:

## DATA HEAD:

![image](https://github.com/VIKRAMK21062005/Implementation-of-SVM-For-Spam-Mail-Detection/assets/120624033/570e6114-4c48-41d5-ac2a-ef30130ab0eb)

## DATA.isnull().Sum()

![image](https://github.com/VIKRAMK21062005/Implementation-of-SVM-For-Spam-Mail-Detection/assets/120624033/f6c68a14-012e-4277-9a8e-2cbec7197e4a)

## Y.Pred():

![image](https://github.com/VIKRAMK21062005/Implementation-of-SVM-For-Spam-Mail-Detection/assets/120624033/de7c7b34-0a1c-46ef-bb7c-26335682ed62)

## Accuracy:

![image](https://github.com/VIKRAMK21062005/Implementation-of-SVM-For-Spam-Mail-Detection/assets/120624033/bf806ce0-9818-417a-a688-cea985d3d763)

## Result:
Thus the program to implement the SVM For Spam Mail Detection is written and verified using python programming.
