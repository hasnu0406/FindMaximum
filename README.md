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



## Output:
![Screenshot 2024-03-24 154216](https://github.com/drgbhuvaneswari/FindMaximum/assets/135305537/71e6af2b-c242-47f7-91b1-c8f3f1dbd2f7)
![Screenshot 2024-03-24 154144](https://github.com/drgbhuvaneswari/FindMaximum/assets/135305537/d2ee98f0-cf03-470d-a6df-5930d795c5d7)
![Screenshot 2024-03-24 154216](https://github.com/drgbhuvaneswari/FindMaximum/assets/135305537/8e82e272-1380-480f-b438-d39d71e0135f)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
