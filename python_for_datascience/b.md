dear friends we<font color="#CCCCCC"> are</font><font color="#E5E5E5"> going to look into</font>

numpy by module today it is extremely

<font color="#E5E5E5">popular in Python</font><font color="#CCCCCC"> community and it</font><font color="#E5E5E5"> is</font>

heavily<font color="#CCCCCC"> used</font><font color="#E5E5E5"> for</font><font color="#CCCCCC"> scientific computing we</font>

will see why it<font color="#CCCCCC"> is</font><font color="#E5E5E5"> so</font><font color="#CCCCCC"> popular so let's</font>

first start<font color="#E5E5E5"> by installing it</font><font color="#CCCCCC"> I will</font>

install it using<font color="#CCCCCC"> pip</font>

you can run pip install numpy<font color="#E5E5E5"> why come</font>

on<font color="#CCCCCC"> to</font><font color="#E5E5E5"> download and install</font><font color="#CCCCCC"> it</font><font color="#E5E5E5"> while it</font>

is installing<font color="#CCCCCC"> number</font><font color="#E5E5E5"> wise main object is</font>

<font color="#E5E5E5">n dimensional array</font><font color="#CCCCCC"> okay so we</font><font color="#E5E5E5"> will look</font>

into<font color="#CCCCCC"> that array</font><font color="#E5E5E5"> so here I have my Python</font>

<font color="#CCCCCC">idle shell open and I am going</font><font color="#E5E5E5"> to import</font>

numpy<font color="#CCCCCC"> Y model here so num I've imported</font>

it as NP and to create an array object

<font color="#E5E5E5">you will use NP dot array and in this</font>

<font color="#E5E5E5">bracket you just</font><font color="#CCCCCC"> pass down your list</font><font color="#E5E5E5"> so</font>

this<font color="#E5E5E5"> is my</font><font color="#CCCCCC"> number Y array</font><font color="#E5E5E5"> if</font><font color="#CCCCCC"> you look</font>

into<font color="#CCCCCC"> it now this is</font><font color="#E5E5E5"> sort</font><font color="#CCCCCC"> of similar to a</font>

list<font color="#CCCCCC"> it is actually very similar to a</font>

list you can access the elements by

index<font color="#E5E5E5"> it looks like a list so the</font>

question is I only<font color="#E5E5E5"> have a list why do I</font>

need<font color="#E5E5E5"> this number</font><font color="#CCCCCC"> Y array well there are</font>

several benefits<font color="#E5E5E5"> of using numpy array</font>

<font color="#E5E5E5">there are three main benefits first is</font>

it requires less memory it<font color="#E5E5E5"> is fast and</font>

convenient<font color="#E5E5E5"> and will go or all these</font>

three benefits<font color="#E5E5E5"> one by one okay</font><font color="#CCCCCC"> so</font>

<font color="#CCCCCC">essentially what we are doing is we are</font>

comparing<font color="#E5E5E5"> numpy Y with number Y array</font>

with a<font color="#E5E5E5"> Python list here okay</font>

so let's first create a Python list<font color="#CCCCCC"> I'm</font>

just going to<font color="#E5E5E5"> say range thousand so I</font>

created a list which has thousand

elements<font color="#E5E5E5"> here and I'm going to print the</font>

size of the list now to print the size

you<font color="#E5E5E5"> need to get a size of one</font>

one element<font color="#E5E5E5"> so one element</font><font color="#CCCCCC"> here is one</font>

<font color="#CCCCCC">number you can give any number here and</font>

<font color="#E5E5E5">then</font><font color="#CCCCCC"> lengths off your list</font><font color="#E5E5E5"> second</font><font color="#CCCCCC"> I</font><font color="#E5E5E5"> am</font>

<font color="#E5E5E5">going to</font><font color="#CCCCCC"> create a non py array so</font><font color="#E5E5E5"> this</font>

is how you<font color="#E5E5E5"> create an umpire array this</font>

function<font color="#CCCCCC"> a range is similar to range is</font>

going<font color="#E5E5E5"> to create an array with element 0</font>

to 99<font color="#CCCCCC"> okay so the size of this numpy</font>

array would be thousand<font color="#E5E5E5"> and to</font><font color="#CCCCCC"> print the</font>

size of this array<font color="#E5E5E5"> you need to call</font>

array dot size so<font color="#E5E5E5"> or a dot size will</font>

<font color="#CCCCCC">give you thousand ok</font><font color="#E5E5E5"> and the size of</font>

every element<font color="#E5E5E5"> will be I will be item</font>

size<font color="#E5E5E5"> so just remember that added or item</font>

size is size<font color="#E5E5E5"> of one element</font><font color="#CCCCCC"> vs. added</font><font color="#E5E5E5"> of</font>

size is the total<font color="#E5E5E5"> length of an array</font>

<font color="#E5E5E5">when you run this program you'll notice</font>

that the Python<font color="#E5E5E5"> list is taking taking 14</font>

thousand<font color="#E5E5E5"> bytes versus number</font><font color="#CCCCCC"> wise taking</font>

<font color="#E5E5E5">only</font><font color="#CCCCCC"> four</font><font color="#E5E5E5"> thousand bytes now this is</font>

because your<font color="#CCCCCC"> Python are the size of one</font>

Python object is like<font color="#E5E5E5"> 14 okay and what's</font>

the size of one<font color="#E5E5E5"> number why are a object</font>

is here in this<font color="#E5E5E5"> case</font><font color="#CCCCCC"> since we are</font>

storing integer numbers<font color="#E5E5E5"> it</font><font color="#CCCCCC"> is only</font><font color="#E5E5E5"> four</font>

bytes<font color="#CCCCCC"> okay so if you look at this</font>

diagram<font color="#CCCCCC"> it kind of should</font><font color="#E5E5E5"> this shows the</font>

memory presentation of our list and

number<font color="#CCCCCC"> I array on the left</font><font color="#E5E5E5"> hand side we</font>

<font color="#CCCCCC">have numpy array</font><font color="#E5E5E5"> which points to</font>

<font color="#E5E5E5">continuous or contiguous location of</font>

memories where you have all your<font color="#E5E5E5"> element</font>

store 1<font color="#E5E5E5"> 2 3 4 5 and so</font><font color="#CCCCCC"> on and each</font><font color="#E5E5E5"> of</font>

these element contain is occupying<font color="#E5E5E5"> 4</font>

byte of memory<font color="#E5E5E5"> versus in case of Python</font>

<font color="#CCCCCC">lists you all know that</font><font color="#E5E5E5"> in Python</font>

<font color="#E5E5E5">everything is an object so the list will</font>

contain a list of pointers first as you

can

see in the diagram<font color="#E5E5E5"> and each pointer will</font>

then point<font color="#E5E5E5"> to another location in</font><font color="#CCCCCC"> the</font>

memory which will be<font color="#E5E5E5"> your object and the</font>

size of<font color="#CCCCCC"> that one object will be</font><font color="#E5E5E5"> 14 bytes</font>

<font color="#E5E5E5">so this is the reason</font><font color="#CCCCCC"> why or numpy why</font>

array the<font color="#CCCCCC"> mammal</font><font color="#E5E5E5"> usage is very less</font>

compared to<font color="#E5E5E5"> a plain Python list now when</font>

you are<font color="#E5E5E5"> array size all this size is very</font>

<font color="#CCCCCC">small you</font><font color="#E5E5E5"> won't notice much difference</font>

but let's say you are dealing<font color="#E5E5E5"> with the</font>

heavy amount of data<font color="#E5E5E5"> where you have</font>

millions<font color="#CCCCCC"> and billions of numbers to</font>

process in that<font color="#CCCCCC"> case it will make</font><font color="#E5E5E5"> sense</font>

<font color="#E5E5E5">to use numpy</font><font color="#CCCCCC"> why</font><font color="#E5E5E5"> all right</font>

the second<font color="#CCCCCC"> advantage of</font><font color="#E5E5E5"> numpy why is</font>

<font color="#CCCCCC">that it is fast</font><font color="#E5E5E5"> and convenient</font><font color="#CCCCCC"> so let</font><font color="#E5E5E5"> me</font>

prove that<font color="#CCCCCC"> point as well so I am going</font>

to<font color="#E5E5E5"> what I'm going to do here is</font><font color="#CCCCCC"> alright</font>

let me<font color="#CCCCCC"> just close this guy here</font><font color="#E5E5E5"> and I'm</font>

going<font color="#CCCCCC"> to now create</font><font color="#E5E5E5"> here</font><font color="#CCCCCC"> two lists first</font>

call it<font color="#E5E5E5"> alone and l2 okay so range</font>

sighs so size is<font color="#E5E5E5"> thousand here and l2 is</font>

also similar so I<font color="#CCCCCC"> created two lists</font><font color="#E5E5E5"> here</font>

<font color="#E5E5E5">and then I am going to create two array</font>

so<font color="#E5E5E5"> NP dot a range again to create a</font>

<font color="#E5E5E5">number</font><font color="#CCCCCC"> Y array and then second array</font>

will be<font color="#E5E5E5"> called a</font><font color="#CCCCCC"> two</font><font color="#E5E5E5"> okay now I want to</font>

<font color="#E5E5E5">measure</font><font color="#CCCCCC"> the time between</font><font color="#E5E5E5"> list processing</font>

and number your array processing<font color="#E5E5E5"> so for</font>

this you use start is equal<font color="#CCCCCC"> to time to</font>

time and now what I'm<font color="#CCCCCC"> going to do is see</font>

<font color="#CCCCCC">the thing the operation that I am doing</font>

<font color="#CCCCCC">here is I am adding these two</font><font color="#E5E5E5"> lists I am</font>

adding<font color="#E5E5E5"> these two lists and producing a</font>

new list call<font color="#E5E5E5"> call it result okay</font>

so to order these<font color="#E5E5E5"> two lists you have</font><font color="#CCCCCC"> to</font>

do<font color="#E5E5E5"> something like this</font><font color="#CCCCCC"> X</font><font color="#E5E5E5"> plus y for X Y</font>

in zip l1 l2 what this will do<font color="#CCCCCC"> is it</font>

will<font color="#E5E5E5"> take first element from l1 first</font>

elements from l2<font color="#E5E5E5"> add them together and</font>

<font color="#CCCCCC">put it</font><font color="#E5E5E5"> in this result as a first element</font>

so it will<font color="#E5E5E5"> just add</font><font color="#CCCCCC"> in usual elements</font>

from<font color="#E5E5E5"> these two lists and put it in a</font>

result<font color="#CCCCCC"> okay</font><font color="#E5E5E5"> pretty</font><font color="#CCCCCC"> straightforward and I</font>

am just going to say Python<font color="#CCCCCC"> list too</font>

this much time<font color="#E5E5E5"> so right now the time</font><font color="#CCCCCC"> is</font>

this<font color="#CCCCCC"> I am going</font><font color="#E5E5E5"> to subtract start from</font>

here<font color="#E5E5E5"> and I'm going</font><font color="#CCCCCC"> to multiply</font><font color="#E5E5E5"> this guy</font>

with thousand<font color="#CCCCCC"> because by default it</font><font color="#E5E5E5"> is</font>

in second I want<font color="#E5E5E5"> to print milliseconds</font>

here<font color="#E5E5E5"> all right now again at this point I</font>

will<font color="#E5E5E5"> capture time one more</font><font color="#CCCCCC"> time</font><font color="#E5E5E5"> and then</font>

I will store result here so now so<font color="#CCCCCC"> this</font>

was your Python list<font color="#E5E5E5"> okay so let me just</font>

<font color="#CCCCCC">say Python</font><font color="#E5E5E5"> list and here now I am</font>

processing<font color="#E5E5E5"> numpy</font><font color="#CCCCCC"> Y array so that's the</font>

<font color="#CCCCCC">difference between these two code blocks</font>

or now<font color="#CCCCCC"> num py is also convenient</font><font color="#E5E5E5"> because</font>

if you want to add two arrays you just

say<font color="#CCCCCC"> a1 plus e2 right so it is</font><font color="#E5E5E5"> not like</font>

you have<font color="#E5E5E5"> to write a list</font><font color="#CCCCCC"> comprehension</font>

<font color="#CCCCCC">okay you can just add them together</font><font color="#E5E5E5"> and</font>

you can<font color="#E5E5E5"> just say print my num py took</font>

this is just a way to measure<font color="#E5E5E5"> the time</font>

that this code block took okay

<font color="#E5E5E5">all right so let's run this</font><font color="#CCCCCC"> program here</font>

<font color="#E5E5E5">okay says Python</font><font color="#CCCCCC"> list</font><font color="#E5E5E5"> of zero point</font><font color="#CCCCCC"> zero</font>

<font color="#E5E5E5">number I to zero point</font><font color="#CCCCCC"> zero because this</font>

size is pretty<font color="#E5E5E5"> small</font><font color="#CCCCCC"> so I'm going to</font>

increase<font color="#E5E5E5"> the size and do a processing</font>

for um about<font color="#CCCCCC"> a million elements</font><font color="#E5E5E5"> here now</font>

you<font color="#E5E5E5"> can see that in order</font><font color="#CCCCCC"> to add million</font>

<font color="#CCCCCC">R elements from to</font><font color="#E5E5E5"> list Python list took</font>

<font color="#CCCCCC">116 millisecond</font><font color="#E5E5E5"> versus numpy</font><font color="#CCCCCC"> Y or eight</font>

took eleven point five seconds<font color="#E5E5E5"> this is</font>

<font color="#E5E5E5">crazy fast</font><font color="#CCCCCC"> so you can see that again</font>

when you're processing<font color="#E5E5E5"> millions and</font>

<font color="#E5E5E5">millions of numbers it just makes sense</font>

<font color="#E5E5E5">to use numpy</font><font color="#CCCCCC"> Y it is also convenient</font>

because you<font color="#E5E5E5"> can see that if you want to</font>

add<font color="#E5E5E5"> two lists together</font><font color="#CCCCCC"> you</font><font color="#E5E5E5"> just do a 1</font>

and a 2 a 1 plus a 2<font color="#E5E5E5"> I</font><font color="#CCCCCC"> I will just</font>

demonstrate that using<font color="#E5E5E5"> idle because it's</font>

this little<font color="#E5E5E5"> easier to demo that</font><font color="#CCCCCC"> in idle</font>

<font color="#E5E5E5">so I'm going to create let's</font><font color="#CCCCCC"> say 2 numpy</font>

our array<font color="#CCCCCC"> okay</font><font color="#E5E5E5"> a 1 a 1 is NP dot array</font>

it has<font color="#CCCCCC"> 1 2 3</font><font color="#E5E5E5"> and a</font><font color="#CCCCCC"> 2 is again n</font><font color="#E5E5E5"> P dot</font>

array<font color="#E5E5E5"> it has let's say element 4 5 6</font><font color="#CCCCCC"> ok</font>

<font color="#CCCCCC">you can do a 1 plus a 2 so it will</font><font color="#E5E5E5"> give</font>

you<font color="#E5E5E5"> that is NC 4 + 1 5 2 + 5 7 and so on</font>

you can also do a 2 minus a 1 you can

see you subtracted this guy from<font color="#E5E5E5"> here</font>

<font color="#E5E5E5">you can also do multiplication so a 1</font>

cross a 2 you can do division<font color="#E5E5E5"> and so on</font>

<font color="#CCCCCC">you</font><font color="#E5E5E5"> can do all these operations</font><font color="#CCCCCC"> okay so</font>

that<font color="#E5E5E5"> was all about numpy our</font>

introduction

you saw<font color="#E5E5E5"> that why num py is so better</font>

than<font color="#CCCCCC"> so much better than the plain</font>

Python list<font color="#CCCCCC"> I will</font><font color="#E5E5E5"> cover more about num</font>

py in our next tutorial<font color="#E5E5E5"> thank you for</font>

<font color="#CCCCCC">watching</font>

