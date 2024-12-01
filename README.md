# agoric-yield-agg-fasthack


<img width="1920" alt="Team@2x" src="https://github.com/user-attachments/assets/ec783f0e-9b6f-472e-813e-33833a59f76c">

![Screenshot 2024-12-01 at 7 36 13 PM](https://github.com/user-attachments/assets/b37be311-f160-48f9-b861-428f4292beac)
![Screenshot 2024-12-01 at 7 35 22 PM](https://github.com/user-attachments/assets/3277fe46-0985-4a85-9b9a-8a5c0213edfd)
![Screenshot 2024-12-01 at 7 06 11 PM](https://github.com/user-attachments/assets/7a7f41c5-333f-4b9a-8ab0-6a15e33b1ca3)
![Screenshot 2024-12-01 at 7 35 05 PM](https://github.com/user-attachments/assets/5a46d818-9f9b-4b26-9030-38aba5ad1e20)
![Screenshot 2024-12-01 at 7 35 46 PM](https://github.com/user-attachments/assets/5d8fb257-08d4-4fd4-a857-d81619d09a7d)

# Defi Yield Aggregator
This project is a simple decentrialized app where a user can deposit DAI into our smart contract.
Once funds are deposited, the contract compares the interest rate of Compound & Aave, and deposits
funds to whichever has the highest interest rate. The user can rebalance his/her funds to ensure
that the funds are still currently in the higher interest rate protocol, and can also withdraw at
any time.

## Technology Stack & Tools

- Solidity (Writing Smart Contract)
- Javascript (React & Testing)
- [Web3](https://web3js.readthedocs.io/en/v1.5.2/) (Blockchain Interaction)
- [Truffle](https://www.trufflesuite.com/docs/truffle/overview) (Development Framework)
- [Ganache-cli](https://github.com/trufflesuite/ganache) (For Local Blockchain)
- [Infura.io](https://infura.io/) (For copying the Ethereum mainnet)
- [MetaMask](https://metamask.io/) (Ethereum Wallet)
- Openzeppelin (Solidity Math)

## Requirements
- Install [NodeJS](https://nodejs.org/en/), I recommend using node version 10.16.3 to avoid any potential dependency issues
- Create or log in to your [Infura.io](https://infura.io/login) account and create a new project, and save your project ID located in your project settings, you'll need this when starting the ganache-cli server.
- Install [MetaMask](https://metamask.io/) in your browser.
- Install [Ganache-cli](https://github.com/trufflesuite/ganache). To see if you have ganache-cli installed, in your command line type `ganache-cli --version`. To install, in your command line type `npm install ganache-cli --global`
