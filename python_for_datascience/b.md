Hello workd, in this blog we will look into Numpy or the numerical python module. It is extremely popular in Python community and it is heavily used for Scientific Computing and Data Science. We will see why it is so popular.

To get started we will install the module. Download and install the module by running
```python
pip install numpy
```

As given in their official documentation, NumPy derives from an old library called Numeric, which was the first array object built for Python. The most basic object in NumPy is the ```ndarray```, or simply an ```array```, which is an **n-dimensional, homogenous** array. By homogenous, we mean that all the elements in a numpy array have to be of the **same data type**, which is commonly numeric (float or integer). 


Let's create an array object.

```python
# np is the standard alias used
import numpy as np
array_1d = np.array([2, 4, 5, 6, 7, 9])
print(array_1d)
print(type(array_1d))
```
    [2 4 5 6 7 9]
    <class 'numpy.ndarray'>



```python
# Creating a 2-D array using two lists
array_2d = np.array([[2, 3, 4], [5, 8, 7]])
print(array_2d)
```

    [[2 3 4]
     [5 8 7]]


We use NP dot array and in the bracket we just pass down the list. If you look into it now this is sort of similar to a list. It is actually very similar to a list you can access the elements by index it looks like a list. So the question is I only have a list why do I need this numpy array? 

There are several advantages of using numpy array over the list. There are three main benefits. 

* It is very convenient to perform standard tasks.
* It is super fast for data operations.
* It requires less memory compared to python list.

We will go over all these three benefits one by one. Essentially what we are doing is we are comparing numpy array with a Python list.

Numpy is convenient because we can write vectorised code on numpy arrays, not on lists, which is convenient to read and write, and concise. So if you want to add two arrays you just say a1 plus a2. It is not like you have to write a list comprehension.

```python
list_1 = [3, 6, 7, 5]
list_2 = [4, 5, 1, 7]

# the list way to do it: map a function to the two lists
product_list = list(map(lambda x, y: x*y, list_1, list_2))
print(product_list)

```
    [12, 30, 7, 35]
    
```python
# The numpy array way to do it: simply multiply the two arrays
array_1 = np.array(list_1)
array_2 = np.array(list_2)

array_3 = array_1*array_2
print(array_3)
print(type(array_3))
```
    [12 30  7 35]
    <class 'numpy.ndarray'>






okay you can just add them together and

you can just say print my num py took

this is just a way to measure the time

that this code block took okay

all right so let's run this program here

okay says Python list of zero point zero

number I to zero point zero because this

size is pretty small so I'm going to

increase the size and do a processing

for um about a million elements here now

you can see that in order to add million

R elements from to list Python list took

116 millisecond versus numpy Y or eight

took eleven point five seconds this is

crazy fast so you can see that again

when you're processing millions and

millions of numbers it just makes sense

to use numpy Y it is also convenient

because you can see that if you want to

add two lists together you just do a 1

and a 2 a 1 plus a 2 I I will just

demonstrate that using idle because it's

this little easier to demo that in idle

so I'm going to create let's say 2 numpy

our array okay a 1 a 1 is NP dot array

it has 1 2 3 and a 2 is again n P dot

array it has let's say element 4 5 6 ok

you can do a 1 plus a 2 so it will give

you that is NC 4 + 1 5 2 + 5 7 and so on

you can also do a 2 minus a 1 you can

see you subtracted this guy from here

you can also do multiplication so a 1

cross a 2 you can do division and so on

you can do all these operations okay so

that was all about numpy our

introduction

you saw that why num py is so better

than so much better than the plain

Python list I will cover more about num

py in our next tutorial thank you for

watching
