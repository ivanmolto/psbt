---
title: Quick Glossary
nextjs:
  metadata:
    title: Quick Glossary
    description: Quick glossary
---

This quick glossary contains many of the terms used in relation to Bitcoin. These terms are used throughout the website, so bookmark this for a quick reference.

---

## address

A Bitcoin address looks like _1DSrfJdB2AnWaFNgSbv3MZC2m74996JafV_. It consists of a string of letters and numbers. It's an encoded base58check version of a public key 160-bit hash. Just as you ask others to send an email to your email address, you would ask others to send you bitcoin to one of your Bitcoin addresses.

## bip

Bitcoin Improvement Proposals. A set of proposals that members of the bitcoin community have submitted to improve bitcoin. For example, BIP-174 is a proposal to define PSBT (Partially Signed Bitcoin Transaction).

## bitcoin

The name of the currency unit (the coin), the network, and the software.

## block

A group of transactions, marked with a timestamp, and a commitment to the previous block. The block header is hashed to produce a proof of work, thereby validating the transactions. Valid blocks are added to the main blockchain by network consensus.

## blockchain

A list of validated blocks, each linking to its predecessor all the way to the genesis block.

## brc-20

BRC-20 is a token standard for the Bitcoin blockchain, inspired by Ethereum’s ERC-20 standard. It allows users to create and transfer fungible tokens on the Bitcoin network using the Ordinals protocol.

## byzantine generals problem

A reliable computer system must be able to cope with the failure of one or more of its components. A failed component may exhibit a type of behavior that is often overlooked, sending conflicting information to different parts of the system. The problem of coping with this type of failure is expressed abstractly as the Byzantine Generals Problem.

## coinbase

A special field used as the sole input for coinbase transactions. The coinbase allows claiming the block reward and provides up to 100 bytes for arbitrary data.
Not to be confused with Coinbase transaction.

## coinbase transaction

The first transaction in a block. Always created by a miner, it includes a single coinbase.
Not to be confused with Coinbase.

## cold storage

Refers to keeping a reserve of bitcoin offline. Cold storage is achieved when Bitcoin private keys are created and stored in a secure offline environment. Cold storage is important for anyone with bitcoin holdings. Online computers are vulnerable to hackers and should not be used to store a significant amount of bitcoin.

## confirmations

Once a transaction is included in a block, it has one confirmation. As soon as _another_ block is mined on the same blockchain, the transaction has two confirmations, and so on. Six or more confirmations is considered sufficient proof that a transaction cannot be reversed.

## consensus

When several nodes, usually most nodes on the network, all have the same blocks in their locally-validated best blockchain.
Not to be confused with consensus rules.

## consensus rules

The block validation rules that full nodes follow to stay in consensus with other nodes.
Not to be confused with consensus.

## difficulty

A network-wide setting that controls how much computation is required to produce a proof of work.

## difficulty retargeting

A network-wide recalculation of the difficulty that occurs once every 2,016 blocks and considers the hashing power of the previous 2,016 blocks.

## difficulty target

A difficulty at which all the computation in the network will find blocks approximately every 10 minutes.

## double-spending

Double spending is the result of successfully spending some money more than once. Bitcoin protects against double-spending by verifying each transaction added to the blockchain to ensure that the inputs for the transaction had not previously already been spent.

## ecdsa

Elliptic Curve Digital Signature Algorithm or ECDSA is a cryptographic algorithm used by Bitcoin to ensure that funds can only be spent by their rightful owners.

## extra nonce

As difficulty increased, miners often cycled through all 4 billion values of the nonce without finding a block. Because the coinbase script can store between 2 and 100 bytes of data, miners started using that space as extra nonce space, allowing them to explore a much larger range of block header values to find valid blocks.

## fees

The sender of a transaction often includes a fee to the network for processing the requested transaction. Most transactions require a minimum fee of 0.5 mBTC.

## fork

Fork, also known as accidental fork, occurs when two or more blocks have the same block height, forking the blockchain. Typically occurs when two or more miners find blocks at nearly the same time. Can also happen as part of an attack.

## genesis block

The first block in the blockchain, used to initialize the cryptocurrency.

## hard fork

Hard fork, also known as Hard-Forking Change, is a permanent divergence in the blockchain, commonly occurs when non-upgraded nodes can’t validate blocks created by upgraded nodes that follow newer consensus rules.
Not to be confused with fork, soft fork, software fork or Git fork.

## hardware wallet

A hardware wallet is a special type of bitcoin wallet which stores the user's private keys in a secure hardware device.

## hash

A digital commitment to some binary input.

## hashlock

A hashlock is a type of encumbrance that restricts the spending of an output until a specified piece of data is publicly revealed. Hashlocks have the useful property that once any hashlock is opened publicly, any other hashlock secured using the same key can also be opened. This makes it possible to create multiple outputs that are all encumbered by the same hashlock and which all become spendable at the same time.

## hd protocol

The Hierarchical Deterministic (HD) key creation and transfer protocol (BIP32), which allows creating child keys from parent keys in a hierarchy.

## hd wallet

Wallets using the Hierarchical Deterministic (HD Protocol) key creation and transfer protocol (BIP32).

## hd wallet seed

HD wallet seed or root seed is a potentially-short value used as a seed to generate the master private key and master chain code for an HD wallet.

## htlc

A Hashed TimeLock Contract or HTLC is a class of payments that use hashlocks and timelocks to require that the receiver of a payment either acknowledge receiving the payment prior to a deadline by generating cryptographic proof of payment or forfeit the ability to claim the payment, returning it to the payer.

## input script

The data generated by a spender which is almost always used as variables to satisfy an output script.

## kyc

Know Your Customer (KYC) is the process of a business, identifying and verifying the identity of its clients. The term is also used to refer to the bank regulation which governs these activities.

## leveldb

LevelDB is an open source on-disk key-value store. LevelDB is a light-weight, single-purpose library for persistence with bindings to many platforms.

## lightning network

Lightning Network is a proposed implementation of Hashed Timelock Contracts (HTLCs) with bi-directional payment channels which allows payments to be securely routed across multiple peer-to-peer payment channels. This allows the formation of a network where any peer on the network can pay any other peer even if they don't directly have a channel open between each other.

## lock time

Lock time is the part of a transaction which indicates the earliest time or earliest block when that transaction may be added to the blockchain.

## mempool

The bitcoin mempool (memory pool) is a collection of all transaction data in a block that have been verified by Bitcoin nodes, but are not yet confirmed.

## merkle root

The root node of a merkle tree, a descendant of all the hashed pairs in the tree. Block headers must include a valid merkle root descended from all transactions in that block.

## merkle tree

A tree constructed by hashing paired data (the leaves), then pairing and hashing the results until a single hash remains, the merkle root. In Bitcoin, the leaves are almost always transactions from a single block.

## miner

A network node that finds valid proof of work for new blocks, by repeated hashing.

## multisignature

Multisignature (multisig) refers to requiring more than one key to authorize a bitcoin transaction.

## network

A peer-to-peer network that propagates transactions and blocks to every Bitcoin node on the network.

## nonce

The "nonce" in a bitcoin block is a 32-bit (4-byte) field whose value is set so that the hash of the block will contain a run of leading zeros. The rest of the fields may not be changed, as they have a defined meaning.

## offchain transactions

An offchain transaction is the movement of value outside of the blockchain. While an onchain transaction&#x2014;usually referred to as simply a transaction&#x2014;modifies the blockchain and depends on the blockchain to determine its validity an offchain transaction relies on other methods to record and validate the transaction.

## opcode

Operation codes from the Bitcoin Script language which push data or perform functions within a pubkey script or signature script.

## op_return

An opcode used in one of the outputs in an OP_RETURN transaction. Not to be confused with OP_RETURN transaction.

## op_return transaction

A transaction type that adds arbitrary data to a provably unspendable pubkey script that full nodes don’t have to store in their UTXO database. Not to be confused with OP_RETURN opcode.

## ordinals

Ordinals are a method of creating unique digital assets on the Bitcoin blockchain. They work by assigning a unique serial number, or ordinal to each satoshi, and attaching additional data to it, such as an image, text, or video, inscribed onto it. This concept is part of the Ordinal Theory, introduced by developer Casey Rodarmor, which enables satoshis to be treated as NFTs.

## orphan block

Blocks whose parent block has not been processed by the local node, so they can’t be fully validated yet. Not to be confused with stale block.

## orphan transactions

Transactions that can't go into the pool due to one or more missing input transactions.

## output

Output, transaction output, or TxOut is an output in a transaction which contains two fields: a value field for transferring zero or more satoshis and a pubkey script for indicating what conditions must be fulfilled for those satoshis to be further spent.

## output script

A script included in outputs which sets the conditions that must be fulfilled for those satoshis to be spent. Data for fulfilling the conditions can be provided in a signature script.

## p2pkh

Transactions that pay a Bitcoin address contain P2PKH or Pay To PubKey Hash scripts. An output locked by a P2PKH script can be unlocked (spent) by presenting a public key and a digital signature created by the corresponding private key.

## p2sh

P2SH or Pay-to-Script-Hash is a powerful new type of transaction that greatly simplifies the use of complex transaction scripts. With P2SH the complex script that details the conditions for spending the output (redeem script) is not presented in the locking script. Instead, only a hash of it is in the locking script.

## p2sh address

P2SH addresses are Base58Check encodings of the 20-byte hash of a script, P2SH addresses use the version prefix "5", which results in Base58Check-encoded addresses that start with a "3". P2SH addresses hide all of the complexity, so that the person making a payment does not see the script.

## p2wpkh

The signature of a P2WPKH (Pay-to-Witness-Public-Key-Hash) contains the same information as a P2PKH spending, but is located in the witness structure instead of the input script. The output script is also modified.

## p2wsh

The difference between P2SH and P2WSH (Pay-to-Witness-Script-Hash) is about the cryptographic proof location change from the input script to the witness structure and the output script that is also modified.

## paper wallet

In the most specific sense, a paper wallet is a document containing all of the data necessary to generate any number of Bitcoin private keys, forming a wallet of keys. However, people often use the term to mean any way of storing bitcoin offline as a physical document. This second definition also includes paper keys and redeemable codes.

## payment channels

A micropayment channel or payment channel is class of techniques designed to allow users to make multiple Bitcoin transactions without committing all of the transactions to the bitcoin blockchain. In a typical payment channel, only two transactions are added to the blockchain but an unlimited or nearly unlimited number of payments can be made between the participants.

## pooled mining

Pooled mining is a mining approach where multiple generating clients contribute to the generation of a block, and then split the block reward according the contributed processing power.

## proof-of-stake

Proof-of-Stake (PoS) is a method by which a cryptocurrency blockchain network aims to achieve distributed consensus. Proof-of-Stake asks users to prove ownership of a certain amount of currency (their "stake" in the currency).

## proof-of-work

A piece of data that requires significant computation to find. In bitcoin, miners must find a numeric solution to the SHA256 algorithm that meets a network-wide target, the difficulty target.

## psbt

A Partially Signed Bitcoin Transactions (PSBT) is a type of transaction format that allows multiple parties to collaboratively sign a Bitcoin transaction.

## reinscription

Reinscription is a new Ordinal technology which allows Ordinal owners to re-inscribe existing satoshis with additional data.

## reward

An amount included in each new block as a reward by the network to the miner who found the Proof-of-Work solution. It is currently 12.5 BTC per block.

## ripemd-160

RIPEMD-160 is a 160-bit cryptographic hash function. RIPEMD-160 is a strengthened version of RIPEMD with a 160-bit hash result, and is expected to be secure for the next ten years or more.

## sat rarity

Similar to rarity on NFTs in Ethereum and other EVM compatible blockchains, sat rarity associates special meaning to specific satoshis.

## satoshi

A satoshi is the smallest denomination of bitcoin that can be recorded on the blockchain. It is the equivalent of 0.00000001 bitcoin and is named after the creator of Bitcoin, Satoshi Nakamoto.

## satoshi nakamoto

Satoshi Nakamoto is the name used by the person or people who designed Bitcoin and created its original reference implementation, Bitcoin Core. The real identity remains unknown.

## script

Bitcoin uses a scripting system for transactions. Forth-like, Script is simple, stack-based, and processed from left to right. It is purposefully not Turing-complete, with no loops.

## secret key (aka private key)

The secret number that unlocks bitcoin sent to the corresponding address. A secret key looks like the following: _5J76sF8L5jTtzE96r66Sf8cka9y44wdpJjMwCxR3tzLh3ibVPxh_

## segregated witness

Segregated Witness is a proposed upgrade to the Bitcoin protocol which technological innovation separates signature data from bitcoin transactions. Segregated Witness is a proposed soft fork; a change that technically makes Bitcoin’s protocol rules more restrictive.

## sha

The Secure Hash Algorithm or SHA is a family of cryptographic hash functions published by the National Institute of Standards and Technology (NIST).

## simplied payment verification

A method for verifying particular transactions were included in a block without downloading the entire block. The method is used by some lightweight Bitcoin clients.

## soft fork

soft fork or Soft-Forking Change is a temporary fork in the blockchain which commonly occurs when miners using non-upgraded nodes don't follow a new consensus rule their nodes don’t know about.
Not to be confused with fork, hard fork, software fork or Git fork.

## stale block

Block that was successfully mined but that isn’t included on the current best blockchain, likely because some other block at the same height had its chain extended first. Not to be confused with orphan block.

## taproot

The Taproot upgrade is an enhancement to the Bitcoin protocol, striving to improve the privacy and efficiency of the network.

## timelock

A timelock is a type of encumbrance that restricts the spending of some bitcoin until a specified future time or block height. Timelocks feature prominently in many Bitcoin contracts, including payment channels and hashed timelock contracts.

## transaction

In simple terms, a transfer of bitcoin from one address to another. More precisely, a transaction is a signed data structure expressing a transfer of value. Transactions are transmitted over the Bitcoin network, collected by miners, and included into blocks, made permanent on the blockchain.

## transaction pool

An unordered collection of transactions that are not in blocks in the main chain, but for which we have input transactions.

## turing completeness

A program language is called "Turing complete" if it can run any program that a Turing machine can run, given enough time and memory.

## unspent transaction output

UTXO is an unspent transaction output that can be spent as an input in a new transaction.

## wallet

Software that holds all your Bitcoin addresses and secret keys. Use it to send, receive, and store your bitcoin.

## wallet import format

WIF or Wallet Import Format is a data interchange format designed to allow exporting and importing a single private key with a flag indicating whether or not it uses a compressed public key.
