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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Naveen kumar V
RegisterNumber: 23000827
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
    

ii)	# To find the maximum marks using the list method max().
''' 
Program to find the maximum marks using the list method max().
Developed by: Naveen kumar V
RegisterNumber: 23000827
'''
def max_marks(marks):
    max_marks=max(marks)
    return max_marks

iii) # To find the maximum marks without using builtin functions.
''' 
Program to the maximum marks without using builtin functions.
Developed by: Naveen kumar V
RegisterNumber: 23000827
'''
def max_marks(list1):
    max_numbers=0
    for num in list1[1:]:
        if num>max_numbers:
            max_numbers=num
    return max_numbers
 

## Output:
1.![image](https://github.com/Naveenkumarvedarajan/FindMaximum/assets/147140428/5ecc0ad0-61f7-4ace-ba8c-3bcad8ba0134)
2.![image](https://github.com/Naveenkumarvedarajan/FindMaximum/assets/147140428/6954c957-5f3d-42d2-bf62-fb52fb8ea4f1)
3.![image](https://github.com/Naveenkumarvedarajan/FindMaximum/assets/147140428/a3984ae9-7edf-4876-9b74-26084f5b085e)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
