
# METACRAFTERS ETH-AVAX INTERMEDIATE PROJECT 2

This project consists of a Solidity contract for an Ethereum-based ATM system and a React frontend that interacts with the contract via MetaMask. The Solidity contract allows users to deposit and withdraw Ether, check balances, and reset the balance to zero. The React frontend provides a user interface to connect MetaMask, display account information, perform deposits and withdrawals, check if the balance is above a certain threshold, and reset the balance.

## Description

The Solidity contract Assessment defines an ATM system, enabling operations such as depositing funds, withdrawing funds (with custom error handling for insufficient balance), checking balances above a specified threshold, and resetting the balance. 

The React component HomePage integrates MetaMask for account connectivity, displaying account details and providing actions to deposit Ether, withdraw Ether, check if the balance exceeds 3 ETH, and reset the balance.

# Getting Started

## Starter Next/Hardhat Project

## Installing

1. Clone the repository:
   ```
   git clone https://github.com/athulyajayanv/ETH-AVAX-Intermediate_Project-2.git

   ```

After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type:
   ```
    npm i
   ```
2. Open two additional terminals in your VS code
3. In the second terminal type:
   ```
    npx hardhat node
   ```
4. In the third terminal, type:
   ```
   npx hardhat run --network localhost scripts/deploy.js
   ```
5. Back in the first terminal, type:
   ```
   npm run dev
   ```
    It will launch the front-end.
   
6. After this, the project will be running on your localhost. 
Typically at http://localhost:3000/


# Connecting to MetaMask

1. Make sure MetaMask is installed in your browser.
2. Switch MetaMask to the local network.
3. When prompted, connect MetaMask to the application by clicking the "Please connect your MetaMask wallet" button.
   

# Help

1. Ensure you have installed all dependencies by running npm install.
2. Check if the Hardhat node is running using npx hardhat node.
3. Make sure you have deployed the contract using npx hardhat run --network localhost scripts/deploy.js.
4. Verify that your MetaMask is connected to the correct network and account.


## Authors

Athulya Jayan V


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
