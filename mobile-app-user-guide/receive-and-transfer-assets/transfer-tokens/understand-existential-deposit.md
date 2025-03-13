---
description: >-
  Understand what an existential deposit is and its importance in token
  transfers.
---

# Understand existential deposit

The existential deposit (ED) refers to the **minimum amount** of native tokens required to keep an address or account active on Polkadot and most Substrate-based networks.

If an account's balance falls below this value, the account is reaped (or "deactivated"), and any remaining funds are permanently lost.

{% hint style="info" %}
The address can be reactivated anytime by depositing an amount greater than the ED, but the lost funds **can't be recovered**.
{% endhint %}

The ED exists so that accounts with very small balances or completely empty do not "bloat" the state of the blockchain. This limit allows the network to maintain high performance and reduce fees.

Here's the information about the existential deposit for native tokens on popular networks:

<table><thead><tr><th width="293">Network</th><th width="224">Native token</th><th>Existential deposit (ED)</th></tr></thead><tbody><tr><td>Polkadot</td><td>DOT</td><td>1 DOT</td></tr><tr><td>Polkadot Asset Hub</td><td>DOT</td><td>0.01 DOT</td></tr><tr><td>Kusama</td><td>KSM</td><td>0.000333333 KSM</td></tr><tr><td>Hydration</td><td>HDX</td><td> 1 HDX</td></tr><tr><td>Vara Network</td><td>VARA</td><td>1 VARA</td></tr><tr><td>Acala</td><td>ACA</td><td>0.1 ACA</td></tr><tr><td>Bifrost Polkadot</td><td>BNC</td><td>0.01 BNC</td></tr><tr><td>Bittensor</td><td>TAO</td><td>0.0000005 TAO</td></tr></tbody></table>

