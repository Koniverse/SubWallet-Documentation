---
description: Aka new Polkadot native wallets and/or Polkadot EVM wallets.
---

# Create a new account with seed phrase

### If this is the first time you install SubWallet

\
**Step 1**: After installing SubWallet extension, open the wallet and choose "Create a new account"

![](<../../.gitbook/assets/image (6) (1).png>)

**Step 2**: Create a master password and click "Continue"

{% hint style="warning" %}
Please note that SubWallet is non-custodial, so you would be the only person who know your password; we cannot help you restore password once it is lost. Please make sure that your password is well-kept.
{% endhint %}

![](<../../.gitbook/assets/image (4) (2).png>)

**Step 3**: Keep your recovery phrase (also known as seed phrase or secret phrase) in a safe place.&#x20;

This recovery phrase is as important as your private key; if someone has your recovery phrase, they will have full control of your account.&#x20;

{% hint style="info" %}
If, for instance, you forget your password, you would need your recovery phrase to import the account again and set up a new password.
{% endhint %}

![](<../../.gitbook/assets/image (3) (1).png>)

**Step 4**: Your account has been successfully set up. Click "Exit" to get to Homepage.

![](<../../.gitbook/assets/image (16) (1).png>)

### If you have already used SubWallet before

In the Homepage, if you click the account name, you would see your list of accounts. You could switch & select your accounts here. We also offer the "All accounts" mode in case you need a quick glance of your total assets.&#x20;

![](<../../.gitbook/assets/image (18).png>) ![](<../../.gitbook/assets/image (8).png>)

For each seedphrase created with SubWallet, you would have a Substrate account and an EVM account. Substrate account would display your assets on Substrate-native blockchains (such as Polkadot, Kusama, Acala), while EVM account would display your assets on EVM chains (such as Moonbeam).&#x20;

{% hint style="info" %}
Please note that in order to see your assets, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](broken-reference) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.&#x20;
{% endhint %}

