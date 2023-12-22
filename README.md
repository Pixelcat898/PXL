PXL is a programming language I'm working on, coded in Lua! Newer versions in other programming languages will be created!

There are 3 Functions as of Version 0.1.7,
prnt(string (without quote marks) or var: (3 letter variable name)) (Prints the string or variable)
addv(var: (3 letter variable name)) (add 1 from the variabl)
subv(var: (3 letter variable name)) (Subtracts 1 from the variable)

How to create a variable:

in the "var" segment, add this line of text after adding 4 spaces:
num:0

You can rename num to anything! (Must be 3 letters)
You can also change 0 to numbers 10 characters long!

How to use "prnt"

in the "code" segment, add these lines of text after adding 4 spaces:

String: prnt(sring)
Variable: prnt(var:num)

How to add and subtract to and from a variable:

in the "code" segment, add these lines of text after adding 4 spaces:

addv(var:num)
subv(var:num)

How to include an extension:

in the "extra" segment, add this line of text after adding 4 spaces:

incl Extensions/Name.lua (Requires an "Extensions" Folder in the same folder as you're code)

to execute, your file must be named "pxlcode.pxl" or replicate the template.

Once creating a PXL file, you should paste the following into the file:
segment"var"{
}
segment"code"{
}
segment"extra"{
}
