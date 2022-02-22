# AetherDAO lite-paper (More to come)
The AetherDAO introduces 3 new Native Assets to the Cardano Ecosystem.
- originAether
- Aether
- governAether

The AetherDAO offers individuals the ability to purchase Aether tokens via a bonding mechanism from the DAO, in addition to this, the DAO will purchase Aether tokens off of the market when the contents of the treasury sufficiently exceeds the current market cap of the token reflected in the integrated liquidity pool(s). Any Aether owned by the DAO treasury will be used to stake into the yield bearing mechanism of the DAO. When the market cap exceeds the treasury contents sufficiently the DAO will unstake and sell enough tokens to lower the market cap sufficiently OR expend all of the Aether held by the DAO. Additional liquidity in the DAOs treasury will be used to interact with defi protocols. When possible this will be done directly; where required, a native-script multi-sig will be leveraged.

In addition to the mechanisms above, the AetherDAO incentivizes holding Aether by offering a yield bearing mechanism known as staking. When you stake your Aether, you will earn an APY that is calculated based on:
1) The current treasury to market cap ratio.
2) The protocol parameters set in the governance module.
This is explained further below.

## Bonding
The bonding discount will be set by the DAO via standard proposals, these bonds take 1, 3, 12, or 18 epochs in order to mature, and the discounts are set differently for each accordingly.

Bonding discounts will also vary depending on the collateral type used.

## Staking
Staking APR is calculated at the end of each epoch and Aether is not set aside for members until the APR is calculated for the past epoch. Members that have not harvested their rewards after 12 epochs will forfeit half of the rewards for the 13th epoch staked to a bot which redeems that epochs reward for the user.

A sigmoid function is used to determine the APR each epoch, if the treasury is under-collateralizing the market cap of Aether, no rewards will be issued.

## DAO Profit: Purchase / Stake / Sell
Coming soon.

## DAO Profit: DeFi
At the most basic level, the DAO will profit from having it's treasury contents staked to a pool that can be decided upon by the DAO. In addition to this, the DAO will seek to maximize yield and do so in a way that maximizes security of members - DeFi will be integrated directly where possible as opposed to leveraging multi-sigs.

The DAO will likely provide liquidity as well as lend through various platforms, as well as seek to leverage undercollateralized flash-loans to arbitrage trade the market.
