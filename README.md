# Monte-Carlo-Pricer-Exercise
There are various numerical methods we can use to quickly price any financial derivatives.

One of the most widely used methods is the Monte Carlo method, which uses statistical techniques to estimate the price of a derivative using averages of samples.

We implement the MC pricer for a quanto European Call Option and quanto Arithmetic Asian Call Option. The reason we do this is to demonstrate the differences in simulating the sample paths for option that is not path dependent (uanto European Call Option) and option that is strongly path-dependent (quanto Arithmetic Asian Call Option).

And lastly we also perform checks to make sure that our numerical pricer are accurate within a certain level of acceptance level and behaves as expected.
