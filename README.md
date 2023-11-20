# Stock Market Prediction Using Markov Chains

## Group Members
- Brandon Monge - Section 008
- Hermann Bauer - Section 005
- Aiden Harris - Section 005
- Michael Kim - Section 004
- Hunter Ross - Section 001

## Project Overview

### Topic
We aim to use Markov Chains as a predictive tool for stock market movements. The project involves aggregating and cleaning historical data for an arbitrary stock, defining different states (bull, stagnant, bear), calculating a transition matrix using Python, and using it to predict stock movements. The accuracy of predictions will be tested using backtesting, and the model's performance will be compared across different types of stocks.

### Relevance
Accurate stock market predictions are crucial for investors and financial analysts. These models contribute to individual financial success and have broader economic implications, providing insights into economic trends and aiding policymakers and businesses in making informed decisions for economic stability.

### Mathematical Interest
The project involves Markov chains, transition matrices, eigenvalues, and eigenvectors—fundamental concepts in linear algebra. Solving for these elements is crucial for understanding the long-term behavior of the Markov chain.

### Data Source
We will use historical stock pricing data obtained from the Yahoo Finance API, a reliable source for financial data.

### Assumptions
The project assumes that financial markets depend solely on historical pricing data, simplifying the complex dynamics of financial markets.

### Resources
- [Markovian model for stock price evolution](https://www.cis.upenn.edu/~mkearns/papers/pricemodel.pdf)
- [Introduction to Markov Chains and Applications](http://www.math.chalmers.se/Stat/Grundutb/CTH/mve220/1617/redingprojects16-17/IntroMarkovChainsandApplications.pdf)
- [Exploring Markov Chains in Stock Market Trends](https://ghannami.com/exploring-markov-chains-in-stock-market-trends/)

### Computations and Software
We will use Python libraries, including NumPy, Pandas, yfinance, and scikit-learn. Tasks include data retrieval, preprocessing, and building the transition probability matrix.

### Team Background and Skills
- Brandon Monge: Computer Science major, Python
- Hermann Bauer: Computer Science and Economics Major
- Aiden Harris: Data science, analysis, and pipeline building in Python
- Michael Kim: Computer Science major, Python
- Hunter Ross: Computer Science major, Python

### Project Timeline

- **Theory Development** (11/22) - Hermann
- **Data Aggregation** (11/23) - Aiden
- **Code Implementation** (11/28) - Hunter, Brandon, and Mikey
- **Final Report** (12/01) - Whole team in a meeting
- **Presentation Deck** (12/01) - Whole team in a meeting
