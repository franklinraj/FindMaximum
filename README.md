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
Developed by:FRANKLIN RAJ G 
RegisterNumber:23001518 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by:FRANKLIN RAJ G 
RegisterNumber:23001518 
'''
def max_marks(marks):
    large=max(marks)
    return large
    



```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by:FRANKLIN RAJ G 
RegisterNumber:23001518 
'''
def max_marks(list1):
    max =list1[0]
    for i in list1:
        if i > max:
            max=i
    return max



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-12-23 143207](https://github.com/franklinraj/FindMaximum/assets/148993740/0dd83368-79a3-4b01-bae2-517d8631ce33)
![Screenshot 2023-12-23 143351](https://github.com/franklinraj/FindMaximum/assets/148993740/bf73a975-d1a1-4202-87ef-ff05afed1167)
![Screenshot 2023-12-23 143411](https://github.com/franklinraj/FindMaximum/assets/148993740/aaa06166-a4e6-4fdc-bf5f-6d3a41de5ad8)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
