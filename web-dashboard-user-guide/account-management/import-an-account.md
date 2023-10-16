---
description: This part will show you how to import an account on SubWallet.
---

# Import an account

### If you have not had any accounts with SubWallet

**Step 1:** Open [SubWallet's web dashboard](https://web.subwallet.app/welcome), at the welcome page, choose "Import an account".&#x20;

<figure><img src="../../.gitbook/assets/image (175).png" alt=""><figcaption></figcaption></figure>

**Step 2**: Choose your preferred way to import an existing account.

<figure><img src="../../.gitbook/assets/image (176).png" alt=""><figcaption></figcaption></figure>

**Step 3:** Create a password and click "Continue".

{% hint style="info" %}
Please note that SubWallet is non-custodial, so you would be the only person who knows your password, we cannot help you restore your password once it is lost. Please make sure that your password is well-kept.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (177).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
After creating the password, users will be directed to the step of creating/importing an account using one of the following methods:

[#import-from-seed-phrase](import-an-account.md#import-from-seed-phrase "mention")

[#import-by-metamask-private-key-currently-supported-with-evm-account](import-an-account.md#import-by-metamask-private-key-currently-supported-with-evm-account "mention")

[#import-from-polkadot-js-import-by-json-file](import-an-account.md#import-from-polkadot-js-import-by-json-file "mention")

[#import-by-qr-code](import-an-account.md#import-by-qr-code "mention")
{% endhint %}

### If you have already used SubWallet before

If you have secret phrase (seed phrase), private key, JSON backup file, or QR code you can import/restore your account and manage them with SubWallet.

**Step 1**: Open SubWallet homepage and click on the account name to get to the account management screen.&#x20;

<figure><img src="../../.gitbook/assets/image (178).png" alt=""><figcaption></figcaption></figure>

**Step 2**: In the account management screen, click the import icon.

<figure><img src="../../.gitbook/assets/image (179).png" alt=""><figcaption></figcaption></figure>

**Step 3**: Choose your preferred way to import account.

<figure><img src="../../.gitbook/assets/image (180).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
After creating the password, users will be directed to the step of creating/importing an account using one of the following methods:

[#import-from-seed-phrase](import-an-account.md#import-from-seed-phrase "mention")

[#import-by-metamask-private-key-currently-supported-with-evm-account](import-an-account.md#import-by-metamask-private-key-currently-supported-with-evm-account "mention")

[#import-from-polkadot-js-import-by-json-file](import-an-account.md#import-from-polkadot-js-import-by-json-file "mention")

[#import-by-qr-code](import-an-account.md#import-by-qr-code "mention")
{% endhint %}

## Import from seed phrase

If you want to import from seed phrase, please choose the corresponding way of import in the step above.

At this step, you will enter your seed phrase and click "Import account".&#x20;

You could choose between importing either a Substrate (Polkadot) account or EVM (Ethereum) account, or both.&#x20;

{% hint style="info" %}
For each seed phrase created with SubWallet, you would have a Substrate account and an EVM account.&#x20;

Substrate account would display your assets on Substrate-native blockchains (such as Polkadot, Kusama, and Acala), while EVM account would display your assets on EVM chains (such as Moonbeam).&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/image (181).png" alt=""><figcaption></figcaption></figure>

In some cases, if you import an account by seed phrase, problems can arise if the seed phrase of your original wallet is not compatible with SubWallet.&#x20;

{% hint style="info" %}
Trust Wallet and Safepal are among the wallets not compatible with us.&#x20;
{% endhint %}

In this case, we would suggest you create a new wallet account with SubWallet and transfer your assets from your original wallet to this new account.&#x20;

## Import by (MetaMask) private key (currently supported with EVM account)

After following this [guide](import-an-account.md#if-you-have-not-had-any-accounts-with-subwallet) to choose your preferred way to import an account, if you want to import by private key, please enter your private key and click "Import account".

<figure><img src="../../.gitbook/assets/image (182).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Ethereum network will be automatically turned on for EVM accounts.

SubWallet automatically enables Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.&#x20;
{% endhint %}

## Import from Polkadot {js} (Import by JSON file)

After following this[ guide ](import-an-account.md#if-you-have-not-had-any-accounts-with-subwallet)to choose your preferred way to import an account, if you want to import by JSON backup file:

**Step 1**: Click on the import field to choose a file from your device, or drag and drop your JSON backup file to import.

<figure><img src="../../.gitbook/assets/image (183).png" alt=""><figcaption></figcaption></figure>

**Step 2**: Enter your JSON file password (created when you set up the wallet for the first time) and click "Import account".&#x20;

<figure><img src="../../.gitbook/assets/image (184).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Please note that if you want to import multiple accounts simultaneously from a JSON file, you are required to enter the password for each account you want to import.
{% endhint %}

{% hint style="info" %}
SubWallet automatically enables Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.
{% endhint %}

## Import by QR code

After following this [guide](import-an-account.md#if-you-have-not-had-any-accounts-with-subwallet) to choose your preferred way to import an account, if you want to import by QR code, please present your QR code back-up of your account's private key and scan this QR code with your current device.&#x20;

**Step 1**: Click the "Scan the QR code" button.

<figure><img src="../../.gitbook/assets/image (185).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Please note that you would need to grant SubWallet permission to use your camera in order to import by QR code. If you have not yet granted this permission, SubWallet will show the following message:

![](<../../.gitbook/assets/image (188).png>)\
\
Click the "Go to Setting" button. You will be directed to our security settings screen. Please switch the toggle and approve the browser pop-up to enable camera access.

![](<../../.gitbook/assets/image (189).png>) ![](<../../.gitbook/assets/image (190).png>)
{% endhint %}

{% hint style="info" %}
If you use the Brave browser, there will be multiple options that allow us to access the camera for different durations. You can choose the time option that best fits your personal preferences. However, to ensure a seamless experience with our system, we recommend selecting the "forever" option.

![](<../../.gitbook/assets/image (198).png>)
{% endhint %}



**Step 2**: Present your QR code and scan it with SubWallet, using your device's camera.&#x20;

<figure><img src="../../.gitbook/assets/image (192).png" alt=""><figcaption></figcaption></figure>

After importing your account by QR code successfully, you will be directed to the homepage.&#x20;

{% hint style="info" %}
SubWallet automatically enables Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.
{% endhint %}

## Disable your permission for camera access

After importing by QR code, if you want to revoke the permission for SubWallet to use your camera, please go to the Security settings section to do so.

{% hint style="info" %}
**Step 1**: Open SubWallet homepage, and choose the Settings tab on the sidebar.

![](<../../.gitbook/assets/image (404).png>)\


**Step 2**: Choose "Security settings".

![](<../../.gitbook/assets/image (196).png>)\
**Step 3**: Disable the toggle next to the "Camera access for QR" option.&#x20;

![](<../../.gitbook/assets/image (195).png>)
{% endhint %}
