# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file
### Step 2:
Open the required file by using the function "with".
### Step 3:
Then use the laptop to assign the i value in the file.
### Step 4:
Using split function to spilt the words
### Step 5:
Finding the given length of the words by using len() fuction.
### Step 6:
Calling the function and Printing the number of words.
## PROGRAM:
```
#Program to find the word count.
#Developed by: RAHUL.V
#RegisterNumber:23006860
num_word=0
with open ("sample.txt",'r') as f:
for i in f:
word=i.split()
num_word+=len(word)
print("number of words ={}".format(num_word)
```
### OUTPUT:
![Screenshot 2023-12-26 141259](https://github.com/23006860/Word-count/assets/139841752/33f9701d-1a39-4755-9778-a1053c83fb0d)

![Screenshot 2023-12-26 141319](https://github.com/23006860/Word-count/assets/139841752/06bba827-acd0-452e-87b4-5ef602e6b369)
## RESULT:
Thus the program is written to find the word count from a text.
