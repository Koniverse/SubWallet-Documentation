---
description: >-
  Learn how derivation paths structure wallet keys and accounts from a single
  seed.
---

# Understand derivation paths

## What is a derivative account?

Derivative accounts are accounts created by deriving the original account (parent account).

{% hint style="info" %}
Derivative accounts share the exact seed phrase as the original account but use different paths.

You can use a derivative account as the original account to make transactions.
{% endhint %}

## Default derivation paths

Currently, SubWallet uses:

* The [BIP-44 standard](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki) for Substrate (Polkadot), EVM (Ethereum), TON accounts.&#x20;
* The [BIP32-Ed25519 standard](https://input-output-hk.github.io/adrestia/static/Ed25519_BIP.pdf) for Cardano accounts.
* The [BIP32-Hierarchical Deterministic Wallets standard](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki) for Bitcoin accounts.

Each account has a default derivation path based on its type. Here's the default derivation path for each type of original account:

<table><thead><tr><th width="192.39996337890625">Account type</th><th>Address type</th><th>Default derivation path</th></tr></thead><tbody><tr><td><strong>Substrate (Polkadot)</strong></td><td></td><td><code>Empty</code></td></tr><tr><td><strong>EVM (Ethereum)</strong></td><td></td><td><code>m/44'/60'/0'/0/0</code></td></tr><tr><td><strong>TON</strong></td><td></td><td><code>m/44'/607'/0'</code></td></tr><tr><td><strong>Cardano</strong></td><td></td><td><code>m/1852'/1815'/0'</code></td></tr><tr><td><strong>Bitcoin</strong></td><td>Legacy (BIP-44)</td><td><code>m/44'/0'/0'/0/0</code></td></tr><tr><td></td><td>Native SegWit (BIP-84)</td><td><code>m/84'/0'/0'/0/0</code></td></tr><tr><td></td><td>Taproot (BIP-86)</td><td><code>m/86'/0'/0'/0/0</code></td></tr></tbody></table>

{% hint style="info" %}
If you're using a unified account, it will include all of the above paths.
{% endhint %}

{% hint style="warning" %}
Currently, SubWallet supports creating derived accounts from these account types:

* [x] Unified account
* [x] Solo account\*

_(\*): With EVM accounts, you can only create derived accounts from **parent accounts imported into SubWallet**_ [_**via seed phrase**_](../import-accounts/import-from-seed-phrase.md)_**.**_

Other account types (watch-only, Ledger, and QR-signer) are not supported.
{% endhint %}

## Supported derivative accounts

### For unified account

You can create multiple derivative accounts from an original account (parent account). Each account from these can create more derivative accounts.&#x20;

To differentiate them, in this document, these accounts will be categorized based on their derivative levels. For example, parent accounts will be known as "Level 0 accounts" or "F0 accounts".

<table><thead><tr><th width="294">Account needed to be derived</th><th width="214">Derivative account(s)</th><th>Shortened derivation path</th></tr></thead><tbody><tr><td>Parent account (F0)</td><td>Level 1 account (F1)</td><td><code>/1</code> or <code>//1</code></td></tr><tr><td>Level 1 account (F1)</td><td>Level 2 account (F2)*</td><td><code>/1/0</code> or <code>//1//0</code></td></tr></tbody></table>

_(\*): Level 2 accounts will be supported for accounts in SubWallet only. Further derivations from this level will not be supported on any wallets_

### For solo account

{% hint style="info" %}
You can derive your solo accounts to Level 2 accounts only.&#x20;

Level 3 accounts and onwards will not be supported on any wallets.
{% endhint %}

{% hint style="warning" %}
Level 2 accounts will be supported in SubWallet only.
{% endhint %}

#### Substrate account

<table><thead><tr><th width="294">Account needed to be derived</th><th width="214">Derivative account(s)</th><th>Derivation path</th></tr></thead><tbody><tr><td>Parent account (F0)</td><td>Level 1 account (F1)</td><td><code>//1</code></td></tr><tr><td>Level 1 account (F1)</td><td>Level 2 account (F2)</td><td><code>//1//0</code></td></tr></tbody></table>

#### EVM account

<table><thead><tr><th width="294">Account needed to be derived</th><th width="214">Derivative account(s)</th><th>Derivation path</th></tr></thead><tbody><tr><td>Parent account (F0)</td><td>Level 1 account (F1)</td><td><code>m/44'/60'/0'/0/1</code></td></tr><tr><td>Level 1 account (F1)</td><td>Level 2 account (F2)</td><td><code>m/44'/60'/0'/0/1/0</code></td></tr></tbody></table>

#### TON account

<table><thead><tr><th width="294">Account needed to be derived</th><th width="214">Derivative account(s)</th><th>Derivation path</th></tr></thead><tbody><tr><td>Parent account (F0)</td><td>Level 1 account (F1)</td><td><code>m/44'/607'/1'</code></td></tr><tr><td>Level 1 account (F1)</td><td>Level 2 account (F2)</td><td><code>m/44'/607'/1'/0'</code></td></tr></tbody></table>

#### Cardano account

<table><thead><tr><th width="294">Account needed to be derived</th><th width="214">Derivative account(s)</th><th>Derivation path</th></tr></thead><tbody><tr><td>Parent account (F0)</td><td>Level 1 account (F1)</td><td><code>m/1852'/1815'/1'</code></td></tr><tr><td>Level 1 account (F1)</td><td>Level 2 account (F2)</td><td><code>m/1852'/1815'/1'/0'</code></td></tr></tbody></table>

#### Bitcoin account

1. _Legacy address_

<table><thead><tr><th width="294">Account needed to be derived</th><th width="214">Derivative account(s)</th><th>Derivation path</th></tr></thead><tbody><tr><td>Parent account (F0)</td><td>Level 1 account (F1)</td><td><code>m/44'/0'/1'/0/0</code></td></tr><tr><td>Level 1 account (F1)</td><td>Level 2 account (F2)</td><td><code>m/44'/0'/1'/0/0/1</code></td></tr></tbody></table>

2. Native SegWit address

<table><thead><tr><th width="294">Account needed to be derived</th><th width="214">Derivative account(s)</th><th>Derivation path</th></tr></thead><tbody><tr><td>Parent account (F0)</td><td>Level 1 account (F1)</td><td><code>m/84'/0'/1'/0/0</code></td></tr><tr><td>Level 1 account (F1)</td><td>Level 2 account (F2)</td><td><code>m/84'/0'/1'/0/0/1</code></td></tr></tbody></table>

3. Taproot address

<table><thead><tr><th width="294">Account needed to be derived</th><th width="214">Derivative account(s)</th><th>Derivation path</th></tr></thead><tbody><tr><td>Parent account (F0)</td><td>Level 1 account (F1)</td><td><code>m/86'/0'/1'/0/0</code></td></tr><tr><td>Level 1 account (F1)</td><td>Level 2 account (F2)</td><td><code>m/86'/0'/1'/0/0/1</code></td></tr></tbody></table>
