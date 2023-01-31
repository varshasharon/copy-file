# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 
Open the first txt file and read it

### Step 2: 
 After that open the second file and append the first one to it
### Step 3: 
Start the for loop
### Step 4:  
 Then write the lines from the first one to the second file using the write function

### Step 5: 
: Print the output

## PROGRAM:
```python
#Developed By: E. VARSHA SHARON
#Reference No: 22004867
with open("text.txt") as f:
    with open("text1.txt","w") as f1:
        for line in f:
            f1.write(line)
```
### OUTPUT:

![copy](https://user-images.githubusercontent.com/98278161/215007396-25e06c3f-074f-422a-8a00-7f107f198a2c.jpeg)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
