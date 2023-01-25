# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open visual studio code or jupyter lab.
### Step 2: 
Create file with .py extension.
### Step 3: 
Also create .txt file and input sentences.
### Step 4:  
Write the code.
### Step 5: 
Run the program.
### Step 6: 
Print the values and end the program.
## PROGRAM:
```
## PROGRAM TO COUNT THE NUMBER OF WORDS
## DEVELOPED BY : SATHISH R
## REFERENCE NO : 22009045
num_words=0
with open('a.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words= ",num_words)
```
### OUTPUT:

![count](https://user-images.githubusercontent.com/120574768/214574194-afad6fcd-7d4d-4a44-a6a0-8f233e299a77.png)
### TEXT FILE
![txt](https://user-images.githubusercontent.com/120574768/214574183-df28df8d-47c0-4bce-8b50-b08e78be4286.png)

## RESULT:
Thus the program is written to find the word count from a text.
