# Monte-Carlo
Monte Carlo Simulation predicting price movement

## Approach
1. Import libraries & download data
2. Compute log returns, variance and drift
3. exp(r) is the random variable
4. Create an empty array with dimensions same as exp(r)
5. Assign the first value of this empty array to be the last Adj Close of MSFT
6. Predict today's price = Yesterday's price * exp(r)
7. Plot the results

![download](https://user-images.githubusercontent.com/78731243/121799848-0ba6e580-cc4c-11eb-9631-2e839058664c.png)

## Interpreting the Simulation
(All prices are in dollars)

The current Price is 257.890

1. Expected price movement after 50 days :
<br>Lowest: 175 
<br>Highest: 350

2. Expected price movement after 150 days :
<br>Lowest: 120 
<br>Highest: 550- 
  
3. Expected price movement after 250 days :
<br>Lowest: 100 
<br>Highest: 700
