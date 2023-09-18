# FLAME super-resolution challenge
Codes and weights for the Stanford FLAME super-resolution challenge. 
1. The standard EDSR code was modified for the best performing model. 
2. The training data was normalized using the mean and standard deviation of the training samples. 
3. A exponential decay learning rate scheduler was used. At 300 epochs, this should give an MSE of 0.00853, which still put us in 4th place. 
4. My some ad-hoc adjustments to the learning rate, we got the MSE down to 0.00839, to still put us in 4th place.
5. The trained weights provided, at 743 and 834 epochs both give an MSE of 0.00839. 
 

