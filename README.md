# EtherPrime

⚡ **EtherPrime** is a Proof-of-Work smart contract blockchain built on the Ethereum execution layer.  
It brings back **PoW + EVM** for a simple, secure, and miner-friendly network.

---

# Network Overview

| Parameter | Value |
|-----------|------|
| Network Name | EtherPrime |
| Chain ID | 131071 |
| Consensus | Ethash (Proof-of-Work) |
| Block Time | ~13 seconds |
| Initial Block Reward | 7 EPX |
| Reward Reduction | 5% every 200,000 blocks |
| Development Reward | 1 EPX per block (until block 2,000,000) |

---

# Go-Prime

Official **Golang execution layer implementation** of EtherPrime.

This repository contains the source code for running an EtherPrime node.

---

# Requirements

Building EtherPrime requires:

- **Go 1.19 or later**
- **C compiler**

Install them using your system package manager.

Example (Ubuntu):

```
sudo apt install golang build-essential
```

---

# Build

Clone the repository:

```
git clone https://github.com/EtherPrime/go-prime.git
```

## Build on Windows

```
go build -o build/bin/geth.exe ./cmd/geth
```

## Build on Ubuntu / Linux

```
go build -o build/bin/geth ./cmd/geth
```

After building, the binary will be located in:

```
build/bin/
```

---

# Hardware Requirements

## Minimum

- CPU with **2+ cores**
- **4GB RAM**
- **1TB storage**
- **8 MBit/sec internet connection**

## Recommended

- Fast CPU with **4+ cores**
- **16GB RAM**
- **High-performance SSD**
- **25+ MBit/sec internet connection**
