# Solana_arbitrage
Test solution arbitrage solana sur Orca
# Orca Typescript SDK

The Orca SDK contains a set of simple to use APIs to allow developers to integrate with the Orca exchange platform.

Learn more Orca [here](https://docs.orca.so).

### Trading Orca Liquidity Pools

- Get detailed quotes and make swaps between trading pairs in an Orca Pool
- Check your Orca Pool LP token balance and total supply

**Supported Orca Pools**

- The SDK supports all pools currently listed on [Orca](https://www.orca.so/pools)

### Provide Liquidity to Orca Pools

- Deposit liquidity to supported Orca Pools
  - Deposit a trading pair, and receive LP token
- Withdraw liquidity from supported Orca Pools
  - Withdraw a trading pair in exchange for LP token

**Aquafarm Support**

- After depositing liquidtiy to a pool, the LP token can be deposited into
  the corresponding farm to receive an equivalent amount of farm token
- Remember to withdraw the LP token in exchange for farm token before
  withdrawing liquidity from Orca Pool

**DoubleDip Support**

- For farms with double-dip, the aquafarm tokens can be deposited into
  double-dip farm to receive double-dip rewards

**Features Coming Soon**

- More trader information (APY, Volume)

# Installation

Use your environment's package manager to install @orca-so/sdk and other related packages into your project.

```bash
yarn add @orca-so/sdk @solana/web3.js decimal.js
```

```bash
npm install @orca-so/sdk @solana/web3.js decimal.js
```
