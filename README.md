# 🔗 Blockchain-Based Supply Chain Tracking System

A decentralized web application that ensures **transparency, authenticity, and traceability** in product delivery across the supply chain — from **Seller → Distributor → Customer** — using **Blockchain** and **QR-based verification**.

---

## 🚀 Features

- **Seller Registration & Product Upload**
  - Seller adds an item with details (name, description, price, etc.).
  - A **unique hash** is generated and stored on the blockchain.
  - A **QR code** is created for each item, representing its digital identity.

- **QR-Based Tracking**
  - At every stage (Seller, Distributor, Customer), the QR is scanned.
  - Each scan records **timestamp**, **location**, and **role** (who scanned) on the blockchain.
  - The system verifies if the item’s hash matches the original — ensuring **no tampering**.

- **Audit Trail (Blockchain Log)**
  - All transactions are publicly verifiable.
  - Shows the complete history of the product from seller to customer.

- **Tamper Detection**
  - If anyone tries to replace or alter data, the hash mismatch will immediately show as **“Tampered”**.
  - Tamper-evident QR labels can be used physically for additional protection.

---
