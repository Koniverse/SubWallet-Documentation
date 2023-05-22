# Import and restore an account

If you have secret phrase (seedphrase), private key, back-up JSON file or QR code you can import/restore your account and manage them with SubWallet.

**Step 1**: Choose the account name to get to your account list

![](<../../.gitbook/assets/image (12) (1).png>)

**Step 2**: In the account list, click the import icon&#x20;

![](<../../.gitbook/assets/image (17) (2).png>)

**Step 3**: Choose your preferred way to import account

![](<../../.gitbook/assets/image (15) (2).png>)



## Import by seedphrase

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by seedphrase, please enter your seed phrase and click "Import account".&#x20;

You could choose between importing either Substrate (Polkadot) account or EVM (Ethereum) account, or both.&#x20;

{% hint style="info" %}
For each seedphrase created with SubWallet, you would have a Substrate account and an EVM account.&#x20;

Substrate account would display your assets on Substrate-native blockchains (such as Polkadot, Kusama, Acala), while EVM account would display your assets on EVM chains (such as Moonbeam).&#x20;
{% endhint %}

![](<../../.gitbook/assets/image (25) (2).png>)

In some cases, if you import account by seedphrase, problems can arise if the seedphrase of your original wallet is not compatible with SubWallet.&#x20;

{% hint style="info" %}
Trust Wallet and Safepal are among the wallets not compatible with us.&#x20;
{% endhint %}

In this case, we would suggest you create a new wallet account with SubWallet and transfer your assets from your original wallet to this new account.&#x20;

After importing the new account into the wallet, you might want to change the account name. Please follow this [guide](broken-reference).

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](broken-reference) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.&#x20;
{% endhint %}

##

## Import by private key (currently supported with EVM account)

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by private key, please enter your  private key and click "Import account".

![](<../../.gitbook/assets/image (1) (1) (2).png>)

Afer importing the new account into the wallet, you might want to change the account name. Please follow this [guide](broken-reference).

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](broken-reference) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.
{% endhint %}

##

## Import by JSON file

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by JSON backup file:

**Step 1**: Click on the import field to choose file from your device, or drag and drop your JSON backup file to import.

![](<../../.gitbook/assets/image (10) (1) (2).png>)

**Step 2**: Enter your master password (created when you set up the wallet for the first time) and click "Import from Json".&#x20;

![](<../../.gitbook/assets/image (23) (1).png>)

Afer importing the new account into the wallet, you might want to change the account name. Please follow this [guide](broken-reference).

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](broken-reference) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.
{% endhint %}

##

## Import by QR code

After following this [guide](broken-reference) to choose your preferred way to import an account, if you want to import by QR code, please present your QR code back-up of your account's private key and scan this QR code with your current device.&#x20;



**Step 1**: Click the "Scan the QR code" button.

![](<../../.gitbook/assets/image (20).png>)

{% hint style="info" %}
Please note that you would need to grant the SubWallet extension the permission to use your camera in order to import by QR code. If you have not yet granted this permission, SubWallet would show the following message:

![](<../../.gitbook/assets/image (7) (3).png>)\
\
Click "Go to Setting" button. You would be directed to our security settings screen. Please switch the toggle to enable camera access.&#x20;

![](<../../.gitbook/assets/image (24) (1).png>)
{% endhint %}



**Step 2**: Present your QR code and scan with SubWallet, using your device's camera.&#x20;

![](<../../.gitbook/assets/image (1) (1).png>) ![](broken-reference)

After the succesful import of your account by QR code, you would be directed to the Homescreen.&#x20;

Afer importing the new account into the wallet, you might want to change the account name. Please follow this [guide](broken-reference).

{% hint style="info" %}
Please note that in order to see your assets after importing your account, your would need to manually enable the networks you want to use & have assets on. Please follow [this instruction](broken-reference) to enable the networks you want to use.

SubWallet automatically enable Polkadot & Kusama networks for Substrate accounts, but you can disable them if you so wish.
{% endhint %}

## Disable your permission for camera access

After importing by QR code, If you want to revoke the permission for SubWallet to use your camera, please go to the Security settings section to do so.

{% hint style="info" %}
**Step 1**: Choose the list icon on the upper left corner of your Homescreen

![](<../../.gitbook/assets/image (22) (1).png>)\


**Step 2**: Choose "Security settings"

![](<../../.gitbook/assets/image (13).png>)\
\
**Step 3**: Disable the toggle next to the "Allow camera access" option.&#x20;

![](<../../.gitbook/assets/image (26).png>)
{% endhint %}
