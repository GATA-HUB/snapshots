# 🔥 GATA Burn Vault

Welcome to the **Burn Vault** — a transparent, on-chain-powered reward system designed to incentivize NFT burns, reduce supply, and reward active participants.

This folder acts as the **public ledger** for all Burn Vault activity.

---

## 🧱 What is the Burn Vault?

The Burn Vault is a growing pool of rewards funded by:

* Unclaimed raffle rewards
* Initial seed: **5,000 PHOTON**

Each month, the vault distributes rewards to participants who burn eligible NFTs.

---

## 🎯 Objectives

* 🔥 Reduce NFT supply through burns
* 🎟️ Reward active participants
* 📈 Increase value for remaining holders
* 🎮 Create engagement across the ecosystem

---

## 🎟️ How to Participate

1. Burn eligible NFTs
2. Earn raffle tickets based on burn weight
3. Enter monthly and yearly raffles

---

## 🧬 Eligible Collections

* YG [(Yield Gorillas) ](https://stargaze.zone/m/cosmos1a4uanyytpvx0cq043yljlf0phhy2h95t6wsraprhnryyaqzdjw2sl3z5rn)
* YP [(Yield Paws)](https://stargaze.zone/m/cosmos1te4992utv2kyfguf6lad2szsunj29gqqsvjzqdsfh9g62yeuvclsvvtl8t)
* YC (Yield Crocs)
* YW  [(Yield Walkers)](https://stargaze.zone/m/cosmos1mzr08swy3m6fx8xgmmfd5cf3wvjgsef8pnv9saacly03s3w4n5jq7qq9st)
* POs [(PengOnes)](https://stargaze.zone/m/cosmos1dvx9q8ck866qmpqpqdy3guqt96579x9ukn6qxx6mtf4x5gxfzfqschuxlw)

---

## 🎫 Ticket System

Each burned NFT grants raffle tickets.

Example (initial weights):

* Yield Crocs (Earth) → 1 ticket (min)
* Pengone 1/1 → 50 tickets (max)

📊 A detailed weighting chart will be published separately.

---

## 🎲 Raffle Structure

### Monthly Raffle

* 75% of vault distributed
* 3 winners
* Only burn participants eligible

### 🏆 Yearly Raffle

* 25% accumulated throughout the year
* 25 winners
* Drawn on **GATA Birthday**

---

## 📁 Folder Structure

```
/burn-vault
  /vault       → Monthly vault balances  
  /tickets     → Ticket snapshots (updated every 48h)  
  /raffles     → Raffle results and proofs  
```

---

## 🔍 Transparency & Verification

This system is designed to be fully verifiable:

* All data is published in this folder
* Ticket allocations are based on on-chain burn activity
* Each update includes a clear timestamp or block reference

---

## 🎰 Randomness & Fairness

Raffle winners are selected using **on-chain randomness**.

We use a publicly announced reference such as:

* A Cosmos block hash
* Or a transaction hash

This ensures:

* No manipulation
* Fully reproducible results

---

## ⛓️ How to Verify

1. Find your address in the latest `/tickets` file
2. Check your ticket count
3. Review the raffle file for:

   * Total tickets
   * Random seed used
   * Winner selection method

Anyone can independently verify the results.

---

## 🔄 Update Frequency

* 🗓️ Tickets → Every 48 hours
* 📊 Vault → Monthly
* 🎲 Raffles → Monthly + Yearly

---

## ⚖️ Sustainability & Exit Strategy

The Burn Vault is designed as a **temporary incentive mechanism**, not a permanent reward loop.

To ensure fairness and avoid over-concentration:

### 📉 Gradual Reduction

* Ticket weights and/or rewards may be adjusted over time
* This reduces long-term dominance by early or large burners

### 🎯 Milestone-Based Evolution

The system may evolve or conclude when key conditions are met:

* Significant supply reduction achieved
* Engagement stabilizes across collections
* Vault reaches predefined thresholds

### 🔄 Transition Options

Upon completion or DAO decision, the Burn Vault may:

* Be replaced with new incentive systems
* Redirect funds to broader community rewards
* Integrate into DAO-controlled yield mechanisms

All changes will be:

* Clearly communicated
* Applied at epoch boundaries
* Governed transparently

---

## ⚠️ Rules

* Only burns within the defined time window are counted
* Each update includes a cutoff (timestamp or block height)
* Rules remain fixed within each monthly cycle

---

## 🚀 Philosophy

The Burn Vault is built on three principles:

* **Transparency over UI**
* **On-chain verification over trust**
* **Participation over passive holding**

---

## 🔥 Final Note

Burning is not just an action — it’s a strategy.

Reduce supply. Increase your odds. Strengthen the ecosystem.

Welcome to the Burn Vault.
