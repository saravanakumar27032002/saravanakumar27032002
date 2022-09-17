- 👋 Hi, I’m @saravanakumar27032002
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
saravanakumar27032002/saravanakumar27032002 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Loading...
Assignment_1.ipynb
Assignment_1.ipynb_
Basic Python
1. Split this string
[ ]
s = "Hi there Sam!"
[ ]
s.split()
['Hi', 'there', 'Sam!']
2. Use .format() to print the following string.
Output should be: The diameter of Earth is 12742 kilometers.
[ ]
planet = "Earth"
diameter = 12742
[ ]
print(f"The diameter of {planet} is {diameter} kilometers")
The diameter of Earth is 12742 kilometers
3. In this nest dictionary grab the word "hello"
[ ]
d = {'k1':[1,2,3,{'tricky':['oh','man','inception',{'target':[1,2,3,'hello']}]}]}
[ ]
list(d.values())[0][3]['tricky'][3]['target'][3]
Numpy
[ ]
import numpy as np
4.1 Create an array of 10 zeros?
4.2 Create an array of 10 fives?
[ ]
np.zeros(10)
array([0., 0., 0., 0., 0., 0., 0., 0., 0., 0.])
[ ]
np.ones(10)*5
array([5., 5., 5., 5., 5., 5., 5., 5., 5., 5.])
5. Create an array of all the even integers from 20 to 35
[ ]
np.arange(20, 35, 2)
array([20, 22, 24, 26, 28, 30, 32, 34])
6. Create a 3x3 matrix with values ranging from 0 to 8
[ ]
np.arange(0, 9).reshape(3, 3)
array([[0, 1, 2],
       [3, 4, 5],
       [6, 7, 8]])
7. Concatenate a and b
a = np.array([1, 2, 3]), b = np.array([4, 5, 6])
[ ]
a = np.array([1, 2, 3])
b = np.array([4, 5, 6])
np.concatenate((a, b), axis=None)
array([1, 2, 3, 4, 5, 6])
Pandas
8. Create a dataframe with 3 rows and 2 columns
[ ]
import pandas as pd
[ ]
data = [['Saravana', 21], ['Sharvesh', 21], ['Siva Rohit', 20]]
df = pd.DataFrame(data, columns=['Name', 'Age'])
df
9. Generate the series of dates from 1st Jan, 2023 to 10th Feb, 2023
[ ]
dates = pd.date_range('01/01/2023', '10/02/2023')
pd.DataFrame(dates)
10. Create 2D list to DataFrame
lists = [[1, 'aaa', 22], [2, 'bbb', 25], [3, 'ccc', 24]]

[ ]
lists = [[1, 'aaa', 22], [2, 'bbb', 25], [3, 'ccc', 24]]
[ ]
df = pd.DataFrame(lists)
df
Colab paid products - Cancel contracts here
