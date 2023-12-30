# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
AIM:
To write a python program for getting the word count from a text.

EQUIPEMENT'S REQUIRED:
PC Anaconda - Python 3.7

ALGORITHM:
### Step 1:
To write a python program for getting the word count from a text file.

### Step 2:
Open the required file by using the function "with"

### Step 3:
Then use the laptop to assign the i value in the file

### Step 4:
Using split function to spilt the words

### Step 5:
Finding the given length of the words by using len() fuction.

### Step 6:
Calling the function and Printing the number of words.
## PROGRAM:
~~~
#Program for getting the word count from the contents of a file using command line arg
#Developed by: GOWTHAM N
#Register Number : 23013437
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
~~~

### OUTPUT:
![output](https://github.com/gowthamsec/Word-count/assets/147933945/bfd7d9a9-8b49-4f12-8451-295b0bab3fcf)



## RESULT:
Thus the program is written to find the word count from a text.
