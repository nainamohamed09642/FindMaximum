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
    return marks[-1]

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(list1):
    marks=list1[0]
    
    for i in range(1,len(list1)):
        if(marks<list1[i]):
           marks=list1[i]
    return marks

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/nainamohamed09642/FindMaximum/assets/151916360/d1af550c-096c-4b94-bdbe-c817bf668f04)
![image](https://github.com/nainamohamed09642/FindMaximum/assets/151916360/bea70384-3cd8-496d-83fd-6ff37fc0093f)
![image](https://github.com/nainamohamed09642/FindMaximum/assets/151916360/4eb74bf8-51c9-49cd-bfdc-d46a981eb251)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
