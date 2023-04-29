# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## STEP1   
Get the list of marks as input
## STEP2   
Use the sort() function or max() function or use the for loop to find the maximum mark.
## STEP3   
Return the maximum value
## Program:

 - ## To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: KISHORE.B
RegisterNumber: 212222110020
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

 - ## To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by:KISHORE.B 
RegisterNumber: 212222110020
'''
def max_marks(marks):
    large=max(marks)
    return large
```

 - ## To find the maximum marks without using builtin functions.
``` 
Program to the maximum marks without using builtin functions.
Developed by: KISHORE.B
RegisterNumber: 212222110020
def max_marks(list1):
    max=list1[0]
    for i in  list1:
        if i > max:
            max=i
    return max
```
## Output:
 - ## To find the maximum of marks using the list method sort.   
![Screenshot 2023-04-29 082037](https://user-images.githubusercontent.com/121484538/235280518-767b795d-88cb-4668-93ba-3c737981b6c9.png)
 - ## To find the maximum marks using the list method max().   
![Screenshot 2023-04-29 082058](https://user-images.githubusercontent.com/121484538/235280537-eeb46232-2952-4172-a774-ac169ad953ff.png)
 - ## To find the maximum marks without using builtin functions.   
![Screenshot 2023-04-29 082124](https://user-images.githubusercontent.com/121484538/235280614-841d7138-3fd7-4129-8074-6dc00f07958d.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
