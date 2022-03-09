## Python Interview Questions

### What is Python? What are the benefits of using Python
Python is a high-level, interpreted, general-purpose programming language. Being a general-purpose language, it can be used to build almost any type of application with the right tools/libraries. Additionally, python supports objects, modules, threads, exception-handling, and automatic memory management which help in modelling real-world problems and building applications to solve these problems.
**Benefits of using Python**
1. Extensive Libraries
Python downloads with an extensive library and contains code for various purposes like regular expressions, documentation-generation, unit-testing, web browsers, threading, databases, CGI, email, image manipulation, and more.
2. Extensible
Python can be extended to other languages. You can write some of your code in languages like C++ or C.
3. Embeddable
Complimentary to extensibility, Python is embeddable as well. You can put your Python code in your source code of a different language, like C++.
4. Improved Productivity
The language’s simplicity and extensive libraries render programmers more productive than languages like Java and C++ do.
5. IOT Opportunities
Since Python forms the basis of new platforms like Raspberry Pi, it finds the future bright for the Internet Of Things.
6. Simple and Easy
When working with Java, you may have to create a class to print ‘Hello World’. But in Python, just a print statement will do.
7. Readable
Because it is not such a verbose language, reading Python is much like reading English. This is the reason why it is so easy to learn, understand, and code.
8. Object-Oriented
This language supports both the procedural and object-oriented programming paradigms.
9. Free and Open-Source
Python is freely available. But not only can you download Python for free, but you can also download its source code, make changes to it, and even distribute it.
10. Portable
When you code your project in a language like C++, you may need to make some changes to it if you want to run it on another platform.
11. Interpreted
Lastly, we will say that it is an interpreted language. Since statements are executed one by one, debugging is easier than in compiled languages.

### What is a Type-checking in language?
- Static - Data Types are checked before execution.
- Dynamic - Data Types are checked during execution.

### What is an Interpreted language?
An Interpreted language executes its statements line by line. Languages such as Python, Javascript, R, PHP, and Ruby are prime examples of Interpreted languages. Programs written in an interpreted language runs directly from the source code, with no intermediary compilation step.

### What is Scope in Python?
A local scope refers to the local objects available in the current function.
A global scope refers to the objects available throughout the code execution since their inception.
A module-level scope refers to the global objects of the current module accessible in the program.
An outermost scope refers to all the built-in names callable in the program. The objects in this scope are searched last to find the name referenced.

### What are lists and tuples? What is the key difference between the two?
Lists and Tuples are both sequence data types that can store a collection of objects in Python.

The objects stored in both sequences can have different data types.

Lists are represented with square brackets `['apple', 13, 0.1]`, while tuples are represented with parantheses `('microsoft', 11, 0.96)`.

The key difference between the two is that while lists are mutable, tuples on the other hand are immutable objects. This means that lists can be modified, appended or sliced on the go but tuples remain constant and cannot be modified in any manner. 

### What is __init__?
`__init__` is a contructor method in Python and is automatically called to allocate memory when a new object/instance is created. All classes have a __init__ method associated with them. It helps in distinguishing methods and attributes of a class from local variables.
```
# class definition
class Student:
   def __init__(self, fname, lname, age, section):
       self.firstname = fname
       self.lastname = lname
       self.age = age
       self.section = section
# creating a new object
stu1 = Student("Sara", "Ansh", 22, "A2")
```

### What is break, continue and pass in Python?
- **Break** -	The break statement terminates the loop immediately and the control flows to the statement after the body of the loop.
- **Continue** - The continue statement terminates the current iteration of the statement, skips the rest of the code in the current iteration and the control flows to the next iteration of the loop.
- **Pass** - As explained above, the pass keyword in Python is generally used to fill up empty blocks and is similar to an empty statement represented by a semi-colon in languages such as Java, C++, Javascript, etc.
```
pat = [1, 3, 2, 1, 2, 3, 1, 0, 1, 3]
for p in pat:
   pass
   if (p == 0):
       current = p
       break
   elif (p % 2 == 0):
       continue
   print(p)    # output => 1 3 1 3 1
print(current)    # output => 0
```

### What do you know about pandas?
Pandas is an open-source, python-based library used in data manipulation applications requiring high performance. The name is derived from “Panel Data” having multidimensional data. This was developed in 2008 by Wes McKinney and was developed for data analysis.
Pandas are useful in performing 5 major steps of data analysis - Load the data, clean/manipulate it, prepare it, model it, and analyze the data.

### Define pandas dataframe.
A dataframe is a 2D mutable and tabular structure for representing data labelled with axes - rows and columns.
The syntax for creating dataframe:
```
import pandas as pd
dataframe = pd.DataFrame( data, index, columns, dtype)
```

### How will you combine different pandas dataframes?
The dataframes can be combines using the below approaches:
**append() method**: This is used to stack the dataframes horizontally. Syntax:
```df1.append(df2)```
**concat() method**: This is used to stack dataframes vertically. This is best used when the dataframes have the same columns and similar fields. Syntax:
```pd.concat([df1, df2])```
**join() method**: This is used for extracting data from various dataframes having one or more common columns.
```df1.join(df2)```

