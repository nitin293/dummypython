# Data types in Python

Data types are the way of representation of data. There are mainly 9 inbuilt data types in python. In python one need not to define the type of the data. Pyhon itself decides the data type during its execution.
 

### Boolean

Boolean data type consists of two values i.e., True or False and represented as

```
>>> a = True
>>> print(a, "| TYPE of a:", type(a))
True | TYPE of a: <class 'bool'>
```

### Integer

Integers are the whole-valued positive or negative numbers or zero and represented as follows

```
>>> a = 3
>>> print(a, "| TYPE of a:", type(a))
3 | TYPE of a: <class 'int'>
```

### Float

Float consists of a decimal point and represented as follows

```
>>> a = 2.93
>>> print(a, "| TYPE of a:", type(a))
2.93 | TYPE of a: <class 'float'>
```

### Complex

Combination of real and imaginary number is known as complex numbers and represented as follows

```
>>> a = 3 + 4j
>>> print(a, "| TYPE of a:", type(a))
(3+4j) | TYPE of a: <class 'complex'>
```

### String

Combination of characters are known as string and represented as follows

```
>>> a = "Nitin Choudhury"
>>> print(a, "| TYPE of a:", type(a))
Nitin Choudhury | TYPE of a: <class 'str'>
```

### List

List is basically a data type that contains data in an ordered sequence and represented as follows

* A single list can contain more than one data types
* List data type is mutable

```
>>> a = [1, 2, "Nitin", 3]
>>> print(a, "| TYPE of a:", type(a))
[1, 2, 'Nitin', 3] | TYPE of a: <class 'list'>
```

More about LIST data type: <a href="./LIST.md">click here</a>

### Tuple

Tuples are similar as python list, but the main difference between list and tuple is that tuple is immutable and is represented as follows

```
>>> a = (1, 2, "Nitin", 3)
>>> print(a, "| TYPE of a:", type(a))
(1, 2, 'Nitin', 3) | TYPE of a: <class 'tuple'>
```

### Set

Set is a data type that contains unique data and represented as follows

```
>>> a = {1, 2, 2, 3, "Nitin", 3}
>>> print(a, "| TYPE of a:", type(a))
{1, 2, 3, 'Nitin'} | TYPE of a: <class 'set'>
```

### Dictionary

Dictionary data type contains 'key-value' pairs and represented as follows

```
>>> a = {"Name": "Nitin Choudhury", "Email": "nitin123@xyz.com"}
>>> print(a, "| TYPE of a:", type(a))
{'Name': 'Nitin Choudhury', 'Email': 'nitin123@xyz.com'} | TYPE of a: <class 'dict'>
``` 