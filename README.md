# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2: 
 Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
### Step 3: 
Read the file using read() method.
### Step 4:  
Use split() method to split the file content into words.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
```python
#Program for getting the word count from the contents of a file using command line arguments.
#Developed by : HEMACHANDIRAN J 
#REG NO: 212224040113
import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```

### OUTPUT:
text file:
![image-1](https://github.com/user-attachments/assets/61030a5c-8b97-4e9b-879e-2655a3f0a950)


output image:
![image](https://github.com/user-attachments/assets/6b512c4a-77b7-452a-a44f-48028b86fb31)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
