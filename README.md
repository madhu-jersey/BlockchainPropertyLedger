BlockchainPropertyLedger

Problem Statement

This project focuses on security and preventing unauthorized manipulation of sensitive public data, such as real estate property records or company shareholder information. By storing this data on a blockchain, it becomes almost impossible to alter, ensuring integrity and trust.

Establish a proof-of-concept for a distributed ledger system.

Develop a blockchain-based application using ‘Records of Property’ as a use-case, similar to cryptocurrencies like Bitcoin.

About Blockchain

Blockchain is a technology where a list of records (blocks) is cryptographically linked with timestamps and other attributes.

This project implements a fully distributed and decentralized application:

There is no central authority.

Transactions are accepted only if the majority of the peer-to-peer (P2P) network agrees via a consensus algorithm.

Every node in the P2P network holds a copy of the ledger.

For this application, the focus is on preventing fraud in the real estate market. Users can buy and sell property directly, without worrying about middlemen or manipulation.

Goals

Store house/property data on the Ethereum blockchain.

Allow adding new houses.

Enable updating house data.

Implement buying functionality, allowing purchases only if the buyer has sufficient funds.

Steps to Run the Project
Step 1: Install MetaMask

Download MetaMask from your browser’s extension store (e.g., Chrome Web Store).

Step 2: Create Accounts & Get Test Ether

Create 2 accounts in MetaMask.

Mine or get 4 Ether for each account on the test network.

Step 3: Clone the Repository
git clone <your-repo-link>
cd <project-folder>

Step 4: Install Node.js

Check installation: node -v

If not installed, download from Node.js
.

Step 5: Install Dependencies
npm install -g gulp
bower install
bower install web3
gulp serve

Step 6: Launch the Application

Open your browser and go to:

http://localhost:9000

Step 7: Explore the Application

Add new houses, update property details, or buy/sell properties using the platform.

All transactions are securely stored on the Ethereum blockchain.
