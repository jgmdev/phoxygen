phoxygen
===============================================================

Some tryout to document php internals using doxygen.

Most of the time is easier to document the source code than doing
documentation seperately. Doxygen serves as a great solution to
automatically generate documentation from the comments on the source.

Beside generating a nice structure to study the code it also generates
graphs and has many other useful features for newcomers to study
the code. Also examples can be written seperately and linked to
any documented element on the code.

Documentation on how to use Doxygen as document the source with it
can be found at http://doxygen.org or http://www.stack.nl/~dimitri/doxygen/manual.html


Generating the documentation
===============================================================

To generate the documentation of all elements, on the root directory
of phoxygen run the following command:

	doxygen Doxyfile
	
The output will be saved in html format on the docs directory.


Documenting the source
===============================================================

Since CodeLite has excelent code-completion is the best tool to 
document the PHP sources that consist on a lot of macro definitions.
The definitions of this macros can easily be explored by 
CTRL + Right Click. Also CodeLite has many good features for navigating
and exploring the source code.

To start working with it install CodeLite from http://codelite.org/
then open the workspace file located on the codelite directory of 
phoxygen using CodeLite.
