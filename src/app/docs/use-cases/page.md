---
title: Use Cases
nextjs:
  metadata:
    title: Use Cases
    description: Use Cases
---

A Partially Signed Bitcoin Transaction is useful for a complex transaction, especially in multi-signature setups where different parties control different inputs.

---

## Multi-sig transactions

PSBT is ideal for scenarios where multiple people or devices need to sign a transaction, like 2-of-3 or 3-of-5 multi-signature wallets.

## Hardware wallets

Many hardware wallets don’t allow raw transactions to be constructed on the device for security reasons, so they work with PSBTs. The PSBT allows them to receive a pre-constructed transaction, sign it offline, and return the signed data.

## Buying and selling Bitcoin Ordinals

The process of using PSBTs to securely buy and sell Ordinals (digital assets on the Bitcoin network) is very straightforward with the following steps:

- Create a PSBT: The buyer generates a PSBT that includes the Bitcoin payment for the Ordinal.

- Share the PSBT: The buyer sends the PSBT, containing both the payment details and information about the Ordinal, to the seller.

- Sign the PSBT: The seller signs the PSBT using their private key, confirming ownership of the Ordinal.

- Broadcast the transaction: Once signed by both parties, the PSBT is broadcasted to the Bitcoin network, finalizing the transaction. The Ordinal is transferred to the buyer, and the payment goes to the seller.

This method ensures transaction security, preventing fraud, and ensuring mutual satisfaction, as neither party has full control over the process.

## Listing Bitcoin Ordinals on multiple marketplaces

PSBTs provide a decentralized way to list Ordinals for sale across multiple marketplaces.

A key example is [Open Ordex](https://openordex.org), which uses NOSTR, a decentralized protocol, to share PSBT listings with other marketplaces. This means that when you list an Ordinal for sale on Open Ordex, the listing automatically spreads to other PSBT-based marketplaces. Thanks to the combination of PSBTs and NOSTR, listings are securely and efficiently propagated across platforms.

## CoinJoin

PSBTs facilitate collaborative transactions where multiple participants mix their coins for privacy.

## Advanced smart contracts

The support of new features such as Taproot inputs in BIP-370 allows for more advanced smart contracts in Bitcoin.

## Auctions and joint-custody accounts

BIP-370 enabled better handling of transaction malleability, making it more suitable for collaborative Bitcoin spending scenarios, such as auctions or joint-custody accounts.
