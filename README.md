py-wellrng
===========

Implementation of WELL1024 RNG in python. 
Use as replacement of original python random library
Note that jumpahead method is missing

Usage Example
=============

    from wellrng import random, randrange
    
    print random(), randrange(-5, 5)
