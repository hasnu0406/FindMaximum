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
![Screenshot 2024-03-24 154126](https://github.com/drgbhuvaneswari/FindMaximum/assets/135305537/5c84441e-fe6d-4951-b547-713de394db1b)
![Screenshot 2024-03-24 154144](https://github.com/drgbhuvaneswari/FindMaximum/assets/135305537/a8cfece2-608a-482c-83a0-7f2add6cf919)
![Screenshot 2024-03-24 154216](https://github.com/drgbhuvaneswari/FindMaximum/assets/135305537/639e9d6e-5279-404b-8202-710ec2f79f8b)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
