# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Decleare number of words is 0

Step 2:
open it with txt file

Step 3:
Give range for i

Step 4:
Then nxt split the words

Step 5:
count the number of words

Step 6:
Giving print statement for getting output

## PROGRAM:
```
## DEVELOPED BY: Manikandan.R
## REFERENCE NUMBER: 23004754
num_words =0
file1 = open("text.txt", "r")
with open('text.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```
##TEXT.File
```
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")
```

### OUTPUT:
![image](https://github.com/Manikandanrag/Word-count/assets/138849491/2cd60550-3811-4dd7-90e8-1501279f57a3)
![image](https://github.com/Manikandanrag/Word-count/assets/138849491/50e1fed7-723d-4fe3-baca-79806a4aa196)



## RESULT:
Thus the program is written to find the word count from a text.
