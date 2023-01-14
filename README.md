# Migration Applications (mApps)

One-click solutions to migrate digital assets from Ethereum L1 into L2 protocols.

**Goal: remove friction for users and increase usage on layer 2.**

_Note: starting with optimism because that's my prefered L2_

## Process

- [ ] Read the [protocol-specs](https://github.com/ethereum-optimism/optimism/tree/develop/specs) to understand how transactions on L1 can be executed on L2. Is it even possible to do this in one transaction on L1 and have the assets deposited directly into L2 protocols?
  - [X] [Introduction](https://github.com/ethereum-optimism/optimism/blob/develop/specs/introduction.md)
  - [X] [Overview](https://github.com/ethereum-optimism/optimism/blob/develop/specs/overview.md)
  - [X] [Deposits](https://github.com/ethereum-optimism/optimism/blob/develop/specs/deposits.md)
  - [X] [Withdrawals](https://github.com/ethereum-optimism/optimism/blob/develop/specs/withdrawals.md)
  - [ ] [Execution Engine](https://github.com/ethereum-optimism/optimism/blob/develop/specs/exec-engine.md)
  - [ ] [L2 Output Root Proposals](https://github.com/ethereum-optimism/optimism/blob/develop/specs/proposals.md)
  - [ ] [Rollup Node](https://github.com/ethereum-optimism/optimism/blob/develop/specs/rollup-node.md)
  - [ ] [Rollup Node P2P](https://github.com/ethereum-optimism/optimism/blob/develop/specs/rollup-node-p2p.md)
  - [ ] [Guaranteed Gas Market](https://github.com/ethereum-optimism/optimism/blob/develop/specs/guaranteed-gas-market.md)
  - [ ] [Messengers](https://github.com/ethereum-optimism/optimism/blob/develop/specs/messengers.md)
  - [ ] [Bridges](https://github.com/ethereum-optimism/optimism/blob/develop/specs/bridges.md)
  - [ ] [Predeploys](https://github.com/ethereum-optimism/optimism/blob/develop/specs/predeploys.md)
- [ ] Proof on concept: deploy a generic deposit contract on L2 with some trivial logic. Execute transaction on L1.
- [ ] Choose a few protocols to start with (probably the big DeFi applications on Optimism)
- [ ] Implement the transaction logic for each protocol, test on Goerli, and Mainnet
- [ ] Build out UI

## Resources

[Interlayer communication](https://github.com/ethereum-optimism/optimism-tutorial/tree/main/cross-dom-comm)
