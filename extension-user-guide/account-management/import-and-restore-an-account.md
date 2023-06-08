---
description: This part will show you How to Import and Restore an Account on SubWallet.
---

# Import and restore an account

### If you have not had any accounts with SubWallet

**Step 1**: After installing SubWallet extension, open SubWallet and choose "Import an account".

![](../../.gitbook/assets/image.png)

**Step 2**: Choose your prefered way to import an existing account

![](<../../.gitbook/assets/Screenshot 2023-06-08 093513.png>)

### If you have already used SubWallet before

If you have secret phrase (seedphrase), private key, back-up JSON file or QR code you can import/restore your account and manage them with SubWallet.

**Step 1**: Open SubWallet homepage and click on the account name to get to the account management screen. &#x20;

![](<../../.gitbook/assets/image (12) (1) (2) (1).png>)

**Step 2**: In the account management screen, click the import icon.

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F2zseowhOCGE5xsJFb2z5%2Fuploads%2FnA5elIEwiVADORTkcDrF%2FScreenshot\_21.png?alt=media\&token=14fc8e7b-d870-4387-8bb5-8b9566504bc8)

**Step 3**: Choose your preferred way to import account.

![](<../../.gitbook/assets/image (15) (2) (1).png>)



## Import by seedphrase

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by seedphrase, please enter your seed phrase and click "Import account".&#x20;

You could choose between importing either Substrate (Polkadot) account or EVM (Ethereum) account, or both.&#x20;

{% hint style="info" %}
For each seedphrase created with SubWallet, you would have a Substrate account and an EVM account.&#x20;

Substrate account would display your assets on Substrate-native blockchains (such as Polkadot, Kusama, Acala), while EVM account would display your assets on EVM chains (such as Moonbeam).&#x20;
{% endhint %}

![](<../../.gitbook/assets/image (25) (2) (1).png>)

In some cases, if you import account by seedphrase, problems can arise if the seedphrase of your original wallet is not compatible with SubWallet.&#x20;

{% hint style="info" %}
Trust Wallet and Safepal are among the wallets not compatible with us.&#x20;
{% endhint %}

In this case, we would suggest you create a new wallet account with SubWallet and transfer your assets from your original wallet to this new account.&#x20;

After importing the new account into the wallet, you might want to change the account name. Please follow this [guide](switch-between-accounts-and-change-account-name.md).

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](../customize-your-networks.md) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.&#x20;
{% endhint %}

##

## Import by private key (currently supported with EVM account)

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by private key, please enter your  private key and click "Import account".

![](<../../.gitbook/assets/image (1) (1) (2) (2).png>)

Afer importing the new account into the wallet, you might want to change the account name. Please follow this [guide](switch-between-accounts-and-change-account-name.md).

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](../customize-your-networks.md) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.
{% endhint %}

##

## Import by JSON file

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by JSON backup file:

**Step 1**: Click on the import field to choose file from your device, or drag and drop your JSON backup file to import.

![](<../../.gitbook/assets/image (10) (1) (2) (1) (1).png>)

**Step 2**: Enter your master password (created when you set up the wallet for the first time) and click "Import from Json".&#x20;

![](<../../.gitbook/assets/image (23) (1) (2).png>)

Afer importing the new account into the wallet, you might want to change the account name. Please follow this [guide](switch-between-accounts-and-change-account-name.md).

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](../customize-your-networks.md) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.
{% endhint %}

##

## Import by QR code

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by QR code, please present your QR code back-up of your account's private key and scan this QR code with your current device.&#x20;



**Step 1**: Click the "Scan the QR code" button.

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F2zseowhOCGE5xsJFb2z5%2Fuploads%2FaegDNDckWS5Pm0iHXNzy%2FScreenshot\_20.png?alt=media\&token=730ceed9-3975-4f66-b14f-4f3e03fd83f0)

{% hint style="info" %}
Please note that you would need to grant the SubWallet extension the permission to use your camera in order to import by QR code. If you have not yet granted this permission, SubWallet would show the following message:
{% endhint %}

{% hint style="info" %}
Click "Go to Setting" button. You would be directed to our security settings screen. Please switch the toggle to enable camera access.&#x20;

![](<../../.gitbook/assets/image (7) (3) (1).png>)\
. Please switch the toggle to enable camera access.&#x20;

![](<../../.gitbook/assets/image (24) (1) (2).png>)
{% endhint %}



**Step 2**: Present your QR code and scan with SubWallet, using your device's camera.&#x20;

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F2zseowhOCGE5xsJFb2z5%2Fuploads%2Fo0LyV3teoGd7K13E4p9S%2Fimage.png?alt=media&#x26;token=487b39c8-2c48-4c67-a496-897714b2549e" alt=""><figcaption></figcaption></figure>

&#x20;

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F2zseowhOCGE5xsJFb2z5%2Fuploads%2FdjKG4ygi6JOKuOifIOiZ%2F2.png?alt=media&#x26;token=9c47ee56-8444-4975-8927-8d32a024bd8e" alt=""><figcaption></figcaption></figure>

After the succesful import of your account by QR code, you would be directed to the Homescreen.&#x20;

Afer importing the new account into the wallet, you might want to change the account name. Please follow this [guide](switch-between-accounts-and-change-account-name.md).

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](../customize-your-networks.md) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.
{% endhint %}

## Disable your permission for camera access

After importing by QR code, If you want to revoke the permission for SubWallet to use your camera, please go to the Security settings section to do so.

{% hint style="info" %}
**Step 1**: Choose the list icon on the upper left corner of your Homescreen.

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F2zseowhOCGE5xsJFb2z5%2Fuploads%2F5JSrnZ74n3ImsMYrofiN%2FScreenshot\_2.png?alt=media\&token=7f65d518-d978-453b-9c3a-545f0a161e23)\


**Step 2**: Choose "Security settings".

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F2zseowhOCGE5xsJFb2z5%2Fuploads%2F8D78OrReXf4WQRZ258aZ%2FScreenshot\_5.png?alt=media\&token=506a8567-6d9b-4d29-8a99-1f4d291c571c)\
\
**Step 3**: Disable the toggle next to the "Allow camera access" option.&#x20;

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F2zseowhOCGE5xsJFb2z5%2Fuploads%2FjOdRHyvzxBLw6jOLlzZM%2FScreenshot\_4.png?alt=media\&token=d7c1e341-f1b4-4f6f-885d-109b21d49e41)
{% endhint %}
