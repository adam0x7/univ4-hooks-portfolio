# Uniswap v4 Hooks Portfolio 🦄

## What are hooks Uniswap v4?
Uniswap v4 hooks are customizable smart contracts that can be plugged into the Uniswap Protocol. They allow developers to modify or extend the behavior of liquidity pools, swaps, fees, and LP positions. Hooks provide a powerful way to innovate on top of the Uniswap Protocol’s liquidity and security, enabling unique trading strategies, optimized yields, and enhanced compliance controls. 
- [Uniswap v4 Whitepaper(Draft)](https://github.com/Uniswap/v4-core/blob/main/whitepaper-v4-draft.pdf)
- [v4 announcement](https://blog.uniswap.org/uniswap-v4)
- [Hayden Adams discussing v4 on Bankless](https://www.youtube.com/watch?v=ZmhdNiGOMRU)

## My V4 Hook Ideas
Feel free to implement these ideas for yourself!

| Name                                         | Description                                                                                                  | Link to Github Repo | Category           |
|----------------------------------------------|--------------------------------------------------------------------------------------------------------------|---------------------|--------------------|
| Multi-Sig Hook                               | A hook that requires multiple signatures for certain pool actions.                                           | [Repo](https://github.com/atj3097/mfa-multisig-hook-v4/tree/main)           | Security           |
| Impermanent Loss Mitigation Hook             | A hook to mitigate impermanent loss by using a rebalancing strategy.                                         |          | Liquidity          |
| Depositing Unused Liquidity into Lending     | A hook that automatically deposits liquidity that is not currently in use (out-of-range) into lending protocols.|         | Yield Optimization |
| KYC (Know Your Customer) Hook                | A hook that integrates KYC procedures for liquidity providers or swappers.                                   |           | Compliance         |
| Whitelist Hook                               | A hook that restricts pool participation to a whitelist of approved addresses.                               |  [Repo](https://github.com/atj3097/whitelist-hook)       | Access Control     |
| Loyalty Reward System Hook                   | A hook that rewards liquidity providers with loyalty points or tokens based on participation duration or volume.|         | Incentives         |

## Example Implementations of Hooks
- [Trading Hours Hook](https://github.com/bennoprice/univ4/blob/main/src/TradingHours.sol)
- [Hedging Mechanisms w/ Hooks](https://github.com/vanillaHill/hedge)
- [Median Oracles](https://github.com/saucepoint/median-oracles)
- [Examples from Uniswap Labs](https://github.com/Uniswap/v4-periphery/tree/main/contracts/hooks/examples)


## Want to Build with Uniswap V4 Hooks?
Uniswap v4 hooks provide an exciting avenue for both seasoned developers and absolute beginners to contribute to the DeFi ecosystem. Here are some beginne to advanced friendly resources:

- If you're totally new to solidity, web3 development in general -> [Alchemy University](https://university.alchemy.com/) is your best friend.
- [Study the Uniswap V4 Periphary & Core Contracts](https://github.com/Uniswap/v4-core)
- [Tutorial / How to ​integrate Uniswap v4 and create custom hooks](https://soliditydeveloper.com/uniswap4)
- [Template to start building your own v4 hooks](https://github.com/saucepoint/v4-template)

#### Last but not least, join the discussion with the rest of the dev community @ [https://hooks.uniswapfoundation.org/](https://hooks.uniswapfoundation.org/)

