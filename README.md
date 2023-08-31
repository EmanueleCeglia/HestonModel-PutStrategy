# Sell-Naked-Put-Strategy-with-Heston-Model
This project uses the Heston model to calculate the probability that a put option will be in the money at expiration. The repository contains the code and documentation needed to use the program.

The Heston model is an option pricing model based on stochastic volatility dynamics. The model predicts the evolution of the volatility of the underlying asset as a stochastic process, which depends on two factors: the square root of the current volatility and a drift term.

Using the Heston model, it is possible to calculate the price of a put option and estimate the probability that the option will be in the money at expiration, that is, that the price of the underlying will be lower than the option's strike price. The prediction depends on the parameters of the model, such as expected volatility and time remaining to expiration.

However, it is important to note that the Heston model is a theoretical and simplified model that does not take into account all the factors that may influence the option price. Therefore, the results obtained with this model should be interpreted with caution and evaluated in conjunction with other option pricing analyses and techniques.

## Step:
1) Run the first model, setting the start date of the time series as desired. Observe the strike price obtained at the end of the model.
2) Enter the strike price into the second model, set the input parameters and the risk free rate, if desired, you can also enter the margin to calculate the margin call probability.

Enjoy :) 
