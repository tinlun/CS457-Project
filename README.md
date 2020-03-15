# CS457-Project
Functional Python genetic algorithm project for class.

Given the digits 0 through 9 and the operators +, -, * , /, %, _ find a sequence 
that will represent a given target number. The operators will be applied 
sequentially from left to right as you read.

The _ operator is an extra operator to concatenate two digits. Ex: 4 _ 2 = 42
1 _ 9 _ 9 _ 3 % 2 _ 9 -> 1993 %2 _ 9 -> 1 _ 9 -> 19

Instructions
-----------
Python 3

Install pymonad and pytest, or run:
`> pip install -r requirements.txt`

To run the program:
`> python main.py`
`> python main.py 30` - To specify a target value.

To run tests:
`> pytest`
