# Hardhat
Welcome to the repository where I've embarked on my journey into the world of cryptocurrencies and smart contracts. This project is built on the Ethereum Virtual Machine (EVM) and has been deployed on the Sepolia Testnet using the powerful Hardhat framework.
### Here are some specifications of the project:
- In tests, I used [ethers.js](https://docs.ethers.org/v6/) to interact with the Ethereum contract, and I used [Mocha](https://mochajs.org/) as my test runner.
- My test token info:
  - There is a fixed total supply of tokens that can't be changed.
  - The entire supply is assigned to the address that deploys the contract.
  - Anyone can receive tokens.
  - Anyone with at least one token can transfer tokens.
  - The token is non-divisible. You can transfer 1, 2, 3 or 37 tokens but not 2.5.
  - Link to **transaction of smart-contract creation** on Sepolia testnet scan [here](https://sepolia.etherscan.io/tx/0xa09d06fc86d9926cad45bb3875d7ace15452e6f04b288b37aca3a6048416ca44) 
