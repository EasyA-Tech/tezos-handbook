# The Tezos Handbook [WiP]

Welcome. This is EasyA's legendary handbook. If you want to learn Tezos like a legend, then you're in the right place.

# Purpose

This handbook serves as a guide to the Tezos ecosystem, geared towards those just joining for the first time. It isn't just a beginners' handbook; it's a legendary handbook. Even if you've already immersed yourself in the ecosystem, you'll find tons of helpful tidbits around here!

# The EasyA App

Of course, the best place to start is always the [EasyA](https://www.easya.io) app! Download it here for the fastest and most fun way to learn about Tezos. Download it directly right [here](https://links.easya.io/links/gotoapp)!

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Core Concepts](#core-concepts)
- [Development Tools](#development-tools)
- [Smart Contracts](#smart-contracts)
- [Tezos Network](#tezos-network)
- [Ecosystem Projects](#ecosystem-projects)
- [Resources](#resources)
- [Handy Code Snippets](#handy-code-snippets)
- [Contributing](#contributing)

## Introduction

What is Tezos:

- [Tezos Website](https://tezos.com/) - The official website for Tezos, a self-amending blockchain network.
- [Tezos Source Code](https://gitlab.com/tezos/tezos) - The official Gitlab repository for Tezos.

## Getting Started

The no-fluff starter:

- [Official Tezos Developers Guide](https://developers.tezos.com/) - Learn how to write smart contracts, use various SDKs, and explore the blockchain.

## Core Concepts

Explanation of fundamental concepts in the Tezos ecosystem:

- [Tezos Agora Learn](https://www.tezosagora.org/learn) - Tezos governance.

## Development Tools

Key tools and environments for Tezos:

[To be added]

## Smart Contracts

How to write and deploy smart contracts on Tezos:

- [LIGO](https://ligolang.org) - The smart contract language for Tezos.

## Tezos Network

Going into the network level:

[To be added]

## Ecosystem Projects

Cool projects built on Tezos:

- [Better Call Dev](https://better-call.dev/) - A Tezos smart contract explorer.

## Resources

Extra stuff:

- [Tezos Agora Forum](https://forum.tezosagora.org/) - A place to discuss and learn Tezos.

## Handy Code Snippets

Get a taste of Tezos development with these code snippets:

### Connecting to Tezos using eztz

```javascript
const eztz = require('eztz.js');

eztz.node.setProvider('https://mainnet.tezos.org.ua');
console.log('Connected to Tezos');
```

### Simple smart contract in LIGO

```ligo
type storage = int

let main (action, store : unit * storage) : operation list * storage =
 ([], store + 1)
```

These examples showcase:
1. How to connect to the Tezos network using the eztz library.
2. A simple smart contract in LIGO that increments a storage value.

## Contributing

We welcome contributions to make this handbook even more legendary! Here's how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-addition`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-addition`)
6. Create a new Pull Request

Please ensure your contributions align with our code of conduct and contribution guidelines.

## Credit/Inspiration

This handbook was inspired by the famous awesome lists by sindresorhus and the Awesome Tezos list. We need awesome lists for Web3 ecosystems, with more of a hacker's guide to how they work. This is the answer to that need.
