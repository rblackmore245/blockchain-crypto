# Blockchain Wallet

This is a simple web application that simulates a blockchain wallet. It allows users to create new wallets, manage transactions, request airdrops, and view blockchain statistics. The application is built using Node.js, Express.js, and HTML/CSS.

## Installation

1. Clone the repository:


2. Open a web browser and go to `http://localhost:3000` to access the Blockchain Wallet application.

## Endpoints

The following HTTP endpoints are available in the application:

- `POST /createWallet`: Creates a new wallet and returns the wallet address and private key.
- `GET /stats`: Retrieves blockchain statistics, including the number of blocks, pending transactions, wallets, tokens transferred, and holding wallet balance.
- `GET /getBalanceOfAddress`: Retrieves the balance of a specific wallet address.
- `GET /getRecentTransactions`: Retrieves a specified number of recent transactions from the blockchain.
- `POST /sendTransaction`: Sends a transaction from one wallet address to another.
- `POST /stake`: Stakes a specified amount from a wallet address.
- `POST /claimAirdrop`: Requests an airdrop for a wallet address.

## How to Use

1. Create a Wallet:
   - Click on the "Create Wallet" button to generate a new wallet.
   - The wallet address and private key will be displayed.
   - Save the private key in a secure location.

2. Manage Wallet:
   - Enter the wallet address, recipient address, amount, and private key in the respective input fields.
   - Click on the "Send Transaction" button to send a transaction.
   - Click on the "Request Airdrop" button to request an airdrop for the wallet address.

3. View Blockchain Statistics:
   - The blockchain statistics, including the number of blocks, pending transactions, wallets, tokens transferred, and holding wallet balance, will be displayed in the corresponding section.

4. Additional Functionality:
   - The application automatically mines a new block every 5 seconds.
   - The blockchain data is saved to a local file (`blockchain.json`) for persistence.

## License

[MIT License](LICENSE)
