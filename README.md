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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: P.Hemasonica
RegisterNumber: 
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
  
''' 

ii)	# To find the maximum marks using the list method max().
```Python

Program to find the maximum marks using the list method max().
Developed by: P.Hemasonica
RegisterNumber: 22003246 
'''
def max_marks(list):
   max=list[0]
   for i in list:
       if i>max:
           max = i
   return max
max_marks([88,67,77,93,95,11,67,89,56,89])  

```

iii) # To find the maximum marks without using builtin functions.
```Python

''' 
Program to the maximum marks without using builtin functions.
Developed by: P.Hemasonica
RegisterNumber: 22003264
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large   

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![Screenshot (55)](https://user-images.githubusercontent.com/118361409/214353323-95603155-3c56-40eb-a613-1f841f00ea76.png)

![Screenshot (56)](https://user-images.githubusercontent.com/118361409/214353553-f97f4c55-e7dc-491e-862a-bf3b13492924.png)


![Screenshot (57)](https://user-images.githubusercontent.com/118361409/214353681-77870402-afa4-4d47-bf94-e087f6a5768d.png)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
