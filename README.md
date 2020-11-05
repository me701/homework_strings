# Homework - Text Processing and Data

Homework for string processing and formats.  Place all of your code in
one file named `homework_tex.py`.  Include some testing and documentation.


## Problem 1 - File Processing and String Manipulation

Write a function named `read_pwr()` that
opens and reads `pwr.log` using any techniques you like and produces two arrays, one
for `kinf` and one for `burnup`.  Note, these correspond to the second
and third full columns, i.e., `burnup = [0, 0.1, 0.5, ...]` and
`kinf = [1.27354, 1.23449, ...]` in the following:

```
                                             ****** *******
   NO VOID    TFU    TMO    TCO    BOR ROD   BURNUP   K-INF   K-INF     M2     PIN   U-235 FISS PU  TOT PU
                                             MWD/KG             TWO-GROUP     PEAK    WT %    WT %    WT %
    1  0.0  900.0  565.0  580.0  900.0        0.000 1.27354 1.27149  62.18   1.059   4.000   0.000   0.000  
    2                                         0.100 1.23449 1.23311  61.64   1.060   3.988   0.002   0.002  
    3                                         0.500 1.22571 1.22445  61.51   1.060   3.941   0.022   0.022  
    4                                         1.000 1.21976 1.21858  61.41   1.060   3.882   0.049   0.050  
```


## Problem 2 - Regex

Write a Python function named `five_chars(s)` to find all five
character long words in a string `s`.  You must use `re`.
