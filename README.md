# Twitter follower gains and losses post-Elon takeover

This repository contains data for The Verge's article, *Conservative Twitter accounts got boost in followers after Musk acquisition, data shows.*

The repo contains 6 CSV files:
* `conservative-list.csv` and `liberal-list.csv` each contain the names and Twitter handles of 50 prominent politicians, pundits and other influencers.
* `conservative-follows.csv` and `liberal-follows.csv` contain 30 days of historical follower data for each account in the above lists, including the absolute numerical follower change day-on-day and the percentage change.
* `conservative-mean-change.csv` and `liberal-mean-change.csv` contain values for the day-on-day percentage change in follower count averaged across ideological groups.

The repo also contains one iPython notebook, `Twitter follower analysis.ipynb`, with some of the basic calculations underlying the article.