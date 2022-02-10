# Random Walk and Monte Carlo Simulation

## I. Random Walk

A random walk is a random process that describes a path that consists of a succession of random steps on a mathematical space, mostly integers.

The first part of this code simulates a 1D random walk along the integer number line. This can be equated to a coin toss, where the coin is flipped with equal probability. If the result is Heads, the walker moves forward by 1 unit. If the result is Tails, the walker moves backward by 1 unit. We do this for n timesteps.

We then take this experiment and run more simulations on it. We measure metrics such as:

* The probability that 2 walkers will be at the same position after n timesteps.
* The probability of the walker reaching the origin after n timesteps.
* The mean and mean squared displacement of the walker from the origin after n timesteps.

## II. Monte Carlo Simulation

Monte Carlo methods, or Monte Carlo experiments, are a broad class of computational algorithms that rely on
repeated random sampling to obtain numerical results. The underlying concept is to use randomness to solve
problems that might be deterministic in principle.

In the second part of this code, we simulate a Monte Carlo experiment to find the value of pi.

We have a unit circle and a unit square, and n point pebbles. We throw the pebbles randomly into the unit square, and check if it lands in the circle. We run this simulation multiple times, for multiple values of n.

## Results

The results of the experiments, as well as the observations and logic used, are present in the Jupyter notebook. In both cases, the results have been obtained by providing n = 100 as input.