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

## Evaluation & Demo Credentials

> [!IMPORTANT]
> **Universal Demo Password:** `Password123!`  
> **Direct Login Portal:** [https://www.honeychain.in/login](https://www.honeychain.in/login)  
> *(Logging in with any account below automatically routes to that role's dedicated portal)*

| Stakeholder Role | Login Email | Key Workflow to Evaluate |
| :--- | :--- | :--- |
| **System Administrator** | `admin@honeychain.org` | Member organization approvals, system metrics & user administration |
| **Beekeeper** | `beekeeper@honeychain.org` | Live IoT hive telemetry, AI health alerts, harvests & on-chain batch creation |
| **Quality Laboratory** | `lab@honeychain.org` | Moisture assays, purity testing & Sepolia smart contract attestation |
| **Processing Plant** | `processor@honeychain.org` | Honey processing, bottling, batch packaging & custody transfer |
| **Cold-Chain Distributor** | `distributor@honeychain.org` | Cold-chain dispatch, transit temperature tracking & custody transfer |
| **Regulatory Auditor** | `auditor@honeychain.org` | Quality audits, compliance checks & emergency batch recall execution |

---

### Public Consumer Verification (No Authentication Required)

Test the public consumer verification experience without logging in:

> **Verification Portal:** [https://www.honeychain.in/verify](https://www.honeychain.in/verify)

| Sample Batch | Status | Verification Scenario | Direct Link |
| :--- | :--- | :--- | :--- |
| `HC-VERIFIED-2026` | Verified (Grade A) | Certified honey with full IoT history & Sepolia hash anchor | [Verify Batch](https://www.honeychain.in/verify/HC-VERIFIED-2026) |
| `HC-PENDING-2026` | Pending Lab | Harvested batch currently awaiting laboratory testing | [Verify Batch](https://www.honeychain.in/verify/HC-PENDING-2026) |
| `HC-RECALLED-2026` | Flagged / Recalled | Failed purity test demonstrating tamper-evident alert on scan | [Verify Batch](https://www.honeychain.in/verify/HC-RECALLED-2026) |

---

## What is HoneyChain?

Every jar of honey should be able to prove where it came from. HoneyChain follows a batch from **hive to shelf** — sensor data, AI health monitoring, lab certification, and custody transfers — all recorded on-chain, so a single QR scan tells the truth.

Built to solve real problems facing India's rural beekeepers under KVIC's Honey Mission: counterfeit honey, weak market linkages, and zero traceability from apiary to consumer.

## Architecture Pipeline

```text
Hive (IoT Sensors) ──> AI Health Model ──> Harvest ──> Batch Registered On-Chain
                                                          │
                                                          v
Consumer Verifies <── QR Generated <── Custody Transferred <── Lab Certified
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

## Tech Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

## Team

Built by a team across backend, frontend, blockchain, ML, and hardware engineering.

---

<div align="center">
<sub>From hive to shelf, every jar tells the truth.</sub>
</div>
