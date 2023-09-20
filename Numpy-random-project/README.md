# **NumPy Random Package**
### Author: Sarah McNelis - G00398343
***
<br>

This is an investigation into the [numpy random package](https://numpy.org/doc/stable/reference/random/index.html) using a jupyter notebook. 

<br>

***

<br>

## **How to run a [jupyter notebook](https://jupyter.org/):**

1. Download [Anaconda]().
2. Download [cmder]() if on windows.
3. Run `jupyter lab` or `jupyter notebook` on the command line 

<br>

***

<br>

## **Quick steps**

### NB viewer

[Nbviewer](https://nbviewer.org/) is an online tool created by the Jupyter community for rendering notebooks in static form. 

You can view this notebook on nbviewer by clicking on the following badge:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](http://nbviewer.org/github/SarahMcN25/numpy-random/tree/main/)


### Binder

[Mybinder](https://mybinder.org/) is an online service where you can share a notebook in a dynamic and interactive way.

You can view this notebook on mybinder by clicking on the following badge:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SarahMcN25/numpy-random/HEAD)

<br>

***

<br>

## **Overview of this notebook**

This notebook explains the following aspects of the numpy random package:

1. The overall purpose of the package.
2. The use of simple random data.
3. The use of permutation functions.
4. The use and purpose of five distribution functions.
5. The use of seeds in generating pseudorandom numbers.s

<br>

### 1. Overview of NumPy Random
Numpy is used when working with arrays. The numpy random package allows users to generate random data. In order to explain and visualise how numpy random works the following packages are imported:

#### *numpy*
- used for working with numerical arrays.

#### *matplotlib.pyplot*
- used for visualising the random data generated using numpy on plots.

#### *default_rng*
- imported from numpy.random as recommended by the quick start guide as the package was updated to version 1.21. This new format is recommended as it is more compatible with numpy. 

<br>

### 2. Simple Random Data
The four different methods of generating simple random data are:

- *Random Integers:* returns random integers in an array.

- *Random Random:* generates an array of random floats.

- *Random Choice:* chooses a random integer from an array. 

- *Random Bytes:* produces random bytes of data. 

<br>

### 3. Permutation Functions
This is used for random ordering of an array. It consists of three methods:

- *Shuffle:* shuffles the contents of an array. 

- *Permutation:* modifies a sequence of an array. 

- *Permuted:* shuffles each piece of an array independently of each other. 

<br>

### 4. Distribution Functions
These functions predict the probability of a set of values. There are 36 in total, however, this notebook only describes the following five in detail:

- *Random Normal:* creates random samples for normal distribution - where data near the mean is more likely to appear.

- *Random Uniform:* generates samples from a uniform distribution - where all outcomes are equally likely. 

- *Random Power:* produces samples using power law distribution - where one variable acts as a power of another. 

- *Random Geometric:* returns samples using geometric distribution with two possible outcomes - success or failure. 

- *Random Gumbel:* simulates the extreme value - either very small or very large. 

<br>

### 5. Seed and Pseudorandom Numbers
When generating random numbers there is always a start point. This inital value can be set using the random seed method. This means that the random data generated will always return the same values. Furthermore, this data is known as pseudorandom numbers because the inital start point or seed is known. 

<br>

***

<br>

## **Conclusion**
This readme contains a quick overview of what this juputer notebook does. It explains the use and purpose of the numpy random package, it describes simple random data, permutation functions and distribution functions and it outlines the seed funciton and its importance in generating pseudorandom numbers. The numpy random package has many functions which are hugely beneficial for data analysts to gather, investigate and interpret data in order to provide detailed analysis as a result. 

<br>

***

<br>

## **References:**

All references and code used in this notebook have been sourced in Oct/Nov 2021 from the following webpages:

- https://numpy.org/doc/stable/reference/random/index.html
- https://numpy.org/doc/stable/reference/random/index.html#random-quick-start
- https://numpy.org/doc/stable/user/whatisnumpy.html
- https://towardsdatascience.com/tagged/arrays
- https://www.javatpoint.com/numpy-random
- https://towardsdatascience.com/change-figure-size-matplotlib-11a409f39584
- https://matplotlib.org/stable/api/matplotlib_configuration_api.html#matplotlib.RcParams
- https://matplotlib.org/stable/gallery/style_sheets/style_sheets_reference.html
- https://stackoverflow.com/questions/43027980/purpose-of-matplotlib-inline
- https://towardsdatascience.com/top-10-magic-commands-in-python-to-boost-your-productivity-1acac061c7a9
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.integers.html#numpy.random.Generator.integers
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.random.html#numpy.random.Generator.random
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.choice.html#numpy.random.Generator.choice
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.bytes.html#numpy.random.Generator.bytes
- https://en.wikipedia.org/wiki/Random_permutation
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.shuffle.html#numpy.random.Generator.shuffle
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.permutation.html#numpy.random.Generator.permutation
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.permuted.html#numpy.random.Generator.permuted
- https://www.britannica.com/science/distribution-function
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.normal.html#numpy.random.Generator.normal
- https://www.investopedia.com/terms/n/normaldistribution.asp
- https://www.stats4stem.org/density-curves
- https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.hist.html
- https://stackoverflow.com/questions/23773131/what-are-n-bins-and-patches-in-matplotlib
- https://realpython.com/python-operators-expressions/
- https://www.geeksforgeeks.org/numpy-sqrt-in-python/
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.uniform.html#numpy.random.Generator.uniform
- https://www.investopedia.com/terms/u/uniform-distribution.asp
- https://numpy.org/doc/stable/reference/generated/numpy.ones_like.html
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.power.html#numpy.random.Generator.power
- https://en.wikipedia.org/wiki/Power_law
- https://numpy.org/doc/stable/reference/generated/numpy.linspace.html
- https://numpy.org/doc/stable/reference/generated/numpy.diff.html
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.geometric.html#numpy.random.Generator.geometric
- https://www.cuemath.com/geometric-distribution-formula/
- https://en.wikipedia.org/wiki/Bernoulli_trial
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.gumbel.html#numpy.random.Generator.gumbel
- https://en.wikipedia.org/wiki/Gumbel_distribution
- https://en.wikipedia.org/wiki/Emil_Julius_Gumbel
- https://www.statisticshowto.com/upper-tail-and-lower-tail/
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.seed.html?highlight=seed#numpy.random.seed
- https://numpy.org/doc/stable/reference/random/bit_generators/generated/numpy.random.BitGenerator.html#numpy.random.BitGenerator
- https://www.geeksforgeeks.org/random-seed-in-python/
- https://www.pcmag.com/encyclopedia/term/pseudo-random-numbers
- https://en.wikipedia.org/wiki/Pseudorandom_number_generator
- https://towardsdatascience.com/how-to-use-random-seeds-effectively-54a4cd855a79#:~:text=A%20random%20seed%20is%20used,get%20the%20exact%20same%20outputs.&text=In%20addition%20to%20reproducibility%2C%20random,important%20for%20bench%2Dmarking%20results.
- https://stats.stackexchange.com/questions/354373/what-exactly-is-a-seed-in-a-random-number-generator
- https://towardsdatascience.com/lets-talk-about-numpy-for-datascience-beginners-b8088722309f
- https://towardsdatascience.com/tools-for-sharing-jupyter-notebooks-online-28c8d4ff821c
- https://mybinder.readthedocs.io/en/latest/introduction.html
- https://www.getsmarter.com/blog/career-advice/data-analysis-important-business/#:~:text=Data%20analysis%20is%20important%20in,provides%20context%20for%20the%20data.
- https://en.wikipedia.org/wiki/Simple_random_sample
- https://en.wikipedia.org/wiki/Permuted_congruential_generator
- https://matplotlib.org/stable/api/style_api.html?highlight=plot%20style#module-matplotlib.style

<br>

***