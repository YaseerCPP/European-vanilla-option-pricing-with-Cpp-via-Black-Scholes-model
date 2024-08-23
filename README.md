# European-vanilla-option-pricing-with-Cpp-via-Black-Scholes-model

The Black-Scholes model is a mathematical model used to calculate the theoretical value of a European-style option, which gives the holder the right but not the obligation to buy or sell an underlying asset at a predetermined price (strike price) on a specific date (expiration date).   

Key components of the Black-Scholes model:

1. Underlying asset price: The current price of the asset on which the option is based.
2. Strike price: The predetermined price at which the asset can be bought or sold.
Time to expiration: The length of time remaining until the option expires.
3. Risk-free interest rate: The interest rate that can be earned on a risk-free investment over the same time period.
4. Volatility: The standard deviation of the annualized returns of the underlying asset.

Black-Scholes formula:

C = S * N(d1) - K * e^(-r*T) * N(d2)
P = K * e^(-r*T) * N(-d2) - S * N(-d1)
where:

C is the price of a call option.
P is the price of a put option.
S is the current price of the underlying asset.
K is the strike price.
r is the risk-free interest rate.   
T is the time to expiration (in years).   
N(x) is the cumulative distribution function of the standard normal distribution.
d1 and d2 are calculated using the following formulas:
d1 = (ln(S/K) + (r + σ^2/2) * T) / (σ * sqrt(T))
d2 = d1 - σ * sqrt(T)

Assumptions of the Black-Scholes model:

1. European-style options: The model only applies to options that can be exercised only on the expiration date.
2. Constant interest rates and volatility: The model assumes that interest rates and volatility remain constant throughout the life of the option.
3. No dividends: The model assumes that the underlying asset does not pay any dividends during the life of the option.
4. Efficient markets: The model assumes that the market is efficient and that all relevant information is reflected in the asset price.
