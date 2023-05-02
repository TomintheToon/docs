---
Description: Dual Investment Pools and Staking Options
---

# Products

**Which tokens can I stake into DIPs to start?**\
SOL (Soon BTC, ETH, MNGO, MSOL and others)

**Which wallets are supported?**\
Currently we support Phantom, Glow, Solflare and Backpack wallets. Any wallet using the solana-wallet-adapter can be easily integrated.

**What is meant by the quoted APY on DIPs?**\
APYs are a normalized way to examine risk and effective yield between different strikes, expirations and products.

**How is APY calculated?**\
APY = Premium / Spot Price / Years until Expiration

**How is the amount of Liquidity Staking Options (LSO) rewarded calculated?**\
LSO quantities are calculated based on the amount you stake into the DIP.

**What determines the strike and expiration of Liquidity Staking Option?**\
The strike is a function of the strike of the DIP that you deposit into. The expiration is set as the same date as the expiry of the DIP.

**Is there a minimum trade amount?**\
DIPs have a minimum deposit calculated as the amount of stake that will pay 0.001 of USDC premium. The minimum amount therefore varies depending upon current yields, but is sufficiently low to enable users to test and become familiar with the product.

**Why is Physical settlement used for DIPs and Staking Options?**\
Physical settlement allows the exchange ('trade') of tokens at the strike price, enabling users to build a position in the option token. It is suited to scenarios where there is low liquidity in the base token, as low liquidity makes determining the current fair price difficult. Staking Options seek to reduce the dependency on pricing oracles, which can easily be manipulated for low liquidity tokens.   

**What are the Advanced Settlement Options?**\
Dual currently offers two alternative exercise methods and a liquidation mechanism, intended for advanced users only:\
**- Cash Settlement:** The cash settlement option allows users to take profits from an ITM option, effectively paying the user the difference between the strike price and the current market price of the base token. This entails the user making two transactions that will (1) purchase the base tokens (as per physical settlement), (2) sell all of the purchased base tokens for USDC via a swap on Jupiter. NB. Users are required to have sufficient USDC in their wallet to cover the entire purchase of the base tokens in step (1) in order to use the Cash Settlement mechanism.\
**- Hybrid Settlement:** The hybrid settlement option allows users to use the profits from an ITM option to purchase base tokens, leaving the user with base tokens at no cost to them. This entails the user making two transaction that will (1) purchase the base tokens (as per physical settlement), (2) sell just enough of the purchased base tokens for USDC in order to cover the cost of the purchase in step (1). NB. Users are required to have sufficient USDC in their wallet to cover the entire purchase of the base tokens in step (1) in order to use the Hybrid Settlement mechanism.\
**- Liquidate:** The liquidate option allows users to take profits from any Staking Option regardless of the current price without having to provide any USDC. Liquidate sells the option rather than exercising it, paying the user a backstop market price. NB. This mechanism is only available on certain Staking/Liquidity Options and includes a 50 bps fee to the user, which is paid to the Dual DAO.

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
