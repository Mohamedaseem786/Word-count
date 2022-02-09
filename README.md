# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a file and then open the reqiured file by using with function.
### Step 2: 
 assign a variable as 0.
### Step 3: 
then use the for loop for assigning the i value in the file.
### Step 4:  
use split() to split the file.
### Step 5: 
using for loop count the numbewr of words.
### Step 6: 
print the number of words.
## PROGRAM:
```
with open("file1.txt","r") as fp:
    count=0
    for data in fp:
        l=data.split()
        for i in l:
            count+=1
    print("No of words",count)
```

### OUTPUT:
![](./out2.png)
![](./out1.png)


## RESULT:
Thus the program is written to find the word count from a text.
