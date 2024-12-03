# SMT - Rewards Distribution - Policy

SMT Rewards will consist of three categories:

* Liquidity Providers (Ethereum, Polygon, BASE)
* RWA Holders (Polygon)
* RWA Stakers (Polygon)

Regular calculations will be made to determine the TVL for each category, applying any boosts, with the weekly SMT allocated distributed proportionally to each category.

Within each category, rewards will be distributed to each wallet address proportional to their contribution to the total TVL.

## Liquidity Provider Rewards
Liquidity Provider rewards are distributed to wallets that make viable offers with eligible assets within the Open dOTC protocol.

**Note that as of December 2, 2024, rewards will be distributed for offers made on dOTC v2 only. Offers on dOTC v1 will no longer be eligible for rewards.  
**

**Boost**: Offers which include an RWA will be given a 2x boost.

**Viable offers** are those offers that are:
* live (not cancelled, expired, or fully taken),
* public (not private offers)
* in-range: priced within 20% of the current market price for the asset pair. The closer the offer price to the market price, the higher the reward.

**Eligible assets** refers to assets for which a price feed exists, currently being:
* Ethereum: SMT, wETH, wBTC, USDC, DAI, USDT, EUROC
* Polygon: SMT, wETH, wBTC, USDC, USDC.e, DAI, WMATIC, AAPL, TSLA, TBONDS01, TBONDS13, COIN, NVDA, MSFT, MSTR, INTC, CPNG, BLK, xGold

The calculated value of each offer and the period of time it is considered in-range will determine the amount of reward to the offer maker, in proportion to the total TVL of the protocol.

## RWA Holder Rewards
Wallets which hold a balance of any of Swarm’s RWA assets (stocks, bonds and gold NFTs) will be counted by taking the value (in USD) of their RWA holdings and applying a 4x boost.

RWAs deposited as offers the Open dOTC protocol are also eligible.

## RWA Staking Rewards
Rewards are distributed per RWA according to the market cap of each RWA in relation to total platform TVL.

Wallets which have staked $SMT against a specific RWA will be entitled to a share of its rewards relative to all wallets staking against the same RWA.

## Deflationary measures
* Rewards will be allocated according to the total value locked on Swarm, with 25% of rewards being allocated per TVL threshold:
- - 0-$10M
- - $10M-$100M
- - $100M-$1Bn
- - +$1B
* Unallocated rewards will be burned each week, reducing the total circulating supply.

## General
* As of 2.12.2024, liquidity provider rewards are distributed for offers made on dOTC v2 (found at app.swarm.com) 
* All values are denominated in USD for calculation purposes and then converted into $SMT based on weekly $SMT price average
* Averages based on daily snapshots during the week
* Weekly distributions based on predefined weekly [SMT rewards release schedule](https://docs.google.com/spreadsheets/d/13XTheJLsMDjeZUs9HGYUkjN6hA5BtsA-u6oRMrf24Ug/edit#gid=1658174309)
* $SMT rewards determined and made claimable after week 
* Any undistributed weekly rewards roll-over to subsequent weekly rewards
