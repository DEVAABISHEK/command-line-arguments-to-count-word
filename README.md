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

### OUTPUT:
![292756711-cb7a6cfa-0e03-411f-97f9-e953a9007fa3](https://github.com/DEVAABISHEK/command-line-arguments-to-count-word/assets/150319305/0331f7b0-d696-4c18-bcb2-4f463fa517a4)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
