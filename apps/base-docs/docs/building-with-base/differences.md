---
title: Differences between Ethereum and Base
slug: /differences
description: Documentation covering the differences between Ethereum and Base. This page includes details on differences between opcodes, blocks, network specifications, and transaction costs.
keywords:
  [
    Ethereum vs Base,
    Base differences,
    difference between Base and Ethereum,
    Bedrock,
    OP Stack,
    Base opcodes,
    Base blocks,
    opcodes on Base,
    blocks on Base,
    Base network specifications,
    network specifications,
    Base transaction costs,
    transaction costs,
  ]
---

# Differences between Ethereum and Base

Base is built on the [Bedrock](https://stack.optimism.io/docs/releases/bedrock/explainer/) release of the [OP Stack](https://stack.optimism.io/), which is designed from the ground up to be as close to Ethereum as possible. Because of this, there are very little differences when it comes to building on Base and Ethereum.

However, there are still some minor discrepancies between the behavior of Base and Ethereum that you should be aware of when building apps on top of Base.

These minor differences include:

- [Opcodes](https://stack.optimism.io/docs/releases/bedrock/differences/#opcode-differences)
- [Blocks](https://stack.optimism.io/docs/releases/bedrock/differences/#blocks)
- [Network specifications](https://stack.optimism.io/docs/releases/bedrock/differences/#network-specifications)
- [Transaction costs](https://stack.optimism.io/docs/releases/bedrock/differences/#transaction-costs)

:::info

Aside from the above, Base Mainnet does not yet support the new [`PUSH0`](https://eips.ethereum.org/EIPS/eip-3855) opcode introduced in Shanghai, which is the default target for the Solidity compiler if you use version `0.8.20` or later.

We recommend using `0.8.19` or lower until this is upgraded.

The update has been deployed to Base Goerli and Base Sepolia.

:::
