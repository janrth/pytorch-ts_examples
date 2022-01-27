Here I ahow how to use the library pytorch-ts, which was developed by the Zalando Research team.

There are two cases:
- Univariate case
- Multivariate case

I show how the appropriate pre-processing is done using GluonTS (which is sometimes a bit complicated). 
For this purpose I apply a method using dictionaries, which is less common (mostly people stack data to
generate the desired data set). Here using dictionaries work fine, but it has to be tested further if this 
scales well to bigger amount of data.

