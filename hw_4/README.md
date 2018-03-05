The machine I ran this on is a Macbook Pro, 2.3 GHz Intel Core i7.

The general behavior of a line in execution time on a log-log scale plot makes sense because the amount of comptionations should go
as a power law.

It makes sense that simple case would be faster for small amounts of darts thrown because the parallel methods have non-negligible start up times
when compared to a simple for loop. However, for larger numbers of darts thrown, the parallel methods would win because the upper limit of simulation speed
is high (ultimately this upper limit should be limited by the number of parallel processes one can perform for this specific problem).

For this simple problem we are considering in this hw, it also makes sense that the two parallel cases would be perform approximately the same at large number of darts thrown.
The differences in small numbers of darts thrown between the parallel methods is simply due to the difference overhead associated starting the two parallel methods. 

