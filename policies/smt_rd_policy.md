# SMT - Rewards Distribution - Policy

## Liquidity Provider Rewards
* 75% of weekly rewards
* SPT balance is calculated per address and per network, then prorated by total liquidity on platform
* Addresses with liquidity on multiple networks are calculated separately.
* Individual user rewards capped at 500% APY for up to $10M platform liquidity, and 250% for $10M-100M. No cap thereafter.
* SMT pools receive a 4x rewards boost vs other pools

## Trading Rewards
* 25% of weekly rewards (in relation to Liquidity Provider Rewards)
* Trading Rewards are calculated based on individual trading volume per address and per network, thenprorated against volume of trades made by all addresses on platform
* 100% of address gas expenses for transactions on Ethereum (trading and liquidity provision) are compensated in SMT

## Loyalty Rewards
* Ratio of SMT held vs total asset value staked in liquidity pools determines loyalty rewards (LINK)
* Loyalty level is calculated per address per network and is not combined across networks.
* SMT balance includes amounts held 1/ in trading wallets, 2/ unclaimed from SMT rewards, and 3/ provided into Swarm Markets liquidity pools 
* Boost factor applied to LP Reward participation and Trading Rewards.

## General
* All values are denominated in USD  for calculation purposes and then converted into SMT based on weekly SMT price average
* Averages based on daily snapshots during the week
* Weekly distributions based on predefined weekly [SMT rewards release schedule](https://docs.google.com/spreadsheets/d/13XTheJLsMDjeZUs9HGYUkjN6hA5BtsA-u6oRMrf24Ug/edit#gid=1658174309)
* SMT rewards determined and made claimable after week 
* Any undistributed weekly rewards roll-over to subsequent weekly rewards
