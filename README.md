# GreenAI

Welcome to the GreenAI ! blockchain-based app rewarding users with GreenCoins for planting trees and reducing carbon emissions, turning eco-friendly actions into valuable carbon credits.

This guide walks you through the setup, deployment, and interaction with the GreenAI application.

![Logo](https://i.ibb.co/9Hgy8fb/logo.png)

## 🧰 Tech Stack

**Client:** Next.Js , Metamask

**Server:** Solidity, Truffle, Ganache, ethers.js

## 📑 Prerequisites

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Truffle](https://www.trufflesuite.com/truffle)
- [Ganache](https://www.trufflesuite.com/ganache)
- [MetaMask](https://metamask.io/)

## 🔥 Features

- **Smart Contract Deployment**: Deploy GreenCoin smart contracts using Truffle.
- **Connect Wallet**: Connect MetaMask to interact with the application and perform transactions.
- **Calculate GreenCoins**: Enter tree information to calculate CO2 sequestered and earn GreenCoins.
- **Transaction Handling**: Handle transactions securely using MetaMask integration.
- **User Interface**: Intuitive UI for seamless interaction and feedback on transactions.
- **Blockchain Interaction**: View and manage GreenCoin balances across multiple accounts on the blockchain.
- **Consult GreenCoin Balance**: Check the balance of GreenCoins for any account on the blockchain.
- **Buy GreenCoins**: Purchase GreenCoins from the chosen account.

## 🚀 Getting Started

This work was conducted using Google Design Sprint methodology:

- [Miro Board ](https://miro.com/app/board/uXjVK7X8j94=/)

📌 Tip: You can access GreenAI services directly from this link, but first, ensure you've configured the GreenChain by following the 3rd, 4th and 6th parts of the installation guide.

If you prefer to deploy it on your own:

### 1. Clone the Repository

```bash
git clone https://github.com/bensaied/GreenAi.git
cd GreenAi
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Truffle Setup

3.1 Install Truffle

```bash
npm install -g truffle
```

3.2 Compile Contracts

```bash
truffle compile
```

3.3 Deploy Contracts
Make sure Ganache is running before migrating the contracts.

```bash
truffle migrate
```

### 4. Ganache Setup

4.1 Download and Install Ganache

Download Ganache from here and install it.

4.2 Start a New Workspace

Open Ganache and click on "New Workspace".

Name your workspace "GreenChain".

Add your project to the workspace by selecting the truffle-config.js file from your project directory.

Click on "Save Workspace".

4.3 Configure Ganache Accounts in MetaMask

Open MetaMask and click on your account icon, then select "Import Account".

Copy the private keys of Ganache accounts and import them into MetaMask.

Repeat this for multiple accounts as needed.

4.4 Configure MetaMask to Use the GreenChain

Open MetaMask and click on the network dropdown.

Select "Custom RPC".

Enter the following details:

![Logo](https://i.ibb.co/FhYx3D0/Green-Chain.png)

Click "Save".

### 5. Running the Application

5.1 Start the Development Server

```bash
npm run dev
```

5.2 Access the Application
Open your browser and navigate to http://localhost:3000.

### 6. Interacting with the Application

6.1 Connecting Your Wallet

Click on "Connect Wallet" in the application.

MetaMask will prompt you to connect your wallet. Select the account you want to use.

6.2 Checking GreenCoin Balance

After connecting your wallet, your GreenCoin balance will be displayed.

You can also view the balances of other connected accounts on the blockchain.

6.3 Buying GreenCoins

Choose an account and enter the amount of GreenCoins you want to buy.

Click "Buy GreenCoins" and confirm the transaction in MetaMask.

Upon successful transaction, the GreenCoins will be transferred to your selected account.

## 🔧 Troubleshooting

Ensure that Ganache is running before deploying contracts with Truffle.

Make sure MetaMask is connected to the correct network (GreenChain) and that the correct accounts are imported.

If transactions fail, check the console for error messages and ensure that you have sufficient ETH for gas fees.

## 📝 Authors

- Github: [@bensaied](https://www.github.com/bensaied)

## Contributing

Contributions are always welcome!

- [Ghassen Ben Ali ](https://github.com/ghassenbenali96)
- [Walid Bzeouich ](https://github.com/walid354)
- [Nourhene Ben Reguigua ](https://github.com/BRnourheene)

## 💝 Support

For support, don't forget to leave a star ⭐️.

## ⚖️ License

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.
