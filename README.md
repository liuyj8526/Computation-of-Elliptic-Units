# Computation-of-Elliptic-Units

## Description
In this project we compute the elliptic units and the polynomial required to generate the Hilbert class field of some real quadratic fields, used for the computation section of [Dasgupta and Kakde (2021) Brumer-Stark Units and Hilbert's 12th Problem](https://arxiv.org/abs/2103.02516). Implemented using SageMath based on [Dasgupta (2007) Computations of elliptic units for real quadratic fields](https://services.math.duke.edu/~dasgupta/papers/comp.pdf).

## Results 
See [tables](./Examples_of_Tables.pdf) for the results from our computations. Details of implementation of the code as well as an errata to the aforementioned paper can be found [here](./Notes_on_the_Implementation.pdf).

## Instructions 
To use the code for computation, download all the files in [code](./code) and run them in SageMath's Jupyter Notebook. 

Open p-adic_Main.ipynb, and specify values for p,N,M in the first cell. In the second cell the default cap is at 1000, but can be changed to any value. The first run will be slow, for example p=5 N=7 M=100 may take a few hours to run. These values are saved in the file and so the next run with the same p,N,M values will load from the file directly instead of calculating them all over again.

In the files, computed integrals for p=3 N=2,M-100, p-5,N-11,M-100, p-7,N-5,M-100 have been added for the convenience of quickly generating examples. 

Please see the code for more details.

## Contributors 
Max Fleischer, Yijia Liu, under the guidance of Prof. Samit Dasgupta.
