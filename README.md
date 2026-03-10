# DAO Governance & Timelock

This repository provides a complete on-chain governance framework. It allows token holders to propose, vote on, and execute protocol changes in a fully decentralized manner.

### Architecture
1. **Governance Token:** An ERC20 token with snapshotting capabilities for voting power.
2. **Governor Contract:** Handles the proposal lifecycle (Proposing, Voting, Quorum validation).
3. **Timelock:** A security layer that delays execution of passed proposals, giving users time to exit if they disagree with a change.



### Governance Process
* **Proposal Threshold:** Minimum tokens required to create a proposal.
* **Voting Period:** Duration during which token holders can cast "For", "Against", or "Abstain" votes.
* **Execution:** Once passed and the timelock delay expires, the transaction is executed on-chain.

### License
MIT
