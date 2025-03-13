---
description: Hassle-free transfer tokens using bridges integrated into SubWallet.
---

# Transfer tokens via bridges

## Supported bridges

### 1. Supported tokens & channels <a href="#id-1.-supported-tokens-and-channels" id="id-1.-supported-tokens-and-channels"></a>

Currently, SubWallet supports these bridges to help you transfer tokens in-app directly:

<table><thead><tr><th width="287">Bridge</th><th>Supported tokens &#x26; channels</th></tr></thead><tbody><tr><td>Polkadot &#x3C;> Kusama Bridge</td><td><ul><li>DOT (Polkadot Asset Hub &#x3C;> Kusama Asset Hub)</li><li>KSM (Polkadot Asset Hub &#x3C;> Kusama Asset Hub)</li></ul></td></tr><tr><td>Snowbridge</td><td><ul><li>WBTC (Polkadot Asset Hub &#x3C;> Ethereum)</li><li>WETH (Polkadot Asset Hub &#x3C;> Ethereum)</li><li>MYTH (Polkadot Asset Hub &#x3C;> Ethereum)</li></ul></td></tr><tr><td>Avail Bridge*</td><td><ul><li>AVAIL (Avail &#x3C;> Ethereum)</li><li>AVAIL Turing (Avail Turing Testnet &#x3C;> Ethereum Sepolia)</li></ul></td></tr><tr><td>Unified Bridge**</td><td><ul><li>ETH (Ethereum &#x3C;> Polygon zkEVM</li></ul></td></tr><tr><td>Polygon PoS Bridge</td><td><ul><li>ETH (Ethereum -> Polygon)</li><li>WETH (Polygon -> Ethereum)</li></ul></td></tr></tbody></table>

{% hint style="info" %}
More bridges & channels will be supported soon!
{% endhint %}

_(\*): Once you initiate the transaction, you need to wait for the funds to reach the destination network. After that, you must manually claim the funds to complete the transaction._

_(\*\*): Once you initiate the transaction from Ethereum to Polygon zkEVM, you need to wait for the funds to arrive at Polygon zkEVM to complete the transaction. In the opposite channel, besides waiting, you need to claim the funds manually on Ethereum to complete the transaction._

### 2. Bridging time <a href="#id-2.-bridging-time" id="id-2.-bridging-time"></a>

<table><thead><tr><th width="359">Channel</th><th width="189">Normal bridging time</th><th width="202">Maximum bridging time</th></tr></thead><tbody><tr><td><p>WBTC (Polkadot Asset Hub &#x3C;> Ethereum)*</p><p>WETH (Polkadot Asset Hub &#x3C;> Ethereum)*</p><p>MYTH (Polkadot Asset Hub &#x3C;> Ethereum)*</p></td><td>20 - 60 minutes</td><td>2 hours</td></tr><tr><td>AVAIL (Avail → Ethereum)**</td><td>30 - 40 minutes</td><td>90 minutes</td></tr><tr><td>AVAIL (Ethereum → Avail)**</td><td>75 minutes</td><td>90 minutes</td></tr><tr><td>ETH (Ethereum → Polygon zkEVM)*</td><td>30 minutes</td><td>40 minutes</td></tr><tr><td>ETH (Polygon zkEVM → Ethereum)</td><td>2 hours 30 minutes</td><td>3 hours</td></tr><tr><td><p>ETH (Ethereum -> Polygon)*</p><p>WETH (Polygon -> Ethereum)*</p></td><td>22 minutes</td><td>30 minutes</td></tr></tbody></table>

## Transfer your tokens via Snowbridge

**Step 1**: Open the SubWallet app and tap the "**Send**" button on the homepage.

<figure><img src="../../../.gitbook/assets/Screenshot_1 (24).png" alt="" width="272"><figcaption></figcaption></figure>

You will be directed to the Transfer screen.

<figure><img src="../../../.gitbook/assets/Screenshot_40 (5).png" alt="" width="272"><figcaption></figcaption></figure>

{% hint style="warning" %}
If you are in Single-account mode, make sure the account you initially chose is not watch-only.
{% endhint %}

**Step 2:** Enter the required information in the corresponding fields.

_In this example, we will transfer MYTH tokens on the Polkadot Asset Hub network to the Ethereum network from "Andy 2" to "Andy 1"._

First, select the token you want to transfer by clicking on the top-left field (_in this example, MYTH on Polkadot Asset Hub_).

<div><figure><img src="../../../.gitbook/assets/Screenshot_11 (27).png" alt="" width="272"><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/Screenshot_12 (17).png" alt="" width="272"><figcaption></figcaption></figure></div>

Next, select the destination network (the network you want to transfer tokens to) by clicking on the top-right field.

<div><figure><img src="../../../.gitbook/assets/Screenshot_21 (20).png" alt="" width="272"><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/Screenshot_22 (14).png" alt="" width="272"><figcaption></figcaption></figure></div>

Enter the recipient's address, then hit "**Next**".

<figure><img src="../../../.gitbook/assets/Screenshot_23 (17).png" alt="" width="272"><figcaption></figcaption></figure>

{% hint style="info" %}
With this type of transfer, you can select the same account for both the sender and recipient.
{% endhint %}

{% hint style="warning" %}
Note that transferring tokens cross-chain to a centralized exchange (CEX) address will result in loss of funds. This is because these CEXs may not recognize or properly credit deposits made to their wallet addresses.

![](https://docs.subwallet.app/~gitbook/image?url=https%3A%2F%2F631687399-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lh39Kwxa1xxZM9WX_Bs%252Fuploads%252FvIiUHFDKXryYf901qdk0%252FScreenshot_39.png%3Falt%3Dmedia%26token%3D10fd8b1e-9cb0-4cfc-85c7-f93b00d2fd8d\&width=300\&dpr=4\&quality=100\&sign=5e6fa971\&sv=2)

If you face this situation, it is recommended that you contact their support team as soon as possible.
{% endhint %}

<details>

<summary>If you're in the "All accounts" mode</summary>

In addition to the above information, you will also need to choose the sender's address.

<img src="../../../.gitbook/assets/Screenshot_26 (12).png" alt="" data-size="original">

</details>

**Step 3:** Enter the amount you want to transfer and then hit "**Transfer**".

<figure><img src="../../../.gitbook/assets/Screenshot_24 (12).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 4**: Read the popup message carefully, then click "**Continue**" to proceed.

{% hint style="warning" %}
The cross-chain transaction on Snowbridge usually incurs a high fee and can take 20 minutes to more than 2 hours to complete, depending on the bridge's status. Transfer at your own risk!
{% endhint %}

<figure><img src="../../../.gitbook/assets/Screenshot_25 (17).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 5**: Check your transaction details, then hit "**Approve**" to proceed.

<figure><img src="../../../.gitbook/assets/Screenshot_37 (6).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 6**: Transaction result is in!

<figure><img src="../../../.gitbook/assets/Screenshot_9 (15).png" alt="" width="272"><figcaption></figcaption></figure>

You can select "**Back to home**" to return to the homepage or "**View transaction**" to see transaction details in the History tab.

{% hint style="info" %}
If you press "**View transaction**", SubWallet will show you the latest transaction record in your transaction history along with the extrinsic hash of the transfer.

<img src="../../../.gitbook/assets/Screenshot_39 (6).png" alt="" data-size="original">
{% endhint %}

## Transfer your tokens via Avail Bridge & Unified Bridge

{% hint style="info" %}
With these bridges, except for the ETH transfer from Ethereum to Polygon zkEVM, you must claim the funds on the destination network to complete the transaction.
{% endhint %}

### Transfer tokens to the destination network

**Step 1**: Open the SubWallet app and tap the "**Send**" button on the homepage.

<figure><img src="../../../.gitbook/assets/Screenshot_1 (20).png" alt="" width="272"><figcaption></figcaption></figure>

You will be directed to the Transfer screen.

{% hint style="warning" %}
If you are in Single-account mode, make sure the account you initially chose is not watch-only.
{% endhint %}

**Step 2:** Enter the required information in the corresponding fields.

_In this example, we will transfer AVAIL Turing tokens on the Avail Turing testnet network to the Ethereum Sepolia network within account "Andy 1"._

First, select the token you want to transfer by clicking on the top-left field.

<div><figure><img src="../../../.gitbook/assets/Screenshot_29 (11).png" alt="" width="272"><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/Screenshot_31 (12).png" alt="" width="272"><figcaption></figcaption></figure></div>

Next, select the destination network (the network you want to transfer tokens to) by pressing the top-right field.

<div><figure><img src="../../../.gitbook/assets/Screenshot_32 (7).png" alt="" width="272"><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/Screenshot_33 (8).png" alt="" width="272"><figcaption></figcaption></figure></div>

Enter the recipient's address, then hit "**Next**".

<figure><img src="../../../.gitbook/assets/Screenshot_34 (9).png" alt="" width="272"><figcaption></figcaption></figure>

<details>

<summary>If you're in the "All accounts" mode</summary>

In addition to the above information, you will also need to choose the sender's address

</details>

**Step 3:** Enter the amount you want to transfer and then hit "**Transfer**".

<figure><img src="../../../.gitbook/assets/Screenshot_35 (6).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 4**: Read the popup message carefully, then click "**Continue**" to proceed.

{% hint style="warning" %}
Depending on the bridge's status, the cross-chain transaction on Avail Bridge can take 30 to 75 minutes for the tokens to arrive at the destination network. Transfer at your own risk!
{% endhint %}

<figure><img src="../../../.gitbook/assets/Screenshot_36 (6).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 5**: Check your transaction details, then hit "**Approve**" to proceed.

<figure><img src="../../../.gitbook/assets/Screenshot_37 (7).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 6**: Transaction result is in!

<figure><img src="../../../.gitbook/assets/Screenshot_38 (7).png" alt="" width="272"><figcaption></figcaption></figure>

You can select "**Back to home**" to return to the homepage or "**View transaction**" to see transaction details in the History tab.

{% hint style="info" %}
If you press "**View transaction**", SubWallet will show you the latest transaction record in your transaction history along with the extrinsic hash of the transfer.

<img src="../../../.gitbook/assets/Screenshot_39 (7).png" alt="" data-size="original">
{% endhint %}

### Claim tokens on the destination network

{% hint style="info" %}
If you transfer ETH from Ethereum to Polygon zkEVM, you won't need to follow the steps below, as the tokens will be credited to the destination network after the bridging time ends.
{% endhint %}

**Step 7**: On the SubWallet homepage, tap the <img src="https://docs.subwallet.app/~gitbook/image?url=https%3A%2F%2F631687399-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lh39Kwxa1xxZM9WX_Bs%252Fuploads%252FABMVKpycPXFreIIe1LiG%252FScreenshot_287.png%3Falt%3Dmedia%26token%3D32cba28e-5292-496a-87d7-1fa00c0a8979&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=d2eee267&#x26;sv=2" alt="" data-size="line"> button at the top right of the screen.

<figure><img src="../../../.gitbook/assets/Screenshot_1 (21).png" alt="" width="272"><figcaption></figcaption></figure>

In the Notifications screen, look for the notification related to claiming bridged tokens, then click on that notification.

<figure><img src="../../../.gitbook/assets/Screenshot_2 (21).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 8**: You will be directed to the Claim tokens screen. Press "**Continue**" to proceed.

<figure><img src="../../../.gitbook/assets/Screenshot_3 (26).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 9**: Check your transaction details, then hit "**Approve**" to proceed.

<figure><img src="../../../.gitbook/assets/Screenshot_4 (19).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 10**: Your transaction has been submitted!

<figure><img src="../../../.gitbook/assets/Screenshot_5 (19).png" alt="" width="272"><figcaption></figcaption></figure>

You can either click "**Back to home**" to return to the homepage or "**View transaction**" to see transaction details in the History tab.

{% hint style="info" %}
If you click "**View transaction**", SubWallet will show you the latest transaction record in your transaction history along with the extrinsic hash of the transfer.

<img src="../../../.gitbook/assets/Screenshot_22 (15).png" alt="" data-size="original">
{% endhint %}
