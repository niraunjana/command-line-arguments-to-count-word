# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys
### Step 2: 
 Initially make count = 0
### Step 3: 
Open the content file using command line arguments.
### Step 4:  
By using for loop name the function as "line"
### Step 5: 
Split the line using .split
### Step 6: 
Split the line using .split


## PROGRAM:
```
##Developed by: NIRAUNJANA GAYATHRI G R
##RegisterNumber: 22008369
import sys
count=0
with open(sys.argv[1],'r') as f1:
        for line in f1:
            word= line.split()
            count += len(word)
print("word Count in file = ",count)  
```


### OUTPUT:
![image](https://user-images.githubusercontent.com/119395610/214828171-26728d02-48c4-47d3-b1a1-503d897bd674.png)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
