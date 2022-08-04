===================================
Accelerating computation with numba
===================================

Python is known as being 'duck typed'. This allows a lot of flexibility in coding, but repeatedly checking types causes certain things (for loops) to be extremely slow.
While loops can be avoided with modules like numpy, sometimes these modules don't work in your application.

A member of the class of python compilers, numba is an LLVM based jit compiler for python, with good numpy compatibility.
Numba forces strict return types, and requires inbuilt alternatives to some python builtins (such as dicts), but in turn can realistically achieve 15-30x speedups in practical code.
In addition, numba allows bypassing the GIL, so can be a basis for threading in python.

See the 5 minute intro below. 
1. `5 minute intro to numba <https://numba.pydata.org/numba-doc/latest/user/5minguide.html>`_
