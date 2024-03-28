## Python-Basic
#### 1. Set & Dictionary in python.
```
The set is an unordered collection of data types that is iterable, mutable and has no duplicate elements.
A dictionary in Python is an ordered collection of data values, used to store data values like a map.
```
#### 2. shallow copy and Deep copy in python.
```
In Python, a shallow copy creates a new object with the same type as the original,
but it only copies references to the original object's internal elements.
Shallow copy is typically faster because it involves less copying.
```
```python
shallow_copy = copy.copy(my_list)
```
```
On the other hand, a deep copy creates a completely independent copy of the original object.
Deep copy tends to be slower due to the recursive nature of copying nested elements.
```
```python
deep_copy = copy.deepcopy(my_list)
```
#### 3. Decorators in python.
```
Decorators in Python are like wrappers for functions.
They enable us to add extra functionality to existing functions without changing their code directly.
It's a way to enhance or modify the behavior of functions dynamically.
```
#### 4. Generators in Python.
```
Generators in Python are functions that allow you to generate a sequence of values dynamically.
They use the 'yield' keyword to produce values one at a time, making them memory-efficient and
useful for handling large datasets or infinite sequences.
```
