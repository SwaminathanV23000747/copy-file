# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
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
## Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
```python
#Program to copy the text from one file to another
#Developed by : Swaminathan V
#Register umber : 23000747
f=open(r"/content/SWAMI-1.txt","r")
a=f.read()
print(a)
b=open(r"/content/swami.txt","w+")
b.write(a)
b.seek(0)
print(b.read())
```
### OUTPUT:
![5B SS1](https://github.com/SwaminathanV23000747/copy-file/assets/148931113/37798115-2313-4b4b-aede-13e5c7d98998)
![5B SS2](https://github.com/SwaminathanV23000747/copy-file/assets/148931113/33ef900c-9db5-400e-adb9-09bd5eebe1b6)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
