# 🎰 Raffle - A Provably Fair Lottery on Ethereum Sepolia

Welcome to **Raffle**, a provably fair, decentralized lottery built on the **Ethereum Sepolia** testnet.  
This project leverages **Chainlink VRF** and **Chainlink Automation** to ensure transparency, randomness, and full decentralization.

---

## 🚀 What Is Raffle?

Raffle is a smart contract-based lottery that ensures **provable fairness**, **true randomness**, and **full automation** through the use of blockchain technology.

Unlike traditional or centralized lottery systems, Raffle provides:
- ✅ Verifiable randomness
- ✅ Immutable code
- ✅ Transparent execution
- ✅ Automated upkeep and winner selection

---

## 🧱 Features

- **Custom Errors** for gas optimization
- **Enums** for cleaner state management
- **Private State Variables** with getter functions for encapsulation
- **Verbose Constructor** for flexible deployment across different chains
- **Automated Raffle Execution** via **Chainlink Automation**
- **Winner Selection** through **Chainlink VRF**
- **CEI Pattern** (Checks-Effects-Interactions) for secure contract logic
- **Helper Configs & Scripts** for easy testing and deployment
- **Mock Deployments** for local development
- **Command Line Scripts** to manage the Raffle lifecycle
- **Comprehensive Testing** with mocked Chainlink functions

---

## ⚙️ How It Works

1. **Deployment**  
   The `Raffle` contract is deployed to Ethereum Sepolia using a configuration helper that allows for seamless deployment to any network.

2. **Entering the Raffle**  
   Users can enter the raffle by sending ETH to the contract.

3. **Automation via Chainlink**  
   Chainlink Automation monitors the contract and triggers the upkeep when certain conditions are met.

4. **Random Winner Selection**  
   When the upkeep is performed, Chainlink VRF is called to generate a provably random winner.

5. **Prize Distribution**  
   The winner is selected and sent the entire lottery pool.

---

## 🛠️ Tech Stack

- **Solidity** (Smart Contract Language)
- **Chainlink VRF v2.5** (Verifiable Random Function)
- **Chainlink Automation** (Decentralized Cron Jobs)
- **Sepolia Testnet**
- **Foundry / Cast** (Optional alternative tools)
---

## 🧪 Testing & Mocking

- Unit tests simulate real-world scenarios.
- Used **mock Chainlink contracts** to simulate Automation and VRF.
- Captured event logs for advanced testing workflows.
- Verified reverts and modifiers using ABI encoder techniques.

---

## 🧵 Script Automation

To streamline usage, custom scripts were written to:
- Deploy the contract
- Add consumer to Chainlink VRF
- Create and fund subscriptions
- Interact with the contract from the CLI without needing Cast manually

---

## 🔗 Deployment Details

- **Network**: Ethereum Sepolia
- **Contract Name**: `Raffle`
- **Chainlink VRF & Automation**: Integrated
- **Contract Status**: Deployed and tested

---

## 📚 Learnings

- Deep dive into Chainlink VRF and Automation
- Advanced Solidity concepts: modifiers, revert conditions, custom errors
- Proper contract architecture following CEI pattern
- Deployment scripts and CLI tooling
- Writing maintainable and readable smart contract code (~200 lines)

---

## 📄 License

MIT License

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you'd like to change.

---

## 📬 Contact

For questions or collaborations, feel free to open an issue or contact me directly.


## Contract Address

- Contract deployed at Sepolia with contract address: 0xbd64bB91260e10a2060EFBf42dD45FE2Ce5BCe58 [Etherscan Sepolia](https://sepolia.etherscan.io/address/0xbd64bB91260e10a2060EFBf42dD45FE2Ce5BCe58)
