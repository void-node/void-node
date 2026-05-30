# void-node

Web3 Security Researcher & Smart Contract Auditor. Specialized in EVM execution logic, DeFi economic vectors, and breaking cryptographic implementations.

### 🛠 Core Stack & Target Vectors
* **Tools:** Foundry (Forge/Cast), Slither, Solc
* **Focus:** Oracle Manipulation (TWAP/Spot), Complex Reentrancy Loops, Signature Malleability, ERC-4626 Share Inflation

### 🔬 Active Security Laboratory (Foundry Matrix)


| ID | Vulnerability / Lab Context | Focus | Status |
| :--- | :--- | :--- | :--- |
| **01** | Basic Reentrancy | Balance mapping update logic | [PASS] |
| **02** | Arithmetic Underflow | Legacy compiler math bypass | [PASS] |
| **03** | Unchecked Calls | Missing return value validations | [PASS] |
| **04** | Access Control | Uninitialized state / modifier flaws | [PASS] |
| **05** | Flash Loan Mechanics | Lending pool price skewing | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/8ebc8b2d2b47e390ced179f5711aa774c1a70421) |
| **06** | Signature Malleability | ECDSA s-value flipping | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/1c4a34e9131a7000e7f17917b4cc8ec65332ceaa) |
| **07** | ERC-4626 Share Inflation | Donation vectors / first depositor attack | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/b417d0d2df9bf972a8f1e6e0bc927877c7c3556e) |
| **08** | Read-Only Reentrancy | AMM pool virtual price distortions | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/6442a917d1ad5439b007155e809c293fb37631cf) |
| **09** | Front-running / MEV | Mempool transaction priority hijacking | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/2dd32282673b8b2a66d75202491dd60e248a62ea) |
| **10** | Uninitialized Proxies | Storage collisions & implementation wipes | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/f97ea1be3a158c889613a6be06a0c3b94231c8e2) |
| **11** | Cross-Contract Reentrancy | Multi-contract state synchronization issues | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/478040e066f1a652861f836563994479ef45059d) |
| **12** | ERC-777 Callbacks | Hook-based reentrancy loops | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/e4e2224fc0a0c209405d5a9d3336c9a83038e0a9) |
| **13** | Vault Math Down-rounding | ERC-4626 integer division exploitation | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/6977447a41976a7f76c55c0650bb4e660ffc6220) |
| **14** | Uniswap V3 TWAP Manipulation | Tick index shifts in low-liquidity zones | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/e8c5c7b570e964599ffc5647e6f79f5640ba8d1c) |
| **15** | Handler-Based Fuzzing | Target invariant testing with boundary checks | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/e930d798e011258792e1565bb9359f938e2da02b) |
| **16** | Cross-Dex Arbitrage Bot | Multi-AMM flash loan extraction loops | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/1c8f57e6b551fc1fcc33be17d95caf0ed51edf90) |
| **17** | ECDSA Signature Replay | Cross-contract reuse via missing chainId/address | [PASS](https://github.com/void-node/My-first-smart-contract-audit-lab/commit/094ccc4842b1c8ea25c89f578883ea5cbe753d6c) |

### ⚡ Operational Notes
* I don't write textbook audits. Everything listed above is backed by local executable PoCs, deep tracing (`-vvvv`), and stress-tested invariants.
* Building a high-fidelity audit portfolio targeting top Immunefi / Sherlock leaderboards.
