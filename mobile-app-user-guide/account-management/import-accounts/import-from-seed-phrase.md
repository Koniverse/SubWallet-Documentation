---
description: >-
  Securely recover your account by importing it using a 12- or 24-word seed
  phrase.
---

# Import from seed phrase

### Supported seed phrase types <a href="#supported-seed-phrase-types" id="supported-seed-phrase-types"></a>

SubWallet currently supports seed phrases created from words in the [BIP-39 wordlist](https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt). Supported seed phrase types include:

| Seed phrase type      | Imported account type                                 |
| --------------------- | ----------------------------------------------------- |
| 12-word seed phrase   | Unified account                                       |
| 24-word seed phrase\* | <ul><li>Unified account</li><li>TON account</li></ul> |

_(\*): If you import a seed phrase created from a non-native TON wallet into SubWallet, SubWallet will generate a unified account for you. If seed phrase is from a TON-native wallet, SubWallet will restore your existing TON account._

{% hint style="warning" %}
If you import a seed phrase incompatible with SubWallet, you may be unable to import the account, or the imported account may not be the one you intended to import.

**Trust Wallet, Safepal, and TON-native wallets** are among the wallets that are not compatible with SubWallet.
{% endhint %}

### **Import your account via seed phrase** <a href="#import-your-account-via-seed-phrase" id="import-your-account-via-seed-phrase"></a>

#### **If you are currently using SubWallet**

**Step 1**: On the SubWallet homepage, hit the account name to access the account selection tab.

<figure><img src="../../../.gitbook/assets/Screenshot_16 (7).png" alt="" width="270"><figcaption></figcaption></figure>

**Step 2**: In the account selection tab, press the <img src="https://docs.subwallet.app/~gitbook/image?url=https%3A%2F%2F631687399-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lh39Kwxa1xxZM9WX_Bs%252Fuploads%252FpGiUsKS7LQbuF7fcmC5Q%252FScreenshot_232.png%3Falt%3Dmedia%26token%3D93a80930-8762-47f2-8c58-c48721795f7e&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=37584144&#x26;sv=2" alt="" data-size="line"> icon at the bottom of the screen.

<figure><img src="../../../.gitbook/assets/Screenshot_22 (6).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 3**: Choose "**Import from seed phrase**" as the chosen method to import your account.

<figure><img src="../../../.gitbook/assets/Screenshot_13 (11).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 4**: Enter your seed phrase by filling in the blank fields. Once done, hit "**Import account**".

<div><figure><img src="../../../.gitbook/assets/Screenshot_17 (7).png" alt="" width="272"><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/Screenshot_18 (1) (2).png" alt="" width="272"><figcaption></figcaption></figure></div>

{% hint style="warning" %}
When you import a seed phrase generated from a non-native TON wallet into SubWallet, a popup will appear informing you that this phrase is incompatible with TON-native wallets:

* Click "**Import**" to proceed.
* Click "**Go back**" to cancel the process.

<img src="../../../.gitbook/assets/Screenshot_19 (1) (3).png" alt="" data-size="original">
{% endhint %}

**Step 5**: Enter a name for your newly imported account, then hit "**Confirm**".

<figure><img src="../../../.gitbook/assets/Screenshot_20 (1) (3).png" alt="" width="272"><figcaption></figcaption></figure>

You've successfully imported your account into SubWallet!

#### **If you have not had any accounts with SubWallet**

**Step 1**: Open the SubWallet app. On the welcome screen, choose "**Import an account**".

<figure><img src="../../../.gitbook/assets/Screenshot_7 (9).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 2**: Choose "**Import from seed phrase**" to import account.

<figure><img src="../../../.gitbook/assets/Screenshot_8 (8).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 3:** Create a master password with at least 6 characters and tick "**I understand that SubWallet can't recover the password**". Once done, hit "**Continue**".

<div><figure><img src="../../../.gitbook/assets/spaces_-Lh39Kwxa1xxZM9WX_Bs_uploads_YfZD15XrQMcFMhoD9n3x_Screenshot_8.webp" alt="" width="270"><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/spaces_-Lh39Kwxa1xxZM9WX_Bs_uploads_jGuadvrKVkyLZGsYxjKN_Screenshot_9 (1).webp" alt="" width="270"><figcaption></figcaption></figure></div>

{% hint style="warning" %}
SubWallet is non-custodial, so you will be the only person who knows your password; we can't help you restore it once it is lost. Make sure that your password is well-kept.
{% endhint %}

Once you create a master password, you can follow the importing procedure provided in [If you are currently using SubWallet](https://docs.subwallet.app/main/extension-user-guide/account-management/import-accounts/import-from-seed-phrase#if-you-are-currently-using-subwallet), starting from **Step 3.**
