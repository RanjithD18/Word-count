# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
~~~
# Developed by : Ranjith D
# Register no. : 21500662
num_words = 0
with open('file1.txt','r') as file1:
    for i in file1:
        word = i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
~~~


### OUTPUT:
![output](https://github.com/RanjithD18/Word-count/blob/main/Screenshot%20(78).png)


## RESULT:
Thus the program is written to find the word count from a text.
