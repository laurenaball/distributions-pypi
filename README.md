# distributions_mlnd_LB package description

This package contains method for creating and performing calculations on Gaussian and Binomial distributions

# installation

'>>> pip install gauss-binomial-mp99'

# files 

Import:	
'>>> from gauss_binomial_mp99 import Gaussian, Binomial
>>> gauss = Gaussian()
>>> gauss.read_data_file('sample.txt') '

### Binomialdistribution.py
Class for calculating and visualizing binomial distribution

### Gaussiandistribution.py
Class for calculating and visualizing Gaussian distribution

### Generaldistribution.py
Class for calculating and visualizing a generic probability distribution

## methods
Methods for computation (used in all classes)

'calculate_mean(): calculates mean of data set
 calculate_stdev(): calculates standard deviation of data set
 plot_histogram(): plots histogram of instance variable data using matplotlib
 pdf(x): calculates probability density function for distribution
 plot_histogram_pdf: plots histogram of data and probability density function together'
