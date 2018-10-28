hello everybody<font color="#E5E5E5"> we are going to dive</font>

deep into numpy by module today<font color="#CCCCCC"> if you</font>

have watched<font color="#E5E5E5"> my previous tutorial you</font>

have initial<font color="#E5E5E5"> idea on what number</font><font color="#CCCCCC"> your</font>

module is and how<font color="#E5E5E5"> to install</font><font color="#CCCCCC"> it in this</font>

tutorial<font color="#E5E5E5"> we are</font><font color="#CCCCCC"> going to look take a</font>

detailed look at number wise or a object

which is<font color="#E5E5E5"> the main feature of this module</font>

<font color="#CCCCCC">so let's begin by</font><font color="#E5E5E5"> importing</font><font color="#CCCCCC"> num py as NP</font>

now as you<font color="#CCCCCC"> all know</font><font color="#E5E5E5"> you can create multi</font>

dimensional array<font color="#CCCCCC"> num py</font><font color="#E5E5E5"> using NP dot</font>

array<font color="#E5E5E5"> now this is how you</font><font color="#CCCCCC"> create let's</font>

say<font color="#E5E5E5"> one dimensional array</font><font color="#CCCCCC"> and you can</font>

access<font color="#CCCCCC"> it just like your list</font><font color="#E5E5E5"> but</font><font color="#CCCCCC"> to</font>

<font color="#CCCCCC">create two dimensional array</font><font color="#E5E5E5"> you can</font><font color="#CCCCCC"> do</font>

again this if the<font color="#E5E5E5"> syntax looks pretty</font>

<font color="#E5E5E5">similar to how</font><font color="#CCCCCC"> you would</font><font color="#E5E5E5"> do</font><font color="#CCCCCC"> it with</font><font color="#E5E5E5"> our</font>

normal Python list so you create your

total two dimensions and<font color="#CCCCCC"> you initialize</font>

it with<font color="#E5E5E5"> these</font><font color="#CCCCCC"> lists of</font><font color="#E5E5E5"> elements so this</font>

<font color="#E5E5E5">is my two dimensional array now there is</font>

<font color="#E5E5E5">this property called ending that you can</font>

use to print the dimensions<font color="#CCCCCC"> okay</font>

so if you have let's say<font color="#E5E5E5"> this array and</font>

if you print and them it<font color="#E5E5E5"> will</font><font color="#CCCCCC"> be one but</font>

<font color="#E5E5E5">now I have this two-dimensional array</font>

for which the dimension<font color="#E5E5E5"> would be two</font>

okay<font color="#E5E5E5"> there is item size</font><font color="#CCCCCC"> property which</font>

will print the byte size of each<font color="#CCCCCC"> of</font>

these<font color="#CCCCCC"> elements now these are integer</font>

elements so that's why the item size is

<font color="#CCCCCC">four bytes</font><font color="#E5E5E5"> as you know that integers</font>

occupy<font color="#E5E5E5"> four bytes</font><font color="#CCCCCC"> if you have float</font>

number so let's let's initialize this

array with<font color="#E5E5E5"> float is a data type now</font>

before I do that let me<font color="#E5E5E5"> print the</font>

current<font color="#E5E5E5"> data type of</font><font color="#CCCCCC"> this array so here</font>

it is saying it is integer 32<font color="#E5E5E5"> now if I</font>

want<font color="#CCCCCC"> to initialize</font><font color="#E5E5E5"> the same array with a</font>

different data type

and I need to use<font color="#CCCCCC"> d-type argument</font><font color="#E5E5E5"> so</font>

here you can say<font color="#E5E5E5"> D type is equal</font><font color="#CCCCCC"> to NP</font>

dot here you can say float64 so float64

is one of the types now<font color="#E5E5E5"> 64 means it</font>

occupies<font color="#CCCCCC"> 8 bytes so now when you print</font>

the item size<font color="#E5E5E5"> instead of 4</font><font color="#CCCCCC"> it's going</font><font color="#E5E5E5"> to</font>

be 8<font color="#E5E5E5"> because now each of these elements</font>

<font color="#CCCCCC">they're floor numbers and they occupy</font><font color="#E5E5E5"> 8</font>

bytes so if you print a here<font color="#E5E5E5"> you can see</font>

8<font color="#E5E5E5"> 1 point something so this is now float</font>

<font color="#E5E5E5">okay so let me just clear this</font><font color="#CCCCCC"> alright</font>

<font color="#E5E5E5">another important property</font><font color="#CCCCCC"> that an array</font>

has is like<font color="#E5E5E5"> me just create</font><font color="#CCCCCC"> okay so it is</font>

sighs so size is basically the size of

your array total total number of

<font color="#E5E5E5">elements so here</font><font color="#CCCCCC"> you can see 1 2 3</font><font color="#E5E5E5"> 4 5 6</font>

so it has like total<font color="#CCCCCC"> six elements then</font>

<font color="#CCCCCC">you have shape so shape represents the</font>

<font color="#CCCCCC">information on dimension so short</font><font color="#E5E5E5"> of</font>

like width and height so here it is it

<font color="#E5E5E5">has</font><font color="#CCCCCC"> 3 rows</font><font color="#E5E5E5"> so 1 2 3 so 3 rows and</font><font color="#CCCCCC"> 2</font>

columns so<font color="#E5E5E5"> 1</font><font color="#CCCCCC"> &</font><font color="#E5E5E5"> 2</font><font color="#CCCCCC"> alright</font><font color="#E5E5E5"> now we already</font>

covered<font color="#E5E5E5"> the D type D type arguments were</font>

here<font color="#E5E5E5"> I</font><font color="#CCCCCC"> covered</font><font color="#E5E5E5"> the D type argument let</font>

me just copy it from<font color="#E5E5E5"> here so you can use</font>

D type to initialize your<font color="#E5E5E5"> array with a</font>

<font color="#E5E5E5">specific data type</font>

okay so<font color="#E5E5E5"> let's</font><font color="#CCCCCC"> okay so now instead of</font>

<font color="#E5E5E5">float64 you can also specify your type</font>

to be the complex number so if<font color="#CCCCCC"> you say</font>

complex<font color="#E5E5E5"> what is</font><font color="#CCCCCC"> going to do is it's</font>

<font color="#E5E5E5">going to create an array with complex</font>

<font color="#E5E5E5">numbers now sometimes you want to</font>

initialize your<font color="#E5E5E5"> array with some</font>

placeholder numbers let's<font color="#E5E5E5"> say you want</font>

to initialize<font color="#CCCCCC"> your array</font>

with all<font color="#CCCCCC"> zeroes</font><font color="#E5E5E5"> if and if you want to do</font>

that you will use<font color="#E5E5E5"> n P dot</font><font color="#CCCCCC"> zeroes</font>

function and just mention<font color="#E5E5E5"> your shape</font>

here shape means the<font color="#E5E5E5"> information on</font><font color="#CCCCCC"> your</font>

dimension so this is<font color="#E5E5E5"> creating an array</font>

of<font color="#E5E5E5"> three by four three rows four columns</font>

1<font color="#CCCCCC"> 2 3 4 all initialized with zeros you</font>

can do same thing but with<font color="#CCCCCC"> once</font><font color="#E5E5E5"> so</font>

instead of<font color="#E5E5E5"> zeros you will say once and</font>

it will initialize all<font color="#CCCCCC"> the elements with</font>

one<font color="#CCCCCC"> number now sometimes you want to</font><font color="#E5E5E5"> use</font>

a function similar to range<font color="#E5E5E5"> so you know</font>

that in<font color="#E5E5E5"> Python there is this range</font>

function that we use for<font color="#E5E5E5"> list right so</font>

what this<font color="#E5E5E5"> function does is it's gonna</font>

<font color="#E5E5E5">create a list of numbers from 0 to 4 so</font>

that's what it did now<font color="#CCCCCC"> num py also has</font>

similar function it<font color="#E5E5E5"> is called a range so</font>

<font color="#CCCCCC">you if</font><font color="#E5E5E5"> you do</font><font color="#CCCCCC"> NP here if you do NP dot a</font>

range<font color="#E5E5E5"> or a range basically</font><font color="#CCCCCC"> 1 to 5 then</font>

this<font color="#E5E5E5"> is going</font><font color="#CCCCCC"> to create array of</font><font color="#E5E5E5"> 1 to</font><font color="#CCCCCC"> 4</font>

number so Phi<font color="#E5E5E5"> is not included by default</font>

<font color="#E5E5E5">that's how to even range function</font>

<font color="#E5E5E5">behaves so this is very similar to</font>

pythons native range function<font color="#CCCCCC"> ok</font>

now sometimes<font color="#E5E5E5"> you want</font><font color="#CCCCCC"> to do the same</font>

thing so<font color="#CCCCCC"> let's say initialize array</font>

which from 1 to 4 but<font color="#E5E5E5"> then you want</font><font color="#CCCCCC"> to</font>

have<font color="#E5E5E5"> like steps of two numbers so this</font>

means<font color="#CCCCCC"> that</font><font color="#E5E5E5"> you start at 1 then you take</font>

a step<font color="#E5E5E5"> of 2 so 1 plus 2</font><font color="#CCCCCC"> is 3 3 plus 2 is</font>

<font color="#E5E5E5">5 but then this is your</font><font color="#CCCCCC"> end so this</font><font color="#E5E5E5"> is</font>

your start this is your end<font color="#E5E5E5"> and these</font>

are like number of steps<font color="#CCCCCC"> so once you</font>

reach 5 you will stop<font color="#CCCCCC"> so that's why it</font>

is 1<font color="#CCCCCC"> & 3</font><font color="#E5E5E5"> here you can also use a</font>

<font color="#CCCCCC">linspace</font><font color="#E5E5E5"> function so let me demo</font>

and field dot linspace<font color="#CCCCCC"> -</font><font color="#E5E5E5"> now here you</font>

<font color="#E5E5E5">will specify your start number and n</font>

<font color="#E5E5E5">number first okay so you will say okay</font>

<font color="#CCCCCC">my start</font><font color="#E5E5E5"> number is let's say 1 and my</font>

stop number is say<font color="#E5E5E5"> 5 and in between</font>

<font color="#E5E5E5">these two numbers</font><font color="#CCCCCC"> I want</font><font color="#E5E5E5"> to generate</font>

<font color="#E5E5E5">let's say 10 numbers</font><font color="#CCCCCC"> ok</font><font color="#E5E5E5"> so what this</font>

will do is<font color="#E5E5E5"> it</font><font color="#CCCCCC"> will generate</font><font color="#E5E5E5"> 10 numbers</font>

between 1<font color="#E5E5E5"> and 5 which are linearly</font>

spaced<font color="#E5E5E5"> so you can see that you got this</font>

nice range of<font color="#E5E5E5"> 1 and 5 and then these</font>

<font color="#E5E5E5">numbers are linearly spaced now if you</font>

do the same thing with let's<font color="#E5E5E5"> save 5 then</font>

they are spaced by<font color="#E5E5E5"> number</font><font color="#CCCCCC"> 1 ok</font><font color="#E5E5E5"> you can</font>

do whatever you can do even<font color="#E5E5E5"> 20 this is</font>

<font color="#CCCCCC">pretty</font><font color="#E5E5E5"> useful if you want to create</font><font color="#CCCCCC"> like</font>

this linear sequence of numbers you can

also reshape your arrays with reshape

<font color="#CCCCCC">functions so</font><font color="#E5E5E5"> for example if you have</font>

this array and then the shape of this

array is<font color="#CCCCCC"> 3 by 2 it has 3 rows and 2</font>

columns now let's say you want to

reshape<font color="#E5E5E5"> this to be 2 by 3</font><font color="#CCCCCC"> so you can say</font>

reshape 2 by 3<font color="#CCCCCC"> basically now</font><font color="#E5E5E5"> you want to</font>

rows and<font color="#CCCCCC"> 3 columns</font><font color="#E5E5E5"> and it would work</font><font color="#CCCCCC"> so</font>

you can reshape<font color="#E5E5E5"> it to any dimensions</font>

that<font color="#CCCCCC"> you like and</font><font color="#E5E5E5"> the dimension should</font>

<font color="#E5E5E5">be compatible with your initial</font>

dimension so<font color="#E5E5E5"> you can even do a dot</font>

reshape to<font color="#CCCCCC"> be let's say you want let's</font>

say<font color="#CCCCCC"> six rows and one call</font>

so you see<font color="#E5E5E5"> six rows one column you can</font>

also use<font color="#CCCCCC"> revell function to flatten your</font>

array so<font color="#E5E5E5"> this will just flatten it make</font>

it one dimension<font color="#E5E5E5"> so you have n dimension</font>

array when you call<font color="#CCCCCC"> it or travel it</font><font color="#E5E5E5"> will</font>

flatten it make it one damaged all right

now when I print a after flattering it<font color="#CCCCCC"> I</font>

see<font color="#E5E5E5"> that is still an original array</font>

because<font color="#E5E5E5"> a dot</font><font color="#CCCCCC"> revell will</font>

not touch the original array it will

return a new array<font color="#E5E5E5"> so you can capture</font>

the<font color="#CCCCCC"> output into</font><font color="#E5E5E5"> new variable and have</font>

access<font color="#CCCCCC"> to flatten structure</font><font color="#E5E5E5"> so that</font>

applies<font color="#CCCCCC"> to all of these</font><font color="#E5E5E5"> functions just</font>

<font color="#E5E5E5">remember that it's</font><font color="#CCCCCC"> not going to alter</font>

your<font color="#CCCCCC"> original array</font><font color="#E5E5E5"> so that's something</font>

<font color="#CCCCCC">you have to keep it in mind</font>

now let's look at<font color="#E5E5E5"> some of the</font>

mathematical functions that<font color="#E5E5E5"> are</font><font color="#CCCCCC"> numpy</font>

<font color="#CCCCCC">wide array</font><font color="#E5E5E5"> cover so you have management</font>

so let's say<font color="#E5E5E5"> I have this array okay if</font>

you do a dot min it's going to print

<font color="#E5E5E5">your minimum element which is</font><font color="#CCCCCC"> one a dot</font>

max will print your maximum element

which<font color="#CCCCCC"> is six</font><font color="#E5E5E5"> okay now you can also do a</font>

dot<font color="#E5E5E5"> sum and it's gonna sum all the</font>

numbers together<font color="#E5E5E5"> now there is a concept</font>

of<font color="#E5E5E5"> excess in</font><font color="#CCCCCC"> our number</font><font color="#E5E5E5"> array axis means</font>

your dimensions to my<font color="#E5E5E5"> X is zero will be</font>

<font color="#E5E5E5">this columns okay</font><font color="#CCCCCC"> and my exes one will</font>

be these rows right<font color="#CCCCCC"> here so when I do a</font>

dot sum and when I say<font color="#E5E5E5"> X is equal</font><font color="#CCCCCC"> to</font>

<font color="#E5E5E5">zero it's gonna look at each</font><font color="#CCCCCC"> of this</font>

column<font color="#CCCCCC"> so it</font><font color="#E5E5E5"> added these numbers</font>

together 5<font color="#CCCCCC"> 3 8 + 1 9 so it printed 9 6 4</font>

10<font color="#CCCCCC"> + 2 is 12 so it's added these</font>

together and printed 12 if you<font color="#CCCCCC"> want to</font>

sum all the elements in rows together

<font color="#E5E5E5">then you use X</font><font color="#CCCCCC"> 1</font><font color="#E5E5E5"> so here 2 N 1</font><font color="#CCCCCC"> is 3</font><font color="#E5E5E5"> 3 +</font>

4 is 7 5<font color="#E5E5E5"> 6 is 11 so that's what it did</font>

<font color="#CCCCCC">so that's</font><font color="#E5E5E5"> what the axis means here you</font>

can also do a square root so if you do

<font color="#E5E5E5">SQ RT a dot s</font><font color="#CCCCCC"> qrt let's see so if you do</font>

so<font color="#E5E5E5"> a dot so s square root is not a</font>

function<font color="#E5E5E5"> of individual array element</font>

it's a generic<font color="#CCCCCC"> function so</font><font color="#E5E5E5"> you have to</font>

do

and P dot<font color="#E5E5E5"> s</font><font color="#CCCCCC"> p RT</font><font color="#E5E5E5"> so</font><font color="#CCCCCC"> NP is</font><font color="#E5E5E5"> your non-pure</font>

module so it's going to compute the

<font color="#E5E5E5">square root of each of</font><font color="#CCCCCC"> these numbers so</font>

<font color="#E5E5E5">for example for square root you know is</font>

<font color="#E5E5E5">2 then</font><font color="#CCCCCC"> 2 square</font><font color="#E5E5E5"> root you obviously you</font>

<font color="#E5E5E5">don't remember but if you open</font><font color="#CCCCCC"> your</font>

calculator and find the square<font color="#CCCCCC"> root is</font>

going<font color="#E5E5E5"> to be this okay you can</font><font color="#CCCCCC"> also do a</font>

standard<font color="#E5E5E5"> deviation so</font><font color="#CCCCCC"> n P dot standard</font>

deviation so standard deviation<font color="#CCCCCC"> of all</font>

these<font color="#E5E5E5"> numbers is here again no one is</font>

going to<font color="#E5E5E5"> remember this</font><font color="#CCCCCC"> but if you do</font>

your math then<font color="#CCCCCC"> you will find that it</font>

<font color="#CCCCCC">will be this number okay we</font><font color="#E5E5E5"> are going to</font>

now look<font color="#E5E5E5"> at</font><font color="#CCCCCC"> some basic mathematical</font>

<font color="#E5E5E5">operations and for this I'm going</font><font color="#CCCCCC"> to</font>

<font color="#E5E5E5">have these</font><font color="#CCCCCC"> two arrays why I just copy</font>

pasted it from<font color="#E5E5E5"> my</font><font color="#CCCCCC"> knot pad but it</font><font color="#E5E5E5"> didn't</font>

work<font color="#E5E5E5"> anyways I will just create it here</font>

so I have<font color="#E5E5E5"> two dimensional array here so</font>

<font color="#CCCCCC">one two three four okay and I have this</font>

second array okay this is my first

dimension<font color="#E5E5E5"> my second dimension is</font><font color="#CCCCCC"> PI six</font>

seven<font color="#E5E5E5"> eight</font>

okay oops I forgot a closing angle

bracket<font color="#E5E5E5"> okay</font><font color="#CCCCCC"> so I have these two array</font><font color="#E5E5E5"> a</font>

a and B<font color="#CCCCCC"> to be dimensional array yeah now</font>

<font color="#E5E5E5">num py supports very basic operations</font>

such as let's see if you want to add

them together it you can do it<font color="#E5E5E5"> using</font>

plus operator<font color="#E5E5E5"> this is something you</font>

cannot do with<font color="#E5E5E5"> Python native list so</font>

it's<font color="#E5E5E5"> very convenient with num py arrays</font>

<font color="#E5E5E5">so</font><font color="#CCCCCC"> this added these together fine one is</font>

six six<font color="#E5E5E5"> and two is eight is basically</font>

<font color="#E5E5E5">adding the individual elements</font><font color="#CCCCCC"> you can</font>

<font color="#CCCCCC">do multiplication</font><font color="#E5E5E5"> you can</font><font color="#CCCCCC"> do</font><font color="#E5E5E5"> division</font>

you can<font color="#E5E5E5"> do all</font><font color="#CCCCCC"> sorts of operation</font><font color="#E5E5E5"> you</font>

<font color="#E5E5E5">can also do a matrix product so if you</font>

do a

a dot<font color="#E5E5E5"> B it's</font><font color="#CCCCCC"> gonna</font><font color="#E5E5E5"> do matrix products of</font>

these two individual matrices<font color="#CCCCCC"> alright so</font>

<font color="#E5E5E5">that was all about on</font><font color="#CCCCCC"> num</font><font color="#E5E5E5"> py or it</font>

wasn't all about num period is actually

<font color="#E5E5E5">we still need to cover few topics such</font>

as indexing slicing<font color="#E5E5E5"> hydrating stacking</font>

these number of errors together but all

those<font color="#E5E5E5"> remaining things we are going to</font>

cover in our<font color="#CCCCCC"> next tutorial until</font><font color="#E5E5E5"> then</font>

thank you<font color="#E5E5E5"> for</font><font color="#CCCCCC"> watching and good luck</font>

with<font color="#CCCCCC"> your Python and numpy by</font><font color="#E5E5E5"> learning</font>

thanks again

