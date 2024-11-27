# option_pricing
A Project Exploring Option Pricing Methods

In this project, I examine different methods for pricing options.

I start by considering Geometric Brownian Motion and using this to model stock prices, which will be the underlying assets to the options I consider.

I then derive the Black-Scholes partial differential equation, solving it to get a function for the price of a European call.

After using this function to price European call options, I consider a numerical approach and use Monte-Carlo simulations to also price European calls. I then compare the two methods briefly.

Following this, I extend the pricing methods comparison to a more exotic option type - Barrier options. I price up-and-out calls using both an analytical, closed-ended solution derived from a modified Black-Scholes partial differential equation, as well as the numerical Monte-Carlo approach too. 

