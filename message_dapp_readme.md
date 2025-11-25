# MessageDApp – Blockchain-based Message Storage

A decentralized application (DApp) that allows users to store and retrieve messages on the Ethereum blockchain. Built with Solidity, Remix IDE, MetaMask, and a modern frontend using HTML, CSS, and Ethers.js.

---

## Features

- Store messages on the Ethereum blockchain (immutable)
- Retrieve all messages or just the latest message
- Connect via MetaMask wallet
- Responsive, modern frontend with dynamic message display
- Optional dark mode with alternate color scheme
- Easy to deploy and test on Ethereum testnets

---

## Tech Stack

- Smart Contract: Solidity
- Blockchain: Ethereum (testnets like Goerli/Hoodi)
- Frontend: HTML, CSS, JavaScript
- Web3 Library: Ethers.js
- Wallet Integration: MetaMask
- Development Environment: Remix IDE

---

## File Structure

```
MessageDApp/
│
├─ index.html        # Frontend HTML
├─ style.css         # Styling for DApp
├─ MessageDapp.sol   # Solidity smart contract
├─ README.md         # Project documentation
└─ screenshots/      # Folder for screenshots
```

---

## Setup & Installation

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/MessageDApp.git
cd MessageDApp
```

2. Start a local server to run the frontend

If you have Python installed:

```bash
python -m http.server 5500
```

Open in browser:

```
http://localhost:5500
```

3. Deploy Smart Contract

- Open `MessageDapp.sol` in Remix IDE
- Compile the contract
- Deploy to an Ethereum testnet (e.g., Goerli, Ethereum Hoodi) using MetaMask
- Copy the deployed contract address

4. Update Frontend

- Open `index.html`
- Replace the `contractAddress` in the JavaScript section with your deployed contract address:

```javascript
const contractAddress = "YOUR_DEPLOYED_CONTRACT_ADDRESS";
```

5. Connect MetaMask

- Make sure your MetaMask wallet is connected to the same testnet where you deployed the contract
- Open the frontend in the browser and interact with the DApp

---

## Usage

1. Type a message in the input box
2. Click **Set Message (write)** to store it on the blockchain
3. Click **Get Message (read)** to fetch all stored messages
4. Messages will appear in the chat-style message box below



