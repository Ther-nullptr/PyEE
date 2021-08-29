# PyEE
Learning and calculating *Fundamentals of Electronic Circuits and System* by Python.

## Introduction

When it comes to solving a *Fundamentals of Electronic Circuits and System* problem, we usually use *Cadence* 

to validate the result. However, it has two disadvantages:

1. It is very slow and complex to use *Cadence* without a Linux virtual machine.
2. Symbolic computation is not supported.

In order to solve these problems, I have an idea: writing a Python lib to packaging some algorithms in *Fundamentals of Electronic Circuits and System*. 

It will have two parts: symbolic computation part and plotting part. The symbolic computation is mainly based on Sympy, while the plotting part is mainly based on matplotlib.

> 1. Why Sympy?
>
>    Sympy(https://www.sympy.org/en/index.html) is a Python library for symbolic mathematics. It has many functions to deal with matrix, calculus and functional transformation. However, its computing power is weaker than MATLAB and Mathematica.
>
>    When we use Sympy in Jupyter Notebook, it is able to display results in $\LaTeX$ style.
>
>    ![image-20210829180419818](C:\Users\86181\AppData\Roaming\Typora\typora-user-images\image-20210829180419818.png)
>
> 2. Why matplotlib?
>
>    Matplotlib(https://matplotlib.org/) has beautiful drawing style and simple operations.
>
>    ![image-20210829180655661](C:\Users\86181\AppData\Roaming\Typora\typora-user-images\image-20210829180655661.png)

## Usage(to do)

Python 3.9+ is required.

```bash
$ pip install PyEE
```

