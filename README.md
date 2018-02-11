# crypto-data-warehouse

## Why?

Crypto world is exploding. There are thousands fo cryptocurrency and tokens on the market now, and more are coming.
Infomation about crypto is scattered on official website, twitter, github, telegram group, slack channel, youtube channel, wechat groups, news site, crypto forums, ico rating site, etc. It's overwhelming if you are a serious investor. It's time to organise those info to save investors' precious time.

## What?

1. Classification. Although there are thousands of cryptocurrencies and tokens, they can be classified into groups. E.g., currencies such as BTC, Zcash, platform tokens such as ETH, NEO, application tokens such as SNT, Steem. 
2. Comparison. Once classified into groups, cryptos can be compared against each other within the same group. They are compared by features collected in the data warehouse. The *features* can be github code updates, github code forks, github code stars, twitter followers, telegram group members, etc.
3. Search. Cryptos can be searched by all the aspects, such as code, name, team members, etc.

*feature* data should be collected over time and form a time series so that we can see how the features change over time. This is very important as we need to identify trend to answer "does it become better or worse", which is very important to an investment decision.

## How?

1. Centralised. Just like Google, we write code to actively collect the data from the internet. Fortunately the data source such as github, twitter provides standard APIs which make the data collection easier than web crawling. 
2. Decentralised. We build a platform so that data providers and data validators feed the platform with quality data to get reward and data consumers pay to consume the data.

## data sources
1. github
2. linkedIn
3. twitter
4. telegram
5. facebook
6. reddit
7. medium
8. slack
9. https://etherscan.io/
10. https://www.smithandcrown.com/icos/
11. https://www.coinmarketcap.com
12. ...

## data to capture
1. crypto/token name
2. crypto/token transactions
3. github code updates
4. github code forks
5. github code stars
6. twitter followers
7. telegram group members
8. facebook page likes
9. reddit posts
10. medium posts
11. team members
12. whitepaper text
13. ...
