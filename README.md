# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 Include the necessary coding and corresponding screenshots
import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

marks = [13,45,63,78]

student=['ABC','QOR','EFB','TOB']

plt.plot(marks,student)

plt.xlabel('Marks')

plt.ylabel('Student Name')

plt.show()

student = ['A','B','C','D']

attendence = [90,85,73,88]

plt.plot(student,attendence)

plt.xlabel('Attendence')

plt.ylabel('student Name')

plt.show() 
<img width="739" height="755" alt="530485636-6d077d9b-6f0c-4aaa-9d40-b04382777754" src="https://github.com/user-attachments/assets/6a9f3fa8-daf1-42c7-8fd8-9f20e0eee080" />
x=[10,20,30,40,50]

y=[100,200,300,400,500]

plt.scatter(x,y,label='stars',color='green',marker='*',s=30)

plt.show() x=np.arange(0,15)

y=np.arange(0,15)

x

y plt.scatter(x,y,c='r')

plt.xlabel('X axis')

plt.ylabel('y axis')

plt.title('Scatter plot')

plt.show()
<img width="685" height="739" alt="530485664-4156ccde-dbfa-41d0-b373-45cd0cee3399" src="https://github.com/user-attachments/assets/fa5781d5-861c-404f-8150-f1a2a5d3e3c2" />
act=['eat','sleep','work','play']

slices=[3,7,8,6]

color=['r','y','g','b']

plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()

feedback=

['Good','excellent','Perfect','Ok'] slices=[4,10,3,8] color=['y','r','b','g']

plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()
act=['eat','sleep','work','play']

slices=[3,7,8,6]

color=['r','y','g','b']

plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()

feedback=

['Good','excellent','Perfect','Ok'] slices=[4,10,3,8] color=['y','r','b','g']

plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()



act=['eat','sleep','work','play']

slices=[3,7,8,6]

color=['r','y','g','b']

plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()

feedback=

['Good','excellent','Perfect','Ok'] slices=[4,10,3,8] color=['y','r','b','g']

plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()
act=['eat','sleep','work','play']

slices=[3,7,8,6]

color=['r','y','g','b']

plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()

feedback=

['Good','excellent','Perfect','Ok'] slices=[4,10,3,8] color=['y','r','b','g']

plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')

plt.legend()

plt.show()

<img width="705" height="689" alt="530485694-6411a633-8d54-4f45-9f9a-95210cef08dc" src="https://github.com/user-attachments/assets/ff77a035-57b5-46ef-8989-1dc3dcb6bfdf" />

x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]

y2 = [5, 7, 9, 11, 13]

y3 = [2, 4, 6, 8, 10]

plt.fill_between(x, y1, color='blue')

plt.fill_between(x, y2, color='green')

plt.plot(x, y1, color='red')

plt.plot(x, y2, color='black')

plt.legend(['y1','y2'])

plt.show() 
<img width="619" height="358" alt="530485712-3fbbfb0b-3079-444d-ba2b-4b8187d6a6d0" src="https://github.com/user-attachments/assets/d64ed655-ac78-45fd-9c89-95942c48add3" />
height = [10, 24, 36, 40, 5]

names = ['one', 'two', 'three', 'four', 'five']

c1=['red', 'green']

c2=['b', 'g']

plt.bar (names, height, width=0.8, color=c1)

plt.xlabel('x - axis')

plt.ylabel('y - axis')

plt.title('My bar chart!')
<img width="548" height="401" alt="530485794-6d41c5e2-1a73-4f98-80e2-e0570254482e" src="https://github.com/user-attachments/assets/c140e910-8687-444d-910b-1ba2931a0933" />
[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]

plt.hist(x, bins = 10, color='blue', alpha=0.5)

plt.show()
<img width="532" height="349" alt="530485815-71cf1d4d-51a0-4679-8881-4248896c23e0" src="https://github.com/user-attachments/assets/02282550-6dde-4a00-9f10-d625625b7f13" />
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)

data
<img width="637" height="371" alt="530485828-c93505b5-35d9-4dc4-85f9-502248a79bc9" src="https://github.com/user-attachments/assets/cc551e7b-5331-4603-920c-b0bb553dbc51" />
fig, ax= plt.subplots()

ax.boxplot(data)

ax.set_xlabel('Data')

ax.set_ylabel('Values')

ax.set_title('Box Plot')
<img width="612" height="425" alt="530485850-5712acd7-c5e4-416d-bde8-2a73752b54a7" src="https://github.com/user-attachments/assets/5ce61140-4505-41b4-8db5-0cbc85d3d725" />
# Result:
 thus,the codes are executed successfully
 
