# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Get the file name and location from the user.

Step 2:
Give a new file name to create a copy of a file content.

Step 3:
Read the file and close the file.

Step 4:
Now write the content in the new file.

Step 5:
When done print"File copied successfully".

Step 6:
End of the program

## PROGRAM:
```
Developed by: SANJAY S
Register Number: 212222230132

print("Enter the name of  Source File: ")
sFile = input()
print("Enter the Name of Target File: ")
tFile = input()
fileHandle = open(sFile, "r")
texts = fileHandle.readlines()
fileHandle.close()

fileHandle = open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()
print("\nfile copied Successfully")  
```
### OUTPUT:
![image](https://github.com/22002102/copy-file/assets/119091638/b88c628b-a600-43c1-b3cb-975ce6519c53)




![image](https://github.com/22002102/copy-file/assets/119091638/9e8999d0-46ce-4a66-a85f-0d16ea4c00f9)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
