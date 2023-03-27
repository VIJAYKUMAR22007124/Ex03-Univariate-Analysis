# Ex03-Univariate-Analysis

CODE:
```
import pandas as pd
df = pd.read_csv('SuperStore.csv')
df1 = pd.read_csv('diabetes.csv')
print(pd.DataFrame(df))
print(pd.DataFrame(df1))

print(df.info())

print(df.describe())

print(df.dtypes)

print(df['Region'].value_counts())

import seaborn as sns
sns.boxplot(x = "Postal Code" , data = df)

sns.countplot(x = 'BloodPressure' , data = df1)

sns.displot(df1['Glucose'])

sns.displot(x = 'Age' , data = df1)

sns.boxplot(x = "Sales",data=df)

df1['BMI'].value_counts()

OUTPUT:
 ```

![Screenshot (245)](https://user-images.githubusercontent.com/119657657/227956991-96a599dd-5f46-41ce-b552-c60a040fc2a0.png)

![Screenshot (246)](https://user-images.githubusercontent.com/119657657/227957174-b881ec5b-29ee-4d71-b4c1-a1e6ab555583.png)

![Screenshot (247)](https://user-images.githubusercontent.com/119657657/227957255-184d5304-f15f-496b-8078-99b4cf819286.png)

![Screenshot (248)](https://user-images.githubusercontent.com/119657657/227957356-eb0fa181-da3f-47f3-8bee-8bd6ef577ccb.png)

![Screenshot (249)](https://user-images.githubusercontent.com/119657657/227957435-c8cf91e1-308a-40c4-853e-c76415c92fdc.png)

![Screenshot (250)](https://user-images.githubusercontent.com/119657657/227957525-41f752aa-c350-493f-a506-209557ada9b2.png)

```


 
