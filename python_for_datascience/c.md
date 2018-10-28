hello everybody we are going to dive

deep into numpy by module today if you

have watched my previous tutorial you

have initial idea on what number your

module is and how to install it in this

tutorial we are going to look take a

detailed look at number wise or a object

which is the main feature of this module

so let's begin by importing num py as NP

now as you all know you can create multi

dimensional array num py using NP dot

array now this is how you create let's

say one dimensional array and you can

access it just like your list but to

create two dimensional array you can do

again this if the syntax looks pretty

similar to how you would do it with our

normal Python list so you create your

total two dimensions and you initialize

it with these lists of elements so this

is my two dimensional array now there is

this property called ending that you can

use to print the dimensions okay

so if you have let's say this array and

if you print and them it will be one but

now I have this two-dimensional array

for which the dimension would be two

okay there is item size property which

will print the byte size of each of

these elements now these are integer

elements so that's why the item size is

four bytes as you know that integers

occupy four bytes if you have float

number so let's let's initialize this

array with float is a data type now

before I do that let me print the

current data type of this array so here

it is saying it is integer 32 now if I

want to initialize the same array with a

different data type

and I need to use d-type argument so

here you can say D type is equal to NP

dot here you can say float64 so float64

is one of the types now 64 means it

occupies 8 bytes so now when you print

the item size instead of 4 it's going to

be 8 because now each of these elements

they're floor numbers and they occupy 8

bytes so if you print a here you can see

8 1 point something so this is now float

okay so let me just clear this alright

another important property that an array

has is like me just create okay so it is

sighs so size is basically the size of

your array total total number of

elements so here you can see 1 2 3 4 5 6

so it has like total six elements then

you have shape so shape represents the

information on dimension so short of

like width and height so here it is it

has 3 rows so 1 2 3 so 3 rows and 2

columns so 1 & 2 alright now we already

covered the D type D type arguments were

here I covered the D type argument let

me just copy it from here so you can use

D type to initialize your array with a

specific data type

okay so let's okay so now instead of

float64 you can also specify your type

to be the complex number so if you say

complex what is going to do is it's

going to create an array with complex

numbers now sometimes you want to

initialize your array with some

placeholder numbers let's say you want

to initialize your array

with all zeroes if and if you want to do

that you will use n P dot zeroes

function and just mention your shape

here shape means the information on your

dimension so this is creating an array

of three by four three rows four columns

1 2 3 4 all initialized with zeros you

can do same thing but with once so

instead of zeros you will say once and

it will initialize all the elements with

one number now sometimes you want to use

a function similar to range so you know

that in Python there is this range

function that we use for list right so

what this function does is it's gonna

create a list of numbers from 0 to 4 so

that's what it did now num py also has

similar function it is called a range so

you if you do NP here if you do NP dot a

range or a range basically 1 to 5 then

this is going to create array of 1 to 4

number so Phi is not included by default

that's how to even range function

behaves so this is very similar to

pythons native range function ok

now sometimes you want to do the same

thing so let's say initialize array

which from 1 to 4 but then you want to

have like steps of two numbers so this

means that you start at 1 then you take

a step of 2 so 1 plus 2 is 3 3 plus 2 is

5 but then this is your end so this is

your start this is your end and these

are like number of steps so once you

reach 5 you will stop so that's why it

is 1 & 3 here you can also use a

linspace function so let me demo

and field dot linspace - now here you

will specify your start number and n

number first okay so you will say okay

my start number is let's say 1 and my

stop number is say 5 and in between

these two numbers I want to generate

let's say 10 numbers ok so what this

will do is it will generate 10 numbers

between 1 and 5 which are linearly

spaced so you can see that you got this

nice range of 1 and 5 and then these

numbers are linearly spaced now if you

do the same thing with let's save 5 then

they are spaced by number 1 ok you can

do whatever you can do even 20 this is

pretty useful if you want to create like

this linear sequence of numbers you can

also reshape your arrays with reshape

functions so for example if you have

this array and then the shape of this

array is 3 by 2 it has 3 rows and 2

columns now let's say you want to

reshape this to be 2 by 3 so you can say

reshape 2 by 3 basically now you want to

rows and 3 columns and it would work so

you can reshape it to any dimensions

that you like and the dimension should

be compatible with your initial

dimension so you can even do a dot

reshape to be let's say you want let's

say six rows and one call

so you see six rows one column you can

also use revell function to flatten your

array so this will just flatten it make

it one dimension so you have n dimension

array when you call it or travel it will

flatten it make it one damaged all right

now when I print a after flattering it I

see that is still an original array

because a dot revell will

not touch the original array it will

return a new array so you can capture

the output into new variable and have

access to flatten structure so that

applies to all of these functions just

remember that it's not going to alter

your original array so that's something

you have to keep it in mind

now let's look at some of the

mathematical functions that are numpy

wide array cover so you have management

so let's say I have this array okay if

you do a dot min it's going to print

your minimum element which is one a dot

max will print your maximum element

which is six okay now you can also do a

dot sum and it's gonna sum all the

numbers together now there is a concept

of excess in our number array axis means

your dimensions to my X is zero will be

this columns okay and my exes one will

be these rows right here so when I do a

dot sum and when I say X is equal to

zero it's gonna look at each of this

column so it added these numbers

together 5 3 8 + 1 9 so it printed 9 6 4

10 + 2 is 12 so it's added these

together and printed 12 if you want to

sum all the elements in rows together

then you use X 1 so here 2 N 1 is 3 3 +

4 is 7 5 6 is 11 so that's what it did

so that's what the axis means here you

can also do a square root so if you do

SQ RT a dot s qrt let's see so if you do

so a dot so s square root is not a

function of individual array element

it's a generic function so you have to

do

and P dot s p RT so NP is your non-pure

module so it's going to compute the

square root of each of these numbers so

for example for square root you know is

2 then 2 square root you obviously you

don't remember but if you open your

calculator and find the square root is

going to be this okay you can also do a

standard deviation so n P dot standard

deviation so standard deviation of all

these numbers is here again no one is

going to remember this but if you do

your math then you will find that it

will be this number okay we are going to

now look at some basic mathematical

operations and for this I'm going to

have these two arrays why I just copy

pasted it from my knot pad but it didn't

work anyways I will just create it here

so I have two dimensional array here so

one two three four okay and I have this

second array okay this is my first

dimension my second dimension is PI six

seven eight

okay oops I forgot a closing angle

bracket okay so I have these two array a

a and B to be dimensional array yeah now

num py supports very basic operations

such as let's see if you want to add

them together it you can do it using

plus operator this is something you

cannot do with Python native list so

it's very convenient with num py arrays

so this added these together fine one is

six six and two is eight is basically

adding the individual elements you can

do multiplication you can do division

you can do all sorts of operation you

can also do a matrix product so if you

do a

a dot B it's gonna do matrix products of

these two individual matrices alright so

that was all about on num py or it

wasn't all about num period is actually

we still need to cover few topics such

as indexing slicing hydrating stacking

these number of errors together but all

those remaining things we are going to

cover in our next tutorial until then

thank you for watching and good luck

with your Python and numpy by learning

thanks again
