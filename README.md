# Alpha-Hunting

### Project 1 - Overnight Returns and Firm-Specific Investor Sentiment

Inspired by this research paper: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2554010

Abstract: "...read... First, we document short-term persistence in overnight returns, consistent with existing evidence of short-term persistence in share demand of sentiment-influenced retail investors..."

Idea: The cumulative overnight returns over a week may be predictive of future returns; hence it's a kind of momentum signal.

### Project 2 - The Formation Process of Winners and Losers in Momentum Investing

Inspired by this research paper: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2610571

"...In other words, when there are two winner (or loser) stocks, the one with convex-shaped historical prices will possess higher future expected returns than the one with concave-shaped historical prices..."

Idea: Regress previous daily prices in the ranking period on an ordinal time variable and the square of the ordinal time variable for each stock, and use the coefficients as factors. So we have 3 alpha factors to test (2 + 1 extra conditional factor).
