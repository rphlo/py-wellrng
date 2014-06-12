py-wellrng
===========

Implementation of WELL1024a RNG in python.

Can be use as replacement of original python random library.

Note that jumpahead method is missing.

Install
=======

wellrng is available on Pypi.

    easy_install wellrng

or 

    pip install wellrng
    

Usage Example
=============

    from wellrng import random, randrange
    
    print random(), randrange(-5, 5)
