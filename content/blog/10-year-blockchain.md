---
title: "10 Year Blockchain"
date: 2017-08-11T13:15:24-07:00
---

# A 10 year blockchain tech roadmap
The ICO boom has released a massive new set of resources for blockchain research and development. For the 1st time, the sector has a entry level resources for developing a radical new set of tools for the global(solar?)  economy. 

Our goal for the next 10-15 years are clear. Blockchain based systems should be the most useful and powerful liquidity rails for all kinds of assets. We have an immense amount of work to do fulfill the nascent potential of the blockchain space.

Here is a non-comprehensive list all the things we need to permanently alter how capital allocated and managed in the global economy.


## Cryptographic Engineering
- Safe, mature libraries for implementing complex protocols. NACL and libsodium aren’t going to cut it. Bitcoin-Core’s [libsecp256k1](https://github.com/bitcoin-core/secp256k1) and Isis & Henry’s [curve25519-dalek](https://github.com/isislovecruft/curve25519-dalek) are the way forward
- Zero knowledge proof libraries need to be substantially matured. Libsnark and the forthcoming STARK work need mature, battle tested domain specific languages and compilers for securely implementing protocols as well as additional research.  All of the anonymous credentials spaces will yield considerable fruits from being commercialized.
- We need a verifiable data structures library and standard in every possible programming language.
- We need signature and other cryptographic systems suitable for low resource devices yet secure enough for blockchain applications

## Blockchain Protocols
- We need to learn if we can build secure proof of stake and/or proof of useful work systems.  Proof of work demands very little in terms of competence 
- We need fast and safe consensus systems that have been battle tested by the real world. 
- Blockchain to blockchain protocols like Cosmos and Polkadot need to be deployed into the real world.
- We need robust, safe and fast smart contract programming languages and executions. We need to move formal analysis tools much closer to front line developers than we have at any point in the past which requires a number of tooling frontiers to be conquered.
- We need formal systems for analyzing blockchain protocols the way we now formally analyze TLS , Noise and Wireguard.
- Layer 2 protocols need to be deployed and matured like lightning


## Governance
- We need robust technical and social systems to govern blockchain networks. Authority should be managed in auditable and verifiable methods via smart contracts.
- Validators need to become more organizationally mature. To achieve scale, we need to be able to start believing that networks have validators capable of operating high availability, high security infrastructures. 
- There needs to be systems for managing and indemnifying validators against regulatory and other risks .
- A set of social institutions need to be built to facilitate shared networks between enterprises and to govern interactions between public networks and large enterprises.
- We need to learn if multiple developer teams can effectively coordinate and contribute to blockchains.
- Governance through network fork is unsustainable but there actual alternatives

## Market infrastructure
- Asset issues must mature and be able to manage entire asset lifecycle from issuance to retirement.
- Exchange infrastructure need to able to provide liquidity for everything from cryptocurrencies to digital assets to blockchain based securities.
- We need to determine if decentralized mechanisms can be significant liquidity providers or if the ideal solution is audible 

## Trusted Computing
- Tooling for SGX and it’s successors needs tremendous work. [Baidu](https://github.com/baidu/rust-sgx-sdk)'s work on top of SGX is a good first 
- HSM’s need to either modernize or be replaced
- We need multiple vendors of modern TEEs
- TEEs need to become available in edge devices to ensure a secure boundary between the physical and blockchain world.


## Other Resources
- [Ethereum Open Problems](https://github.com/ethereum/wiki/wiki/Problems)
-[Vitalik's Hard Problems in Crypto](https://www.youtube.com/watch?v=p5qwbOkCZSc)


