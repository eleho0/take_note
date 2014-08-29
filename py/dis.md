# python dis tool

> from:
>http://stackoverflow.com/questions/19916729/how-exactly-is-python-bytecode-run-in-cpython
>https://docs.python.org/2/library/dis.html

``
import dis
``


>  >>> dis.dis('i/3')
>   1           0 LOAD_NAME                0 (i)
>               3 LOAD_CONST               0 (3)
>               6 BINARY_TRUE_DIVIDE
>               7 RETURN_VALUE
> 
