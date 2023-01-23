# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file and add some content into it.

### Step 2:
Open file using with keyword/built-in function in read mode.

### Step 3:
Use read() to read the contents of the file.

### Step 4:
Split the lines using split().

### Step 5:
Iterate the list and increment the count

### Step 6:
Print the output.

## PROGRAM:
```
def wordcount():
  count = 0
  with open("MyFile.txt","r") as f2:
    data=f2.read()
    for line in data.split():
      count += 1
  print("The total number of word count is", count)
wordcount()
```

### OUTPUT:
MyFile.txt
![output1](https://user-images.githubusercontent.com/119477890/214043919-21812b71-3222-4d0b-9748-9fa38e30d889.png)

Output
![output2](https://user-images.githubusercontent.com/119477890/214044074-cdb1fbee-e135-4f96-80d0-eb8b83ee688a.png)

![output2 (1)](https://user-images.githubusercontent.com/119477890/214044107-b0fb44e2-dab9-4395-bbd7-87d4ed462f48.png)


## RESULT:
Thus the program is written to find the word count from a text.
