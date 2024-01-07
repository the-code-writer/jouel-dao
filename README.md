# JOUEL DAO

Jouel DAO is a DAO that was created by the Jouel Network, a platform that aims to provide decentralized energy solutions using blockchain technology and smart contracts The Jouel Network allows users to generate, store, trade, and consume renewable energy using peer-to-peer transactions and microgrids

The Jouel DAO and its members own and operate an NFT marketplace called eNFTis, which stands for energy non-fungible tokens An NFT is a unique and indivisible digital asset that represents ownership of something, such as art, music, or in this case, energy eNFTis are NFTs that represent units of energy that can be produced, consumed, or traded on the Jouel Network

The Jouel DAO is responsible for governing the eNFTis marketplace and ensuring its security, fairness, and sustainability. The Jouel DAO members can vote on various proposals and policies related to the eNFTis marketplace, such as fees, rewards, rules, and upgrades The Jouel DAO members can also benefit from the revenue generated by the eNFTis marketplace, as well as the appreciation of their energy NFTs

The Jouel DAO is an example of how a DAO can create and manage a novel and innovative NFT marketplace that leverages the power of blockchain technology and renewable energy

# Advanced Sample Hardhat Project

This project demonstrates an advanced Hardhat use case, integrating other tools commonly used alongside Hardhat in the ecosystem.

The project comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts. It also comes with a variety of other tools, preconfigured to work with the project code.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
npx hardhat help
REPORT_GAS=true npx hardhat test
npx hardhat coverage
npx hardhat run scripts/deploy.js
node scripts/deploy.js
npx eslint '**/*.js'
npx eslint '**/*.js' --fix
npx prettier '**/*.{json,sol,md}' --check
npx prettier '**/*.{json,sol,md}' --write
npx solhint 'contracts/**/*.sol'
npx solhint 'contracts/**/*.sol' --fix
```

# Etherscan verification

To try out Etherscan verification, you first need to deploy a contract to an Ethereum network that's supported by Etherscan, such as Ropsten.

In this project, copy the .env.example file to a file named .env, and then edit it to fill in the details. Enter your Etherscan API key, your Ropsten node URL (eg from Alchemy), and the private key of the account which will send the deployment transaction. With a valid .env file in place, first deploy your contract:

```shell
hardhat run --network ropsten scripts/deploy.js
```

Then, copy the deployment address and paste it in to replace `DEPLOYED_CONTRACT_ADDRESS` in this command:

```shell
npx hardhat verify --network ropsten DEPLOYED_CONTRACT_ADDRESS "Hello, Hardhat!"
```
