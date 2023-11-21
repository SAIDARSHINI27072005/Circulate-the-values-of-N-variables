# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
define a function named circulate
### Step 2: 
take a list as input from the user and assign it to the variable l
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
update the list by taking the slice frm index n to the end of the list and appending it with the slice fromm the start of the list to index n
### Step 5: 
print the updated list l with the message "after circulating the valuesare:".

## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![image](https://github.com/SAIDARSHINI27072005/Circulate-the-values-of-N-variables/assets/147474227/a18d772c-d5bc-4035-b93f-429008c5f6bb)


## Result:
thus the circulation of values are successfully executed
