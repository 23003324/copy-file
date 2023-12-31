# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.

### Step 2: 
Open the existing file to read.
 
### Step 3: 
Open the new file to write.

### Step 4:  
Copy the contents from existing file to new file.


### Step 5: 
Get the inputs from the user for existing file and new file. Call the function.

### Step 6: 
End the program.

## PROGRAM:
```
#Python program for copying the contents from one file to another file.
#Developed by: HARITHA RAMESH
#Register Number: 23003324

def copy(fname,newfile):
  with open(fname,'r')as fp:
    with open(newfile,'w')as fp1:
      data1=fp.read()
      fp1.write(data1)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for new file: ")
copy(fname,newfile)
```

## OUTPUT:
Read file:
![Alt text](sam.png)
Write file:

![Alt text](res.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.