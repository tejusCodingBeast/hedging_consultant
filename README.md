# hedging_consultant

You no doubt have experienced sleepness nights worrying about droughts and tweets causing
disruptions to your fairy-tale corn farmer existence. Well, Farmer Brown awoke from her nightmare to
realize that the drought had not happened, and Donald Trump had instead chosen hydroxychloroquine
as his COVID remedy of choice. Nevertheless, she realized she would need to be smarter in choosing a
hedging strategy. Therefore, she has asked you to simulate hedging outcomes and design a suitable
strategy for her.

To begin, let’s assume the current spot price of corn is $4 in both Chicago and Kansas City. Corn prices
are assumed to follow an arithmetic random walk. 

It is currently Feb 1, and we are preparing for a July 1 harvest/sale date. Corn futures contracts are for
5000 bu each. The corn will be sold at the spot price on July 1.
The futures price of corn is determined by taking its expected value in July as a function of the spot price
and stochastic process parameters. (You may ignore the jump for this calculation, but the futures price
should go up when the spot price jumps up.)

The quantity of corn produced can be assumed to be a random number determined by the minimum of
either 1,000,000 or a random number with mean 1,000,000 and standard deviation 300,000 bu,
reflecting the risk of weather-related performance. The amount of corn is assumed unknown until the
harvest date.

QUESTIONS
1. Assume we have a static strategy where we take a single futures position. Simulate, graph and
explain the probability distribution of the possible margin requirements per futures contract.
2. Determine the optimal number of contracts she should use to hedge, assuming her objective is
to minimize the standard deviation of the total profit/loss as of the harvest date.
3. Repeat (1) and (2) assuming she hedges with the KCBOT futures but sells the corn in Chicago.
4. Prepare a 1-2 page writeup with graphs and texts, making any recommendations to her that you
think appropriate.

See the PDF for more details.
