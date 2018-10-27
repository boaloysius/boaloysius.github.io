Hello workd, in this blog we will look into Numpy or the numerical python module. It is extremely popular in Python community and it is heavily used for Scientific Computing and Data Science. We will see why it is so popular.

To get started we will install the module. Download and install the module by running
```python
pip install numpy
```

As given in their official documentation, NumPy derives from an old library called Numeric, which was the first array object built for Python. The most basic object in NumPy is the ```ndarray```, or simply an ```array```, which is an **n-dimensional, homogenous** array. By homogenous, we mean that all the elements in a numpy array have to be of the **same data type**, which is commonly numeric (float or integer). 


Let's import numpy and create a first array object.

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


you will use NP dot array and in this

bracket you just pass down your list so

this is my number Y array if you look

into it now this is sort of similar to a

list it is actually very similar to a

list you can access the elements by

index it looks like a list so the

question is I only have a list why do I

need this number Y array well there are

several benefits of using numpy array

there are three main benefits first is

it requires less memory it is fast and

convenient and will go or all these

three benefits one by one okay so

essentially what we are doing is we are

comparing numpy Y with number Y array

with a Python list here okay

so let's first create a Python list I'm

just going to say range thousand so I

created a list which has thousand

elements here and I'm going to print the

size of the list now to print the size

you need to get a size of one

one element so one element here is one

number you can give any number here and

then lengths off your list second I am

going to create a non py array so this

is how you create an umpire array this

function a range is similar to range is

going to create an array with element 0

to 99 okay so the size of this numpy

array would be thousand and to print the

size of this array you need to call

array dot size so or a dot size will

give you thousand ok and the size of

every element will be I will be item

size so just remember that added or item

size is size of one element vs. added of

size is the total length of an array

when you run this program you'll notice

that the Python list is taking taking 14

thousand bytes versus number wise taking

only four thousand bytes now this is

because your Python are the size of one

Python object is like 14 okay and what's

the size of one number why are a object

is here in this case since we are

storing integer numbers it is only four

bytes okay so if you look at this

diagram it kind of should this shows the

memory presentation of our list and

number I array on the left hand side we

have numpy array which points to

continuous or contiguous location of

memories where you have all your element

store 1 2 3 4 5 and so on and each of

these element contain is occupying 4

byte of memory versus in case of Python

lists you all know that in Python

everything is an object so the list will

contain a list of pointers first as you

can

see in the diagram and each pointer will

then point to another location in the

memory which will be your object and the

size of that one object will be 14 bytes

so this is the reason why or numpy why

array the mammal usage is very less

compared to a plain Python list now when

you are array size all this size is very

small you won't notice much difference

but let's say you are dealing with the

heavy amount of data where you have

millions and billions of numbers to

process in that case it will make sense

to use numpy why all right

the second advantage of numpy why is

that it is fast and convenient so let me

prove that point as well so I am going

to what I'm going to do here is alright

let me just close this guy here and I'm

going to now create here two lists first

call it alone and l2 okay so range

sighs so size is thousand here and l2 is

also similar so I created two lists here

and then I am going to create two array

so NP dot a range again to create a

number Y array and then second array

will be called a two okay now I want to

measure the time between list processing

and number your array processing so for

this you use start is equal to time to

time and now what I'm going to do is see

the thing the operation that I am doing

here is I am adding these two lists I am

adding these two lists and producing a

new list call call it result okay

so to order these two lists you have to

do something like this X plus y for X Y

in zip l1 l2 what this will do is it

will take first element from l1 first

elements from l2 add them together and

put it in this result as a first element

so it will just add in usual elements

from these two lists and put it in a

result okay pretty straightforward and I

am just going to say Python list too

this much time so right now the time is

this I am going to subtract start from

here and I'm going to multiply this guy

with thousand because by default it is

in second I want to print milliseconds

here all right now again at this point I

will capture time one more time and then

I will store result here so now so this

was your Python list okay so let me just

say Python list and here now I am

processing numpy Y array so that's the

difference between these two code blocks

or now num py is also convenient because

if you want to add two arrays you just

say a1 plus e2 right so it is not like

you have to write a list comprehension

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
