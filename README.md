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
| **05** | Flash Loan Mechanics | Lending pool price skewing | [PASS] |
| **06** | Signature Malleability | ECDSA s-value flipping | [PASS] |
| **07** | ERC-4626 Share Inflation | Donation vectors / first depositor attack | [PASS] |
| **08** | Read-Only Reentrancy | AMM pool virtual price distortions | [PASS] |
| **09** | Front-running / MEV | Mempool transaction priority hijacking | [PASS] |
| **10** | Uninitialized Proxies | Storage collisions & implementation wipes | [PASS] |
| **11** | Cross-Contract Reentrancy | Multi-contract state synchronization issues | [PASS] |
| **12** | ERC-777 Callbacks | Hook-based reentrancy loops | [PASS] |
| **13** | Vault Math Down-rounding | ERC-4626 integer division exploitation | [PASS] |
| **14** | Uniswap V3 TWAP Manipulation | Tick index shifts in low-liquidity zones | [PASS] |
| **15** | Handler-Based Fuzzing | Target invariant testing with boundary checks | [PASS] |
| **16** | Cross-Dex Arbitrage Bot | Multi-AMM flash loan extraction loops | [PASS] |
| **17** | ECDSA Signature Replay | Cross-contract reuse via missing chainId/address | [[PASS]] (https://github.com/void-node/My-first-smart-contract-audit-lab/commit/094ccc4842b1c8ea25c89f578883ea5cbe753d6c) |

### ⚡ Operational Notes
* I don't write textbook audits. Everything listed above is backed by local executable PoCs, deep tracing (`-vvvv`), and stress-tested invariants.
* Building a high-fidelity audit portfolio targeting top Immunefi / Sherlock leaderboards.
