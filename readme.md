# intro

py_classic_error is classic way to show erros for python users.

# why you need py_classic_error ?

- easy to use
- more readable error & compact
- show error code

# you can install via pip

    pip install py_classic_error

# example

    numbers = [1,2,3]

    try:
        # now we're trying to access index doesn't contains in numbers list
        print(numbers[8])
    except:
        py_classic_error()

    -------py_classic_error------- 
    errtype: <class 'IndexError'>
    err: list index out of range
    Path: "d:\weatherapp\ll.py"
    => 11 print(numbers[8])

# License
The unlicense

# Copyright
Suresh P @ 2022 | py_classic_error | Unlicense