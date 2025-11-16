# L1-L2-Findings
This repo contains some of my findings related to L1/L2 protocols


## Bug Reports

| Project | Title | Severity | Language | Platform | Report |
| --- | --- | --- | --- | --- | --- |
| Telecoin Network | Lack of Per-Transaction Gas Limit Allows Single Transaction to Block Entire Batch in Telcoin Network | High | Rust/solidity | Cantina |  [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/Telecoin-Finding-High-1.md)   |
| Telecoin Network | Incorrect Assignment of Delegator and Validator Fields in Delegation Struct Results in Delegator Losing Reward Claim Rights | High | Rust/solidity | Cantina |  [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/Telecoin-Finding-High-2.md)   |
| Telecoin Network | Lack of Mandatory Base Fee Enforcement Enables Fee-Free Attacks | Medium | Rust/solidity | Cantina |  [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/Telecoin-Finding-Medium-1.md)   |
| Telecoin Network | Low-Level Call Allows EIP-7702 Wallets to Block Slashing/Burn, Enabling Denial-of-Service Against Protocol Enforcement | Medium | Rust/solidity | Cantina |  [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/Telecoin-Finding-Medium-2.md)   |
| Telecoin Network | Double-Decrement of Committee Length After Ejection Causes Incorrect Committee Size Validation | Low| Rust/solidity | Cantina |   [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/Telecoin-Finding-Low-1.md)  |
| Telecoin Network | Unsafe Non-Blocking Shutdown Lead To Database Corruption and Extended Validator Downtime | Info | Rust/solidity | Cantina |   [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/Telecoin-Finding-Info-1.md)  |
| Telecoin Network | Incorrect Committee Size Validation During Slashing of PendingExit Validators Causes Unintended Reverts | Info | Rust/solidity | Cantina |  [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/Telecoin-Finding-info-2.md)   |
| Space and Time | Critical Replay and State Confusion in Staking Contract Allows Double Withdrawal of Unstaked Funds | High | Rust/solidity | Cantina |   [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/SXT-Finding-High-1.md)  |
| Space and Time | validateMessage Fails with Unordered Signatures, Leading to Permanent Loss of Access to Unstaked Funds | Medium | Rust/solidity | Cantina |   [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/SXT-Finding-Medium-1.md)  |
| Space and Time | Hardcoded 10-Day EVM Timelock Desynchronizes with SXT Chain's 7-Day Unbonding, Impairing Unstake Cancellation Utility | Medium | Rust/solidity | Cantina |   [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/SXT-Finding-Medium-2.md)  |
| Space and Time | Users Trapped in UnstakeClaimed State with No Recovery Path After SXT Chain Reorganization | Medium | Rust/solidity | Cantina |   [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/SXT-Finding-Medium-3.md])  |
| Space and Time | Protocol Performs Unfunded Work and Pays Gas for Queries Submitted with Minimal Deposits | Medium | Rust/solidity | Cantina |   [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/SXT-Finding-Medium-4.md)  |
| Space and Time | Malicious customLogicContractAddress Allows Diversion of Protocol Fees and Gas Reimbursements| Medium | Rust/solidity | Cantina |   [LINK](https://github.com/CHupinex/L1-L2-Findings/blob/main/SXT-Finding-Medium-5.md)  |
