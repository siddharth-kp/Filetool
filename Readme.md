to Get the repo use
```git clone https://github.com/siddharth-kp/filetool.git```

to generate the build use 
```go install```

to see usages run 
```filetool --help```

### Commands available

`scan` → Scans a directory recursively and prints the number of lines in each `.txt` file.<br>
`freq` → Counts word frequencies across all `.txt` files in a directory and shows the top 10 most frequent words.

<br>

# USAGE

## Scan

go to any directory and use
```filetool scan .```

or use 
```filetool scan "C:/Users/Siddharth Panda/Desktop/Desktop folder/testdata"```

this will show output like - 
```
PS C:\Users\Siddharth Panda\Desktop\Desktop folder\testdata> filetool scan .
abc1.txt: 50 lines
fol-1\abc2.txt: 50 lines
fol-1\fol2\abc3.txt: 50 lines
PS C:\Users\Siddharth Panda\Desktop\Desktop folder\testdata>
```

## Freq count

go to any directory and use
```filetool freq .```

or use 
```filetool freq "C:/Users/Siddharth Panda/Desktop/Desktop folder/testdata"```

this will show output like - 
```
PS C:\Users\Siddharth Panda> filetool freq "C:/Users/Siddharth Panda/Desktop/Desktop folder/testdata"
Top 10 words:
the: 119
a: 58
to: 56
of: 45
he: 30
that: 28
it: 27
was: 25
on: 24
and: 23
PS C:\Users\Siddharth Panda>
```