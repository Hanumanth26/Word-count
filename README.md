# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in text mode
### Step 2: 
Read the text using read() function.
### Step 3: 
Split the text using space separator .we assume that words in a sentence are separated by a space character.
### Step 4:  
The length of the split list should equal the numbe of words in the text file.
### Step 5: 
You can refine the count by clearing the string prior t splitting or validatting the words after splitting


## PROGRAM:
```
'''
Program for getting the word count from a text.
developed by : hanumanth
Register Number: 22005234
'''
num=0
with open("git.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:

![214307057-e19824c0-7e5e-4309-a409-bbd799049fd7](https://user-images.githubusercontent.com/121033192/214799661-0bca03b0-846c-4ac6-9017-f1c64c8184ea.jpg)


## RESULT:
Thus the program is written to find the word count from a text.
