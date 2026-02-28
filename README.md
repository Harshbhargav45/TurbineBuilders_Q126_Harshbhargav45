# 🚀 TurbinePB_Q126 — Harsh Bhargava

A **monorepo-style learning repository** containing multiple **Solana + Rust + Anchor projects**, managed using **Git submodules**.  
Building upon the foundations of Q425, this collection focuses on advanced protocols, DeFi mechanisms, and full-stack dApp architectures.

## 📦 Repository Structure

This repo aggregates multiple independent projects:

- 🏗️ **solana_starter** – Base Solana/Anchor project template
- 🏦 **anchor_vault** – Token vault for deposits and withdrawals
- 🔐 **anchor_escrow** – Secure token escrow program
- 🎲 **Dice** – On-chain random number-based gaming logic
- 📈 **quadratic_funding** – Implementation of quadratic funding on Solana
- 💰 **staking** – Token staking reward program
- 🔄 **amm** – Automated Market Maker implementation
- 🐉 **anchor_mplxcore** – NFT minting using Metaplex Core
- 🗳️ **dao_voting** – DAO-style proposal and voting system

---

## 🏆 Featured Full-Stack Application

### 🗳️ DAO Voting Platform (`dao_voting`)
A sophisticated governance system that allows communities to manage their treasury and make collective decisions transparently.
- **Frontend App**: Built with **Next.js**, featuring a clean dashboard for proposing and voting.
- **On-Chain Governance**: Supports token-weighted voting and automated winner selection.
- **Treasury Logic**: Integrated mechanisms for users to purchase governance tokens using SOL.
- **Transparent Lifecycle**: Immutable records for every proposal, from registration to resolution.

---

## 🔱 Advanced Protocols (Q1 2026 Specials)

### 📈 Quadratic Funding (`quadratic_funding`)
A democratic funding mechanism that amplifies small contributors to support public goods.
- **QF Algorithm**: Rust implementation of the mathematical formula for fair fund distribution.
- **Pool Management**: Real-time tracking of project registrations and donation pools.

### 🔄 AMM: Automated Market Maker (`amm`)
A decentralized exchange protocol based on the **Constant Product (x*y=k)** formula.
- **Liquidity Pools**: Instructions for adding/removing liquidity and maintaining pool balance.
- **Price Discovery**: Real-time on-chain swaps with Slippage and Fee management.

### 💰 Staking Protocol (`staking`)
A DeFi incentive system designed to reward long-term asset commitment.
- **Yield Accrual**: Automated reward calculation based on duration and stake weight.
- **User Flow**: Simplified instructions for staking, unstaking, and claiming rewards.

---

## ⚓ Anchor Foundational Projects

### 🔐 Token Escrow (`anchor_escrow`)
A zero-trust swap mechanism facilitating atomic peer-to-peer exchanges.
- **Atomic Execution**: Ensuring both sides of the trade occur simultaneously or not at all.
- **Secure Vaults**: Using PDAs to hold assets in transit during the "Make" and "Take" phases.

### 🏦 Asset Vault (`anchor_vault`)
A secure custody system for SPL tokens and SOL.
- **PDA Security**: Every vault is a Program Derived Address, ensuring only specific instructions can sign for transfers.
- **Rent Reclamation**: Efficient logic for closing accounts and recovering SOL.

### 🎲 Dice Gaming (`Dice`)
A fair gaming program utilizing Solana's high-speed transaction capabilities.
- **Randomness Logic**: Processing bets and payouts based on secure on-chain resolution.

---

## 🛠 Tech Stack
- **Languages**: Rust, TypeScript
- **Frameworks**: Anchor, Next.js, React
- **Solana Ecosystem**: SPL Token, Metaplex Core (MPLX Core)
- **Tooling**: [Surfpool](https://surfpool.run) (Runbooks, Surfnet, and Local Testing), Solana CLI

## 🧠 Learning Goals
- Mastering **Program Derived Addresses (PDAs)** for state management.
- Implementing **Cross-Program Invocations (CPI)** for complex DeFi flows.
- Building **Full-Stack dApps** with seamless wallet integration and real-time on-chain data.
- Exploring advanced math implementations in Rust for decentralized finance.

---
