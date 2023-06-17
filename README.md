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
```
 
Program to mark the maximum of marks using the list method sort
Developed by: SANJAY S
RegisterNumber: 212222230132

def max_marks(marks):
    marks.sort()
    return marks[-1]
    return max



```

ii)	# To find the maximum marks using the list method max().
```
Developed by: SANJAY S
RegisterNumber: 212222230132

def max_marks(marks):
   maxi=max(marks)
   return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```
Developed by: SANJAY S
RegisterNumber: 212222230132


def max_marks(list1):
    l=list1[0]
    for i in list1:
        if i>l:
            l=i
    return l        
  


```
## input:
![image](https://github.com/22002102/FindMaximum/assets/119091638/934bfdd5-489f-47f0-8992-9fa06e10c43d)


## Output:


![image](https://github.com/22002102/FindMaximum/assets/119091638/db34f52d-d22e-41df-b10b-3f3914b4e318)






## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
