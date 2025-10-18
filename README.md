# 🌿 GreenCarbon

GreenCarbon is a decentralized carbon credit trading platform built using **Solidity** and deployed on the **CORE Testnet**. It enables certified environmental organizations to issue, transfer, and retire carbon credits transparently and securely on the blockchain.

---

## 📜 Live Deployment

* **Blockchain:** Flow EVM Testnet
* **Deployed Contract Address:** [0x81F3284Cac78049924EdcfD516D6e3BE5615c978]
* **Transaction Hash:** [0x4fd983b4d27353bcd3890593125259513de395ff40233b05cbd043a4622164eb]
* Deploy on flow testnet :-[https://evm-testnet.flowscan.io/address/0x81F3284Cac78049924EdcfD516D6e3BE5615c978]

✅ Successfully created on **Flow EVM Testnet — Verified & Confirmed.**

---

## ✨ New Features

✅ **🏛 Certified Issuers Only** – Only authorized issuers can mint carbon credits.
✅ **🔁 Transferable Tokens** – Credits follow an ERC-20-like structure for flexible trading.
✅ **🔥 Retire/Burn Functionality** – Credits can be destroyed to represent carbon offsetting.
✅ **🔍 Public Verification** – Anyone can view issuance, transfers, and retirements on-chain.
✅ **⚙ Upgradeable Process** – Smart contract ready for upgrades and integrations.

---

## 🛠 How It Works

### 1️⃣ Admin Authorizes Issuers

The platform admin grants permission to verified organizations to act as credit issuers.

```solidity
addCertifiedIssuer(address issuer);
```

### 2️⃣ Issuers Mint Carbon Credits

Certified entities mint new carbon credits to businesses or platforms.

```solidity
mintCredits(address to, uint256 amount);
```

### 3️⃣ Users Transfer Credits

Anyone can trade carbon credits like ERC-20 tokens.

```solidity
transfer(address to, uint256 amount);
approve(address spender, uint256 amount);
transferFrom(address from, address to, uint256 amount);
```

### 4️⃣ Companies Retire Credits

To officially offset carbon, credits are permanently burned.

```solidity
burn(uint256 amount);
```

---

## 📁 Project Structure

```
greencarbon/
├── contracts/
│   └── GreenCarbon.sol     # Smart contract code
├── scripts/
│   └── deploy.js           # Hardhat deployment script
├── test/
│   └── greencarbon.test.js # Automated tests
├── README.md
├── hardhat.config.js
└── package.json
```

---

## 🧪 Installation & Testing

### ✅ Prerequisites

* Node.js v16+
* Hardhat
* MetaMask (for CORE Testnet interaction)

### ✅ Steps

```bash
git clone https://github.com/yourusername/greencarbon.git
cd greencarbon
npm install
npx hardhat compile
npx hardhat test
```

---

## 🔄 Deployment (Optional)

Update the deploy script and run:

```bash
npx hardhat run scripts/deploy.js --network coreTestnet
```

---

## 📜 Contract Function Summary

| Function               | Description                                   | Access           |
| ---------------------- | --------------------------------------------- | ---------------- |
| `addCertifiedIssuer()` | Add an authorized entity to issue credits     | Admin only       |
| `mintCredits()`        | Issue carbon credits to a wallet              | Certified issuer |
| `transfer()`           | Send credits to another user                  | Public           |
| `approve()`            | Allow another address to spend on your behalf | Public           |
| `transferFrom()`       | Transfer using allowance                      | Public           |
| `burn()`               | Permanently retire carbon credits             | Public           |

---

## 🌍 Real-World Use Cases

* Government climate programs
* Voluntary carbon offsetting by corporations
* NGO-led green initiatives
* Blockchain-powered emission trading systems

---

## 📄 License

**MIT License** – Free to use, modify, and distribute.

---

## 🤝 Contributing

We welcome community collaboration!

1. Fork the repo
2. Create your branch:

```bash
git checkout -b feature/xyz
```

3. Commit and push:

```bash
git push origin feature/xyz
```

4. Submit a Pull Request

---

## 👋 Contact

**Maintainer:** Debkanta-Dey
📧 **Email:** [debkantadey29@gmail.com](mailto:debkantadey29@gmail.com)

---

# 🌱 GreenCarbon – Enabling sustainable climate action, one smart contract at a time.

---

## 📷 Screenshot

<img width="1919" height="959" alt="Screenshot 2025-10-18 122928" src="https://github.com/user-attachments/assets/072b76b1-d30c-4034-a757-1230c6ad009d" />

