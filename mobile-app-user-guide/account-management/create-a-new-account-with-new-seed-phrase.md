# Create a new account with new seed phrase

## If you are new to SubWallet

You can create a new account immediately from the "Welcome" screen. You can create a new account using seed phrase.&#x20;

![](<../../.gitbook/assets/image (44) (1).png>) ![](<../../.gitbook/assets/image (23) (3).png>)



## If you have already had an account with SubWallet

You might create a new account with new seed phrase, or [derive a new account from an existing account](derive-a-new-account-from-an-existing-account.md).&#x20;

In this case we are introducing creating new account with seed phrase.&#x20;

**Step 1**: Open SubWallet homepage and click on the account name to get to the account management screen.

![](<../../.gitbook/assets/image (28) (1).png>)

**Step 2**: In the account management screen, click "Create new account".

![](<../../.gitbook/assets/image (71) (1).png>)

**Step 3**: Choose "Create with new seed phrase".

![](<../../.gitbook/assets/image (39) (1).png>)



## Create account with new Seed phrase

**Step 1**: SubWallet would present you with a totally new seed phrase. Please keep it in a safe place. Then click "Continue".

This recovery phrase is as important as your private key; if someone has your recovery phrase, they will have full control of your account.&#x20;

{% hint style="info" %}
If, for instance, you forget your password, you would need your recovery phrase to import the account again and set up a new password.
{% endhint %}

![](<../../.gitbook/assets/image (41) (2).png>)



**Step 2**: Enter your seed phrase in the correct order.

![](<../../.gitbook/assets/image (78) (1).png>)



**Step 3**: Enter your SubWallet password and click "Apply" to confirm the creation of your new account.

![](<../../.gitbook/assets/image (14) (2).png>)

Afer importing the new account into the wallet, you might want to change the account name. Please follow this [guide](switch-between-accounts-and-change-account-name.md).

For each seedphrase created with SubWallet, you would have a Substrate account and an EVM account. Substrate account would display your assets on Substrate-native blockchains (such as Polkadot, Kusama, Acala), while EVM account would display your assets on EVM chains (such as Moonbeam).&#x20;

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](../customize-your-blockchains.md) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.&#x20;
{% endhint %}

