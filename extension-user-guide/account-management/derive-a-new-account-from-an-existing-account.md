---
description: >-
  Generate derived accounts linked to your original one, simplifying management
  and enhancing security on SubWallet.
---

# Derive a new account from an existing account

### Understand derivative accounts

#### What is a derivative account?

Derivative accounts are accounts created by deriving the original account (parent account).

{% hint style="info" %}
Derivative accounts share the exact seed phrase as the original account but use different paths.

You can use a derivative account as the original account to make transactions.
{% endhint %}

#### Default derivation paths

Currently, SubWallet uses the [BIP-44 standard](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki) for Substrate (Polkadot), EVM (Ethereum), and TON accounts. Each account has a default derivation path based on its type.

Here's the default derivation path for each type of original account:

<table><thead><tr><th width="298">Account type</th><th>Default derivation path</th></tr></thead><tbody><tr><td>Substrate (Polkadot)</td><td><code>Empty</code></td></tr><tr><td>EVM (Ethereum)</td><td><code>m/44'/60'/0'/0/0</code></td></tr><tr><td>TON</td><td><code>m/44'/607'/0'</code></td></tr></tbody></table>

{% hint style="info" %}
If you're using a unified account, it will include all of the above paths.
{% endhint %}

{% hint style="warning" %}
Currently, SubWallet supports creating derived accounts from these account types:

* [x] Unified account
* [x] Solo account: Substrate, EVM\* & TON account.&#x20;

_(\*): With EVM accounts, you can only create derived accounts from **parent accounts imported into SubWallet**_ [_**via seed phrase**_](import-accounts/import-from-seed-phrase.md)_**.**_

Other account types (watch-only, Ledger, and QR-signer) are not supported.
{% endhint %}

#### Supported derivative accounts

You can create multiple derivative accounts from an original account (parent account). Each account from these can create more derivative accounts.&#x20;

To differentiate them, in this document, these accounts will be categorized based on their derivative levels. For example, parent accounts will be known as "Level 0 accounts" or "F0 accounts".

<table><thead><tr><th width="294">Account needed to be derived</th><th width="214">Derivative account(s)</th><th>Shortened derivation path</th></tr></thead><tbody><tr><td>Parent account (F0)</td><td>Level 1 account (F1)</td><td><code>/0</code> or <code>//0</code></td></tr><tr><td>Level 1 account (F1)</td><td>Level 2 account (F2)*</td><td><code>/0/0</code> or <code>//0/0</code></td></tr><tr><td>Level 2 account (F2)</td><td>Level 3 account (F3)**</td><td><code>/0/0/0</code> or <code>//0/0/0</code></td></tr></tbody></table>

_(\*): Level 2 accounts will be supported for Substrate accounts only_

_(\*\*): Level 3 accounts and onwards will not be supported on any wallets_

### Create a new account derived from an existing one

**Step 1**: Open the SubWallet extension and click on the account name to access the account selection tab.

<figure><img src="../../.gitbook/assets/Screenshot_135.png" alt="" width="363"><figcaption></figcaption></figure>

**Step 2**: In the account selection tab, you can choose to create a derived account using either of the following ways:

* Click the "**Create a new account**" button
* Click the **pen icon** next to the account you want to derive

<figure><img src="../../.gitbook/assets/image (4).png" alt="" width="363"><figcaption></figcaption></figure>

Choose your preferred tab to continue.

{% tabs %}
{% tab title="Click the button" %}
**Step 3**: Choose the "**Derive from an existing account**" button to derive a new account.

<figure><img src="../../.gitbook/assets/Screenshot_142 (1).png" alt="" width="363"><figcaption></figcaption></figure>

**Step 4**: Choose the account you want to derive from.

<figure><img src="../../.gitbook/assets/Screenshot_143 (1).png" alt="" width="363"><figcaption></figcaption></figure>

**Step 5**: Enter a valid derivation path and a name for your derived account. Once done, click "**Create account**".

<figure><img src="../../.gitbook/assets/Screenshot_144 (1).png" alt="" width="363"><figcaption></figcaption></figure>

**Step 6**: You've successfully created a derived account! Head over to your account list to see it.

<figure><img src="../../.gitbook/assets/Screenshot_146 (1).png" alt="" width="363"><figcaption></figcaption></figure>

{% hint style="info" %}
You can create solo derivative accounts from a unified account by customizing the derivation path to align with the ecosystem's formatted derivative path.

<img src="../../.gitbook/assets/Screenshot_147 (1).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_148 (1).png" alt="" data-size="original">
{% endhint %}
{% endtab %}

{% tab title="Click the pen icon" %}
**Step 3**: In the Account details tab, click the "**Derive**" button at the bottom of the screen to start deriving a new account.

<figure><img src="../../.gitbook/assets/Screenshot_145 (1).png" alt="" width="363"><figcaption></figcaption></figure>

**Step 4**: Enter a valid derivation path and a name for your derived account. Once done, click "**Create account**".

<figure><img src="../../.gitbook/assets/Screenshot_144 (1).png" alt="" width="363"><figcaption></figcaption></figure>

**Step 5**: You've successfully created a derived account! Head over to your account list to see it.

<figure><img src="../../.gitbook/assets/Screenshot_146 (1).png" alt="" width="363"><figcaption></figcaption></figure>

{% hint style="info" %}
You can create solo derivative accounts from a unified account by customizing the derivation path to align with the ecosystem's formatted derivative path.

<img src="../../.gitbook/assets/Screenshot_147 (1).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_148 (1).png" alt="" data-size="original">
{% endhint %}
{% endtab %}
{% endtabs %}

