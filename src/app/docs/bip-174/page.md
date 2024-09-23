---
title: BIP-174
nextjs:
  metadata:
    title: BIP-174
    description: BIP-174
---

---

[BIP-174](https://github.com/bitcoin/bips/blob/master/bip-0174.mediawiki) is a Bitcoin Improvement Proposal that defines the format for Partially Signed Bitcoin Transaction (PSBT) standard which was authored by Ava Chow, and presented the first version specification for PSBTs known as a PSBTv0.

PSBT allows wallets to collaborate on creating, signing, and finalizing Bitcoin transactions safely as there is no exposure of private keys. This is useful for complex transactions, especially in multi-signature scenarios.

This BIP also defines a set of operator roles which are capable of not only signing but also updating the inputs or outputs within the PSBT. The roles are creator, updater, signer, combiner, input finalizer and transaction extractor.

A later specification defined in BIP-370 described a second version known as a PSBTv2 adding additional features.
