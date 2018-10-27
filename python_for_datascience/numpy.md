<h1>Numpy</h1>
<p>Numpy or numerical python is a library written for Scientific computation and Data Science in Python. It is very popular that, it is one of the most widely used libraries for Data Science. As given in their official documentation, <a href="http://www.numpy.org/old_array_packages.html">NumPy</a> derives from an old library called Numeric, which was the first array object built for Python.</p>

The <code>ndarray</code> or simply an <code>array</code> is the basic object in numpy. It is a homogenous n-dimensional array, which constaints all elements to be the same data type, generally numeric (float or integer).

<h2>Advantages of NumPy</h2>
What is the use of arrays over lists, specifically for data analysis? Putting crudely, it is convenience and speed :

You can write vectorised code on numpy arrays, not on lists, which is convenient to read and write, and concise.
Numpy is much faster than the standard python ways to do computations.
Vectorised code typically does not contain explicit looping and indexing etc. (all of this happens behind the scenes, in precompiled C-code), and thus it is much more concise.

Let's see an example of convenience, we'll see one later for speed.
