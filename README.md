## NAME : HASNA MUBARAK AZEEM
## REG NO : 212223240052
## DATE : 23/03/2024

# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:
DEVELOPED BY : HASNA MUBARAK AZEEM
REG NO:212223240052

i)	# To find the maximum of marks using the list method sort.
```PYTHON
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
    
```
ii)	# To find the maximum marks using the list method max().
```PYTHON
def max_marks(marks):
    large = max(marks)
    return large
```
iii) # To find the maximum marks without using builtin functions.

```PYTHON
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```

## Output 1:
![qqq1](https://github.com/hasnu0406/FindMaximum/assets/135305537/6ca8a918-e62e-4632-a221-71e12cc2337d)


## Output 2:
![qq2](https://github.com/hasnu0406/FindMaximum/assets/135305537/f10ebd1d-e898-41b4-ae5f-37ef29aa2894)

## Output 3:
![qq3](https://github.com/hasnu0406/FindMaximum/assets/135305537/c3f69235-6033-45ad-800d-e1c7edd56d02)





## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
