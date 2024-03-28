## Python-Basic
#### 1. Set & Dictionary in python.
```
The set is an unordered collection of data types that is iterable, mutable and has no duplicate elements.
A dictionary in Python is an ordered collection of data values, used to store data values like a map.
```
#### 2.  shallow copy and Deep copy in python.
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
