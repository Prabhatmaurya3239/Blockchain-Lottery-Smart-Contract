# 🎰 Ethereum Lottery Smart Contract

This is a simple **Lottery DApp Smart Contract** written in Solidity. It allows users to participate by sending a fixed amount of Ether and randomly selects one winner among them. Only the manager can start the lottery and pick a winner.

## 🚀 Features

- Participants can enter by sending **0.002 ETH**
- Only the **manager** can view the balance and pick a winner
- Uses **keccak256** and block properties for pseudo-random number generation
- Sends the entire contract balance to the randomly selected winner
- Resets participants after each round

---

## 📦 Contract Details

```solidity
pragma solidity >=0.5.0 <0.9.0;
