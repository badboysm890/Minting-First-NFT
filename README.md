# **Minting Your First NFT. ðĪŠ **

Hi this is my first course (DRAFT) in which we will be meeting the first NFT of your life. Course you will learn how to use solidity & JavaScript to mint an NFT. All the things required and environment set up will be followed in the same course so that at the end of this course you will be learning how to maintain an NFT and also create and smart contract with using solidity.


# Installation

Clone the given repository which will kickstart the project initially. 

    npm install


# Config â ïļ

Create a file named **hardhat.config.js**

Add the following snippet with the nessasary code.

    require("@nomiclabs/hardhat-waffle");
    module.exports  = {
    defaultNetwork:  "rinkeby",
    networks: {
    rinkeby: {
    url:  '{alchemy HTTP API URL}',
    accounts: ['Wallet Private Key']
    }
    },
    solidity:  '0.8.4'
    }

# Course Plan 

**Minting Your First NFT - Draft 1**

1. Intro to **Cryptocurrency**, **Tokens**, **NFT** and **DAO**
2. What is a **blockchain** ?
3. Dipping Toes deeper into Blockchain â
4. Setting up the wallet (Meta Mask). ððŧ
5. WTF ð§ is a **NFT** ? 
6. Basic intro to **SOLIDITY** and **JAVASCRIPT** ð§ðŧâðŧ

6. Lets mint our own NFT - 1 ðŠ
-  Tech Stack
-  Installation and Env Setup
-  Testing

7. Lets Mint out own NFT - 2 ð 
- Creating a Smart contracts to mint an NFT
- Mint an NFT

8. **On-Chain** NFT ð
- What is DATA URI
- Mint NFT on-chain using the same Contract
- End of Part one (Keystone Project)
