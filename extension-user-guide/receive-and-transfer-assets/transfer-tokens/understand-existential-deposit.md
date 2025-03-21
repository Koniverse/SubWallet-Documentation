---
description: >-
  Understand what an existential deposit is and its importance in token
  transfers.
---

# Understand existential deposit

The existential deposit (ED) refers to the **minimum amount** of native tokens required to keep an address or account active on Polkadot and most Substrate-based networks.&#x20;

If an account's balance falls below this value, the account is reaped (or "deactivated"), and any remaining funds are permanently lost.&#x20;

{% hint style="info" %}
The address can be reactivated anytime by depositing an amount greater than the ED, but the lost funds **can't be recovered**.
{% endhint %}

The ED exists so that accounts with very small balances or completely empty do not "bloat" the state of the blockchain. This limit allows the network to maintain high performance and reduce fees.

Here's the information about the existential deposit for native tokens on popular networks:

| Network          | Native token | Existential deposit |
| ---------------- | ------------ | ------------------- |
| Polkadot         | DOT          | 1 DOT               |
| Kusama           | KSM          | 0.000333333 KSM     |
| Hydration        | HDX          | 1 HDX               |
| Vara             | VARA         | 1 VARA              |
| Acala            | ACA          | 0.1 ACA             |
| Bifrost Polkadot | BNC          | 0.01 BNC            |
| Bittensor        | TAO          | 0.0000005 TAO       |
