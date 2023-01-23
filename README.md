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
![output1](https://user-images.githubusercontent.com/119477890/214042514-e7c74f9c-d8bf-41a0-ab24-0a1c9e25cd4f.png)

output
![output](https://user-images.githubusercontent.com/119477890/214042550-cbd6f603-b521-4202-90ee-5b43332076a0.png)

![output](https://user-images.githubusercontent.com/119477890/214042578-f612c549-557c-4383-948c-b11fb248d3c3.png)

## RESULT:
Thus the program is written to find the word count from a text.
