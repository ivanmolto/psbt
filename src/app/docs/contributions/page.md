---
title: Contributions
nextjs:
  metadata:
    title: Contributions
    description: Contributions
---

Some contributions and updates related to PSBT.

---

## 2024

### Add a PSBT per-output field for BIP 353 DNSSEC Proofs

For a full description, see PR [#1657](https://github.com/bitcoin/bips/pull/1657).

## 2023

### Bitcoin Core adds a new descriptorprocesspsbt

It can be used to update a PSBT with information that will help it later be signed or finalized.

For a full description, see PR [#25796](https://github.com/bitcoin/bitcoin/pull/25796).

## 2022

### Pay-to-contract tweak fields for PSBT

For a full description, see PR [#1293](https://github.com/bitcoin/bips/pull/1293).

### Implement BIP 370 PSBTv2

For a full description, see PR [#549](https://github.com/bitcoin-core/HWI/pull/549).

### PSBT version, proprietary, and xpub fields

For a full description, see PR [#17034](https://github.com/bitcoin/bitcoin/pull/17034).

## 2021

### BlueWallet v6.1.0 released

[BlueWallet’s v6.1.0 release](https://github.com/BlueWallet/BlueWallet/releases/tag/v6.1.0) adds functionality for using PSBTs with HD watch-only wallets.

### Add BIP-370: PSBT Version 2

For a full description, see PR [#1059](https://github.com/bitcoin/bips/pull/1059).

## 2020

### PSBT Toolkit v0.1.2 released

New [PSBT Toolkit](https://github.com/benthecarman/PSBT-Toolkit) software providing GUI for working with PSBTs

### Lily Wallet initial release

Initial release of [Lily Wallet](https://lily-wallet.com) supporting PSBTs.

### Bitcoin Core adds GUI support for signing & broadcasting PSBTs

For a full description, see PR [#18027](https://github.com/bitcoin/bitcoin/pull/18027).

### C-Lightning adds initial support for BIP174

For a full description, see PR [#3738](https://github.com/ElementsProject/lightning/pull/3738).

### Bitcoin Core allows saving and loading PSBTs from files

For a full description, see PR [#17509](https://github.com/bitcoin/bitcoin/pull/17509).

### PSBT channel funding

This PR introduces channel funding through PSBTs.

For a full description, see PR [#4079](https://github.com/lightningnetwork/lnd/pull/4079).

### Set default bip32derivs to true for PSBT methods

Changed the default in RPCs that create or process PSBTs to include any known BIP32 HD wallet derivation path.

For a full description, see PR [#17264](https://github.com/bitcoin/bitcoin/pull/17264).

### Bitcoin Core allows GUI to place a PSBT in the clipboard

For a full description, see PR [#17492](https://github.com/bitcoin/bitcoin/pull/17492).

## 2019

### Additional utility RPCs for PSBT

This PR adds 3 new utility RPCs for interacting with PSBTs.

For a full description, see PR [#13932](https://github.com/bitcoin/bitcoin/pull/13932).

## 2018

### BIP-174 PSBT Serializations and RPCs

For a full description, see PR [#13557](https://github.com/bitcoin/bitcoin/pull/13557).

### PSBT included in Bitcoin Core 0.17

Partially Signed Bitcoin Transactions (PSBTs) supported in Bitcoin Core 0.17 to facilitate better interoperability between multisig wallets, hot/cold wallets, and coinjoins.

For more details, visit the [GitHub repo](https://github.com/bitcoin/bips/blob/master/bip-0174.mediawiki)
