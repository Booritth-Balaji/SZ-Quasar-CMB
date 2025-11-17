This repo contains all the files that I used in my project analyzing data obtained from matched filtering of simulated CMB maps with kSZ effect observed due to early universe quasar bubbles. 

My codes and data used can be found under the "Codes" and "Codes/Data" folders respectively. The other folders contain resources on MCMC sampling and CMB data analysis techniques. The "Example fitting a gaussian.ipynb" is an example for performing MCMC sampling on a generated data set, and the "root_finding_code.ipynb" is the code I used to obtain numerical results for finding t. 

In the "Codes/Data" folder, the naming scheme is explained as below: 
* The first letter, "u" or "l", represents either unlensed bubbles or lensed bubbles respectively.
* The number next to the letter (0.0, 1.0, 10.0, 30.0) represents the noise in the bubble, 0.0 being no artificial noise

The "MCMC Sampling.ipynb" contains the code for the analysis done using MCMC, and "Grid Sampling.ipynb" contains the code for the analysis done by going through the grid of parameters. 

The "root_vals.csv" and "root_vals_red.csv" files contain the root results from "root_finding_code.ipynb", the latter being a reduced version with a larger step size between the samples. 

The "Codes/Output" folder contains all the output graphs and tables from the analaysis. 
