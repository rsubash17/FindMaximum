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
```''' 
Program to mark the maximum of marks using the list method sort
Developed by: SUBASH R
RegisterNumber: 23003821
'''
def max_marks(marks):
    marks.sort()
    lar=marks[-1]
    return lar
```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: SUBASH R
RegisterNumber: 23003821
'''
def max_marks(marks):
    lar=max(marks)
    return lar
```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: SUBASH R
RegisterNumber:23003821
'''
def max_marks(marks):
    lar=max(marks)
    return lar
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-12-25 122232](https://github.com/rsubash17/FindMaximum/assets/147139828/37ab61f7-88e7-46af-bee0-6e6bded5238d)
![image](https://github.com/rsubash17/FindMaximum/assets/147139828/adf57d06-f540-4005-ae84-9b9572debfd2)
![Screenshot 2023-12-25 122309](https://github.com/rsubash17/FindMaximum/assets/147139828/f8a6c5ca-3020-42fb-8f4e-336438f2cf5f)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
