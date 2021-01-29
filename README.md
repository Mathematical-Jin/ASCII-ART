# ASCII-ART
```python
#ASCII art Problem
print("ASCII art Problem")

def ASCIIART(name):
    name = name.upper()
    ASCIINAME = "" 
    BORDER = "+-"
    length = len(name)
    newword = name[0:length - 1] 
    lastletter = name[length - 1] 
    for i in newword:
        ASCIINAME += "|{}".format(i) 
    ASCIINAME += "|{}|".format(lastletter)

    print(BORDER * len(name) + "+")
    print(ASCIINAME)
    print(BORDER * len(name) + "+")

name = input("Type a Name ")
ASCIIART(name)
```
