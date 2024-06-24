---
description: >-
  We round up frequently asked questions, along with their solutions in this
  section. Should any other issues arise, you can always visit us on Discord and
  Telegram.
---

# FAQs

## I want to log off my wallet when I’m not at my computer. Can I do this with SubWallet?

To keep the security of your assets while you are away, you can use the **lock function** of SubWallet. Please follow the instructions [here](getting-started/lock-and-unlock-your-wallet/).

## Where can I get my account address?

Your account address should be visible under your account name. If you cannot see the address, you are likely in the "All accounts" mode. Since an address must go with a specific account, you would need to choose the exact account for which you want to get the address.

To choose an account, click on the account name to get to the account management, select the specific account you want, and the address will be visible.&#x20;

<figure><img src="../.gitbook/assets/image (1950).png" alt="" width="389"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1951).png" alt="" width="394"><figcaption></figcaption></figure>

## I cannot see my assets. What’s the problem?

You can change the endpoint/provider or add a new endpoint/provider by following the instructions [here](customize-endpoint-provider.md).

In case you have changed your provider but still cannot see the asset, you should restart the wallet or check again later. Some providers have slow processing speeds, and sometimes nodes can be unstable. If you need extra support, you can always visit us on [Discord](https://discord.gg/CvVewvApry) and [Telegram](https://t.me/subwallet).

## I imported an account from another wallet, and I cannot see my assets. What is the problem?

Please make sure that you have activated the network on which you have the assets.

In some cases, if you import an account by seedphrase, problems can arise if the seedphrase of your original wallet is not compatible with SubWallet. Trust Wallet and Safepal are among the wallets that are not compatible with us. In this case, we suggest you create a new wallet account with SubWallet and transfer your assets from your original wallet to this new account.&#x20;

To create a new wallet account with SubWallet, please follow the instructions [here](https://docs.subwallet.app/user-guide/create-an-account).&#x20;

To receive assets with a SubWallet account, please follow the instructions [here](receive-and-transfer-assets/receive-tokens-and-nfts.md).

If you need further information, feel free to reach out to us via [Discord](https://discord.gg/CvVewvApry) and [Telegram](https://t.me/subwallet).

## How do I add my USDT/USDC to SubWallet?

Before adding your USDT/USDC, you should select the correct network corresponding to your USDT/USDC in SubWallet.

With **USDT**, SubWallet currently supports a list of the networks below.

* Acala
* Astar
* Astar - EVM
* Bifrost Polkadot
* Calamari
* Parallel
* HydraDX
* Interlay
* Kintsugi
* Pendulum
* Polkadot Asset Hub (Statemint)
* Moonbeam
* Kusama Asset Hub (Statemint)
* Shiden - EVM
* Equilibrium
* Binance Smart Chain
* Ethereum
* Polygon
* Arbitrum One
* Optimism
* Viction
* HydraDX Rococo
* HydraDX

With **USDC**, we support a list of the below networks.

* Calamari
* Moonbeam
* Moonriver
* Astar - EVM
* Shiden - EVM
* Binance Smart Chain
* Ethereum
* Polygon
* Arbitrum One
* Optimism
* Viction
* Polkadot Asset Hub (Statemint)
* HydraDX
* Acala
* Interlay
* Centrifuge
* Ethereum Goerli
* Ethereum Sepolia

## I cannot unstake. What might be the problem?

The unstake feature can be unavailable if you haven't yet withdrawn the amount you have unstaked earlier. Please claim/withdraw the assets you have unstaken before, and you can continue unstaking.

## Where can I withdraw my unstaked amount?

Before withdrawing your unstaked assets, please make sure that you are NOT in All Accounts mode, since this is a read-only mode. Then please follow the instructions for unstaking & withdrawing [here](manage-staking/).&#x20;

## Why did I stake but not receive any rewards?

There are several reasons why you cannot see/receive staking rewards.

1. You might want to double-check the pool/validator you staked in.&#x20;

With **Nomination pool**, you will not be rewarded if your selected pool appears in **Not earning** status. This occurs when either you choose a pool with a Not earning status from the start, or your selected pool is inactive.

An example of a _Not earning nomination pool_ would look like this.

<figure><img src="../.gitbook/assets/image (1940).png" alt="" width="438"><figcaption></figcaption></figure>

With **Direct nomination**, you can go to the [Staking tab on Subscan website](https://polkadot.subscan.io/validator) to check whether your chosen validator is active. Here, we attached a link to the Staking tab on Polkadot network for your example.

<figure><img src="../.gitbook/assets/image (1941).png" alt=""><figcaption></figcaption></figure>

2. Your chosen pool/validator might be slashing. If you were actively nominating that pool/validator when the slash occurred, your stake would get slashed too.
3. If you unstake your chosen pool/validator midway, the staking status will change to unbond, and you will not receive any rewards.
4. You might not see your staking rewards due to UI bugs, even if you actually received them. In this case, please contact us via [Discord](https://discord.gg/CvVewvApry) and [Telegram](https://t.me/subwallet) for support.

## I cannot see my staking rewards

For some networks, there have not been any data indexers to track real-time information about your staking rewards. However, you can observe your balance to know whether or not your staking is paying off. A slight increase in your total balance would be a sign of staking rewards.&#x20;

If you stake with a validator, your staking rewards will be automatically claimed in your wallet. Below are the instructions for checking your rewards in the Rewards History tab.

<figure><img src="../.gitbook/assets/image (1932).png" alt="" width="425"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1918).png" alt="" width="437"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1919).png" alt="" width="434"><figcaption></figcaption></figure>

## My transaction was successful, but I cannot see it in the History tab

In this case, you might want to select the network corresponding to the transactions you made on that network.&#x20;

**Step 1: Check your account**&#x20;

In order to change your account, you can click on the account name to get to the account management screen.&#x20;

<div align="center">

<figure><img src="../.gitbook/assets/image (1957).png" alt="" width="437"><figcaption></figcaption></figure>

</div>

SubWallet supports two types of accounts: EVM and Substrate. We choose a _Substrate account_ for this example.

<div align="center">

<figure><img src="../.gitbook/assets/image (1958).png" alt="" width="431"><figcaption></figcaption></figure>

</div>

**Step 2: Check your network**\
Click on the network name to get to the network management screen.

<div align="center">

<figure><img src="../.gitbook/assets/image (1959).png" alt="" width="437"><figcaption></figcaption></figure>

</div>

A list of networks will appear for you to choose from. We choose the _Polkadot network_ for this example.

<div align="center">

<figure><img src="../.gitbook/assets/image (1960).png" alt="" width="433"><figcaption></figcaption></figure>

</div>

## I cannot see my NFTs

{% hint style="info" %}
&#x20;While SubWallet covers many standard NFTs and Tokens, some may not be supported automatically. If yours are among these, please reach out to us on [Discord](https://discord.gg/CvVewvApry) or [Telegram](https://t.me/subwallet) for assistance.
{% endhint %}

If you don't see your NFTs and Tokens, you can manually import them into SubWallet.

<div align="center">

<figure><img src="../.gitbook/assets/image (1944).png" alt="" width="434"><figcaption></figcaption></figure>

</div>

<div align="center">

<figure><img src="../.gitbook/assets/image (1945).png" alt="" width="434"><figcaption></figcaption></figure>

</div>

In case you have imported your NFTs into SubWallet, it might take some loading time for the wallet to display them. Please wait for a while and check again later.&#x20;

## I cannot see my crowdloans in SubWallet

At the moment, if you participate in crowdloans via third parties, such as [Bifrost Finance](https://bifrost.finance/) and [Parallel Finance](https://parallel.fi/), your crowdloans would not be visible in SubWallet.&#x20;

## I lost my account after a transaction

Before signing a transaction, please make sure that the remaining balance in your account after that transaction is above the existential deposit amount. More information on existential balance can be found [here](https://support.polkadot.network/support/solutions/articles/65000168651-what-is-the-existential-deposit-).

## I cannot use  dApp after connecting dApp with SubWallet extension

This issue can happen if you have multiple extension wallets with your browser. Extension wallets can cause conflict among each other.

We suggest you disable other extension wallets and reconnect SubWallet. If that also does not work, please reach out to us via [Discord](https://discord.gg/CvVewvApry) and [Telegram](https://t.me/subwallet).&#x20;

## What if I mistakenly transfer an unsupported network’s token into my Ledger account?

{% hint style="info" %}
Which situation does this user guide refer to?

When a user attaches a Ledger account to any hot wallet and chooses to connect a Substrate network (aka Polkadot SDK network such as Polkadot, Kusama, etc.), all the actions users can execute are only limited to the chosen network. For example, if a user chooses to connect Polkadot network, this user can only see the balance of DOT and make transactions on the Polkadot network.\
\
For some reason, users can mistakenly send different tokens to the chosen Substrate network. To illustrate, when a user sends his/her CFG tokens to his/her Ledger account on Polkadot network, these tokens can not be displayed and as a result, they can not be used for any kind of transactions, either. (Including token transfer, staking, etc)\
\
In this FAQ, we will demonstrate the case where CFG is mistakenly transferred to a Ledger account currently on Polkadot and How you can withdraw it using our tool.&#x20;
{% endhint %}

{% hint style="info" %}
Note: This method also applies to the following networks: Acala, Ajuna Network, Aleph Zero, Astar, Bifrost (Polkadot), Bifrost (Kusama), Centrifuge, Composable Finance, Darwinia2, Dock, Edgeware, Equilibrium, Genshiro, HydraDX, Interlay, Karura, Khala, Kusama, Nodle, OriginTrail, Parallel, Pendulum, Phala, Picasso, Polkadex, Polkadot, Polymesh Mainnet, QUARTZ by UNIQUE, AssetHub (Polkadot), AssetHub (Kusama), Ternoa, Unique Network, Zeitgeist, and SORA.
{% endhint %}



**Step 1: Download the tool from this** [**link**](https://github.com/Koniverse/Ledger-Account-Recovery-Tool/releases)

<figure><img src="../.gitbook/assets/image (1920).png" alt=""><figcaption></figcaption></figure>

**Step 2: Turn off your internet connection**

**Step 3: Extract the folder from the downloaded zip file and open index.html**

<figure><img src="../.gitbook/assets/image (1961).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1962).png" alt=""><figcaption></figcaption></figure>

**Step 4: Open the file in a browser**

We use _Chrome_ for this example.

<figure><img src="../.gitbook/assets/image (1926).png" alt=""><figcaption></figcaption></figure>

**Step 5: Select the network of the Ledger account, enter the seed phrase, and account address**

<figure><img src="../.gitbook/assets/image (1927).png" alt=""><figcaption></figcaption></figure>

**Step 6: Click Export JSON file, and create a strong password to protect the JSON file**

<figure><img src="../.gitbook/assets/Untitled.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1928).png" alt="" width="427"><figcaption></figcaption></figure>

**Step 7: Import the JSON file into SubWallet and recover the funds by sending all tokens to another account**

You can see how to import the JSON file into SubWallet [here](account-management/import-and-restore-an-account.md).

<figure><img src="../.gitbook/assets/image (1929).png" alt="" width="433"><figcaption></figcaption></figure>

The imported account will have the name "Ledger Recovery".

<figure><img src="../.gitbook/assets/image (1931).png" alt="" width="428"><figcaption></figcaption></figure>

Then, you send all your tokens to another account. You can follow the instructions [here](receive-and-transfer-assets/transfer-tokens/) to transfer all your assets to another account.

That's how you can recover the tokens you mistakenly transferred to an unsupported network in your Ledger account. Should any issues arise, please reach out to us via [Discord](https://discord.gg/CvVewvApry) and [Telegram](https://t.me/subwallet).&#x20;

## I see the "Connection unsuccessful" pop-up when connecting to dApp via WalletConnect.

In this case, please try re-connecting WalletConnect again using 1 of the 2 options below:

#### **Option 1: Get the latest connection on WalletConnect and re-connect**

**Step 1**: Open the dApp you want to connect and choose “WalletConnect”.

Here, we are using Galxe as an example.

<figure><img src="../.gitbook/assets/Screenshot_48.png" alt=""><figcaption></figcaption></figure>

**Step 2**: Get the latest connection from the WalletConnect pop-up by selecting your preferred way to connect.

{% hint style="info" %}
Here, there will be 2 ways to connect your wallet:

* Save the QR code and use it to connect.
* Copy the URI link by clicking the copy icon and use it to connect.

<img src="../.gitbook/assets/Screenshot_49.png" alt="" data-size="original">
{% endhint %}

**Step 3**: Open the SubWallet extension, go to Settings, choose WalletConnect, then select “New Connection”.

#### **Option 2: Check the VPN connection and repeat the process as in Option 1**

{% hint style="info" %}
WalletConnect connection access can be restricted/blocked in some countries, as stated in Section (C) of [WalletConnect's Terms of Service](https://walletconnect.com/terms). As a result, before connecting dApp via WalletConnect, please ensure the VPN connection is not connected to the servers of these countries.

Once done, you can repeat the process as in Option 1.
{% endhint %}

## I need to connect to a dApp, but it doesn't have a SubWallet option to connect.

To connect to a dApp that does not have a SubWallet wallet option, you can connect via WalletConnect using this [guide](https://docs.subwallet.app/main/extension-user-guide/connect-dapps-and-manage-website-access/connect-dapp-with-walletconnect).

If there is no WalletConnect option, please suggest it to us so we can work on integrating it as soon as possible.

## I can’t send tokens. The pop-up message says “Transaction failed” / “Cannot get balance”.

When you receive these messages, please do the following:

**Step 1**: On the SubWallet homepage, click on the list item at the upper left corner to get to the Settings section.

<figure><img src="../.gitbook/assets/Screenshot_50.png" alt="" width="294"><figcaption></figcaption></figure>

**Step 2**: In the Settings section, choose "Manage networks".

<figure><img src="../.gitbook/assets/Screenshot_51.png" alt="" width="293"><figcaption></figcaption></figure>

**Step 3**: Search for the network that supports your token to check the network connection.&#x20;

If the connect icon is yellow/grey → You need to turn off the network and enable it back or [change to another provider](customize-endpoint-provider.md) to restore the network connection.&#x20;

If it still doesn’t work (due to all the RPCs not working at that moment), please come back another time and try again.

## It kept loading forever and showed no information whenever I tried to open the SubWallet extension on the Firefox/Microsoft Edge browser.

The reason it happened is that you have not yet enabled the configuration to display WebGL images (3D images) in the browser.

To enable configuration in Firefox/Chrome/Microsoft Edge, please follow the instructions [here](https://help.constructiononline.com/en/scheduling-webgl-and-hardware-acceleration).

## How can I import my Metamask account (or other wallet accounts) onto the SubWallet extension?

SubWallet offers a variety of options for importing accounts from other wallets to SubWallet.

You can import a Metamask account onto the SubWallet extension using the [Import by private key](https://docs.subwallet.app/main/extension-user-guide/account-management/import-and-restore-an-account#import-by-private-key-currently-supported-with-evm-account) option, in which the private key is exported from the account.

In addition, SubWallet also supports the following methods:

* [Import by seed phrase](https://docs.subwallet.app/main/extension-user-guide/account-management/import-and-restore-an-account#import-from-seed-phrase) (if you have a seed phrase)
* [Import by JSON file](https://docs.subwallet.app/main/extension-user-guide/account-management/import-and-restore-an-account#import-from-polkadot-js-import-by-json-file)
* [Import by QR code](https://docs.subwallet.app/main/extension-user-guide/account-management/import-and-restore-an-account#import-by-qr-code).

## I can’t export the seed phrase of my account.

The “**Export seed phrase**” feature is only available for accounts:

* Imported onto the SubWallet extension by seed phrase after the release of [version v1.0.3](https://github.com/Koniverse/SubWallet-Extension/releases/tag/v1.0.3) **OR**
* Created on the SubWallet extension after the release of [version v1.0.3](https://github.com/Koniverse/SubWallet-Extension/releases/tag/v1.0.3).

## I forgot the password to open my wallet.

SubWallet does not store any copy of your password. If you don't remember your password, you will need to reset your wallet by re-importing your account.

To reset your wallet, please follow the instructions [here](https://docs.subwallet.app/main/extension-user-guide/getting-started/create-a-master-password/forgot-master-password).

## What is “Derive account”?

“Derive account” is a feature allowing you to create a new account from an original one. With one seed phrase, you can create many different accounts to use.

{% hint style="info" %}
Derivative accounts have the exact seed phrase and different paths.

You can use a derivative account as the original account to make transactions.
{% endhint %}

## Which networks does SubWallet support staking?

Subwallet lets you easily stake your tokens and receive staking rewards by directly nominating validators or joining a nomination pool.

**With the direct nomination staking option, SubWallet is currently supporting the following networks:**

* Polkadot
* Kusama
* Aleph Zero
* Avail
* Vara
* Calamari
* Turing
* Polkadex
* Amplitude
* Bifrost Kusama
* Bifrost Polkadot
* Edgeware
* Ternoa
* Pendulum
* Creditcoin Mainnet
* Kilt
* Astar
* Shiden
* Shibuya
* Moonbeam
* Moonriver

**With the nomination pool staking option, SubWallet is currently supporting the following networks:**

* Polkadot
* Kusama
* Aleph Zero
* Avail
* Vara

## I can't sign transactions via Polkadot Vault on EVM networks.

This is due to the latest update of the Polkadot Vault app, in which Polkadot Vault no longer supports signing transactions for the EVM networks (Moonbeam, Moonriver, Moonbase).

If you have assets on these networks on Polkadot Vault, please follow the steps below to transfer them out of your Polkadot Vault account:

{% hint style="info" %}
In this example, we want to transfer GLMR on Moonbeam out of the account.
{% endhint %}

**Step 1**: On the homepage, click on the Moonbeam Key Set.

<figure><img src="../.gitbook/assets/Screenshot_33.png" alt="" width="376"><figcaption></figcaption></figure>

**Step 2**: Click on the 3-dot icon at the top right of the screen and select the "Share Private Key" option.

<figure><img src="../.gitbook/assets/Screenshot_34.png" alt="" width="374"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot_41.png" alt="" width="374"><figcaption></figcaption></figure>

**Step 3**: Enter your passcode to authorize the action, then choose the "Export Private Key" button.

<figure><img src="../.gitbook/assets/image (1967).png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot_35.png" alt="" width="377"><figcaption></figcaption></figure>

The "Export Private Key" screen will pop up with the QR code of your private key. Screenshot and keep it in a safe place.

<figure><img src="../.gitbook/assets/image (1968).png" alt="" width="375"><figcaption></figcaption></figure>

**Step 4**: Open the SubWallet extension. On the SubWallet homepage, click on the account name at the top left of the screen to get to the account list.

<figure><img src="../.gitbook/assets/Screenshot_63 (1).png" alt="" width="363"><figcaption></figcaption></figure>

**Step 5**: Click the "Import" icon at the bottom of the account list.

<figure><img src="../.gitbook/assets/Screenshot_64.png" alt="" width="368"><figcaption></figcaption></figure>

**Step 6**: Choose the "Import by QR code" option.

<figure><img src="../.gitbook/assets/Screenshot_65.png" alt="" width="366"><figcaption></figcaption></figure>

**Step 7**: Click the "Scan the QR code" button.

<figure><img src="../.gitbook/assets/Screenshot_66.png" alt="" width="366"><figcaption></figcaption></figure>

**Step 8**: If you have not previously granted camera access to SubWallet, please click "OK" to allow.

Then, put your phone (with the QR code of your private key taken in **Step 3**) close to the screen to scan it with SubWallet.

<figure><img src="../.gitbook/assets/Screenshot_67.png" alt="" width="366"><figcaption></figcaption></figure>

**Step 9**: After successfully importing the account, you will be directed to the homepage. You can now transfer your GLMR to another account using the guide [here](https://docs.subwallet.app/main/extension-user-guide/receive-and-transfer-assets/transfer-tokens).

## I can't connect my accounts to any dApps on Firefox. What should I do?
