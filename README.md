# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
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
    Developed by: Jude Clement Jose G
    Register no: 24005310
    import sys
    fp=open(sys.argv[1])
    wordcount=0
    for i in fp:
        words=i.split()
        wordcount+=len(words)
    print("Total no of words in file is",wordcount)
    fp.close()
### OUTPUT:
![alt text](image.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
