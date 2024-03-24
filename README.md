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

i)	# To find the maximum of marks using the list method sort.
```Python

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num


```



## Output 1:
<img width="957" alt="Screenshot 2024-03-24 161637" src="https://github.com/hasnu0406/FindMaximum/assets/135305537/86360ba5-1d76-4ca1-83ac-e3d54dcf16dd">

## Output 2:
<img width="903" alt="Screenshot 2024-03-24 161646" src="https://github.com/hasnu0406/FindMaximum/assets/135305537/36f8c741-7dd7-42bd-a47c-1a6fd94aa0fb">

## Output 3:
<img width="911" alt="Screenshot 2024-03-24 161656" src="https://github.com/hasnu0406/FindMaximum/assets/135305537/673ff5b0-e0fc-4ed8-ab67-b7112bbca230">




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
