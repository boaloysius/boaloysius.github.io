hello everyone this is orders from ATO

Rekha and in today's session we are

going to focus on num py module

available in Python so let us move

forward and have a look at the agenda

for today first we'll see what is numpy

then we are going to compare it with

list and we'll see why it is better than

list then we are going to see various

operations that we can perform with

numpy arrays and there are certain

special functions as well that we are

going to focus on later in the session

so are we all clear with the agenda

timely give me a quick confirmation by

writing down in the chat box Devon says

e square so dusty on Johnny says move

forward bases go on Lavinia Jason are

you see Dorothy near or at fine guys so

I've got a confirmation from almost

everyone so let us move forward and

understand what exactly is an umpire so

what is numpy number is basically a

module or you can say a library that is

available in python for scientific

computing now it contains a lot of

things it contains a powerful n

dimensional array object then tools for

integrating with C C++ it is also very

useful in linear algebra Fourier

transform and random number capabilities

now let me tell you guys numpy can also

be used as an efficient

multi-dimensional container for data for

generic data now let me tell you what

exactly is multi-dimensional array now

over here this picture actually depicts

multi-dimensional array so we have

various elements that are stored in

their respective memory locations so we

have one two threes in their own memory

locations now why is it two dimensional

it is two dimensional because it has

rows as well as columns so you can see

we have three columns and we have four

rows available so that is the reason why

it becomes a two dimensional array so if

I would have had only one row then I

would have said that it is a one

dimensional array but since it contains

rows as well as columns that is it is

represented in a matrix form that is why

we call this as a two dimensional array

so I hope we are clear with what exactly

two dimensional arrays if you have any

questions about you can ask me any

questions

and oh are you she geography Nia Lavinia

Jason Theon Dave or a fine guy so we

have no questions so let me open my

pycharm and I will tell you practically

how to actually create an umpire Eric

so this is my Python guys over here the

first thing that you need to do is first

installed the num py module and how

you're going to do that click on file go

to settings tab and you see the project

interpreter option and on the right hand

side you'll see a plus symbols go on and

type the module that you wanna install

so I'm going to install numpy wises go

there click on it and install package

I've already done that so I'm not going

to repeat it so this is my PI charms the

first thing that I need to do is import

numpy Y as NP now after that I need to

create a num py RA so for that I'm going

to define a variable that it be a and

I'm going to type in here NP dot array

and certain elements inside it so I'm

going to put in 1 2 3 and a print hit

that's all

this will actually print a single

dimensional arrays so 1 2 3 has appeared

now if I wanna convert this to a 2d

array so for that I'll keep this in

parentheses and after a comma I'll add

one more element and I'm going to give

certain values inside that so I can give

say 4 5 and 6 now go ahead and print

this so as you can see that it is now a

two-dimensional array so this is ru a

quickly at our edge using num py module

if you have any questions or doubts you

can ask me they say these clear so dusty

on Allen though I usually geography fine

alright so we have no questions so now

I'm going to open my slides and we'll

move forward and see what is our next

topic now let us see why I will be using

numpy instead of a list

all right so many of you might be

thinking why are we using numpy why when

we have lists all right so basically we

use them py because of three main

reasons the first thing is it occupies

less memory when compared to lists then

it is actually pretty fast when you are

compared with list and at the same time

it is very convenient to work with numpy

Y so these are the three major

advantages that num py has over list and

that is the reason why we use numpy why

instead of list now don't worry I'm

actually going to prove it to you

practically by

bring my pycharm so why this is my

pycharm again the first thing that I

need to do is import numpy why as empty

and now what I'm going to do is I'm

going to import a couple of more modules

I'm going to import time I'm going to

import sis all right done so our first

step is to actually define a list and

the name that I'm going to give to my

list is say s and I'll type in here

range thousand so what this will

actually do it will actually take all

the integer values between 0 to thousand

and it will give it to a variable s so

this list will contain the integer

values between 0 to 2000 but 8 more in

2000 it will be only there till triple

night that is 999 and now I'm going to

print the space occupied with this

particular listed are what I need to do

it in to type and print sis dot get size

off any one element okay so you can give

3 4 5 anything I'm going to give it as 5

any one element and multiply that with

the length of my list that's all so this

will actually give me the space that has

been occupied by the list because sis

dot get size off will actually give me

the memory occupied by one element and

when I multiply that with length of my

list

I get the entire memory that I will be

occupied by my list now the same I'm

going to do with my num py array as well

let me give a name to that I'm gonna

type in D NP taught a range and the

range will be thousand now a range

function is pretty much similar to the

range which is there so the same thing

will happen here the integer values

between 0 to thousand but it won't in

few thousand will be present in my

variable T so we have created an um py

array now let us print the space

occupied by it so the first thing is I'm

going to type in here d dot size so this

will actually give me the space occupied

by one single element and when I

multiply that with the length of my num

py RA

I get the entire memory that is occupied

by the numpy Y array so I'm going to

type in here

d dot item size that's all now go ahead

and print this so this actually shows

the memory that has been occupied by my

list and this shows the memory that has

been occupied by my num py addict so as

you can see there is a quite a lot of

difference between both of them so we

have proved the first point that it

actually occupies less memory now when I

talk about num py array is faster and

more convenient than the list so the

next step is I'm going to prove it to

you that num p/yr a is actually faster

and more convenient than list so I

remove all of this and so now I'm going

to show you that num py arrays are

faster than lists and at the same time

it is easier and more convenient in

order to work with num py r is when

compared to lists let me show you

practically so first what I'm going to

do is I'm going to define our variable

say size which is equal to say 1000 and

then I'm going to define two lists now

what I'm going to do is I'm going to add

those two lists as well as I'm going to

add two numbers I added which I'm going

to define now and then I'm going to

compare the time taken in order to find

the sum for list and the sample numpy y

RS so first let me define two lists and

to arrays for my first list will be

equal to range size same goes for my

second list as well

just change the name to l2 and now I'm

going to define two numpy virus a1 equal

to NP dot a range size go ahead and do

the same for the second numpy wide array

as well and change the name as a two so

we have two lists and two arrays and we

need to compute the sum of both of these

lists as well as address now before that

I'm going to define a variable say start

which is equals to time dot time and now

I'm going to calculate the sum so I'm

going to save that in result and first

I'm going to calculate the sum of Lists

that is L 1 and L 2 so for that what I

need to do is I need to run a for loop

because if I directly write L 1 plus L 2

it is going to give me a result which is

nothing but the concatenation of both

the lists so in order to calculate the

sum I need to use for loop let me show

you how to do that first

I'm going to type in X comma Y and we

have already studied loops and detail

for X comma Y in zip and the name of the

tool list that is l1 comma l2 that's all

so what will happen here it will first

take the first element of list l1 and

then it'll take the first element of

list l2 it will go in it will calculate

some and store in result and then you

keep on repeating until the range has

been exceeded now this is how you

calculate sum in list but when you talk

about arrays what you need to do is you

need to just write in a 1 plus a 2

that's all that's why I'm saying that it

is more convenient in order to work with

num py arrays and compared to lists now

our next step is now our next step is to

define the same variable start and

initialize it with time dot time and now

I'm going to find the sum of my - num py

RS which is nothing but a1 plus a2

that's all and now print the time taken

so print time dot time - start and then

multiply it with thousand because by

default it will take it in seconds and I

need to convert it into milliseconds now

I forgot to actually print the same

thing for my list so I'm going to do it

over here so this will actually give me

the time taken by my list in order to

compute the sum and this statement will

give me the time taken by my num py

array in order to compute the sum so of

your clear till here if you have any

doubts or questions you can ask me any

questions guys alright so we have no

questions so let us go ahead and execute

this and still see what happens so it

gives me 0 milliseconds because the size

is small let me star a couple more zeros

let's make it a million now go ahead and

execute this now you can notice the

difference that there is a significant

change lists took 208 milliseconds

whereas num p/yr it took almost 67

milliseconds so there is a huge

difference between the compute time of a

list as well as num py array that's why

I say that num py array are faster

convenient and at the same time they

occupy less space

compared to lists so that is the reason

why we choose mpy a days over list if

you have any questions doubts you can

ask me any questions guys any questions

alright so we have no questions so let

us go ahead and move forward towards the

next topic that is num py operations so

let me go back to my slides so now is

the time to see various operations that

you can perform with the num py Alice so

you can find at the dimension of your

array whether it is a two-dimensional or

a single dimensional array then you can

even calculate the bite size of each

element it is pretty easy I'm going to

tell you that practically you don't need

to worry about that and you can even

find the data types of the elements that

are stored in your array so if you want

to know what is the data type of the

elements you can do that as well so let

me show you these three operations first

and then we'll move forward to the other

operations I'm going to open my Python

ones for guys let me remove all of this

so we have imported the num py module

now what I'm going to do is I'm going to

define a numpy Y array I'm going to name

it as a and I'll write here n P dot

array 1 comma 2 comma 3 put that in

parenthesis now add one more element say

2 comma 3 comma 4 all right so it's a

two dimensional array now if I want to

know whether it's a two dimensional or a

single dimensional array so I'm just

going to type and print it dot end them

and it'll give me the dimension so let

me show you that and I'm going to run

this so it says 2 that means it is a two

dimensional array so what if I move this

part and make it as a single dimensional

array it should give us the result as

one let's see if it does that or not and

yep it gives us one as a result so this

is how you actually calculate the

dimension of Ferrari now if you want to

find a bite size of each of the elements

so what you need to do is instead of end

him you can call a function called item

size go ahead execute this and you'll

get so each element occupies 4 bytes

after if you want to know the datatype

that is stored in the array so you can

just type in

d-type go ahead execute this it should

give us integers integers 32-bit alright

so this is how you can actually perform

the b3 function that I've told you in my

slides it's pretty basic if you have any

questions or doubts you can ask me

alright so we have no questions so let

us proceed with the presentation now let

us move forward and see one of the other

operations that you can perform with num

py module so by using num PV array you

can actually find the size of your

addict how you can do that that I will

show you practically you don't need to

worry about that so when I say size of

the array that means the total number of

elements are present at the Attic so if

this is an array of the total number of

elements become 4 1 2 3 & 4

now you can even find the shape of your

array now what do you mean by shape so

basically the total number of columns

and rows now over here we have 3 columns

and four rows so our shape is actually

three columns and four rows now let me

show you practically how you can do that

again I'm going to open my pycharm and

show you let me remove this print

statement from here now if I want to

find the size of my num py array I just

need to type in print a dot size that's

all you have to do and it'll give the

size of your honor so there are three

elements if I go on and add some more

elements say 4 5 6 7

then if I execute this you'll see that

seven elements have appeared that means

the total number of elements in my array

is 7 then comes the shape part that I

was talking about so in order to find

the shape what you can do is you can

just type in here a dot shape and it

will give you the shape so let us see

what happens so it has 7 columns but

there are no rows so it has given 7

comma black so what I can do is I can

close this in parenthesis and I can

define one more element say 8 9 10 11 12

13 14 go ahead and execute this and you

can see 2 comma 7 because we have two

rows and seven columns available with us

so this is how you can actually find the

size of your array as well as you can

find the shape of your array now let us

move forward and see what are the other

operations that you can perform with num

py module so we saw how to find the size

and the shape of an array so we can

perform reshape as well as slicing

operation using numpy why

now when I talk about reshape what do

you actually mean by reship can I get

some answers guys anyone

all right so Devon says when you change

the number of rows and columns that is

called reshaping all right fine that is

absolutely corrective on and I've got

correct answers from other people as

well our nails will say the same so does

Jason Janice jaggedy all right fine

so if that is absolutely correct guys

now over here there is an example so we

have three columns and two rows which we

have converted to two columns and 3 rows

now let me show you that practically how

you can do it in a variable and I'm

going to start a num Pira and I'll have

two elements in that my first element

will be 1 comma 2 comma 3 comma 4 and my

other element will be say 3 comma 4

comma 5 comma 6 so I have a

two-dimensional array that contains 2

rows and 4 columns now I can convert

that to 4 rows into columns let me show

you how to do that you're just going to

type in a is equal to 8 dot reshape and

I'm going to convert it to say 4 rows

and 2 columns go ahead and trim this so

it has converted that to 4 rows and 2

columns as you can see in front of your

screen now let me show you that earlier

this is not the case I'm going to type

in a print statement here as well in

order to show you that how it has

reshaped so earlier we had four columns

as well as two rows but now we have two

columns are four rows so this is how you

can perform the reshape operation now

let us talk about slicing so slicing is

basically extracting particular set of

elements from your array and the slicing

operation that happens there is pretty

much similar to the one which is there

in lists as well so suppose if I want

only this particular element that is 3

so for that what I need to print

I'll show you print a and the index

value of 3 which is present at 0 comma

and the index is 2 let me tell you how

indexing happens so this element will be

0 this element will be 1 now if I want 3

from here

the from the zeroth element I want the

index to indexing starts from 0 1 & 2 so

that's why I've written 0 comma 2 and it

should print 3 for me let us see if it

does that or not and yep it prints 3 now

say if I want to print 4 & 6 now for

that what I need to do is I need to

remove this 2 here and I'm going to put

a colon that says all the rules

including 0 and in that row I want only

index 3 so we have only 2 rows so if I

would have written 0 colon 1 then it

wouldn't have included this particular

row so if I have one more element here

so I can actually write here too so that

would actually include the element which

is present of the second index so when I

say 0 colon this actually means all the

rows that infused 0 as well so we have

only 2 rows it will include both the

rows and at the same time it will

actually going to print the third index

from both of these rows so let me show

you if that happens or not and yep it

happens we have 4 & 6 available with us

now just to remove confusion what I'm

going to do is I'm going to add one more

element and I'm going to give values to

it say seven eight nine and ten

so now if I want four and six I can't

just write 0 colon because if I do that

it'll print 10 as well let me show you

that yep it has printed 10 now in order

to avoid that what I can do is I can

write in here too so I've told you this

is the 0th element first element and the

second element so when I write 0 colon -

it won't include this second element

he'll only infused 0 as well as the

first element now inside that we have

index 3 from both of these rows that is

I will actually get 4 and 6 never see if

that happens or not and you can see 4 &

6 is now available so this is all you

can perform slicing when we in numpy by

RS now what I'm going to do is I'm going

to type in a equal to NP dot line space

and now over here first I write 1 comma

say 3 and I want say 5 values between 1

comma 3 what this will do is it'll

actually print the five values which are

equally spaced between one two three so

let me print this first I'm going to

type in print a and go ahead exit

you this and you can see that we have

one then we have 1.5 then we have to 2.5

as well as 3 so if I would have written

here 10 it'll actually give me 10 values

between 1 2 3 and yep you can see we

have 2 10 values between 1 2 3 so this

is how you can perform line spacing as

well so any questions or any doubts till

now guys you can ask me so there are no

questions will be open my slides and

we'll see what other operations that you

can perform with numpy why so we saw how

to perform reshaping and slicing now let

us see what are the other operations so

we are now going to find out the minimum

maximum as well as the sum of our numpy

by arrays so let us go ahead and execute

that practically let me remove all of

this and now I'm going to find one more

num py ra n P dot array and I want

elements in it say 1 2 3 now if I want

to find the element which has the

maximum value so what I can do is I can

just type in here friend a dot max

that's all and it will give me the

maximum value in my a numpy yr a which

is 3 obviously if I want to find minimum

value so I'm just going to type in here

min and we print the same for me which

is 1 now if I want to calculate sum it

is pretty easy just go on and type sum

and it will give you this sum that's all

guys it start simple I pretty sure there

won't be any doubts here if there are

you can just ask me fine so there are no

doubt so Johnny's have the question

she's asking me is it that simple to

work with non py already on it so let me

tell you that whatever I'm telling you

these are all the basics that you

require after that whatever your

requirement is there on that basis you

need to use those basic knowledge that

you have and implement it now the best

way to do that now the best way to

understand any programming language is

to play around with it so you know the

basics with the help of those basics

just install Python first and try out

new things like how should I get that

how should I get this and if I'm not

getting it what is the reason behind it

so go on and try to discover new new

things so the conclusion is you need to

actually perform things practically you

need to make sure that you are not only

getting the theoretical knowledge you

need to perform it practically that's

why I always say the type

I said when I'm executing these

particles you need to do that as well

although you might find it pretty basic

but with the help of this knowledge you

can perform a lot bigger tasks as well

all right the Janus looks happy now so

let's move forward to the slides so now

comes the axis concept here guys it is

pretty similar we have an umpire array

which looks like this and zeros are

called axis one and columns are call

axes zero

now you must be thinking what is the use

of this axis suppose if you want to

calculate the sum of all the rows then

you can actually use the axis and you

can do that now let me show you

practically how it happens I'm going to

open my pie charm again and I'm going to

show it to let me remove this and let me

add one more element here 3 comma 4

comma 5 all right so if I want to find

the sum of axis 0

it's very very easy just go on and type

print a dot sum and type in axis equal

to 0 go ahead and print this and you can

see 4 6 & 8 1 plus 3 is 4 2 plus 4 is 6

similarly three plus five is eight if I

make this as axis one and print this so

it gives me 6 and 12 because 3 plus 2

plus 1 is 6 similarly 4 plus 5 plus 3 is

12 so this is pretty easy I know now let

us go back to our slide and see what are

the other operations so there are many

mathematical functions that you can

perform with numpy why that is to find

the square root of each element you can

even find the standard deviation all

right so we have a question popped on my

screen and dave is asking me what

exactly you mean by standard deviation

or it's a standard deviation basically

means that whatever the elements that

are there in your npy are a do you find

the mean of that and you actually find

out how much each element deviates from

that means that exactly is standard

deviation I hope this answers a question

all right so these two operations can be

performed with the help of numpy why you

can find the square root you can find

the standard deviation now let me show

you that how you can do it

this is my pie charm again so now I'm

going to remove this print statement

here

I want to print the square root of each

of the elements that are there in Magnum

PU IRA which is actually assigned to a

variable a so I'm going to type in her

print n P dot s QR T that is square root

of mine mpy array a go ahead and execute

this and it is actually printed the

square root of each of the elements of

the square root of 1 is 1 for 2 it is 1

point 4 1 4 4 3 it is 1.73 I gave a 3 it

is 1.73 then for 4 it is 2 then for five

it is 2 point 2 3 this is how you can

find the square root of each of the

element now when I talk about standard

deviation so you can find that by typing

here so now if I want to find it started

deviation what I need to do is instead

of sq RT I will just type in an STD and

it will give you the standard deviation

that is how much each element varies

from the mean value of mynum py re and

this is the standard deviation guys it

starts simple so this is how you find

standard deviation now let's go back to

our slides and see what are the other

operations that are still left now these

are the basic mathematical functions

that you can perform with mum py RS like

addition multiplication subtraction and

division and that will actually happen

element wise so basically you are

performing matrix addition matrix

multiplication matrix division as well

as matrix subtraction let me go ahead

and show it to you practically it is

very very simple guys so similarly I'm

going to define one more array and let

me name it as D let me remove this print

statement now if I want to calculate the

sum so what I need to do is I need to

type and print a plus B that's all you

need to do but when I talk about lists

again I'm telling you that when I talk

about lists if I do that it will

concatenate both lists so if I want to

print list that is the addition of two

lists I need to use for loop so that is

where numpy wire is stands apart and it

is pretty convenient go ahead and

execute this and you see that element

wise addition has happened 1 plus 1 is 2

2 plus 2 is 4 3 plus 3 is 6 similarly 3

plus 3 is 6 then 4 plus 4 is 8 pi plus 5

is 10 all right so

this is how you can perform addition you

can perform subtraction by using the

subtraction operator go ahead execute

this and you'll find all zeros because 1

minus 1 2 minus 2 3 minus 3 3 minus 3 4

minus 4 PI minus 5 will be 0 only right

no rocket st. now go ahead and multiply

it as well and see what happens so you

have 1 into 1 is 1 2 into 2 is 4 3 into

3 is 9 again 3 into 3 is 9 4 4 16 5 into

5 is 25 if I go ahead and divide this it

will give me all ones and yep it does so

this is how you can actually perform

addition subtraction multiplication and

division using a numpy y RS now let me

go back to my slides and see what are

the other operations present so now guys

let me tell you one more thing if I

actually want to concatenate two arrays

I don't just want to add those two

arrays you can say that if my one adder

is a box then I want another array on

top of it so let me show you how you can

do that actually there are two ways to

do that one is called vertical stacking

and another is called horizontal

stacking let me show it to you one by

one first I'm going to show you vertical

stacking without what I need to do is

print n P dot V stack and a comma B let

us see what happens when I run this so

we have 1 2 3 3 4 5 then again we have 1

2 3 & 3 4 5 so this is called vertical

stacking if I want that horizontally

I'll just write in here H stack and I'm

going to run this now and you can see

that we have 1 2 3 then again 1 2 3 that

means these two are present added

horizontally and we have 3 4 5 again we

have 3 4 5 so this is how you can

perform stacking as well now there's one

more thing that I want to show you if I

actually want to convert this particular

in numpy y array that is a to say a

single column so how I can do that

thus type in here print a dot revell

that's all you have to do go ahead and

execute this so now 1 2 3 3 4 5 so you

have 1 2 3 3 4 5 let me go back to my

slides and see what are the other topics

that we are going to cover now come

certain numpy Y special functions now

I'm going to talk about sine function

and cosine function first now I hope all

of us know what is a sine function and

what is the cosine function if you have

any doubt

with respect to what these two are you

can ask me although I'm pretty much

expecting that you guys know this all

right so I've got answers all right so

I've got answers from almost everyone

and they say that they know it fine guys

so what I'm going to do is I'm going to

use this cosine and sine function I'm

going to plot sine and a cosine graph so

for that I'm going to import a module

called matplotlib so you don't need to

worry about that module because I'm

going to discuss about matplotlib in the

upcoming sessions so there'll be a

detailed session especially on

matplotlib so you don't need to worry

about what exactly matplotlib is and how

it works and all those things because

that'll be covered in the upcoming

session for now what we are going to do

we are just going to use sine and cosine

function in order to print their graph

so that I'll open white pycharm and let

me remove this and import my plot lip

dot pie plot as PLT now we are going to

define two coordinates that is x and y

first x is equal to NP dot arrange 0

comma 3 n 2 NP dot pi comma 0 point 1

now I'm going to find y so for that I'll

type y NP dot sine X now I'm going to

use PLT in order to plot the graph X

comma Y now finally show the plot for

that I'll type plot dot show you must

plot that show to make a graphics up

here so plot dot show and here we go

go ahead and execute this and you might

be able to see a graph and yep it is

here

similarly for if I change the sign to

cause and should give me the cosine

graph go ahead and run this and you can

see we have a cosine graph as well

similarly if I write in air tan that is

any other trigonometric function and I

print this so I get the graph for tan as

well so any doubt still here guys no

doubts fine so

open my presentation once more and we

are going to see what are the other

special functions that we can use with

num py now num py comes with two very

good functionality that would say that

is called exponential function and in

logarithmic functions

now exponential this e value is

somewhere equal to point seven and we

all know load so when I talk about log

it is actually log base 10 and when I'm

talking about natural log that is log

base E I will write it as Ellen so

instead of that I've written log that

means log base 10 so you can perform

these operations with the help of num py

let me show you how you can do that or

before that if you have any questions

with what exactly these two things are

you can ask me this is pretty basic

alright so no questions fine I suppose

everyone know about this so I'll open my

pycharm let me remove this and I'm going

to define a non py array let it be a are

equal to NP dot array 1 comma 2 comma 3

now I want to calculate the exponential

value I'm going to throw in a print

statement and I'm going to write in here

n P dot exp AR and this will calculate

the exponential value for me and let us

see if a does that or not so up as I've

told you earlier as well value of e is 2

point 7 1 so e to the power of 1 is

actually equal to e so it has it

returned the e value but e to the power

of 2 will be somewhere equal to seven

point three eight e to the power of

three will be some very equal to 20

point zero eight five five now in order

to calculate log what you can do is you

can just type in here log now this will

give you natural log so when I talk

about natural log it is nothing but Ln

or you can say log base E but if I want

to calculate log base 10 so I need to

type in here ten first let me show you

how you can find the natural log just go

ahead and execute this alright so when I

talk about one so e to the power of zero

will be equal to one right so log or Ln

a are equal to zero similarly the other

values as well now if I want log base

ten instead of Ln or you can say natural

log I can just write in ten and go ahead

execute this and you'll find

log base 10 values so obviously when

answer is one that means anything to the

power of zero is equal to one so your

answer will be zero here and similarly

we have other answers as well if you are

pretty if you're unsure about it you can

open your calculators and do that or

it's 11 essays I trust you thank you

love and err for those kind words let me

open my slides once more and by this we

come to the end of today's session if

you have any questions or doubts you can

ask me right now John is say the amazing

session

thank you John is for those kind words

Jessica say is very informative Thank

You Jessica

all right fine guys so let me give you a

brief summary of what all things we have

discussed first we saw what exactly is

lump I then we compared umpire with list

and we understood why we use numpy

instead of lists then we saw various

numpy operations like slicing stacking

addition subtraction multiplication all

those things then we focus on certain

special functions like sine and cosine

functions thank you guys for attending

today's session this video will be

uploaded into your LMS so you can go

through it if you have any questions or

doubts you can ask our 24/7 support team

or you can even bring your doubts in the

next class as well thank you and have a

great day I hope you enjoyed listening

to this video please be kind enough to

like it and you can comment any of your

doubts and queries and we will reply to

them at the earliest to look out for

more videos in our playlist and

subscribe to our at Eureka channel to

learn more happy learning
