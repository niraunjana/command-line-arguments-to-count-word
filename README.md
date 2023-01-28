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
count = {}
with open(sys.argv[1], 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word] = 1
            else:
                count[word] += 1
print(count)
f.close()
```


### OUTPUT:
![WhatsApp Image 2023-01-28 at 12 38 23](https://user-images.githubusercontent.com/119395610/215252359-b160c110-21fd-450e-b6fd-1f3d47ad629c.jpg)






## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
