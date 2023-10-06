---
description: This part will show you How to Import and Restore an Account on SubWallet.
---

# Import and restore an account

### If you have not had any accounts with SubWallet

**Step 1**: After installing SubWallet extension, open SubWallet and choose "Import an account".

![](<../../.gitbook/assets/image (82) (1).png>)

**Step 2**: Choose your prefered way to import an existing account

![](<../../.gitbook/assets/Screenshot 2023-06-08 093513.png>)

**Step 3:** Create a master password and click "Continue".

{% hint style="warning" %}
Please note that SubWallet is non-custodial, so you would be the only person who know your password; we cannot help you restore password once it is lost. Please make sure that your password is well-kept.
{% endhint %}

![](<../../.gitbook/assets/image (83) (1).png>)

{% hint style="info" %}
After creating the master password, users will be directed to the step of creating/importing an account using the selected method.

[#import-by-seedphrase](import-and-restore-an-account.md#import-by-seedphrase "mention")[#import-by-private-key-currently-supported-with-evm-account](import-and-restore-an-account.md#import-by-private-key-currently-supported-with-evm-account "mention")[#import-from-polkadot-js-import-by-json-file](import-and-restore-an-account.md#import-from-polkadot-js-import-by-json-file "mention")                                   [#import-by-qr-code](import-and-restore-an-account.md#import-by-qr-code "mention")
{% endhint %}

### If you have already used SubWallet before

If you have secret phrase (seedphrase), private key, back-up JSON file or QR code you can import/restore your account and manage them with SubWallet.

**Step 1**: Open SubWallet homepage and click on the account name to get to the account management screen. &#x20;

![](<../../.gitbook/assets/image (126).png>)

**Step 2**: In the account management screen, click the import icon.

![](<../../.gitbook/assets/image (17).png>)

**Step 3**: Choose your preferred way to import account.

![](<../../.gitbook/assets/image (18).png>)

{% hint style="info" %}
After creating the master password, users will be directed to the step of creating/importing an account using the selected method.

[#import-by-seedphrase](import-and-restore-an-account.md#import-by-seedphrase "mention")[#import-by-private-key-currently-supported-with-evm-account](import-and-restore-an-account.md#import-by-private-key-currently-supported-with-evm-account "mention")[#import-from-polkadot-js-import-by-json-file](import-and-restore-an-account.md#import-from-polkadot-js-import-by-json-file "mention")                                      [#import-by-qr-code](import-and-restore-an-account.md#import-by-qr-code "mention")
{% endhint %}

## Import by seedphrase

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by seedphrase, please enter your seed phrase and click "Import account".&#x20;

You could choose between importing either Substrate (Polkadot) account or EVM (Ethereum) account, or both.&#x20;

{% hint style="info" %}
For each seedphrase created with SubWallet, you would have a Substrate account and an EVM account.&#x20;

Substrate account would display your assets on Substrate-native blockchains (such as Polkadot, Kusama, Acala), while EVM account would display your assets on EVM chains (such as Moonbeam).&#x20;
{% endhint %}

![](<../../.gitbook/assets/image (98).png>)

In some cases, if you import account by seedphrase, problems can arise if the seedphrase of your original wallet is not compatible with SubWallet.&#x20;

{% hint style="info" %}
Trust Wallet and Safepal are among the wallets not compatible with us.&#x20;
{% endhint %}

In this case, we would suggest you create a new wallet account with SubWallet and transfer your assets from your original wallet to this new account.&#x20;

After importing the new account into the wallet, you might want to change the account name. Please follow this [guide](switch-between-accounts-and-change-account-name.md).

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](../customize-your-networks.md) to enable the networks you want to use.

Ethereum network will be automatically turned on for EVM accounts.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.&#x20;
{% endhint %}

## Import by private key (currently supported with EVM account)

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by private key, please enter your  private key and click "Import account".

![](<../../.gitbook/assets/image (127).png>)

After importing the new account into the wallet, you might want to change the account name. Please follow this [guide](switch-between-accounts-and-change-account-name.md).

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](../customize-your-networks.md) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.
{% endhint %}

## Import from Polkadot {js} (Import by JSON file)

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by JSON backup file:

**Step 1**: Click on the import field to choose file from your device, or drag and drop your JSON backup file to import.

![](<../../.gitbook/assets/image (10) (1) (2) (1) (1).png>)

**Step 2**: Enter your JSON file password (created when you set up the wallet for the first time) and click "Import from JSON file".&#x20;

![](<../../.gitbook/assets/image (298).png>)

{% hint style="info" %}
Please note that if you want to import multiple accounts simultaneously from a JSON file, you are required to enter the password for each account you want to import.
{% endhint %}

After importing the new account into the wallet, you might want to change the account name. Please follow this [guide](switch-between-accounts-and-change-account-name.md).

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](../customize-your-networks.md) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.
{% endhint %}

## Import by QR code

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by QR code, please present your QR code back-up of your account's private key and scan this QR code with your current device.&#x20;



**Step 1**: Click the "Scan the QR code" button.

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F2zseowhOCGE5xsJFb2z5%2Fuploads%2FaegDNDckWS5Pm0iHXNzy%2FScreenshot\_20.png?alt=media\&token=730ceed9-3975-4f66-b14f-4f3e03fd83f0)

{% hint style="info" %}
Please note that you would need to grant the SubWallet extension the permission to use your camera in order to import by QR code. If you have not yet granted this permission, SubWallet would show the following message:

![](<../../.gitbook/assets/image (29) (2).png>)\
\
Click "Go to Setting" button. You would be directed to our security settings screen. Please switch the toggle and approve the browser pop-up to enable camera access.

![](<../../.gitbook/assets/image (99).png>) ![](<../../.gitbook/assets/image (39) (2).png>)
{% endhint %}

{% hint style="info" %}
If you use Brave browser, there will be multiple options that allow us to access the camera for different durations. You can choose the time option that best fits your personal preferences. However, to ensure a seamless experience with our system, we recommend selecting the "forever" option.

![](<../../.gitbook/assets/image (38) (1).png>)
{% endhint %}



**Step 2**: Present your QR code and scan with SubWallet, using your device's camera.&#x20;

<div align="left">

<figure><img src="../../.gitbook/assets/image (303).png" alt="" width="290"><figcaption></figcaption></figure>

</div>

<div align="left">

<figure><img src="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F2zseowhOCGE5xsJFb2z5%2Fuploads%2Fo0LyV3teoGd7K13E4p9S%2Fimage.png?alt=media&#x26;token=487b39c8-2c48-4c67-a496-897714b2549e" alt="" width="375"><figcaption></figcaption></figure>

</div>

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

![](<../../.gitbook/assets/image (22) (1).png>)\


**Step 2**: Choose "Security settings".

![](<../../.gitbook/assets/image (296).png>)\
\
**Step 3**: Disable the toggle next to the "Allow camera access" option.&#x20;

![](<../../.gitbook/assets/image (297).png>)
{% endhint %}
