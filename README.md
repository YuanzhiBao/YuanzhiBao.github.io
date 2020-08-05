# YuanzhiBao.github.io
Blog

python:
*python2 python3
difference of next()
In python2 next() is called next() in a class
In python3 next() is called __next__() in a class
when you call (next(A)) it automatically call next() function in class A
__iter__() return a callable class A itself.
for i in A:
it will go into the class to find Python2 next(), Python3 __next__() function
