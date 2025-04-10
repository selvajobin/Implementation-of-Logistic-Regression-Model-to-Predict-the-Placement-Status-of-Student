# Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student

## AIM:
To write a program to implement the the Logistic Regression Model to Predict the Placement Status of Student.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import necessary libraries (pandas, LabelEncoder, train_test_split, etc.).
2. Load the dataset using pd.read_csv().
3. Create a copy of the dataset and drop unnecessary columns (sl_no, salary).
4. Check for missing and duplicate values using isnull().sum() and duplicated().sum().
5. Encode categorical variables using LabelEncoder() to convert them into numerical values. 

## Program:
```
/*
Program to implement the the Logistic Regression Model to Predict the Placement Status of Student.
Developed by: SELVA JOBIN S
RegisterNumber:  212223220102

import pandas as pd
pf=pd.read_csv("Placement_Data.csv")
pf.head()
pf1=pf.copy()
pf1=pf1.drop(['sl_no','salary'],axis=1)
pf1.head()
pf1.isnull().sum()
pf1.duplicated().sum()
x=pf1.iloc[:,:-1]
x
y=pf1["status"]
y
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)
from sklearn.metrics import accuracy_score,confusion_matrix,classification_report
accuracy=accuracy_score(y_test,y_pred)
accuracy
confusion=confusion_matrix(y_test,y_pred)
confusion
classification=classification_report(y_test,y_pred)
print(classification)
lr.predict([[1,80,1,9,1,1,90,1,0,85,1,85]])
*/
```

## Output:
![Screenshot 2025-03-28 123601](https://github.com/user-attachments/assets/800110c0-df4c-4271-bd92-d84d2022b4e3)

![Screenshot 2025-03-28 123613](https://github.com/user-attachments/assets/06c61909-785e-4b2d-9ffe-cbd8bd3e33d8)

![Screenshot 2025-03-28 123622](https://github.com/user-attachments/assets/63b43a33-c8a2-416c-bc0b-3fd5b8e377b9)

![Screenshot 2025-03-28 123635](https://github.com/user-attachments/assets/be43ef31-1dc7-4ecc-9798-f58dea38af50)


![Screenshot 2025-03-28 123733](https://github.com/user-attachments/assets/50cf020a-1aaf-43cf-beae-3641d03f9832)

![Screenshot 2025-03-28 123747](https://github.com/user-attachments/assets/16248e05-b308-4a94-a8fb-811bac016623)


![Screenshot 2025-03-28 123801](https://github.com/user-attachments/assets/9d393d35-b6dd-423e-801a-9d671f836402)


![Screenshot 2025-03-28 123815](https://github.com/user-attachments/assets/00a09ca2-c40f-493f-8bab-3ea562c03213)


![Screenshot 2025-03-28 123831](https://github.com/user-attachments/assets/2c98c677-db70-406f-b436-1d3729f51791)









## Result:
Thus the program to implement the the Logistic Regression Model to Predict the Placement Status of Student is written and verified using python programming.

