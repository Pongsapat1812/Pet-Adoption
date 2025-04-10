# 🐶🐱 Pet-Adoption Platform

A blockchain-based pet adoption platform developed to help address the stray animal crisis in Thailand.

---

## 📌 Introduction

Thailand is currently facing a significant issue with a growing population of stray dogs and cats. In response, this project aims to **connect homeless animals with loving adopters** through a transparent, secure, and traceable system.

This web-based platform helps streamline the pet adoption process while using **blockchain technology** to ensure trustworthy record-keeping of health and ownership history.

---

## 🧩 Key Features

### 🐾 Animal Profile Creation
Each animal listed for adoption will have a dedicated profile containing:
- Name (if available)
- Breed
- Approximate age
- Gender
- Health status
- Photos

### 📜 Adoption Tracking
Once an animal is adopted, the system records:
- Adopter's name and address
- Adoption date

This enables full tracking of ownership transfers and promotes responsible pet ownership.

### 🔐 Smart Contract Integration
Using blockchain technology, the platform implements **Smart Contracts** to ensure immutability of:
- Health history
- Adoption records

This guarantees data transparency, accuracy, and long-term traceability.

---

## 🚀 Setup & Deployment Guide

Follow these steps to set up and deploy the Smart Contract:

### 1. Install Ganache

Download and install Ganache from the official site:  
🔗 [https://archive.trufflesuite.com/ganache/](https://archive.trufflesuite.com/ganache/)

---

### 2. Install Truffle

Use Node.js to globally install Truffle:

```bash
npm install -g truffle
```

---

### 3. Add `truffle-config.js`

Create or update the `truffle-config.js` file with the following configuration to connect with your local Ganache:

```js
module.exports = {
  networks: {
    development: {
      host: "127.0.0.1",
      port: 7545,
      network_id: "*"
    }
  },
  compilers: {
    solc: {
      version: "0.8.0"
    }
  }
};
```

---

### 4. Compile the Smart Contract

Navigate to the project directory where your contracts are located:

```bash
cd page
truffle compile
```

---

### 5. Deploy the Smart Contract

Deploy your compiled contract to the local blockchain:

```bash
truffle migrate
```

---

## 🌟 Benefits

- 🏠 Gives stray animals a chance at a new home
- 🩺 Allows adopters to systematically monitor pet health
- 🔗 Promotes transparency using Blockchain technology
- 📉 Helps reduce the number of stray animals in the long term

---

## 🛠️ Tools & Technologies

- **Ganache** – Personal Ethereum blockchain
- **Truffle Suite** – Development framework for smart contracts
- **MetaMask** – Ethereum wallet and Web3 gateway

---

## ✅ Conclusion

This project merges technology with compassion, building a bridge between stray animals and caring adopters. By leveraging **blockchain**, we simplify adoption, ensure trust, and foster systemic impact on animal welfare.

> _"A better future for stray animals starts with smart, transparent solutions — and people who care."_ 🐾
