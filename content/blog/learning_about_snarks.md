---
title: "Learning About ZK SNARKs"
date: 2017-09-07T13:38:05-07:00
draft: false
---


ZK SNARKs are one of the most amazing products of modern cutting edge cryptography. They let a prover secretly run a program of arbitrary complexity and generate a compact proof that any can verify that correctly ran the program. The program can have secret inputs and the prover reveals nothing to the user.

Zk SNARKs have been deployed in the ZCash cryptocurrency and many other protocols are examining using them. SNARKs represent the culimination of decades of research into the field anonymous credentials. Blockchain transactions are a type of credential and the potential applications of SNARK transactions in a blockchain context seem limitless.

SNARKs are a synthesis of multiple areas of cryptography and theoretical computer science that were unified into a cohesive whole. This requires conducting a survey over a large field of research.

The resources below are a great starting point.

## Surveys


1. [ZK-SNARKs in a Nut Shell](https://blog.ethereum.org/2016/12/05/zksnarks-in-a-nutshell/)


Ethereum have been very interested getting the ability to evalute various SNARK protocols into the Ethereum system to enhance the privacy properties of smart contracts. This survery of SNARKs is very comprehensive and good jumping off point for someone familar with cryptography.


2. Eran Tromer's introduction to SNARKs is a also a decent jumping off point.

{{< youtube ViIK2Ly-Xjo >}}


## Qudratic Arithmetic Programs
1. [Quadratic Arithmetic Programs: from Zero to Hero](https://medium.com/@VitalikButerin/quadratic-arithmetic-programs-from-zero-to-hero-f6d558cea649)

SNARKs are a synthesis of multiple lines of research the combined reseachers observed that progress in compiling aribrary programs into arithmetic functions could be combined with progress in certain fields of partially homomorphic cryptography. Vitalik does a deep dive into how simple programs get turned into arhtmetic functions. This is one of the most magical parts of the SNARK system.

2. [Succinct Non-Interactive Arguments from Quadratic Arithmetic Programs](https://courses.cs.ut.ee/MTAT.07.022/2013_fall/uploads/Main/alisa-report)

Alisa Pankova did an incredible literature review of the entire field of Quadratic arithemetic programs.

## Pairing Cryptography

1. [http://www.craigcostello.com.au/pairings/PairingsForBeginners.pdf](Pairings for Beginners)

Highly reccomend Parings for Beginners for learning about the pairing cryptosystems that allow QAPs to generate such compact proofs

## Core SNARK papers

1. [SNARKs for C: Verifying Program Executions Succinctly and in Zero Knowledge](https://eprint.iacr.org/2013/507.pdf)

Check out Appendix A. It's p cool on how simple verification is.

2. [Succinct Non-Interactive Zero Knowledge for a von Neumann Architecture](https://eprint.iacr.org/2013/879.pdf)

3. [The Hunting Of the SNARK](https://eprint.iacr.org/2014/580.pdf)


{{< youtube 4fzz6of5KI4 >}}

## Recent research

1. [On The Size of Pairing-based Non-Interactive Arguments](https://eprint.iacr.org/2016/260)


{{< youtube OseAdq0CoOY >}}

2016 work from Jens Goth that shrinks the size of proofs to their theoretical limits, increases speed of verification and potentially increases the number of parties involved in generating the CRS dramatically. Will be used in the next ZCash protocol upgrade.


2. [Snarky Signatures: \\ Minimal Signatures of Knowledge from Simulation-Extractable SNARKs](https://eprint.iacr.org/2017/540)

2017 work from Goth that trade larger proofs for built in non-malleability.


3. [A multi-party protocol for constructing the public parameters of the Pinocchio zk-SNARK](https://eprint.iacr.org/2017/540)

The Techniques Zcash used in their CRS generation ceremony.