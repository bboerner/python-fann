python-fann
===========

Python bindings for the Fast Artificial Neural Network ("FANN") library

This python binding is provided by Vincenzo Di Massa <hawk.it@tiscalinet.it>
and Gil Megidish <gil@megidish.net>

DESCRIPTION
===========
Using this wrapper it is possible to use libfann from python scripts.

USAGE
=====
Just 

>> from pyfan import libfann 

and then create libfann.neural_net and libfann.training_data objects

>> ann        = libfann.neural_net()
>> train_data = libfann.training_data()

Look at the examples in examples/ and at the FANN documentation and its 
C++ bindings for further reference.

TESTING
=======
To test the python bindings type 
$ make test
to build the library and execute example scripts in the example directory.

BUILDING
========
see INSTALL

