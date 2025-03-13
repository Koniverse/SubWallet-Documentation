---
description: >-
  Generate derived accounts linked to your original one, simplifying management
  and enhancing security on SubWallet.
---

# Derive a new account from an existing account

### Understand derivative accounts <a href="#understand-derivative-accounts" id="understand-derivative-accounts"></a>

#### **What is a derivative account?**

Derivative accounts are accounts created by deriving the original account (parent account).

{% hint style="info" %}
Derivative accounts share the exact seed phrase as the original account but use different paths.

You can use a derivative account as the original account to make transactions.
{% endhint %}

#### Default derivation paths

Currently, SubWallet uses the [BIP-44 standard](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki) for Substrate (Polkadot), EVM (Ethereum), and TON accounts. Each account has a default derivation path based on its type.

Here's the default derivation path for each type of original account:

<table><thead><tr><th width="302">Account type</th><th>Default derivation path</th></tr></thead><tbody><tr><td>Substrate (Polkadot)</td><td><code>Empty</code></td></tr><tr><td>EVM (Ethereum)</td><td><code>m/44'/60'/0'/0/0</code></td></tr><tr><td>TON</td><td><code>m/44'/607'/0'</code></td></tr></tbody></table>

{% hint style="info" %}
If you're using a unified account, it will include all of the above paths.
{% endhint %}

{% hint style="warning" %}
Currently, SubWallet supports creating derived accounts from these account types:

* [x] Unified account
* [x] Solo account: Substrate, EVM\* & TON account.

_(\*): With EVM accounts, you can only create derived accounts from **parent accounts imported into SubWallet**_ [_**via seed phrase**_](https://docs.subwallet.app/main/extension-user-guide/account-management/import-accounts/import-from-seed-phrase)_**.**_

Other account types (watch-only, Ledger, and QR-signer) are not supported.
{% endhint %}

#### **Supported derivative accounts**

You can create multiple derivative accounts from an original account (parent account). Each account from these can create more derivative accounts.

To differentiate them, in this document, these accounts will be categorized based on their derivative levels. For example, parent accounts will be known as "**Level 0 accounts**" or "**F0 accounts**".

<table><thead><tr><th width="282">Account needed to be derived</th><th>Derivative account(s)</th><th>Shortened derivation path</th></tr></thead><tbody><tr><td>Parent account (F0)</td><td>Level 1 account (F1)</td><td><code>/0</code> or <code>//0</code></td></tr><tr><td>Level 1 account (F1)</td><td>Level 2 account (F2)*</td><td><code>/0/0</code> or <code>//0/0</code></td></tr><tr><td>Level 2 account (F2)</td><td>Level 3 account (F3)**</td><td><code>/0/0/0</code> or <code>//0/0/0</code></td></tr></tbody></table>

_(\*): Level 2 accounts will be supported for Substrate accounts only._

_(\*\*): Level 3 accounts and onwards will not be supported on any wallets._

### Create a new account derived from an existing one

**Step 1:** On the SubWallet homepage, tap the account name at the top of the screen to access the account selection tab.

<figure><img src="../../.gitbook/assets/Screenshot_16 (7).png" alt="" width="270"><figcaption></figcaption></figure>

**Step 2**: In the account selection tab, you can choose to create a derived account using either of the following ways:

* Press the "**Create a new account**" button
* Hit the <img src="../../.gitbook/assets/Screenshot_67 (5).png" alt="" data-size="line"> **icon** next to the account you want to derive

Choose your preferred tab to continue.

{% tabs %}
{% tab title="Press the button" %}
**Step 3**: Choose the "**Derive from an existing account**" button to derive a new account.

<figure><img src="../../.gitbook/assets/Screenshot_3 (10).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 4**: Select the account you want to derive from.

<figure><img src="../../.gitbook/assets/Screenshot_4 (4).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 5**: Enter a valid derivation path and a name for your derived account. Once done, hit "**Create account**".

<figure><img src="../../.gitbook/assets/Screenshot_5 (1) (2).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 6**: You've successfully created a derived account! Head over to your account list to see it.

<div><figure><img src="../../.gitbook/assets/Screenshot_6 (7).png" alt="" width="272"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_7 (6).png" alt="" width="272"><figcaption></figcaption></figure></div>

{% hint style="info" %}
You can create solo derivative accounts from a unified account by customizing the derivation path to align with the ecosystem's formatted derivative path.

<img src="../../.gitbook/assets/Screenshot_10 (7).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_11 (17).png" alt="" data-size="original">
{% endhint %}
{% endtab %}

{% tab title="Hit the icon" %}
**Step 3**: In the Account details tab, press the "**Derive**" button at the bottom of the screen to start deriving a new account.

<figure><img src="../../.gitbook/assets/Screenshot_8 (6).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 4**: Enter a valid derivation path and a name for your derived account. Once done, hit "**Create account**".

<figure><img src="../../.gitbook/assets/Screenshot_9 (1) (3).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 5**: You've successfully created a derived account! Head over to your account list to see it.\\

<div><figure><img src="../../.gitbook/assets/Screenshot_6 (8).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_7 (7).png" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
You can create solo derivative accounts from a unified account by customizing the derivation path to align with the ecosystem's formatted derivative path.

<img src="../../.gitbook/assets/Screenshot_12 (7).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_11 (18).png" alt="" data-size="original">
{% endhint %}
{% endtab %}
{% endtabs %}

