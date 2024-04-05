# Real Estate NFT DApp

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (React & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/)

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Run tests
`$ npx hardhat test`

### 4. Start Hardhat node
`$ npx hardhat node`

### 5. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`


About Project
Blockchain based realestate website 
List properties online with blockchain and let people buy property directly from their wallet

User going to connect their wallet and interact with website
Website is going to talk with smart contract that user created
Website has property and each property is represented by NFT
Each property is listed in escrow and hence, property has to be approved by other parties and funded before property ownership transfer and finalizing transaction







Escrow Contract
Seller list property 
Buyer goes through the process of buying by paying down payment,
Appraisal
Inspection
Buyer gets approval of loan from lender and lender provide remaining sum of money to seller
Transfer ownership from seller to buyer
Transfer payment from buyer to seller

Using Openzeppelin library 

