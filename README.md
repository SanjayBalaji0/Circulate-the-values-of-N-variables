# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 

### Step 1:
Get input values from the user as list.
### Step 2: 
circulate() function is used.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:
The values circulated and recorded.
### Step 6: 
Then the values printed as the result.
## Program:
#Program to circulate N values.
#Developed by: Sanjay Balaji S
#RegisterNumber:23005804

def circulate():
     list1=eval(input())
     n=int(input())
     result=list1[n:]+list1[:n]
     print("After circulating the values are:",result)

## Output:
![image](https://github.com/SanjayBalaji0/Circulate-the-values-of-N-variables/assets/145533553/c1a1e1c6-43b6-440e-a558-3cf6c787b930)

## Result:
By this we can circulate the values in a list.
