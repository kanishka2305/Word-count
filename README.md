# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Create a file and add some content into it.

Step 2:
Open file using with keyword/built-in function in read mode.

Step 3:
Use read() to read the contents of the file.

Step 4:
Split the lines using split().

Step 5:
Iterate the list and increment the count

Step 6:
Print the output.

## PROGRAM:
```python
To write a program for getting the word count from a file.
Developed by: kanishka.v.s
RegisterNumber: 22003409

def wordcount():
    cnt = 0
    with open("MyFile.txt","r") as fp:
        data = fp.read()
        for line in data.split():
            cnt += 1
    print("The number of words in the given file is:",cnt)
wordcount()
```

### OUTPUT:
![output](/output1.png)
![output](/output2.png)



## RESULT:
Thus the program is written to find the word count from a text.
