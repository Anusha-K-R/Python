# Python basics
## Comments
```python
# Shorter one line comment
""" Longer 
    multi-line 
    comment """
```
## Variables
### Case sensitivity
```python
x = 2 # variable assignment
x = 3 # variable reassignment
X = 4 # case sensitive
```
### Acceptable variable name formats
```python
height = 5 
Height = 5
height1 = 5
height_ = 5 
height1_ = 5
height_1 = 5 
_height = 5 # Private variables usually start with an underscore
HEIGHT = 5 # Constansts are usually in uppercase
```
### Unacceptable variable name formats
#### 1height = 5
#### height- = 5
#### height 1 = 5
A variable name cannot start with a number, contain spaces, or include special characters.
## Basic operations
```python
"2" + "3" # joining strings
2 + 3 # Addition
2 - 3 # Subtraction
2 * 3 # Multiplication
2 / 3 # Division
2 ** 3 # Exponentiation
2 % 3 # Modulus/remainder
2 // 3 # Floor division/quotient
2 == 3 # Comparison
x + X # Mathematical operations on variables
```
## Data types
```python
2 # Integer - whole numbers
2.0 # Float - decimal numbers
'2' # String - text
"2" # String - text
'2.0' # String - text
"abc" # String - text
[2, 3, 5, 1] # List- ordered collections of items.
(2, 3, 5, 1) # Tuple - ordered, immutable collections of items.
{2, 3, 5, 1} # Set - unordered collections of unique items.
{'a': 2, 'b': 3, 'c': 5, 'd': 1} # Dictionary - unordered collections of key-value pairs.  
True # Boolean 
2 + 3j # Complex - numbers with a real and imaginary part
b'hello' # Bytes - immutable sequences of bytes used for binary data
```
### Lists - a compound data type
#### Create a list
```python
hall = 11.25
kit = 18.0
liv = 20.0
bed = 10.75
bath = 9.50

# Create list areas
areas = [hall, kit, liv, bed, bath]
```
#### Create lists with different data types
```python
areas = ["hallway", hall, "kitchen", kit, "living room", liv, "bedroom", bed, "bathroom", bath]
```
#### List of lists
```python
house = [["hallway", hall],
         ["kitchen", kit],
         ["living room", liv],
         ["bedroom", bed],
         ["bathroom", bath]]
```
#### Subsetting and indexing
```python
areas = ["hallway", 11.25, "kitchen", 18.0, "living room", 20.0, "bedroom", 10.75, "bathroom", 9.50]
print(areas[1])
print(areas[-1])
print(areas[5])