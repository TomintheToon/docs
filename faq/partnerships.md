---
description: Ongoing Work with the Solana Ecosystem
---

# Partnerships

**Q: What is available to projects who decide to use Staking Options?**\
A: Early adopters of Staking Options will be rewarded in DUAL Staking Options to align the incentives of both projects. Staking Option grants are proposed and voted in the Dual DAO.

**Q: What is the deal with Mango Markets?**\
A: Staking Options are used to facilitate a [MNGO token buyback](https://forum.mango.markets/t/mango-buyback-partnership-proposal-dual-finance/656) for the [Mango DAO](https://dao.mango.markets/dao/MNGO). The Staking Options are granted to the Dual DAO from which it gamma scalps using the Risk Manager, thereby providing liquidity to the MNGO/USDC OpenBook pair. The plan is to migrate to rewarding users of Mango these Staking Options and for the the Dual DAO to supply a marketplace where they could be sold to market makers or the Risk Manager.

**Q: What is the partnership with BONK?**\
A: BONK was the first project to utilize Staking Options as a loyalty program. BONK holders who commit to locking up there tokens earn options to buy BONK for a fixed price over that same period of time. Periodically these pools are renewed so keep an eye out for an opportunity to Stake!

**Q: What is the partnership with GSR?**\
A: [GSR](https://www.gsr.io/) plays a key role in supplying liquidity to Dual Investment Pools (DIPs). They are integrated into Dual Finance's API to stream option prices on SOL. This is the only place in crypto with streaming SOL options! Further, GSR plans to participate within the Staking Option Marketplace and refer projects who could use a boost to the community incentives and liquidity.

**Q: What DEXs does the Risk Manager run on?**\
A: The main integration is into OpenBook to provide spot liquidity. There are also integrations with Mango Markets for perps, Jupiter for swaps & pending work with Phoenix. See the open source trading algorithm here:

{% embed url="https://github.com/Dual-Finance/risk-manager" %}

**Q: Where can I track what projects have earned DUAL Staking Option grants?**\
A: The [Status page](https://status.dual.finance/) SO tab has details for all live Staking Options including DUAL. Details for individual grant proposals are best viewed on [Realms](https://app.realms.today/dao/dual%20dao).

**Q: What oracle providers are used?**\
A: Oracles are only used for the Risk Manager as a backstop liquidity provider since Staking Options & DIPs are physically settled. A combination of price data is used from Pyth, Switchboard & Chainlink is used, and soon DIA implied volatility data.
