---
description: This document will show you how to export & backup accounts on SubWallet.
---

# Export & backup accounts

### Supported export methods

Export your backup information in different forms of backup files, and use these files to restore & import the account again if you so wish.

Depending on the type of account you want to export, SubWallet supports different export methods:

<table><thead><tr><th width="224">Account type</th><th data-type="checkbox">Seed phrase</th><th width="136.42578125" data-type="checkbox">JSON file²</th><th data-type="checkbox">Private key</th><th data-type="checkbox">QR code</th></tr></thead><tbody><tr><td><strong>Unified account</strong></td><td>true</td><td>true</td><td>false</td><td>false</td></tr><tr><td><strong>Substrate account</strong></td><td>true</td><td>true</td><td>false</td><td>true</td></tr><tr><td><strong>EVM account</strong><sup><strong>1</strong></sup></td><td>true</td><td>true</td><td>true</td><td>true</td></tr><tr><td><strong>TON account</strong></td><td>true</td><td>true</td><td>true</td><td>false</td></tr><tr><td><strong>Cardano account</strong></td><td>false</td><td>true</td><td>false</td><td>false</td></tr><tr><td><strong>Bitcoin account</strong></td><td>false</td><td>true</td><td>false</td><td>false</td></tr><tr><td><strong>QR-signer account</strong></td><td>false</td><td>true</td><td>false</td><td>false</td></tr><tr><td><strong>Watch-only account</strong></td><td>false</td><td>true</td><td>false</td><td>false</td></tr><tr><td><strong>Ledger account</strong><sup><strong>3</strong></sup></td><td>false</td><td>false</td><td>false</td><td>false</td></tr></tbody></table>

<sup>_1_</sup>_&#x20;Exporting via QR code for EVM accounts is only possible if the account is previously imported via seed phrase._

<sup>_2_</sup>_&#x20;The exported JSON file **cannot be imported** into EVM-compatible wallets (Metamask, Phantom, Rabby, etc.) or Cardano-native wallets (Typhoon)._

<sup>_3_</sup>_&#x20;Ledger accounts are not supported for exporting._

### Export & backup an account

**Step 1**: On the SubWallet homepage, click on the account name to access the account selection tab.

<figure><img src="../../.gitbook/assets/image (2239) (1).png" alt=""><figcaption></figcaption></figure>

**Step 2**: In the account selection tab, click the <img src="../../.gitbook/assets/Screenshot_219 (1).png" alt="" data-size="line"> icon on the right-hand side of the account you wish to export.&#x20;

_In this example, we will export the backup information of "Andy T" - a unified account._

<figure><img src="../../.gitbook/assets/image (2240) (1).png" alt=""><figcaption></figcaption></figure>

**Step 3**: In the Account details screen, choose "**Export**".

<figure><img src="../../.gitbook/assets/image (2241) (1).png" alt=""><figcaption></figcaption></figure>

**Step 4**: A popup screen will appear on the right side. Enter your password and select the export method(s) you want.&#x20;

{% hint style="info" %}
You will notice that even if you correctly enter your password, the "**Confirm**" button is still unclickable. You would need to choose your preferred form of export to continue.
{% endhint %}

As "_Andy T_" is a unified account, there are 2 options to export the account, as listed in the table above.

<figure><img src="../../.gitbook/assets/image (2244) (1).png" alt=""><figcaption></figcaption></figure>

Once done, click "**Confirm**".

<figure><img src="../../.gitbook/assets/image (2245) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Please save and keep your backup files secure.&#x20;

Furthermore, you will need these backup files to restore your account in case you forget your SubWallet password.
{% endhint %}

{% hint style="danger" %}
**Don't share your seed phrase with anyone, including us.**&#x20;

SubWallet is non-custodial, which means we don't store any of your backup information to ensure user privacy and security.
{% endhint %}

### Export multiple accounts

{% hint style="info" %}
This feature allows you to export backup information of multiple accounts (no matter its account type) in **one JSON file**.
{% endhint %}

**Step 1**: On the SubWallet homepage, click on the account name to access the account selection tab.

<figure><img src="../../.gitbook/assets/image (2239) (1).png" alt=""><figcaption></figcaption></figure>

**Step 2**: In the account selection tab, click on the export icon <img src="../../.gitbook/assets/Screenshot_14 (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> at the top right of the screen.

<figure><img src="../../.gitbook/assets/image (2246) (1).png" alt=""><figcaption></figcaption></figure>

**Step 3**: In the Export account screen, select as many accounts to export as you wish.

_In this example, we want to export 3 accounts. Once done, click on the "**Export 3 accounts**" button._

<figure><img src="../../.gitbook/assets/image (2248) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
As Ledger accounts are not supported for this feature, you will not see them in the available account list.
{% endhint %}

**Step 4**: A popup will appear on the center of the screen. Enter your password to confirm, then click "**Submit**" to proceed.

<figure><img src="../../.gitbook/assets/image (2249) (1).png" alt=""><figcaption></figcaption></figure>

Once clicked, the Chrome browser will download a JSON file. Click **Ctrl + J** to locate the file.

<figure><img src="../../.gitbook/assets/Screenshot_229.png" alt=""><figcaption></figcaption></figure>

**Step 5**: You have successfully exported multiple accounts! Click "**Finish**" to return to the homepage.

<figure><img src="../../.gitbook/assets/image (2250) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If you want to import these accounts to use them on other devices and browsers, you can import the JSON file downloaded from **Step 4** using this guide.
{% endhint %}
