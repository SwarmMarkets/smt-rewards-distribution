# SMT - Rewards Distribution - Policy

## Liquidity Provider Rewards
* 50% of weekly rewards
* Liquidity (SPT) balance is calculated per address and per network, then prorated by total liquidity on platform
* Addresses with liquidity on multiple networks are calculated separately.
* Individual user rewards capped at 500% APY for up to $10M platform liquidity, and 250% for $10M-100M. No cap thereafter.
* Pools with RWAs (stocks, bonds and indexes) receive a 4x rewards boost vs other pools

## RWA Holder Rewards
* 25% of weekly rewards
* RWA Holder Rewards are calculated based on each address's USD-equivalent holdings of RWAs issued on the Swarm protocol prorated against Total Market Cap of all RWAs 

## Staking Rewards
* 25% of weekly rewards
* Staking Rewards are based on each address's amount of $SMT staked against a specific RWA, calculated using the RWA's Market Cap (TVL) as a proportion of total RWA Market Cap, prorated against all $SMT stakes against the specific RWA.

## Loyalty Rewards
* Ratio of $SMT held vs total asset value staked in liquidity pools determines loyalty rewards.
* Loyalty level is calculated per address per network and is not combined across networks.
* $SMT balance includes amounts held 1/ in trading wallets, 2/ unclaimed from $SMT rewards, and 3/ provided into Swarm Markets liquidity pools 
* Boost factor applied to LP Reward participation.

## Deflationary measures
* Rewards will be allocated according to the total value locked on Swarm, with 25% of rewards being allocated per TVL threshold:
- - 0-$10M
- - $10M-$100M
- - $100M-$1Bn
- - +$1B
* Unallocated rewards will be burned each week, reducing the total circulating supply.

## General
* All values are denominated in USD for calculation purposes and then converted into $SMT based on weekly $SMT price average
* Averages based on daily snapshots during the week
* Weekly distributions based on predefined weekly [SMT rewards release schedule](https://docs.google.com/spreadsheets/d/13XTheJLsMDjeZUs9HGYUkjN6hA5BtsA-u6oRMrf24Ug/edit#gid=1658174309)
* $SMT rewards determined and made claimable after week 
* Any undistributed weekly rewards roll-over to subsequent weekly rewards
