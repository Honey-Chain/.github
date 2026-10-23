<div align="center">

<table>
  <tr>
    <td width="120" align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/Honey-Chain/.github/main/profile/logo.png" width="100" alt="HoneyChain logo" />
    </td>
    <td valign="middle">
      <h1>HoneyChain</h1>
    </td>
  </tr>
</table>

**Blockchain-based honey traceability & smart beekeeping management**

Built for **Smart India Hackathon 2026** · Problem Statement `26021` · Ministry of MSME

[![Website](https://img.shields.io/badge/website-honeychain.in-D69E1F?style=flat-square)](https://www.honeychain.in/)
[![Live App](https://img.shields.io/badge/portal-Live%20Demo-blue?style=flat-square)](https://www.honeychain.in/login)
[![License](https://img.shields.io/badge/license-MIT-4A2E12?style=flat-square)](https://opensource.org/license/mit)
[![Network](https://img.shields.io/badge/network-Ethereum%20Sepolia-4B7B4E?style=flat-square)](https://sepolia.etherscan.io/address/0x65afF3B44441FfF68171a9a0AA28063BC83C208d)

</div>

---

## 🔑 Judge & Evaluation Demo Credentials

To facilitate rapid evaluation of HoneyChain's end-to-end supply chain, pre-seeded accounts are provided across all role portals.

> **Live Login Portal:** [https://www.honeychain.in/login](https://www.honeychain.in/login)  
> **Universal Demo Password:** `Password123!`

### Stakeholder Role Accounts

| Role | Email | Password | Representative | Organization & Scope | Dashboard Path |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **`admin`** | `admin@honeychain.org` | `Password123!` | System Administrator | **HoneyChain Authority**<br>System oversight, user management, cluster analytics | `/authority/dashboard` |
| **`beekeeper`** | `beekeeper@honeychain.org` | `Password123!` | Rajesh Kumar | **Sundarbans Apiary Cooperative**<br>Hive IoT telemetry, harvests & on-chain batch creation | `/farmer/dashboard` |
| **`lab`** | `lab@honeychain.org` | `Password123!` | Dr. Ananya Sen | **National Honey Quality Lab**<br>Moisture assays, purity testing & smart contract attestation | `/lab/dashboard` |
| **`processor`** | `processor@honeychain.org` | `Password123!` | Vikram Patel | **Bengal Organic Honey Processing**<br>Bulk receipt, processing, packaging & custody transfer | `/processor/dashboard` |
| **`distributor`** | `distributor@honeychain.org` | `Password123!` | Gurpreet Singh | **SafeHive Cold Chain Logistics**<br>Transit tracking, warehouse custody & retail dispatch | `/distributor/dashboard` |
| **`auditor`** | `auditor@honeychain.org` | `Password123!` | Priya Sharma | **FSSAI Quality & Compliance Bureau**<br>Regulatory inspection & emergency recall execution | `/authority/dashboard` |

---

### 🔍 Consumer QR & Traceability Verification (No Login Required)

Consumers scan bottle QR codes or query the verification portal to inspect raw IoT hive telemetry, AI diagnostics, lab purity certificates, and Sepolia blockchain transactions:

- **Public Verification Portal:** [https://www.honeychain.in/verify](https://www.honeychain.in/verify)

#### Test Batches Available for Immediate Verification

| Batch ID | Verification Status | Features Demonstrated | Direct Verification Link |
| :--- | :--- | :--- | :--- |
| `HC-VERIFIED-2026` |  **Certified & Verified** | Grade A purity, complete multi-custodian chain of custody, Sepolia on-chain hash anchor | [Verify Batch](https://www.honeychain.in/verify/HC-VERIFIED-2026) |
| `HC-PENDING-2026` | ⏳ **Awaiting Lab** | Harvested & registered batch currently undergoing laboratory verification | [Verify Batch](https://www.honeychain.in/verify/HC-PENDING-2026) |
| `HC-RECALLED-2026` | ⚠️ **Recalled / Flagged** | Tamper detection & regulatory recall preventing consumer distribution | [Verify Batch](https://www.honeychain.in/verify/HC-RECALLED-2026) |

---

## What is HoneyChain?

Every jar of honey should be able to prove where it came from. HoneyChain follows a batch from **hive to shelf** — sensor data, AI health monitoring, lab certification, and custody transfers — all recorded on-chain, so a single QR scan tells the truth.

Built to solve real problems facing India's rural beekeepers under KVIC's Honey Mission: counterfeit honey, weak market linkages, and zero traceability from apiary to consumer.

## How it works

```text
Hive (IoT sensors) ──► AI Health Model ──► Harvest ──► Batch Registered On-Chain
                             │
                             ▼
Consumer Verifies ◄── QR Generated ◄── Custody Transferred ◄── Lab Certified
```

## Repositories

| Repo | Description |
|---|---|
| [`honeychain-backend`](https://github.com/Honey-Chain/HoneyChain_Backend/tree/main/backend) | Node.js/Express API — MongoDB, Ethereum Sepolia integration, ML microservice bridge |
| [`honey-chain-frontend`](https://github.com/Honey-Chain/HoneyChain_Backend/tree/main/frontend) | Next.js web app — beekeeper, lab, processor, and consumer-facing interfaces |
| [`honeychain-contracts`](https://github.com/Honey-Chain/HoneyChain_Backend/tree/main/blockchain) | Solidity smart contracts — batch registry, custody, quality certification |
| [`honeychain-ml`](https://github.com/Honey-Chain/HoneyChain_ML) | Python inference service — hive health & disease risk classification |
| [`honeychain-yield-ml`](https://github.com/Honey-Chain/HoneyChain_Yield_ML) | Python microservice — LightGBM harvest window and yield prediction |
| [`honeychain-iot-simulator`](https://github.com/Honey-Chain/HoneyChain_IoT_Simulator) | IoT hive telemetry simulator streaming MQTT/HTTP environmental readings |

## Tech stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

## Team

Built by a small team across backend, frontend, blockchain, ML, and hardware.

---

<div align="center">
<sub>🐝 From hive to shelf, every jar tells the truth.</sub>
</div>
