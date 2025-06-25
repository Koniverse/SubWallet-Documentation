---
description: >-
  This document will show you how to connect accounts on your Ledger device via
  the Polkadot app on SubWallet.
---

# Connect via the Polkadot app

### Understand the new Polkadot app

On July 1, 2024, the new Polkadot app was released (version 100.0.5). With this new app, you will be able to use a single Ledger account across any Substrate-based network.

To ensure compatibility with the new Polkadot app, all Substrate-based networks need to update their runtime logic. To check if a network has performed this action, visit the [Parachains Metadata dashboard](https://dashboards.data.paritytech.io/metadata.html). If it hasn't, continue using the corresponding Ledger app.

{% hint style="warning" %}
If your Polkadot app is on a version lower than 100.0.5, you're required to update the app in order to continue using and connecting to SubWallet.
{% endhint %}

### Select the right account type for use when connecting via Polkadot app

Starting from version [100.0.14](https://github.com/LedgerHQ/app-polkadot/releases/tag/v100.0.14), users will be able to connect and perform transactions on Substrate-based networks that use EVM addresses (e.g., _Mythos, Moonbeam, Moonriver_) through the Polkadot app. As these networks use a different signing method from those who fully Substrate-based, you will need to select a different account type to connect.

In particular, after selecting the Polkadot app option, depending on your needs, you will need to choose the account type you want:

<table><thead><tr><th width="232.13336181640625">Account type</th><th>Compatibility</th></tr></thead><tbody><tr><td>Polkadot account</td><td>Manage, receive &#x26; transfer assets on <strong>fully Substrate-based networks</strong> (i.e., networks that use Substrate address format - starting with 5)</td></tr><tr><td>Ethereum account</td><td>Manage, receive &#x26; transfer assets on <strong>Substrate-based networks that are EVM-compatible</strong> (i.e., networks that use EVM address format - starting with 0x)</td></tr></tbody></table>

### Connect your accounts via Polkadot app

**Step 1**: Have your Ledger device ready & connected to your computer. Choose the Polkadot App on your Ledger.

<div><figure><img src="../../../.gitbook/assets/photo_2024-12-11_16-58-17.jpg" alt="" width="563"><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/photo_2024-12-11_16-58-22.jpg" alt="" width="563"><figcaption></figcaption></figure></div>

**Step 2**: Open the SubWallet extension and click on the account name to access the account selection tab.

<figure><img src="../../../.gitbook/assets/Screenshot_23 (4).png" alt="" width="362"><figcaption></figcaption></figure>

**Step 3**: In the account selection tab, click the <img src="../../../.gitbook/assets/Screenshot_191.png" alt="" data-size="line"> button at the bottom right corner of the screen.

<figure><img src="../../../.gitbook/assets/Screenshot_55.png" alt="" width="362"><figcaption></figcaption></figure>

**Step 4**: Choose "**Connect a Ledger device**".

<figure><img src="../../../.gitbook/assets/Screenshot_56.png" alt="" width="362"><figcaption></figcaption></figure>

**Step 5**: You will be directed to a new window. Select the Polkadot app, and your extension will display the following pop-up:

<figure><img src="../../../.gitbook/assets/Screenshot_212.png" alt=""><figcaption></figcaption></figure>

Click on the device name (Nano X in this case) and click "**Connect**".

**Step 6**: After SubWallet has successfully found your Ledger, click "**Connect Ledger device**".

{% hint style="info" %}
Don't forget to turn on the corresponding app on the Ledger device.
{% endhint %}

<figure><img src="../../../.gitbook/assets/Screenshot_209.png" alt=""><figcaption></figcaption></figure>

**Step 7**: Choose the account(s) you want to use, then click "**Connect Ledger device**".

<figure><img src="../../../.gitbook/assets/Screenshot_210.png" alt="" width="363"><figcaption></figcaption></figure>

**Step 8**: Your Ledger account is ready!

If you repeat the action in **Step 2**, you will see your newly connected Ledger Polkadot accounts displayed in the "**Ledger Account**" section.

<figure><img src="../../../.gitbook/assets/Screenshot_211.png" alt="" width="363"><figcaption></figcaption></figure>
