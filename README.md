# 🐧 kingpepe-daemon-linux

`kingpepe-daemon-linux` is the core daemon (background service) for the **KingPepe blockchain** built to run on Linux-based systems. It powers full node operation, blockchain synchronization, and wallet functionalities via RPC commands.

---

## 🧩 What It Does

- 🌐 Connects to the KingPepe peer-to-peer (P2P) network
- 📦 Stores the full blockchain locally
- 🔧 Offers remote procedure calls (RPC) for wallet and node operations
- 🧠 Enables block generation, transaction validation, and indexing

---

## 📂 Included Binaries

- `kingpeped` — The main daemon process (KingPepe Core)
- Often used alongside:
  - `kingpepe-cli` — Command-line interface to communicate with the daemon
  - `kingpepe-tx` — Utility for raw transaction manipulation

---
kingpepe-cli getblockcount
kingpepe-cli getblockchaininfo

