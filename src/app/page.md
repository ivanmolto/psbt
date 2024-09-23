---
title: A tech explanation for the nerds out there
---

A PSBT is a standardized format introduced by BIP-174 that allows multiple parties to collaboratively sign a Bitcoin transaction without requiring full signatures at each step. {% .lead %}

{% quick-links %}

{% quick-link title="BIP-174" icon="installation" href="/docs/bip-174" description="Getting started with the BIP that defined the format for PSBT." /%}

{% quick-link title="Contributions" icon="plugins" href="/docs/contributions" description="Learn how the internals work and contribute." /%}

{% quick-link title="Memes" icon="presets" href="/docs/memes" description="Partially Signed Bitcoin Transactions as a Meme-a-Palooza" /%}

{% quick-link title="Quick Glossary" icon="theming" href="/docs/quick-glossary" description="A glossary containing many of the terms used in relation to Bitcoin." /%}

{% /quick-links %}

It’s particularly useful for multi-signature wallets, hardware wallets, and complex setups involving multiple inputs, outputs, and signers.

---

Key components:

- Inputs & Outputs: Like a regular Bitcoin transaction, a PSBT includes the inputs (UTXOs being spent) and outputs (where the Bitcoin is going). However, unlike a fully signed transaction, some or all inputs are only partially signed.

- Metadata: A PSBT carries additional information such as:redeem scripts, witness scripts, public keys, partial signature...

- State of Signatures: Initially, the PSBT is unsigned (or partially signed). Each signer adds their signature(s) to the PSBT, marking their approval of the inputs they can authorize.
  The transaction remains incomplete until all required signatures are added.

- Collaborative Workflow: multiple signers can pass around the PSBT to incrementally sign it.

- Finalization: once all necessary signatures are collected, the PSBT is "finalized" by adding complete witness data and converting it into a fully signed transaction broadcasted to the bitcoin network.

---

In short, PSBT is a modular, extendable format that allows multiple parties to safely sign a Bitcoin transaction in a secure, flexible, and interoperable manner.
