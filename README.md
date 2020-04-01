You need the QT5 library and its development packages to compile it.


## Enki simulator compilation under Unix (library)

Change into the enki subdirectory and type:

	qmake

and then build Enki by running:

	make

and finally install the library with
	
	sudo make install


## Compiling AI

Move into clBP/build and run "cmake .."

## Compiling/running the examples

To compile the examples you need to do again `qmake` and `make`. This uses the
previously compiled enki library.

To run it type, for example, `./playground`


## Working on source code

compiling is handled through the enkiSimulator.pro file in examples/line_follower 

Compile changes by running 

-make clean
-qmake
-make
-./enkisimulator 
