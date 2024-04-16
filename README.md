# Dappcord

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (React & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)
- [Socket.io](https://socket.io/) (Client & Server communication)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/)

## Setting Up
### 1. Clone the Repository

### 2. Start Hardhat node
`$ npx hardhat node`

### 3. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 4. Start Socket.io server
`$ node server.js`

### 5. Start frontend
In a separate terminal execute:
`$ npm run start`
