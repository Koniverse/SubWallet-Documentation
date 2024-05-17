---
description: This document will show you how to export & backup accounts on SubWallet.
---

# Export & backup accounts

### Export & backup an account

Export your private key in different forms of backup files, and use these files to restore & import the account again if you so wish.

Depending on the type of account you want to export, SubWallet supports different export methods:

<table><thead><tr><th width="312">Account's type</th><th>Supported export method</th></tr></thead><tbody><tr><td>Polkadot (Substrate) account</td><td><ul><li>Export seed phrase</li><li>Export JSON file</li><li>Export QR code</li></ul></td></tr><tr><td>Ethereum (EVM) acccount</td><td><ul><li>Export seed phrase</li><li>Export JSON file</li><li>Export private key</li><li>Export QR code</li></ul></td></tr><tr><td>Watch-only account</td><td>None</td></tr><tr><td>Ledger account</td><td>None</td></tr><tr><td>QR-signer account</td><td>None</td></tr></tbody></table>

**Step 1**: On the SubWallet homepage, click on the account name to get to the account selection tab.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot_4.png" alt="" width="367"><figcaption></figcaption></figure>

**Step 2**: In the account selection tab, click the edit icon on the right-hand side of the account you wish to export.&#x20;

In this example, we chose account "Andy" - a Polkadot (Substrate) account - to export.

<figure><img src="../../.gitbook/assets/Screenshot_5 (1).png" alt="" width="367"><figcaption></figcaption></figure>

**Step 3**: In the Account details section, choose "Export".

<figure><img src="../../.gitbook/assets/Screenshot_6 (2).png" alt="" width="367"><figcaption></figcaption></figure>

**Step 4**: Enter your password.&#x20;

{% hint style="info" %}
You will notice that even if you correctly enter your password, the "Confirm" button is still unavailable. You would need to choose your preferred form of export file to continue.
{% endhint %}

As "Andy" is a Polkadot account, there are 3 options to export the private key, as listed in the table above.

<figure><img src="../../.gitbook/assets/Screenshot_13 (1).png" alt="" width="367"><figcaption></figcaption></figure>

**Step 5**: Choose your preferred way(s) to export your private key. Then, click "Confirm".

<figure><img src="../../.gitbook/assets/Screenshot_8 (1).png" alt="" width="367"><figcaption></figcaption></figure>

{% hint style="warning" %}
Please save and keep your backup files in a secure place.&#x20;

Do not share these files because they contain your private key; anyone with these files can use your assets.

Furthermore, you would need these backup files to restore your account in case you forget your SubWallet password.&#x20;
{% endhint %}

### Export multiple accounts

This feature allows users to export the private keys of multiple accounts (whether they are Polkadot accounts or Ethereum accounts) in the form of **one** JSON file.&#x20;

{% hint style="info" %}
In this example, we will export multiple accounts on the SubWallet extension using the Chrome browser.
{% endhint %}

**Step 1**: On the SubWallet homepage, click on the account name to get to the account selection tab.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot_4.png" alt="" width="367"><figcaption></figcaption></figure>

**Step 2**: In the account selection tab, click on the Export icon <img src="../../.gitbook/assets/Screenshot_14 (1).png" alt="" data-size="line"> at the upper right.

<figure><img src="../../.gitbook/assets/Screenshot_9.png" alt="" width="369"><figcaption></figcaption></figure>

**Step 3**: In the Export account screen, select as many accounts to export as you wish.

<figure><img src="../../.gitbook/assets/Screenshot_10.png" alt="" width="368"><figcaption></figcaption></figure>

In this example, we want to export 4 accounts. Once done, click on the "Export 4 accounts" button.

<figure><img src="../../.gitbook/assets/Screenshot_11 (1).png" alt="" width="368"><figcaption></figcaption></figure>

**Step 4**: Enter your password to confirm, then click "Submit" to proceed.

<figure><img src="../../.gitbook/assets/Screenshot_12 (1).png" alt="" width="368"><figcaption></figcaption></figure>

Once clicked, the Chrome browser will download a JSON file.

<figure><img src="../../.gitbook/assets/Screenshot (2) (1).png" alt=""><figcaption></figcaption></figure>

**Step 5**: You have successfully exported multiple accounts! Click "Finish" to return to the homepage.

<figure><img src="../../.gitbook/assets/Screenshot_15 (1).png" alt="" width="365"><figcaption></figcaption></figure>

{% hint style="info" %}
If you want to import these accounts to use them on other devices and browsers, you can import the JSON file downloaded from **Step 4** using this [guide](import-and-restore-an-account.md).
{% endhint %}
