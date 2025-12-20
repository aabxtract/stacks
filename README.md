# Stacks: Bitcoin's Smart Contract Layer

Stacks extends Bitcoin's functionality by adding smart contracts and decentralized applications while maintaining trustless integration with the Bitcoin blockchain. This allows developers to build on Bitcoin without modifying its base layer.

## Key Documentation
- **Stacks Whitepaper**: [HTML](https://stacks-network.github.io/stacks/stacks.html) | [PDF](https://stacks-network.github.io/stacks/stacks.pdf)
- **sBTC Whitepaper**: [HTML](https://stacks-network.github.io/stacks/sbtc.html) | [PDF](https://stacks-network.github.io/stacks/sbtc.pdf)
- **Overview Slides**: [View on Google Drive](https://drive.google.com/file/d/19IX1PHshiXfdg7HXVJSQ8bPME_uizH6-/view)

## Evolution of Stacks

**2021 Launch** introduced Bitcoin transaction settlement, the Clarity programming language for secure smart contracts, and atomic swaps with BTC.

**Nakamoto Upgrade** ([SIP-021](https://github.com/stacksgov/sips/blob/56b73eada5ef1b72376f4a230949297b3edcc562/sips/sip-021/sip-021-trustless-two-way-peg-for-bitcoin.md)) adds three major enhancements:
- Trustless two-way Bitcoin peg for moving BTC in and out of the layer
- Bitcoin finality for transaction security
- Fast transactions between Bitcoin blocks

This upgrade transforms Bitcoin into a fully programmable asset, potentially activating hundreds of billions in dormant Bitcoin capital.

## What Makes Stacks Unique

**S** – **Secured** by Bitcoin's complete hash power and finality  
**T** – **Trustless** Bitcoin peg with write capabilities  
**A** – **Atomic** BTC swaps and Bitcoin address ownership  
**C** – **Clarity** language for provably safe contracts  
**K** – **Knowledge** of complete Bitcoin state  
**S** – **Scalable** fast transactions settling on Bitcoin

## Why Build on Bitcoin?

Bitcoin is the most secure and durable blockchain, designed for stability and minimal change. Stacks adds functionality without altering Bitcoin's base layer. Thousands of Stacks transactions settle as single Bitcoin transactions, while microblocks enable rapid confirmations. The Nakamoto release proposes fast transactions between Bitcoin blocks ([SIP-21](https://github.com/stacksgov/sips/blob/56b73eada5ef1b72376f4a230949297b3edcc562/sips/sip-021/sip-021-trustless-two-way-peg-for-bitcoin.md)), with additional scaling through [subnets](https://github.com/hirosystems/stacks-subnets) and [appchains](https://gist.github.com/jcnelson/c982e52075337ba75e00b79942164e31).

## Making Bitcoin Productive

**sBTC Peg**: A trust-minimized Bitcoin peg operated by economically incentivized actors. [Learn more about sBTC](https://stacks.co/sbtc).

**Atomic Swaps**: Trustless BTC deployment into DeFi and NFT marketplaces:
- [Magic BTC](https://magic.fun) - Atomic swaps
- [Catamaran Swaps](https://www.hiro.so/blog/bitcoin-defi-is-here-a-deep-dive-into-trust-less-swaps) - Trustless trading
- [Lightning Swaps](https://lnswap.org) - Lightning Network integration

Explore applications: [Stacks Ecosystem](https://www.stacks.co/explore/discover-apps)

## STX Token Utility

The STX token powers the Stacks ecosystem:
- Mining incentives and block subsidies
- sBTC peg-out signing rewards
- Gas fees for smart contract execution
- Stacking rewards (lock STX to earn Bitcoin)

STX was distributed through the first SEC-qualified token offering in U.S. history. The project decentralized before its January 2021 mainnet launch, with [30+ independent companies](https://twitter.com/zrixes/status/1433248424271355905?s=20) now active in the ecosystem.

Learn about earning Bitcoin: [Stacking.club](https://stacking.club)

## Clarity: Safe Smart Contracts

Clarity prioritizes safety through its unique design:
- **Decidable**: Code behavior is predictable and verifiable
- **Interpreted**: Not compiled, reducing attack vectors
- **Public source**: All code published on-chain ([example](https://explorer.stacks.co/txid/SP000000000000000000002Q6VF78.pox?chain=mainnet))

Resources:
- [Clarity Book](https://book.clarity-lang.org/)
- [Clarity Website](https://clarity-lang.org)
- [Security Blog](https://stacks.org/bringing-clarity-to-8-dangerous-smart-contract-vulnerabilities/)

## Proof-of-Transfer (PoX) Consensus

[PoX consensus](https://blockstack.org/pox.pdf) bridges Bitcoin and Stacks without burning electricity. Miners bid using BTC for block leadership, with elections occurring on Bitcoin and blocks written on Stacks. This recycles proof-of-work energy to provide Nakamoto-style consensus.

[Detailed PoX Explanation](https://medium.com/@sonkaos999/the-bullish-case-for-stacks-8ef75849861f)

## Developer Resources

**Getting Started:**
- [Latest Documentation](https://docs.stacks.co/)
- [Stacks Blockchain (Rust)](https://github.com/stacks-network/stacks-blockchain)
- [Stacks.js Library](https://github.com/hirosystems/stacks.js)
- [Stacks Explorer](https://github.com/hirosystems/explorer)
- [Community Documentation](https://github.com/stacks-network/docs)

**Additional Resources:**
- [Working Groups](https://github.com/stacks-network/stacks/discussions)
- [Video Interview](https://www.youtube.com/watch?v=dEQFPNWaOHY)
- [Improvement Proposals (SIPs)](https://github.com/stacksgov/sips/tree/main/sips)

## How to Contribute

- **Code**: Submit pull requests ([good first issues](https://github.com/stacks-network/stacks-blockchain/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22))
- **Testing**: Run the software and report issues
- **Community**: [Join evangelists](https://community.stacks.org/evangelists) worldwide
- **Meetings**: Weekly discussions on [Discord](https://stacks.chat)

## Community Channels

- [Forum](https://forum.stacks.org)
- [Discord](https://stacks.chat)
- [Telegram](https://t.me/StacksChat)
- [Twitter](https://twitter.com/stacks)
- [YouTube](https://www.youtube.com/channel/UC3J2iHnyt2JtOvtGVf_jpHQ)
- [Newsletter](https://stacks.org/updates)
