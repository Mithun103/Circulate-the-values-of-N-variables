# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
get the value from the user
### Step 2: 
using the slicing concept rotate the list
### Step 3: 
print the values
### Step 4: 
end of program
## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## output
 
![Screenshot from 2022-12-26 18-24-53](https://user-images.githubusercontent.com/118344695/209552396-c8751233-a9d2-46de-a0a6-06cd39f59d8c.png)
## result
the program executed successfully
