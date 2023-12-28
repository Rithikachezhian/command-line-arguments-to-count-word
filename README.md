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

 Then decleare count is equal to 0


### Step 3: 

Read the file with python file name

### Step 4:  

Splitting the word

### Step 5: 

After splitting count the number of words in the line

### Step 6: 

In last statement give the print statement

## PROGRAM:
```
'''
#Program to copy the file.
#Developed by: RITHIKA.N
#RegisterNumber:212223230172

import sys
count=0
with open("text.txt",'r') as f:
    for line in f:
         word=line.split()
         count+=len(word)
print("Word Count in File=",count)
```
### OUTPUT:
![command 1](https://github.com/Rithikachezhian/command-line-arguments-to-count-word/assets/145742406/93ba5279-394f-4c71-93f4-c211e71c8c69)
![command 2](https://github.com/Rithikachezhian/command-line-arguments-to-count-word/assets/145742406/476a49c2-b4dd-46d4-a74d-a7a6be6d0f75)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
