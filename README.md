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
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```
```

x = [1, 2, 3, 4, 5]
y = [3, 6, 2, 7, 1]
plt.plot(x,y,label='line1')
```
![image](https://github.com/user-attachments/assets/62c39aa2-846d-4575-9303-ed22e6d93341)
```
x1=[1,2,3]
y1=[2,4,1]
x2=[1,2,3]
y2=[4,1,3]

x1=[1,2,3]
y1=[2,4,1]
x2=[1,2,3]
y2=[4,1,3]
```
```

plt.plot(x1,y1,label='line1')
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/886d9fac-6573-4d7e-9716-17bb7f31744f)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
plt.title('Some cool customizations!')
plt.show()
```
![image](https://github.com/user-attachments/assets/1bba3ee4-2c89-492f-9c63-42c56e7fa13f)
```
yiled_apples=[0.895,0.91,0.919,0.926,0.931]
plt.plot(yiled_apples)
```
![image](https://github.com/user-attachments/assets/cdc08024-e902-4622-9da8-9bdcf011454d)
```
years=[2010,2012,2013,2014,2015]
yiled_apples=[0.895,0.91,0.919,0.926,0.931]
plt.plot(years,yiled_apples)
```
![image](https://github.com/user-attachments/assets/d68ffde9-a385-421f-aa62-ad064646f74e)
```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);
```
![image](https://github.com/user-attachments/assets/2bc14902-7f7f-40a8-8018-c0f1f6d891e2)
```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);
```
![image](https://github.com/user-attachments/assets/257c5aec-36d6-43f5-9199-fc6b40c5dd2b)
```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```
![image](https://github.com/user-attachments/assets/2e463686-0e77-40d8-9fdc-d5de36fe50a5)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
#x array([0,1,2,3,4,5,6,7,8,9])
#y array([11,12,13,14,15,16,17,18,19,20])

plt.scatter(x,y,c='r')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Scatter Plot')
plt.savefig('Test.png')
plt.scatter(x,y,c='r')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Scatter Plot')
plt.savefig('Test.png')


```
![image](https://github.com/user-attachments/assets/6b4ee22f-2c4b-4375-ad33-83281106d1d0)
```
y=x*x
#y array([ 0,  1,  4,  9, 16, 25, 36, 49, 64, 81])
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.tittle('2d diagram')
plt.legend(['y-values']);
```
![image](https://github.com/user-attachments/assets/e6872eac-eb8c-471e-84c1-4adb562be3d0)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![image](https://github.com/user-attachments/assets/6a2c0102-0806-4abf-b67c-eb1111ea262b)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')

plt.fill_between(x,y2,color='green')
plt.show()
```
![image](https://github.com/user-attachments/assets/589ac76a-82d0-4867-943b-6cfeec787869)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]

plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/user-attachments/assets/6e00323b-a113-4204-97c8-756968ae8a7d)

```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![image](https://github.com/user-attachments/assets/70a37470-53c4-4d79-afdf-22dd2b4d404f)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')

plt.xlabel('X axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/07ec45ff-27a5-4c4e-a98e-61ff7bbc1e03)

```
import matplotlib.pyplot as plt 
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40] 
range=(0,100) 
bins=10 
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8) 
plt.xlabel('age') 
plt.ylabel('No. of people') 
import matplotlib.pyplot as plt 
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40] 
range=(0,100) 
bins=10 
plt.hist(ages,bins=bins,range=range,color='green',histtype='bar',rwidth=0.8) 
plt.xlabel('age') 
plt.ylabel('No. of people') 
plt.title('My histogram') 
plt.show()
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
```
![image](https://github.com/user-attachments/assets/41e968f2-4ff5-408c-a822-d5d3d4038222)

![image](https://github.com/user-attachments/assets/cacd573c-8bc5-477b-bdfd-8cdda025bb5d)
```

import matplotlib.pyplot as plt import numpy as np np.random.seed(0) data=np.random.normal(loc=0,scale=1,size=100) data
  array([ 1.76405235,  0.40015721,  0.97873798,  2.2408932 ,  1.86755799,        -0.97727788,  0.95008842, -0.15135721, -0.10321885,  0.4105985 ,
        0.14404357,  1.45427351,  0.76103773,  0.12167502,  0.44386323,
        0.33367433,  1.49407907, -0.20515826,  0.3130677 , -0.85409574,        -2.55298982,  0.6536186 ,  0.8644362 , -0.74216502,  2.26975462,
       -1.45436567,  0.04575852, -0.18718385,  1.53277921,  1.46935877,
        0.15494743,  0.37816252, -0.88778575, -1.98079647, -0.34791215,
        0.15634897,  1.23029068,  1.20237985, -0.38732682, -0.30230275,        -1.04855297, -1.42001794, -1.70627019,  1.9507754 , -0.50965218,
       -0.4380743 , -1.25279536,  0.77749036, -1.61389785, -0.21274028,
       -0.89546656,  0.3869025 , -0.51080514, -1.18063218, -0.02818223,         0.42833187,  0.06651722,  0.3024719 , -0.63432209, -0.36274117,        -0.67246045, -0.35955316, -0.81314628, -1.7262826 ,  0.17742614,
       -0.40178094, -1.63019835,  0.46278226, -0.90729836,  0.0519454 ,         0.72909056,  0.12898291,  1.13940068, -1.23482582,  0.40234164,        -0.68481009, -0.87079715, -0.57884966, -0.31155253,  0.05616534,
       -1.16514984,  0.90082649,  0.46566244, -1.53624369,  1.48825219,         1.89588918,  1.17877957, -0.17992484, -1.07075262,  1.05445173,        -0.40317695,  1.22244507,  0.20827498,  0.97663904,  0.3563664 ,
        0.70657317,  0.01050002,  1.78587049,  0.12691209,  0.40198936])
fig,ax=plt.subplots() ax.boxplot(data) ax.set_xlabel('Data') ax.set_ylabel('Values') ax.set_title('Box Plot') Text(0.5, 1.0, 'Box Plot')
```

![image](https://github.com/user-attachments/assets/477e9e0c-3f0d-46a3-be32-9ea37f8bf71a)



















 Include the necessary coding and corresponding screenshots

# Result:

 Thus, The implementation of data visualization using matplotlib has been successfully verified.
