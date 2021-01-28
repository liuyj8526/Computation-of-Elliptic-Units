# Computation-of-Elliptic-Units

## Description
In this project we compute the elliptic units and the polynomial required to generate the Hilbert class field of some real quadratic fields. Implemented using SageMath based on *S. Dasgupta, Computations of Elliptic Units for Real Quadratic Fields, Canadian Journal of Mathematics, 59 (2007), 553-574*.

## Results
We display the tables of our computations in [tables](./). The details of implementation of the code, as well as an errata to the aforementioned paper can be found [here]('./Notes on the Implementation.pdf')

## Instructions 
To use the code for computation, download all the files in [code](./code) and run them in SageMath's Jupyter Notebook. 

Open p-adic_Main.ipynb, and specify values for p,N,M in the first cell. In the second cell the default cap is at 1000, but can be changed to any value. The first run will be slow, for example p=5 N=7 M=100 may take a few hours to run. These values are saved in the file and so the next run with the same p,N,M values will load from the file directly instead of calculating them all over again.

Please see the code for more details.

## Contributers 
Max Fleischer, Yijia Liu, under the guidance of Prof. Samit Dasgupta.
