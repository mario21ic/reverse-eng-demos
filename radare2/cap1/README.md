
```
$ gcc -m32 -w main.c
$ radare2 -d ./a.out

# Fully analyze the binary
> aaaa

# List all the functions in the binary
> afl

# General Information
> iI

# List Imports
> ii

# List Strings
> iz

# Seek to a function -> sf function
> sf main

# Print disassembly of the basic block
> pdb

# Print dissasembly of a function
> pdf
> 
```
