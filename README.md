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
Program to mark the maximum of marks using the list method sort
Developed by: VASANTHARAJ J
RegisterNumber: 23012935 
def max_marks(marks):
    large=max(marks)
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by:  vasanthraj j
RegisterNumber: 23012935 
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: vasantharaj j
RegisterNumber: 23012935
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        
```
## Sample Input and Output

## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/Vasanth2k4/FindMaximum/assets/147139769/2c9ea703-4ac0-4c1f-8415-f7a3284fc437)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/Vasanth2k4/FindMaximum/assets/147139769/1bcdda08-9d98-4040-af93-b24cdf760761)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Vasanth2k4/FindMaximum/assets/147139769/a1619cbf-86e1-4774-bcc2-b7b5d3acf769)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
