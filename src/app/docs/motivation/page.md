---
title: Motivation
nextjs:
  metadata:
    title: Motivation
    description: Motivation
---

Before BIP-174, creating unsigned or partially signed transactions to be passed around to multiple signers was previously implementation dependent, making it hard for people using different wallet software from being able to easily do so.

---

One of the goals of BIP-174 was to create a standard and extensible format that could be used between clients to allow people to pass around the same transaction to sign and combine their signatures. The format was also designed to be easily extended for future use which was harder to do with existing transaction formats.

Signing transactions also requires users to have access to the UTXOs being spent. The PSBT transaction format allows offline signers such as air-gapped wallets and hardware wallets to be able to sign transactions without needing direct access to the UTXO set and without risk of being defrauded.
