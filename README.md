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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: SANJAY S
RegisterNumber: 212222230132
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large




```

ii)	# To find the maximum marks using the list method max().
```
Developed by: SANJAY S
RegisterNumber: 212222230132
def max_marks(marks):
   large = max(marks)
   return large


```

iii) # To find the maximum marks without using builtin functions.
```
Developed by: SANJAY S
RegisterNumber: 212222230132
def max_marks(list1):
    
   max=list1[0]
   for i in list1:
       if i >max:
           max=i
   return max


```
## Sample Input and Output
![image](https://github.com/22002102/FindMaximum/assets/119091638/626e749c-c9dc-4d57-94b8-30db68fb9698)


![image](https://github.com/22002102/FindMaximum/assets/119091638/f95abbef-faf7-4300-844c-7dbedd280721)


![image](https://github.com/22002102/FindMaximum/assets/119091638/5b03c14d-2f2d-493b-b078-86ffdb7ba800)


## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
