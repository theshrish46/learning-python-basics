# Lists

A list is a sequence, like a string, a list is a sequence of values. The values in a list are called elements or sometimes items.


### Some properties of lists are
1. List are mutable
2. Lists are ordered
3. Lists are dynamic
4. Lists can contain any arbitrary objects

### Traversing a List

The most common way to traverse the elements of a list is with a for loop.
```py
cheeses = ['Cheddar', 'Edam', 'Gouda']

for cheese in cheeses:
    print cheese
```

### List Operations

The ' + ' operator concatenates the lists:
```py
a = [1, 2, 3]
b = [4, 5, 6]
c = a + b
print c
[1, 2, 3, 4, 5, 6]
```

Similarly ' * ' operator repeats a list a given number of times:

```py
[0] * 4
[0, 0, 0, 0]

[1, 2, 3] * 3
[1, 2, 3, 1, 2, 3, 1, 2, 3]
```

### List Slices

The slice operator also works on lists:
```py
t = ['a', 'b', 'c', 'd', 'e', 'f']

t[1:3]
['b', 'c']

t[:4]
['a', 'b', 'c', 'd']

t[3:]
['d', 'e', 'f']

t[:]
['a', 'b', 'c', 'd', 'e', 'f']
```

We can also initialize the list by using slice operator:
```py
t[1:3] = ['x', 'y']
print t
['a', 'x', 'y', 'd', 'e', 'f']
```

### List Methods

append() method adds a new element to the end of a list.
```py
t = ['a', 'b', 'c']
t.append('d')
print t
['a', 'b', 'c', 'd']
```

extend() takes a list as an argument and appends all of the 
elements:

This example leaves t2 unmodified
```py
t1 = ['a', 'b', 'c']
t2 = ['d', 'e']
t1.extend(t2)
print t1
['a', 'b', 'c', 'd', 'e']
```

sort() arranges elements of the list from low to high
```py
t = ['d', 'c', 'e', 'b', 'a']
t.sort()
print t
['a', 'b', 'c', 'd', 'e']
```