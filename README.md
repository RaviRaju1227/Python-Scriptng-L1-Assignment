# Python-Scriptng-L1-Assignment

Exercise – 1: Filename: ex1.py

Implement the function ruler() which takes a number (for example, 43) as argument, 
and produces output as shown below. 
 1 2 3 4 
 1234567890123456789012345678901234567890123
(note: 1st row values are aligned to respective 0s of the 2nd row)
Test correctness of the function with the following values :
 5, 10, 25, 51 and 80
 
 
**Exercise – 2: Filename: ex2.py**

Implement the function isWhiteLine(), which takes a string and returns TRUE if the 
string contains only white space & tab characters.
Making use of the above function, write a program, which should read a file given as 
command-line argument, and print only non-blank lines onto the standard output.


**Exercise – 3: Filename: ex3.py**

Implement the function isListOfInts(), which takes a list, and checks if the list has 
only "int" type values, as per the specification given below:
• The function should return True, if the list has only "int" type values, otherwise 
should return False.
• The function should return True, if an empty list is passed as argument.
• If the argument is not of ‘list’ type, then the function should throw ValueError 
exception, with the error message 'arg not of <list> type'
• The function should have only one return statement.
To test correctness of the function isListOfInts(),implement the function testList()
which is called as shown below and should produce output as indicated.
Function call Expected output
testList([])
testList([1])
testList([1,2])
testList([0])
testList(['1'])
testList([1,'a'])
testList(['a',1])
testList([1, 1.])
testList([1., 1.])
testList((1,2))
[] --> True
[1] --> True
[1, 2] --> True
[0] --> True
['1'] --> False
[1, 'a'] --> False
['a', 1] --> False
[1, 1.0] --> False
[1.0, 1.0] --> False
ValueError: (1, 2) - arg not of <list> typ
