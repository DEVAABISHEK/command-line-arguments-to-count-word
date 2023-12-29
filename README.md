# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys
### Step 2: 
Initially make count = 0
### Step 3: 
Open the content file using command line arguments
### Step 4:  
By using for loop name the function as "line"
### Step 5: 
Split the line using .split
### Step 6: 
End the program
## PROGRAM:
```
#Program for getting the word count from the contents of a file using command line arguments
#Developed by: DEVA ABISHEK P
#RegisterNumber: 23012976
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![Screenshot 2023-12-29 165350](https://github.com/DEVAABISHEK/command-line-arguments-to-count-word/assets/150319305/f3c0a8ae-0f5b-41e4-9f92-71486e65548b)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
