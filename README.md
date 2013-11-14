IJulia_PLEAC
============

IJulia version of [PLEAC - Programming Language Examples Alike Cookbook] (http://pleac.sourceforge.net/).
PLEAC examples are drawn from the "Perl Cookbook" (by Tom Christiansen & Nathan Torkington, published by O'Reilly.
They provide a nice range of examples oriented toward data munging, 
the type of work I tend to want to do first when learning a new language.

####A Caution
I am new to Julia, and working through these examples as a learning exercise.  
The code in these workbooks likely does not represent best practice -- 
and your suggestions for improving the solutions are most welcome.


####"Why didn't you contribute to the main PLEAC repo?"
The main PLEAC site contains solutions in many languages, so why not add Julia solutions there?

Two reasons:  

1. The PLEAC project appears to have been dormant since early 2011.
2. I wanted to use the IJulia notebook, which is incompatible with the PLEAC file format.


#### View the notebooks using nbviewer:
The Julia examples below are principally translations from the [Python version](http://pleac.sourceforge.net/pleac_python).
The examples are not complete. Missing items are generally noted in comments.

1. [PLEAC Strings](http://nbviewer.ipython.org/urls/raw.github.com/catawbasam/IJulia_PLEAC/master/1_pleac_string.ipynb)

2. [PLEAC Numbers](http://nbviewer.ipython.org/urls/raw.github.com/catawbasam/IJulia_PLEAC/master/2_pleac_numbers.ipynb)

3. [PLEAC Dates and Times*](http://nbviewer.ipython.org/urls/raw.github.com/catawbasam/IJulia_PLEAC/master/3_pleac_datetime.ipynb)

4. [PLEAC Arrays](http://nbviewer.ipython.org/urls/raw.github.com/catawbasam/IJulia_PLEAC/master/4_pleac_arrays.ipynb)

5. [PLEAC Hashes/Dictionaries](http://nbviewer.ipython.org/urls/raw.github.com/catawbasam/IJulia_PLEAC/master/5_pleac_dictionaries.ipynb)

_* Dates and Times currently uses a mix of Base, Datetime.jl, and Calendar.jl. 
 When time permits I hope to build separate Datetime.jl and Calendar.jl versions._
