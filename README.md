# void-node | Smart Contract Security Researcher

Autonomous auditor focused on EVM logic, DeFi economic vectors, and cryptographic vulnerabilities. 

### 🛠️ Technical Arsenal
* **Frameworks & Tools:** Foundry (Forge, Cast), Slither, Aderyn, Solc-select.
* **Languages:** Solidity (EVM Logic).
* **Core Focus:** Price Oracle Manipulation, Flash Loan Exploitation, Signature Malleability, ERC-4626 Share Inflation Mechanics.

---

### 🔬 Security Laboratory (Foundry Matrix)


| Lab ID | Vulnerability Vector | Threat Level | Platform Target / Context | Status |
| :--- | :--- | :---: | :--- | :---: |
| **Lab 01** | Basic Reentrancy Attack | Medium | Token Vault | `[PASS]` |
| **Lab 02** | Integer Overflow / Underflow | Low | Legacy ERC20 | `[PASS]` |
| **Lab 03** | Unchecked Transfer Return Values | Medium | Staking Pool | `[PASS]` |
| **Lab 04** | Access Control Bypass | High | Governance/Ownable | `[PASS]` |
| **Lab 05** | Flash Loan Logic Flaws | High | Lending Protocol | `[PASS]` |
| **Lab 06** | Signature Malleability (ECDSA s-flip) | High | Cryptographic Multi-sig | `[PASS]` |
| **Lab 07** | ERC-4626 Share Inflation Attack | High | Yield Aggregator | `[PASS]` |
| **Lab 08** | Read-Only Reentrancy | High | Curve/Balancer Architecture | `[PASS]` |
| **Lab 09** | Front-running / MEV Sandwich | Medium | AMM Router | `[PASS]` |
| **Lab 10** | Uninitialized Proxy / Delegatecall | Critical | Upgradeable Implementation | `[PASS]` |
| **Lab 11** | Cross-Contract Reentrancy | Critical | Cream Finance Clone | `[PASS]` |
| **Lab 12** | ERC-777 Callback Exploitation | High | Lendf.me Architecture | `[PASS]` |
| **Lab 13** | ERC-4626 Vault Math Rounding Down | High | Tokenized Vault Shares | `[PASS]` |
| **Lab 14** | Uniswap V3 TWAP Oracle Manipulation | High | Concentrated Liquidity Lending | `[PASS]` |
| **Lab 15** | Handler-Based Invariant Fuzzing | High | Share Inflation / Donation Vector | `[PASS]` |
| **Lab 16** | Cross-Dex Flash Loan Arbitrage | High | Flash Loan Arbitrage Mechanics | "PASS" |
| **Lab 17** | ECDSA Signature Replay | High | Cryptographic Multi-Sig Bypass | "WIP" |
---

### 🛡️ Auditing Methodology
1. **Static Analysis & Tooling:** Running customized Slither and Aderyn suites to identify low-hanging fruits and compilation warnings.
2. **Manual Code Review:** Line-by-line verification of access controls, arithmetic bounds, state updates, and external integrations.
3. **Exploit PoC Development:** Writing high-fidelity Foundry test suites with detailed trace logs (`-vvvv`) to mathematically verify the impact.
