---
description: >-
  Securely recover your account by importing it using a 12- or 24-word seed
  phrase
---

# Import from seed phrase

## Supported seed phrase types

SubWallet currently supports seed phrases created from words in the [BIP-39 wordlist](https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt). Supported seed phrase types include:

| Seed phrase type                | Corresponding imported account type                   |
| ------------------------------- | ----------------------------------------------------- |
| 12-word seed phrase             | Unified account                                       |
| 15-word seed phrase<sup>1</sup> | Unified account                                       |
| 24-word seed phrase<sup>2</sup> | <ul><li>Unified account</li><li>TON account</li></ul> |

<sup>_1_</sup>_&#x20;SubWallet only supports importing 15-word seed phrases from Cardano-native wallets (Yoroi, Typhoon, Lace, etc.). After importing, SubWallet will generate a unified account for you, ensuring that its Cardano address matches the address displayed from those native wallets._

<sup>_2_</sup>_&#x20;If you import the seed phrase created from a non-native TON wallet into SubWallet, SubWallet will generate a unified account for you. If the seed phrase is from a TON-native wallet, SubWallet will restore your existing TON account._

{% hint style="warning" %}
If you import a seed phrase incompatible with SubWallet, you may be unable to import the account, or the imported account may not be the one you intended to import.

**Trust Wallet, Safepal, and TON-native wallets** are among the wallets that are not compatible with SubWallet.&#x20;
{% endhint %}

## **Import your account via seed phrase**

### If you're on the homepage

**Step 1**: On the SubWallet homepage, click on the account name to access the account selection tab.

<figure><img src="../../../.gitbook/assets/Screenshot_130 (4).png" alt=""><figcaption></figcaption></figure>

**Step 2**: In the account selection tab, click the <img src="../../../.gitbook/assets/Screenshot_232.png" alt="" data-size="line"> icon at the bottom of the screen.

<figure><img src="../../../.gitbook/assets/Screenshot_131 (3).png" alt=""><figcaption></figcaption></figure>

**Step 3**: Choose "**Import from seed phrase**" as the chosen method to import your account.

<figure><img src="../../../.gitbook/assets/Screenshot_132 (2).png" alt=""><figcaption></figcaption></figure>

**Step 4**: Enter your seed phrase by filling in the blank fields.&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot_136 (4).png" alt=""><figcaption></figcaption></figure>

Once done, click "**Import account**".&#x20;

<figure><img src="../../../.gitbook/assets/Screenshot_137 (3).png" alt=""><figcaption></figcaption></figure>

<details>

<summary>To choose the seed phrase type you want to import</summary>

Besides the 12-word seed phrase, SubWallet also allows you to import the 15 and 24-word seed phrases.&#x20;

To do that, click on the drop-down button next to "**12 words**" and then select the seed phrase type you want to import.

<figure><img src="../../../.gitbook/assets/Screenshot_138 (2).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/Screenshot_139 (3).png" alt=""><figcaption></figcaption></figure>

</details>

{% hint style="warning" %}
When you import a seed phrase generated from a non-native TON wallet into SubWallet, a popup will appear informing you that this phrase is incompatible with TON-native wallets:

* Click "**Import**" to proceed.
* Click "**Go back**" to cancel the process.

<img src="../../../.gitbook/assets/Screenshot_140 (4).png" alt="" data-size="original">
{% endhint %}

**Step 5**: Enter a name for your newly imported account, then click "**Confirm**".

<figure><img src="../../../.gitbook/assets/Screenshot_141 (5).png" alt=""><figcaption></figcaption></figure>

You've successfully imported your account into SubWallet!

### If you're on the Welcome page

**Step 1**: Open [SubWallet Web dashboard](https://web.subwallet.app/). The welcome screen will appear.

<figure><img src="../../../.gitbook/assets/image (2289) (1).png" alt=""><figcaption></figcaption></figure>

Select the "**Import an account**" option.

<figure><img src="../../../.gitbook/assets/image (2288) (1).png" alt=""><figcaption></figcaption></figure>

**Step 2**: Make sure you read all the Terms of Use by clicking on the scroll-down button and agree with them by ticking the box beside "**I understand and agree to the Terms of Use, which apply to my use of SubWallet and all of its feature**".

<figure><img src="../../../.gitbook/assets/image (2290) (1).png" alt=""><figcaption></figcaption></figure>

Once done, click "**Continue**".&#x20;

<figure><img src="../../../.gitbook/assets/image (2291) (1).png" alt=""><figcaption></figcaption></figure>

**Step 3:** A popup screen will appear on the right side. Choose "**Import from seed phrase**".

<figure><img src="../../../.gitbook/assets/Screenshot_126 (2).png" alt=""><figcaption></figcaption></figure>

**Step 4:** Enter a strong password with at least 8 characters and tick "**I understand that SubWallet can't recover the password**".&#x20;

{% hint style="info" %}
Password should contain at least 1 uppercase letter, 1 number, and 1 special character.
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (2292) (1).png" alt=""><figcaption></figcaption></figure>

Once done, click "**Continue**".

<figure><img src="../../../.gitbook/assets/image (2293) (1).png" alt=""><figcaption></figcaption></figure>

Once you create a master password, you can follow the importing procedure provided in[#if-youre-on-the-homepage](import-from-seed-phrase.md#if-youre-on-the-homepage "mention"), starting from **Step 4.**
