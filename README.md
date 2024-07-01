# ETH-AVAX_PROOF_Module2
Module 2 Smart Contract Management Project: Function Frontend

## Interact with Your Smart Contract through Front-end Practice Code

### Description
The files `index.js`, `Assessment.sol`, and `deploy.js` contain code to practice interacting with the `SmartContract_with_Front_end_interaction` smart contract through a website.

### Note
The `deploy.js` file contains the frontend code.

### Environment Setup for Executing the Files
Follow these steps:

1. Clone this repository or download and extract the zip file.

2. The repository contains all necessary files to interact with our smart contract.

3. Copy the contents of `index.js` from this repository to the `index.js` file in the `pages` folder.

4. Copy the contents of `deploy.js` from this repository to the `deploy.js` file in the `scripts` folder.

5. Install the MetaMask Browser Extension.

### Starter Next/Hardhat Project

After cloning the GitHub repository, follow these steps to get the code running on your computer:

1. Inside the project directory, in the terminal, type: `npm i`

2. Open two additional terminals in your VS code.

3. In the second terminal, type: `npx hardhat node`

4. In the third terminal, type: `npx hardhat run --network localhost scripts/deploy.js`
   (Note: You can also verify the address of deployment in the `contractAddress` variable in the `index.js` file)

5. Back in the first terminal, type `npm run dev` to launch the frontend.

After this, the project will be running on your local host, typically at `http://localhost:3000/`.

### Setting up the Local Host Network and a Dummy Account in Your MetaMask Wallet

To interact with the smart contract locally, set up a local network with the MetaMask wallet:

1. Click on the MetaMask extension and then click on the network selection button at the top middle.

2. Click on "Add a Network."

3. Click on "Add a Network Manually."

4. Give the Network a name (choose any name you like).

5. Set the New RPC URL to `http://127.0.0.1:8545/`.

6. Set the Chain ID to `31337`.

7. Set the Currency symbol to `ETH`.

8. Now, set the MetaMask wallet network to the newly created local network.

To set up an account, import an account with the account's private key, which you can find in the second terminal where you executed the command `npx hardhat node`. After hitting enter, you will see many account numbers with private keys listed in the terminal. Take any account's corresponding private key to import it into your MetaMask Wallet.

Head to `http://localhost:3000/` to start interacting with the MetaMask Wallet.

You can also see all transaction details in the deploy terminal.
