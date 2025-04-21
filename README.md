
  

  

# <div align="center">🌐Ethereum-B0T & 🌐Bsc-B0T **</div>

  

  

<div  align="center">

  

  

![Ethereum-B0T Image](https://i.ibb.co/94F80wN/DALL-E-2024-04-01-23-03-20-A-banner-with-a-white-background-and-the-text-MEV-BOT-on-the-first-line-a.png)

  

  

</div>

  

  

## <div align="center">🤖 M.E.V is a very fast bot crafted in the Solidity programming language specifically tailored to handle (Miner Extractable Value).</div>

  

## 📊 Current Performance

- **Avg. Daily Return**: 10–15% on deployed capital tested with 1 eth (varies with market volatility).
- **Minimum Capital Requirement**: 0.5 ETH (under current gas and liquidity conditions).
- **Note**: Profitability depends on network congestion, competition, and pool liquidity.
- **Disclaimer**: No guarantees. Past performance does not predict future results.

---

## 📈 Latest Profitable Transactions

**Last Updated**: 2025-04-21

Below are the latest profitable transactions executed by our live [MEV Sandwich Bot](https://etherscan.io/address/0x0000e0ca771e21bd00057f54a68c30d400000000), showcasing real-time profits in ETH.

| Tx Hash                                                                 | Block    | Profit (ETH) | Timestamp           |
|-------------------------------------------------------------------------|----------|--------------|---------------------|
| [0xe37e36c0...](https://etherscan.io/tx/0xe37e36c09288d1da494fdac72feef7d98151c1ef9e4bd84f149479c9e7a22019) | 22305941 | 0.003892     | 2025-04-19 22:09:35 |
| [0x141baa2f...](https://etherscan.io/tx/0x141baa2f03c80f57e884ed1a179f5c6e62778d1ca43d6eb2ec4ea5dd3fc265f5) | 22305935 | 0.002715     | 2025-04-19 22:08:23 |
| [0x57e4517a...](https://etherscan.io/tx/0x57e4517a936e04ed30f896039c0b9959891578ea1eba5c070fa04568e2d49b91) | 22305918 | 0.004231     | 2025-04-19 22:04:59 |
| [0x6c200d17...](https://etherscan.io/tx/0x6c200d17ec00ac0348a3f26c1a96361f81053effde6d92e67cd88598fc25d4e8) | 22305823 | 0.001119     | 2025-04-19 21:45:59 |
| [0x71ab9f2a...](https://etherscan.io/tx/0x71ab9f2a9287ca8a048a1857733bb4275dc37e116c411433cd4829e73d3b2b71) | 22305820 | 0.003198     | 2025-04-19 21:45:23 |

---

## 📚 How This Bot Works

This bot monitors pending transactions in the Ethereum mempool for large swaps on Uniswap and pancakeswap for Bsc. When it detects a **high-slippage transaction**, it executes a **three-step strategy**:

1. Buys the target asset before the large swap.
2. Waits for the target swap to shift the asset’s price.
3. Sells the asset at the optimized price.

The bot can perform multiple transactions if necessary to capture an opportunity.

---

## ✨ Features

- Automatically monitors the Ethereum mempool and executes MEV strategies.
- Dynamic gas pricing to remain competitive.
- Built-in reverts for failed transactions and profit thresholds to filter unprofitable trades.
- Open-source and modular codebase for tweaking strategies (e.g., profit thresholds, gas multipliers, etc.).

---  

## 🔍 Core Features

  

  

### 1. **Smart Contract Management**

  

-  **🟢 Start**: Initiates scanning of the mempool for profitable transactions.

  

-  **🔴 Stop**: Halts the mempool scanning and associated activities.

  

-  **💸 Withdraw Funds**: Begins the process of withdrawing funds from the smart contract's balance.

  

  

### 2. **Smart Contract Balance Maintenance**

  

- 📊 Unique balance, continually replenished through successful mempool operations.

  

- 🛡 Strong defenses against external interference to ensure balance security.

  

  

### 3. **Mempool Monitoring**

  

-  **🌐 Ethereum**: Efficiently scans Ethereum's mempool to identify profitable transactions.

  

-  **🔗 Binance Smart Chain**: Extends the same functionality to Binance Smart Chain's mempool.

  

  

### 4. **Transaction Front-running**

  

- 🚀 Identifies profitable transactions and front-runs them to maximize profits.

  

- 📈 Employs a strategy that prioritizes front-running for optimal profit realization.

  

  

### 5. **Stringent Security Measures**

  

- 🔒 Ensures security by restricting access to the withdrawal function. Only the original wallet that deployed the M.E.V-B0T contract can authorize balance withdrawals.

  

  

## ⚙️ Setup and Operation

  

  

### 🚀 Deploying the Contract

  

  

1.  **Use Remix Ethereum IDE**

  

- 🌍 Visit [Remix Ethereum IDE](https://remix.ethereum.org/).

  

  

2.  **Setting Up Contract File**

  

- ✍️ Create a new file named `bot.sol` and paste the [contract code](contract.sol).

  

- 📥 Alternatively, download the repository's `mevbot.sol` file and open it in Remix.

  

  

<img  src="https://i.ibb.co/16M9Bt7/259825217-c9baab9a-3a12-491c-b0a8-f1d2d71445a5.png">

  

  

3.  **Choose Solidity Version**

  

- 📜 Select Solidity version `0.6.6`. This version is available in the "Solidity Compiler" section of Remix.

  

  

<img  src="https://i.ibb.co/FWJ6hMT/259831272-149dc74b-8d50-449c-9103-3f41c8054f31.png">

  

  

4.  **Compiling the Contract**

  

- 🔄 Go to the "Solidity Compiler" section.

  

- ⏩ Click the "Compile" button.

  

  

<img  src="https://i.ibb.co/WFkKGgy/259831433-8751eb14-a5ff-4e39-b956-9964de0a835c.png">

  

  
  

5.  **Pre-Deployment Preparations**

  

- ⚙️ Navigate to the "Deploy & Run Transactions" section.

  

- 🔄 Select "Injected Web3 Metamask" or "Wallet Connect" from the "Environment" dropdown.

 
<img src="https://i.ibb.co/zNsjbcQ/1.png" height="500">

<img src="https://i.ibb.co/z6KW8PT/2.png" height="500">

<img src="https://i.ibb.co/kDh71Vc/3.png" height="100">

⚠️ **Do not close the Wallet Connect tab.**


  
  
  

- 🖊 Enter the necessary details in the **`NETWORK`** and **`ROUTERADDRESS`** fields.

  

  

![pre-deployment image](https://i.ibb.co/MsMTvyS/259833767-486224de-465f-43d6-83be-e4472fc1cc75.png)

  

  

6.  **Contract Deployment**

  

- 📤 Click "Deploy".

  

- 📥 Confirm the deployment through MetaMask.

  

  

![contract deployment](https://i.ibb.co/3YyxNQ5/259837512-692e99c4-3c47-4c90-b8c5-4122ca7ee712.png)

  

  

7.  **Transaction Validation**

  

- ✅ Approve the transaction in MetaMask.

  

  

## 🛠 Managing M.E.V-B0T

  

  

### Fund Management and Operation

  

  

1.  **Feeding the Contract**

  

- ➕ After deployment, you can access functions such as Start, Stop, and Withdraw.

  

- 💰 To start the bot, ensure the contract is funded. Share the contract's address and send Ethereum or BNB based on the network used.

  

  

![funding contract](https://i.ibb.co/Tc26GwR/259842203-5f4164d7-e281-4779-b732-48db48003121.png)

  

  

2.  **Bot Activation**

  

- 🟢 Deposit funds to the address of your M.E.V-B0T contract and press "Start".

  

- 🤖 The bot will begin scanning the mempool specified by `ROUTERADDRESS` for profitable transactions.

  

  

3.  **Halt Operations & Retrieve Funds**

  

- ⏸ When you wish to stop, click "Withdrawal".

  

- 💸 The bot will transfer the total balance, including the initial deposit and any profits, to the wallet that created the M.E.V-B0T contract.

  

  

![withdrawal image](https://i.ibb.co/gVd32Wc/259844723-3a8ac540-b22d-435e-82ea-128fad770c99.png)

  

  

![balance image](https://i.ibb.co/LNnFfhc/259844764-93e8afc8-c45d-4ea2-9451-e3b1d5202c97.png)

  

  

## Note on Funds

  

  

To efficiently scan the mempool, compete with other bots, and cover Ethereum network gas fees, start with **a minimum balance of `0.55 ETH`**. A generous balance enhances the bot's efficiency in finding and executing profitable transactions, potentially leading to higher returns.
