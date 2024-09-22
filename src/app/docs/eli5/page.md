---
title: ELI5
nextjs:
  metadata:
    title: ELI5
    description: ELI5
---

---

A **PSBT**, or **Partially Signed Bitcoin Transaction**, is like a "to-do list" for a group of people who are sending some Bitcoin together.

![](https://ivanmolto.mypinata.cloud/ipfs/QmckAuCUiUtgZ1B1eUR1xkrRDESqZL6xu45b1hGrGNwc5G)

Imagine you're with a few friends, and you all want to chip in to buy a gift. But before paying everyone has to agree and sign their name on the bill. You create a list of who owes what and where the money is going (this is the PSBT).

Now, each friend can look at the list, say, "yep, this looks right", and sign it. But until everyone signs it, the money won't actually go to buy the gift. So the PSBT is kind of like an unfinished agreement that needs everyone's signature before it becomes a real transaction.

{% callout title="You should know!" %}
In Bitcoin, PSBT is used to help people (or computers) prepare a transaction that involves multiple signatures, but it stays unfinished until everyone involved has signed it.
{% /callout %}
