# Exp.No:18  
## FILES - FREQUENCY OF CHARACTERS IN A FILE

### AIM  
To write a Python program that reads a file and counts the frequency of each character in it.

### ALGORITHM

1. Begin the program.  
2. Import defaultdict from the collections module.
3. Define create_file(file_path, content) to create a file and write the given content into it.
4. Define char_frequency(file_path) to read the file, count the frequency of each character using defaultdict, and return the result.
5. Terminate the program.

### PROGRAM

```
Reg.No: 212223060305
Name: Vishnu priya E

from collections import defaultdict
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)
def char_frequency(file_path):
    char_count=defaultdict(int)
    with open(file_path, 'r')as file:
        content=file.read()
        for char in content:
           char_count[char]+=1
    return char_count

```
### OUTPUT
<img width="1138" height="342" alt="image" src="https://github.com/user-attachments/assets/5b5aa837-8d28-4574-b47a-2e7dc23ff044" />

### RESULT
Thus a Python program that reads a file and counts the frequency of each character in it are verified.
