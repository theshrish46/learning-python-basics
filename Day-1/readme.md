# First Python Program

### We will begin our first lesson by printing a simple Hello World! program.

```py
print("Hello World!")
```
Yes it is that simple unless like other languages here you don't need to import or include any files and then write a main function to print basic statements.

## Variables Python

Now we will look into variables.
Variables are nothing fancy but just a keyword which is user defined and pointing towards a memory location.

You can declare any kind of variable (int, float, boolean) and store the date of different type. 

So lets declare a variable and store some data.

```py
name = "Shrish"
roll = 141
student = True

```
You can print the stored value using ```py print``` function which is a built in function.

```py
print(name)
print(roll)
print(student)
```
Or you can print them on a single line by providing all the three variables simultaneously.

```py
print(name, roll, student)
```

Now we have successfully declared three variables which contains three different types of values. However we can in-fact we have to explicitly define which type of data we are storing.


## Data types in Python

Variables can hold values, and every value has a data-type. Python is a dynamically typed language; hence we do not need to define the type of the variable while declaring it. The interpreter implicitly binds the value with its type.

There are 5 basic data-types in Python
- Numbers
- Sequence Type
- Boolean
- Set
- Dictionary

<dl>
<img src="./assets/python-data-types.png" alt="img">
</dl>

Now lets deep dive into every data-type

### Numbers
Number stores numeric values. The integer, float and complex values belong to a Python Numbers data-type.
Python also provide tpe() function which is used to check the type of the data being stored in any variable.

#### int 
Int stores the integer values such as 10, 342, 2345. Python has no restriction on the length of an integer.

#### float
Float is used to store floating-point numbers like 0.4, 3.343, 100.454, etc. It is accurate upto 15 decimal points.

#### complex
A complex number contains an ordered pair, i,e., x + iy where x and y denote the real and imaginary parts, respectively. The complex numbers like 2.14j, 2.0 + 2.3j, etc.



### Sequence Type

#### String 
The string can be defined as the sequence of characters represented in the quotation marks. In Python, we can use single, double or triple quotes to define a string.

In the case of string handling, we can use + operator to concatenate two strings.

```py
print('hello' + 'python')
```

```
'hello python'
```
