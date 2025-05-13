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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):
    maximum=marks[0]
    for i in marks:
        if(i>maximum):
            maximum=i
    return maximum 
```
Program developed by : NIHITHA RANI B

Register No : 23012494


## Output:
![image](https://github.com/user-attachments/assets/741cd0ae-05a3-4252-be2d-0f9f62edc5ab)
![image](https://github.com/user-attachments/assets/42eda6db-3130-4c6d-aab6-401d8baae2b3)
![image](https://github.com/user-attachments/assets/7e2de1f0-65f2-4e82-9ab2-e0e586f0b68e)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
