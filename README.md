# Word-count
## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7


## ALGORITHM: 

## Step 1:
To write a python program for getting the word count from a text file.

## Step 2:
Open the required file by using the function "with"

## Step 3:
Then use the laptop to assign the i value in the file.

## Step 4:
Using split function to spilt the words

## Step 5:

Finding the given length of the words by using len() fuction.

## Step 6:

Calling the function and Printing the number of words.

## PROGRAM:

```
Program to count the words in a file
Developed by: Gopika R
Register Number: 212222240031

fname=input("enter the file name:")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words: ",num_words)
```


### OUTPUT:
![Screenshot (148)](https://github.com/Gopika-9266/Word-count/assets/122762773/6c304fe7-75c8-465b-ba93-c4acaea87cf5)


## RESULT:
Thus the program is written to find the word count from a text.
