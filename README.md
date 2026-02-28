# 🚀 TurbinePB_Q126

A **monorepo-style learning repository** containing multiple **Solana + Rust + Anchor projects**, managed using **Git submodules**.  
Built as part of the **Turbine Builder Program (PB)** to practice on-chain development from fundamentals.

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

## ⚓ Anchor Projects & Deep Dives

### 🏦 anchor_vault
Implemented a secure token vault system where users can deposit and withdraw tokens. This project covers:
- Secure asset custody using **Program Derived Addresses (PDAs)**.
- Instruction logic for `deposit` and `withdraw` operations.
- Professional Rent management and account closure logic.

### 🔐 anchor_escrow
A secure token swap mechanism that facilitates peer-to-peer exchanges without trust. Highlights include:
- **Atomic Swaps**: "Make" instruction to initialize escrow and "Take" for execution.
- **Vault Protection**: Integrated SPL token vault for secure intermediation.
- **Refund Logic**: Automatic mechanisms to reclaim funds if a swap is aborted.

### 🗳️ dao_voting
A sophisticated, decentralized governance system featuring:
- **Treasury Management**: Admin-controlled SOL/token balances and configuration.
- **Proposal Lifecycle**: End-to-end flow to Create, Vote, and Resolve on-chain proposals.
- **Token-Weighted Voting**: Ensuring community influence is proportional to governance stake.

### 💰 staking
A DeFi reward system allowing users to earn yield by locking their assets:
- **Incentive Logic**: Automated reward accrual based on staking duration.
- **Stake/Unstake**: User-friendly flow for asset commitment and redemption.

### 🎲 Dice
A fair gaming program utilizing Solana's speed and security:
- **On-chain Resolution**: Processing bets and payouts based on random-based logic.
- **House Management**: Integrated treasury for handling payouts and platform fees.

### 🔄 amm
An Automated Market Maker (AMM) implementation based on the **Constant Product (x*y=k)** formula:
- **Pool Management**: Instructions for adding and removing liquidity.
- **Decentralized Swaps**: Real-time on-chain price discovery and token swaps.

### 📈 quadratic_funding
A democratic funding mechanism that amplifies small contributors:
- **QF Algorithm**: Rust implementation of the mathematical formula for fair fund distribution.
- **Community Projects**: Tracking project registrations and donation pools.

## 🧠 Purpose
- Learn Solana account model & PDAs  
- Practice Anchor framework & Rust  
- Build real on-chain programs step by step  
- Understand NFTs, escrow, vaults, and marketplaces  

## 🛠 Tech Stack
- **Solana** (Devnet)  
- **Anchor** (Rust)  
- **SPL Token** & **Metaplex Core**  
- **Surfpool** (Runbooks, Surfnet, and Local Testing)
- **Web3.js** & **Next.js**

## 📌 Notes
- Each folder is a **Git submodule**  
- Projects are **independent** and focused on learning  
- Deployed and tested mainly on **Devnet**
