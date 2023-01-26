# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys

### Step 2: 
 Open file using commandline arguments.

### Step 3: 
Using for loop find the word count from the contents of a file.


### Step 4:  
Use len to count number of words.


### Step 5: 
Give print statement.

### Step 6: 
End the program

## PROGRAM:
```python
Program for getting the word count from the contents of a file using command line arguments.
Developed by: S.Aishwarya
RegisterNumber: 22008635
import sys
count=0
with open(sys.argv[1],'r') as f:
    for line in f:
        word = line.split()
        count+= len(word)
print("Word Count in File = ",count)  
```
### OUTPUT:

![command line ](https://user-images.githubusercontent.com/121418444/214851952-1bffebb0-85d2-4448-942d-f1a52a3908e1.png)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
