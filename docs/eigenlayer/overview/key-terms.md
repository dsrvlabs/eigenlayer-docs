# Key Terms

- **Actively Validated Services (AVS):** Any system that requires its own distributed validation semantics for verification, such as sidechains, data availability layers, new virtual machines, keeper networks, oracle networks, bridges, threshold cryptography schemes, and trusted execution environments.
- **AVS Developer**: development team that builds an AVS service.
- **Cryptoeconomic security:** security model that uses economic incentives and cryptography to ensure the proper functioning and security of a network.
- **Delegation in EigenLayer:** feature that allows restakers holding ETH or LSTs to delegate their assets to other entities who will operate off-chain software containers of service modules built on EigenLayer, rather than operating the software themselves.
- **EigenPod:** contract that is deployed on a per-user basis that facilitates native restaking.
- **Free-market governance:** EigenLayer provides an open market mechanism that allows stakers to choose which services to opt into, based on their own risk and reward analysis.
- **Liquid Staking:** a service that enables users to deposit their ETH into a staking pool and receive a liquid staking token. This token represents a claim on their ETH and its staking yield. Liquid staking tokens can be traded in the DeFi ecosystem and redeemed for their underlying ETH value after a waiting period.
- **LST Restaking:** a method where LST holders restake their Liquid Staking Tokens (LSTs) by transferring them into the EigenLayer smart contracts.
- **Native Restaking:** a method where Ethereum stakers restake their staked ETH natively by pointing their withdrawal credentials to the EigenLayer contracts.
- **On-chain slashing contract:** a smart contract deployed by service modules on EigenLayer that enforces slashing, specifying and penalizing any misbehavior.
- **Operator:** an entity who helps run AVS software built on top of EigenLayer. Operators register in EigenLayer and allow Stakers to delegate to them, then opt in to provide various services (AVSs) built on top of EigenLayer. Operators may also be Stakers; these are not mutually exclusive.
- **Pooled security via restaking:** when multiple parties combine their resources to provide greater security for a system. In EigenLayer, Ethereum stakers can “restake” their ETH or Liquid Staking Tokens (LST) by opting into new services built on EigenLayer.
- **Quorum**: grouping of Strategies to be used by an AVS for shared security measures.
- **Quorum Threshold**: the minimum amount of Operator responses and their stake % that must be received by the Aggregator entity.
- **Restaker**: a person who restakes Native or LST ETH to the EigenLayer protocol.
- **Restaking Points:** a measure of your total EigenLayer restaking contribution. Based on amount of ETH staked over time, in units of ETH per second. For a precise definition of how Restaking Points are calculated, please refer to the [next](../restaking-guides/0-restaking-user-guide/restaked-points.md) section.
- **Stake**: the amount of ETH delegated to the current set of Operators.
- **Strategies**: assets that are restaked into the platform.
- **Withdrawals**
  - **Full Withdrawals:** 32ETH Stake + Eth Staking Rewards (until now).
  - **Partial Withdrawals:** ETH consensus layer rewards (until now).
