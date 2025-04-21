# EXNO2DS
# AIM:
      To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:

  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

dt = pd.read_csv("/content/titanic_dataset.csv")

dt

![Screenshot 2025-04-21 210437](https://github.com/user-attachments/assets/772cb10d-585a-43ff-8eb3-28782d51393f)
![Screenshot 2025-04-21 210448](https://github.com/user-attachments/assets/4e9bdca1-e965-406a-a028-13b6504eac37)
![Screenshot 2025-04-21 210459](https://github.com/user-attachments/assets/6aa9cc05-7c3c-4e82-b53e-97fb88a2d8f9)
![Screenshot 2025-04-21 210510](https://github.com/user-attachments/assets/cd1624be-3fe8-405c-9467-a3d0960d7898)

![Screenshot 2025-04-21 210521](https://github.com/user-attachments/assets/70850633-96d9-4a61-96f0-2ed550b4f2cb)

![Screenshot 2025-04-21 210532](https://github.com/user-attachments/assets/d6ae66ce-98d8-4704-ab0a-d94e3d42ffaa)

![Screenshot 2025-04-21 210546](https://github.com/user-attachments/assets/6c01736f-1d96-4a3e-abec-1a2c007200e8)

![Screenshot 2025-04-21 210559](https://github.com/user-attachments/assets/69b3c676-1887-4f78-8fbf-06ce482fad2e)

![Screenshot 2025-04-21 210921](https://github.com/user-attachments/assets/5fb80e7a-a49b-4ca4-9e76-00bc1ddc7385)

![Screenshot 2025-04-21 210935](https://github.com/user-attachments/assets/1c9d516f-2ed8-4a4e-8ac8-25d7479bdc99)

![Screenshot 2025-04-21 211006](https://github.com/user-attachments/assets/e7c1dabf-ab13-4c98-8296-6f52e0e2bb12)

![Screenshot 2025-04-21 211019](https://github.com/user-attachments/assets/6a984a40-500c-419c-b0f5-06b5945a9a8b)

![Screenshot 2025-04-21 211028](https://github.com/user-attachments/assets/fb63c3c8-f8ef-4c59-8b77-118b932db64d)

![Screenshot 2025-04-21 211040](https://github.com/user-attachments/assets/cbdf9276-8d09-4322-ab5c-46a7b035943d)

![Screenshot 2025-04-21 211054](https://github.com/user-attachments/assets/d99beddf-97ef-42dc-a0be-ad3f97c16d12)

![Screenshot 2025-04-21 211103](https://github.com/user-attachments/assets/4d4e9692-81f4-4912-a264-342e4c395f6b)

![Screenshot 2025-04-21 211145](https://github.com/user-attachments/assets/cc5c46bd-dbc5-4cae-b67d-272447fbbe4e)

# RESULT
Performed explanatory Data Analysis on the given data set.
