# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file from which we need to copy the test
### Step 2: 
Using keyword("with") to open the required file.
 
### Step 3: 
Again using the with keyword to open the empty file.

### Step 4:  
The empty file is open by using "w" which is used to write only.
### Step 5: 
The for function is used to take each line from the main file.
### Step 6: 
Write() is used to write the lines of main file to empty file or do the directed file.
## PROGRAM:
with open("file1.txt","r") as fp:
    with open("file2.txt","w") as fp1:
        v = fp.read()
        fp1.write(v)
       
### OUTPUT:
![image](https://user-images.githubusercontent.com/94828147/153799494-744aad98-ac64-4dd6-b7a3-725ca4b37e01.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
