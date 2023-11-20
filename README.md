# ETHAVAX2 SMART CONTRACT PROJECT - FUNCTION FRONTEND

## Overview

This project implements a basic smart contract that simulates how an online ATM machine works with the application of DeFi apps.

## Smart Contract Details

- **Contract Name**: Assessment
- **License**: MIT
- **Solidity Version**: 0.8.9

## Functions

### `getBalance()`

Returns the current balance of the ATM.

### `deposit(uint256 _amount)`

Allows the owner to deposit funds into the ATM, increasing the balance.

### `withdraw(uint256 _withdrawAmount)`

Allows the owner to withdraw funds from the ATM, decreasing the balance.

### `multiplyBalance(uint256 _multiplier)`

Allows the owner to multiply the current balance by a specified multiplier.

### `divideBalance(uint256 _divider)`

Allows the owner to divide the current balance by a specified divider.

## Events

- `Deposit(uint256 amount)`: Triggered when a deposit is made.
- `Withdraw(uint256 amount)`: Triggered when a withdrawal is made.
- `BalanceMultiplied(uint256 previousBalance, uint256 newBalance)`: Triggered when the balance is multiplied.
- `BalanceDivided(uint256 previousBalance, uint256 newBalance)`: Triggered when the balance is divided.

## Usage

### Deploying the Smart Contract

After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

### Interacting with the Smart Contract

- Connect your Ethereum wallet to the deployed smart contract.
- Use the provided functions to deposit, withdraw, multiply, and divide the balance.

## Author

  Mendizabal, Jed Marco
    GitHub: @MarcoJSY
  
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
