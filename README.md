Hackmoney Demo:
https://youtu.be/02_wbnqb71M?t=2956

Description
This project combines a dynamic transaction building front end with a tokenised on-chain transaction encoder. In order to demonstrate the power of these tokenised transactions (we call them treasure maps) we also built treasure planets, which is a simple treasury management contract capable of executing treasure maps.

Managing DAO's funds is often very hard especially if it requires complex execution and advanced programming knowledge, Our goal was to create a way for DAOs to manage their funds in a convenient and transparent way, even if they want to create complex transactions.

TreasureBuidl showcase

How it's made
This project utilised the proposal storage and execution pattern laid out by the compound governance contracts. We integrated with Aave, Compound, Uniswap, Balancer and StakeDAO to allow for flexible transaction building with the most popular protocols within the front end. 

The front-end is built with React.js, Node.js, and Ethers.js.

The smart contract architecture is novel, and we see great potential for the concept of tokenised transactions

<div align="center">
    <h1>TreasureBuidl</h1>
    <h6>
        An onchain transaction builder with a built in escrow, enabling efficient treasury management for cross application investments. 
    </h6>
</div>

---

# About

This project has been split into the following folders:
* [onchain](./packages/onchain/README.md)
* [frontend](./packages/frontend/README.md)

The on chain folder contains the smart contract side of the project, while the front end folder contains the UI, and data management. 

This project was built for the EthGlobal HackMoney 2021 hackathon. 
