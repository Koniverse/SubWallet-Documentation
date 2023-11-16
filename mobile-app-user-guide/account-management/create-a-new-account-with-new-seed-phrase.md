---
description: This document will show you how to create a new account on SubWallet.
---

# Create a new account with new seed phrase

## If you are new to SubWallet

You can create a new account immediately from the welcome screen. You can create a new account using seed phrase.&#x20;

![](<../../.gitbook/assets/image (17) (1).png>)&#x20;



## If you have already had an account with SubWallet

You might create a new account with a new seed phrase, or [derive a new account from an existing account](derive-a-new-account-from-an-existing-account.md).&#x20;

In this case, we are introducing creating new account with seed phrase.&#x20;

**Step 1**: Open SubWallet homepage and click on the account name to get to the account management screen.

![](<../../.gitbook/assets/image (28) (1) (1) (1) (1) (1) (1).png>)

**Step 2**: In the account management screen, click **Create new account**.

![](<../../.gitbook/assets/image (71) (1) (1) (1) (1) (1).png>)

**Step 3**: Choose "Create with new seed phrase".

![](<../../.gitbook/assets/image (39) (1) (1) (1) (1) (1) (1).png>)



## Create account with new seed phrase

**Step 1**: SubWallet will present you with a new seed phrase. Please keep it in a safe place. Then click **Continue**.

<div align="left">

<figure><img src="../../.gitbook/assets/image (42).png" alt="" width="324"><figcaption></figcaption></figure>

</div>

This recovery phrase is as important as your private key; if someone has your recovery phrase, they will have full control of your account.&#x20;

{% hint style="info" %}
If, for instance, you forget your password, you will need your recovery phrase to import the account again and set up a new password.
{% endhint %}

**Step 2**: Enter your seed phrase in the correct order.

![](<../../.gitbook/assets/image (21) (1).png>)



**Step 3**: Enter your SubWallet password and click "Apply" to confirm the creation of your new account.

![](<../../.gitbook/assets/image (14) (2).png>)

After importing the new account into the wallet, you might want to change the account name. Please follow this [guide](switch-between-accounts-and-change-account-name.md).

For each seed phrase created with SubWallet, you would have a Substrate account and an EVM account. Substrate account would display your assets on Substrate-native blockchains (such as Polkadot, Kusama, and Acala), while EVM account would display your assets on EVM chains (such as Moonbeam).&#x20;

{% hint style="info" %}
Please note that in order to see your assets after importing your account, you would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](../customize-your-blockchains.md) to enable the networks you want to use.

SubWallet automatically enables Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.&#x20;
{% endhint %}

