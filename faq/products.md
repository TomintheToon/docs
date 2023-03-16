---
description: Dual Investment Pools and Staking Options
---

# Products

**Which tokens can I stake into DIPs to start?**\
SOL (Soon BTC, ETH, MNGO, MSOL and others)

**Which wallets are supported?**\
Currently we support Phantom, Glow, Solflare and Backpack wallets. Any wallet using solana-wallet-adapter can be easily integrated.

**What is meant by the quoted APY on DIPs?**\
APYs are a normalized way to examine risk and effective yield between different strikes, expirations and products.

**How is APY calculated?**\
APY = Premium / Spot Price / Years until Expiration

**How is the amount of Liquidity Staking Options (LSO) rewarded calculated?**\
LSO (Coming Soon!) quantities are calculated based on the amount you stake into the DIP.

**What determines the strike and expiration of Liquidity Staking Option?**\
The strike will be a function of the strike of the DIP that you deposit into. The expiration equals the same date as the DIP.

**Is there a minimum trade amount?**\
DIPs minimum deposit is the amount of stake that pays 0.001 of USDC premium. This amount may vary depending upon current yields, but is sufficiently low to enable user testing to become familiar with the product.

**Why is Physical settlement used for DIPs and Staking Options?**\
Physically settlement allows the actual exchange or trade of tokens at the strike price, unlike Cash settlement which just pays the difference of the strike and current price. Physically settlement is better for illiquid tokens which have hard to determine current prices and eliminates the dependency on oracles which can be easily maninpulated on the illiquid markets which Staking Options are seeking to improve.

**How can I exercise a Staking Option I've earned?**\
Go to [Balances](https://beta.dual.finance/balance) any time before the expiration date and have enough USDC in your wallet to be able to buy for the strike price.

**Do my Staking Options automatically get exercised if they're profitable?**\
No, options do not automatically exercise. They require a transaction to be confirmed from the owner prior to expiration exercising their right to actually purchase the asset.

**What is the "Source" in the DIP confirmation?**\
Source is either Backstop - meaning Dual Finance's Risk Manager is providing the price and premium OR Streaming - meaning an external Market Maker is streaming prices.

**How is the premium provided?**\
Premiums are quoted directly from Option Market Makers or via the Dual Finance Backstop Volatility Model. This premium updates in real-time. The first integrated Option Market Maker is [GSR](https://www.gsr.io/)

**Why are DIPs and Staking Options fully collateralized?**\
Fully collateralized means the option has all of the assets required to pay if it were exercised. For each token staked, users receive a premium for that quantity, no leverage is allowed. Therefore there is no counterparty risk or default risk from utilizing these products.

**Why isn’t my staking transaction going through?**\
Most likely there is not enough SOL for the transaction fee, or not enough of the token being staked. Please create a [ticket](https://discord.com/channels/937797334048325673/1070906120622854154) in discord if issues persist or you identify bugs.
