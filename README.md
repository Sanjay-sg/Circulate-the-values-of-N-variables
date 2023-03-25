# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7

## Algorithm: 

### Step 1: 
Define a function
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Defining datatype for the input
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
print the output
### Step 6:
End the program

## Program:
```
#Program to circulate N values.
#Developed by: Sanjay G
#RegisterNumber:212222230131
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![image](https://user-images.githubusercontent.com/119559022/227699890-887aaceb-1c83-4bd8-bac2-bf9470c172bf.png)


## Result:
Thus the Circulate the values of N variables are successfully executed
