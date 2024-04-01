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
#### 5. *args and **kwargs in python.
```
If you do not know how many arguments that will be passed into your function,
add a * before the parameter name in the function definition.
If you do not know how many keyword arguments that will be passed into your function,
add two asterisk: ** before the parameter name in the function definition.
```
```python
def details(*args, **kwargs):
    print(args)
    print(kwargs)
details('Ahmedabad','Chennai','Mumbai',city='Dehlhi', country = 'India')
```
```output
('ahmedabad', 'chennai', 'mumbai')
{'city': 'Dehlhi', 'country': 'India'}
```
#### 6. How is memory management done in Python.
```
Python uses its private heap space to manage the memory. Basically,
all the objects and data structures are stored in the private heap space.
```
#### 7. What is Python Path.
```
Python path is an environment variable that is used to specify the location of python libraries
```
#### 8. What is '__init__' in python.
```
It is constructor method & automatically called when new object/class is created. All Classes have a init method.
```
```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
```
### OOP (Object-Oriented Programming)
#### In Python, oop is a that type of programming example that uses objects and classes in programming. It's aims to implement real-world entities like inheritance, polymorphisms, encapsulation, etc.
#### 9. Class & Object in python.
```
A class like an object constructor, or a 'Blueprint' for creating objects.
```
```python
class MyClass:
  x = 5
```
```
Almost everything in python is an object, with it's properties and Methods.
```
```pyton
p1 = Myclass()
print(p1.x)
```
#### 10. 










