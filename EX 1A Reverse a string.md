# EX 1A Reverse a String
## DATE:
## AIM:
To write a program to create a recursive function to reverse a string.

## Algorithm
1. Calls itself by returning the last character plus the reverse of the remaining string.
2. Uses a for loop to prepend each character to a result string.
3. Utilizes Python's slicing syntax s[::-1] for a concise, built-in solution.
4. Converts the string to a stack (list), then pops characters to build the reversed string.
5. Swaps characters from both ends of a list version of the string until the middle is reached.   

## Program:

### Developed By:ROSELIN MARY JOVITA S
### Register Number:212222230122

```
def rev(s):
    if(len(s)<1):
        return s
    return s[-1]+rev(s[:-1])
s=input()
print(rev(s))
```

## Output:

![image](https://github.com/user-attachments/assets/2b8684d1-775d-44ac-a555-22b3c8e82135)


## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
