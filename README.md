# Bitcoin Research

## About this project
This project provides a short list of Bitcoin research papers. For each paper, a short discussion outlines the main contributions. This list should help finding good papers for a specific topic, and is intended to grow over time.
For an extensive list of papers please have a look at [this list](https://docs.google.com/spreadsheets/d/1VaWhbAj7hWNdiE73P-W-wrl5a0WNgzjofmZXe0Rh5sg/edit#gid=0).

Contributions and criticisms regarding this project are appreciated. Additions, corrections, and other changes may be contributed via [Pull Request](https://github.com/C-Otto/bitcoin-research/pulls) or creating a new [Issue](https://github.com/C-Otto-research/bitcoin/issues).
Furthermore it is also possible to send direct feedback via [E-Mail](mailto:bitcoin@c-otto.de).

## Topics
- [Proof of Work and Proof of Stake](#proof-of-work-and-proof-of-stake)
 - Proof of Activity: Extending Bitcoin's Proof of Work via Proof of Stake

## Authors
### Dr. Carsten Otto
[Carsten Otto](mailto:bitcoin@c-otto.de) received a PhD in computer science and is employed as an Agile Software Engineer.
Some of his main interests are the technical details of Bitcoin.

## Proof of Work and Proof of Stake
### [Proof of Activity: Extending Bitcoin's Proof of Work via Proof of Stake](https://eprint.iacr.org/2014/452.pdf) (Iddo Bentov, Charles Lee, Alex Mizrahi, Meni Rosenfeld) 2014

- Suggests Proof of Activity (PoA) to secure network with the combined efforts of stakeholders and miners
- Focus on long term sustainability, PoW faces problems with insufficient block rewards, discusses Tragedy of the Commons in a PoW system where miners are subsidized mostly by fees
- PoA offers cheaper security compared to PoW
- Additional benefits: lower energy consumption, healthy network, more full nodes
- PoA combines PoW blocks with blocks provided by online nodes randomly selected based on their stake.
- "follow the satoshi": Randomly pick satoshi, determine current address holding this satoshi by following the transactions
- "limited-withdrawal keys": Keys that can be used to prove ownership, but are only useful to withdraw a fraction of the funds
- Paper discusses issues of offline nodes, securing private keys, Multi-Signature addresses, stake pools, ...
- Paper includes proofs regarding security and analyses of attack costs
