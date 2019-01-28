# Machine Learning for Sports Betting with Neural Network and custom loss function.
We present a way to incorporate bets' potential profit into a neural network classifier model using a custom loss function. We believe this to be extremely useful for anyone looking to use machine learning to create a betting system. It is what we do at BetSentiment.com.

## Data.
For our data we take a list of 200 games from the English Premier League, season 2018–2019, August to December 2018. It contains descriptive game data such as team names, bookmaker odds from BetFair, and our BetSentiment sentiment score (representing the percentage of positive tweets over the positive and negative tweets - 30 millions tweets analyzed so far!).

## Custom loss function
We set up our custom loss function with Keras on top of TensorFlow.

For more info please check our article on medium