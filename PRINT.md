# Print statement:

Print is basically used to display some text in the console window. In python, `print()` function is used to perform this particular operation.

### Printing the string "Hello World"

```
>>> print("Hello World !")
Hello World !
```
 
### Printing a variable

```
>>> a = "Hello World"
>>> print(a) 
Hello World
```


### Concatenate and print

> Example 1: <b>String</b> concatenation using `+`

```
>>> a = "Hello "
>>> b = "World"
>>> print(a + b)
Hello World
```
 
> Example 2: <b>String</b> and <b>Integer</b> concatenation using `+`

```
>>> a = "I have "
>>> n = 4
>>> print(a + str(n) + " apples")
I have 4 apples
```

> Example 3: <b>String</b> and <b>Integer</b> concatenation using `,`

```
>>> a = "I have"
>>> n = 4
>>> print(a, n, "apples")
I have 4 apples
```
 
> Example 4: <b>String</b> and <b>Integer</b> concatenation using `fstring`

```
>>> a = "I have"
>>> n = 4
>>> print(f"{a} {n} apples")
I have 4 apples
```

### Printing nested `"`

```
>>> print("Shadow says,\"Hello World !\"")
Shadow says,"Hello World !"
```

### Printing in next line

```
>>> print("Hello there\nNitin this side")
Hello there
Nitin this side
```

### Printing `tab`
```
>>> print("Hello\tThere")
Hello   There
``` 



