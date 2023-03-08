---
description: Dual Investment Pools & Staking Options
---

# Products

Q: Which tokens can I stake to start? \
A: SOL & BONK (Soon BTC, ETH, MNGO and others)

Q: Which wallets are supported? \
A: Currently we support Phantom, Glow, Solflare and Backpack wallets.

Q: What is meant by the quoted APY on DIPs? \
A: APYs are a normalized way to examine risk and effective yield between different strikes, expirations and products.

Q: How is APY calculated? \
A: APY % = Premium / Spot Price / Years until Expiration

Q: How is the amount of Liquidity Staking Options (LSO) rewarded calculated? \
A: LSO (Coming Soon!) quantities are calculated based on the notional you stake into the DIP. Initially, 25% of the staked notional is paid in LSOs on DUAL. For example if you stake 1 BTC worth $40,000, you would earn $10,000 of DUAL LSOs. The $10,000 is divided by the price of DUAL to determine the quantity.

Q: What determines the strike & expiration of Liquidity Staking Option? \
A: The strike equals the % difference between the DIP asset’s spot & strike price at the time of staking. The expiration equals the same date as the DIP. For example, if you stake into a 1 week DIP that is 20% higher than spot price, you earn an LSO for 1 week that is also 20% higher than spot price.

Q: Is there a minimum trade amount? \
A: Initially no, feel free to test DIPs out to get comfortable with their mechanics.

Q: Why is Physical settlement used for DIPs & Staking Options?\
A: Physically settlement allows the actual exchange or trade of tokens at the strike price, unlike Cash settlement which just pays the difference of the strike and current price. Physically settlement is better for illiquid tokens which have hard to determine current prices and reduces dependencies on oracles.

Q: How can I exercise a Staking Option I've earned?\
A: Go to [https://beta.dual.finance/balance](https://beta.dual.finance/balance) any time before the expiration date and have enough USDC in your wallet to be able to buy for the strike price.&#x20;

Q: Do my Staking Options automatically get exercised if they're profitable?\
A: No, options do not automatically exercise. They require a transaction to be confirmed from the owner prior to expiration exercising their right to actually purchase the asset.

Q: What is the "Source" in the DIP confirmation?\
A: Source is either Backstop - meaning Dual Finance's Risk Manager is providing the price and premium OR Streaming - meaning an external Market Maker is streaming prices.

Q: How is the premium provided? \
A: Premiums are quoted via an API directly from Option Market Makers or via the Dual Finance Backstop Volatility Model. This premium updates in real-time so you can better time the market. The first integrated Option Market Maker is GSR [gsr.io](https://www.gsr.io/)

Q: What is fully collateralized? \
A: Fully collateralized means the option has all of the assets required to pay if it were exercised. For each token staked, users receive a premium 1 to 1 with that quantity, no leverage is allowed.

Q: Why isn’t my staking transaction going through? \
A: Most likely there is not enough SOL for the transaction fee, not enough of the associated token, or you’re not using the correct wallet/address. Please create a ticket in discord if issues persist or you identify bugs.
