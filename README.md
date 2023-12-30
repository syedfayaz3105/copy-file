# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.

### Step 2:
Write some lines in that file.
 
### Step 3: 
Create a python file.

### Step 4:  
Write a code to copy the content of the file to a new file.

### Step 5:
Run the program.

### Step 6: 
Display the output

## PROGRAM:
```
with open("thala","r") as f1:
    with open("copy.txt","w") as f2:
        line=f1.read()
        f2.write(line)
```

### OUTPUT:
![Screenshot 2023-12-23 114913](https://github.com/syedfayaz3105/copy-file/assets/147144126/e3c6f536-171b-424a-ac82-a9622e8e5a2d)
![Screenshot 2023-12-23 114934](https://github.com/syedfayaz3105/copy-file/assets/147144126/a979da00-fe7f-41a9-b2a5-246960c3634c)
![Screenshot 2023-12-23 114956](https://github.com/syedfayaz3105/copy-file/assets/147144126/ab7d605c-de66-4589-8948-f1beb48b0577)






## RESULT:
Thus the program is written to copy the contents from one file to another file.
