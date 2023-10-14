# Hardhat
Welcome to the repository where I've embarked on my journey into the world of cryptocurrencies and smart contracts. This project is built on the Ethereum Virtual Machine (EVM) and has been deployed on the Sepolia Testnet using the powerful Hardhat framework. ***But you better check my another work, My decentralized application on zkSync Era Testnet.*** https://github.com/disiminar/zkSync-test-proj
### Here are some specifications of the project:
- In tests, I used [ethers.js](https://docs.ethers.org/v6/) to interact with the Ethereum contract, and I used [Mocha](https://mochajs.org/) as my test runner.
- My test token info:
  - There is a fixed total supply of tokens that can't be changed.
  - The entire supply is assigned to the address that deploys the contract.
  - Anyone can receive tokens.
  - Anyone with at least one token can transfer tokens.
  - The token is non-divisible. You can transfer 1, 2, 3 or 37 tokens but not 2.5.
  - Link to **transaction of smart-contract creation** on Sepolia testnet scan [here](https://sepolia.etherscan.io/tx/0xa09d06fc86d9926cad45bb3875d7ace15452e6f04b288b37aca3a6048416ca44) 
- I am using [Infura](https://www.infura.io/) to get API private key for deploying smart-contract on real network (testnet)
- In order not to waste time on the front-end, I used a ready-made example from the Hardhat team (Hardhat Boilerplate). link on [repository](https://github.com/NomicFoundation/hardhat-boilerplate)

#### After this, i can transfer tokens by using the Boilerplate GUI on localhost, or console.
Example of output: 
```
eth_sendTransaction
  Contract call:       Token#transfer
  Transaction:         0x460526d98b86f7886cd0f218d6618c96d27de7c745462ff8141973253e89b7d4
  From:                0xc783df8a850f42e7f7e57013759c285caa701eb6
  To:                  0x7c2c195cd6d34b8f845992d380aadb2730bb9c6f
  Value:               0 ETH
  Gas used:            37098 of 185490
  Block #8:            0x6b6cd29029b31f30158bfbd12faf2c4ac4263068fd12b6130f5655e70d1bc257

  console.log:
    Transferring from 0xc783df8a850f42e7f7e57013759c285caa701eb6 to 0x0987a41e73e69f60c5071ce3c8f7e730f9a60f90 100 tokens
```
