# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a new file in visual studio code and type the words in that file.

### Step 2: 
 Save the file and after opening new folder type the required code to generate the program.
### Step 3: 
Import sys from the module.
### Step 4:  
Split the word count using command line arguments
### Step 5: 
print the len(words())
### Step 6: 
End the program.
## PROGRAM:
```
#Program to find the command-line-arguments-to-count-word
#Developed by: Malligesh M
#RegisterNumber: 23002936

import sys
f=open(sys.argv[1],'r')
x=f.read().split()
word=(len(x))
print("Number of words:",word)


```
### OUTPUT:
![output](/Screenshot%20(19).png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
