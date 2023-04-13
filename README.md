# Data Structures Complexity and Algorithms
## NOTES
### Matrix
A matrix is an array filled with numbers, symbols or expressions

Can be represented with lists
```
a = [
[1, 2, 3],
[4, 5, 6],
[7, 8, 9]
]
```
i.e. (2,1) = 6

- All rows must have the same number of values
- All columns must have the same number of values
- All items in the 2D List must have the same data types
- Since indexing always starts at 0 ... row 1 is technically located at matrix_A[0]

### List Comprehension
An alternative, more concise method to create/define a list\
Espescially when made with iterable data, such as other lists
```# Solution
a = [1,2,3]
b = [3,1,4]

result = [[x, y] for x in a for y in b if x != y]
print(result)```
