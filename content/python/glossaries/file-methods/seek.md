---
Title: ".seek()"
Subjects:
  - "Computer Science"
  - "Data Science"
Tags:
  - "Files"
  - "Methods"
  - "Functions"
  - "Strings"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-python-3"
  - "https://www.codecademy.com/learn/paths/computer-science"
  - "https://www.codecademy.com/learn/paths/data-science"
---

## Definition

Allows the user to move the location of the file handle's reference point within an open file from one place to another.

## Syntax

```py
file.seek(offset, from what location)
```

## Example 1

Use `.seek()` to change the position of the reference point within the **gullivers_travels.txt** file:

```codebyte/python
f = open("gullivers_travels.txt", "r")

# Print first line of the document from default 0th position
print(f.readline())

# Change the reference point to the 50th index position
f.seek(50)

# Print line from new reference point
print(f.readline())

f.close()
```
