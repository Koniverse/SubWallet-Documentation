---
description: Hassle-free transfer tokens using bridges integrated into SubWallet.
---

# Transfer tokens via bridges

## Supported bridges

### 1. Supported tokens & channels

Currently, SubWallet supports these bridges to help you transfer tokens in-app directly:

<table><thead><tr><th width="260">Bridge</th><th>Supported tokens &#x26; channels</th></tr></thead><tbody><tr><td>Polkadot &#x3C;> Kusama Bridge</td><td><ul><li>DOT (Polkadot Asset Hub &#x3C;> Kusama Asset Hub)</li><li>KSM (Polkadot Asset Hub &#x3C;> Kusama Asset Hub)</li></ul></td></tr><tr><td>Snowbridge</td><td><ul><li>WBTC (Polkadot Asset Hub &#x3C;> Ethereum)</li><li>WETH (Polkadot Asset Hub &#x3C;> Ethereum)</li></ul></td></tr><tr><td>Avail Bridge<sup>1</sup></td><td><ul><li>AVAIL (Avail &#x3C;> Ethereum)</li><li>AVAIL Turing (Avail Turing Testnet &#x3C;> Ethereum Sepolia)</li></ul></td></tr><tr><td>Unified Bridge<sup>2</sup></td><td><ul><li>ETH (Ethereum &#x3C;> Polygon zkEVM)</li></ul></td></tr><tr><td>Polygon PoS Bridge</td><td><ul><li>ETH (Ethereum -> Polygon)</li><li>WETH (Polygon -> Ethereum)</li></ul></td></tr><tr><td>Across Bridge</td><td><ul><li>ETH (across 10+ networks)</li><li>WETH (across 10+ networks)</li></ul></td></tr></tbody></table>

{% hint style="info" %}
More bridges & channels will be supported soon!
{% endhint %}

<sup>_1_</sup>_&#x20;Once you initiate the transaction, you need to wait for the funds to reach the destination network. After that, you must manually claim the funds to complete the transaction._

<sup>_2_</sup>_&#x20;Once you initiate the transaction from Ethereum to Polygon zkEVM, you need to wait for the funds to arrive at Polygon zkEVM to complete the transaction. In the opposite channel, besides waiting, you need to claim the funds manually on Ethereum to complete the transaction._

### 2. Bridging time

<table><thead><tr><th width="359">Channel</th><th width="167.3333740234375">Normal bridging time</th><th>Maximum bridging time</th></tr></thead><tbody><tr><td><p>WBTC (Polkadot Asset Hub &#x3C;> Ethereum)<sup>1</sup></p><p>WETH (Polkadot Asset Hub &#x3C;> Ethereum)<sup>1</sup></p></td><td>20 - 60 minutes</td><td>2 hours</td></tr><tr><td>AVAIL (Avail → Ethereum)<sup>2</sup></td><td>30 - 40 minutes </td><td>90 minutes</td></tr><tr><td>AVAIL (Ethereum → Avail)<sup>2</sup></td><td>75 minutes</td><td>90 minutes</td></tr><tr><td>ETH (Ethereum → Polygon zkEVM)<sup>1</sup></td><td>30 minutes</td><td>40 minutes</td></tr><tr><td>ETH (Polygon zkEVM → Ethereum)</td><td>2 hours 30 minutes</td><td>3 hours</td></tr><tr><td><p>ETH (Ethereum -> Polygon)<sup>1</sup></p><p>WETH (Polygon -> Ethereum)<sup>1</sup></p></td><td>22 minutes</td><td>30 minutes</td></tr><tr><td>Across Bridge</td><td>Instant</td><td>Instant</td></tr></tbody></table>

<sup>_1_</sup>_&#x20;No token claiming is required for this channel._

<sup>_2_</sup> _The same applies to its testnet channel._

## Transfer your tokens via Avail Bridge & Unified Bridge

{% hint style="info" %}
With these bridges, except for the ETH transfer from Ethereum to Polygon zkEVM, you must claim the funds on the destination network to complete the transaction.
{% endhint %}

### Transfer tokens to the destination network

**Step 1**: On the SubWallet homepage, click the "**Send**" button at the upper right corner of the screen.

<figure><img src="../../../.gitbook/assets/image (2417).png" alt=""><figcaption></figcaption></figure>

The Transfer screen will popup on the right side.

<figure><img src="../../../.gitbook/assets/image (2418).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
If you are in Single-account mode, make sure the account you initially chose is not watch-only.
{% endhint %}

**Step 2:** Enter the required information in the corresponding fields.

<figure><img src="../../../.gitbook/assets/image (2422).png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
First, you will need to select the token you want to transfer and the destination network to which you want your tokens transferred.

<figure><img src="../../../.gitbook/assets/image (2419).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (2420).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Next, select the recipient address and the amount you want to transfer.

<figure><img src="../../../.gitbook/assets/image (2421).png" alt=""><figcaption></figcaption></figure>

In the "**To**" field, you can select one account from the account list or paste a valid address.

{% hint style="info" %}
With this type of transfer, you can select the same account for both the sender and recipient.
{% endhint %}

{% hint style="info" %}
From version v1.3.3 onwards, we have introduced a new feature: **Advanced address detection**.

This feature, when enabled, will allow you to enter any Substrate-based address for transactions. This means you are no longer restricted to using only the fixed addresses from your account list; for example, you can input an Acala address as the recipient address when transferring VARA tokens rather than just using the VARA address.

{% hint style="warning" %}
However, we strongly recommend not using this feature if you aren't an expert in transactions on the Polkadot ecosystem, as transferring to the wrong address will result in loss of funds.
{% endhint %}

![](<../../../.gitbook/assets/image (2381).png>) ![](<../../../.gitbook/assets/image (2382).png>)
{% endhint %}
{% endstep %}
{% endstepper %}

<details>

<summary>If you are in the "All accounts" mode</summary>

In this case, in addition to the above information, you will also need to choose the sender's address.

<figure><img src="../../../.gitbook/assets/image (2378).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (2379).png" alt=""><figcaption></figcaption></figure>

</details>

{% hint style="warning" %}
Note that transferring tokens cross-chain to a centralized exchange (CEX) address will result in loss of funds. This is because these CEXs may not recognize or properly credit deposits made to their wallet addresses.

![](https://docs.subwallet.app/main/~gitbook/image?url=https%3A%2F%2F631687399-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lh39Kwxa1xxZM9WX_Bs%252Fuploads%252FvIiUHFDKXryYf901qdk0%252FScreenshot_39.png%3Falt%3Dmedia%26token%3D10fd8b1e-9cb0-4cfc-85c7-f93b00d2fd8d\&width=300\&dpr=4\&quality=100\&sign=5e6fa971\&sv=2)

If you face this situation, it is recommended that you contact their support team as soon as possible.
{% endhint %}

Below is the complete transfer request. Once done, click "**Transfer**".

<figure><img src="../../../.gitbook/assets/image (2423).png" alt=""><figcaption></figcaption></figure>

**Step 3**: Read the popup message carefully, then click "**Continue**" to proceed.

<figure><img src="../../../.gitbook/assets/image (2424).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
The cross-chain transaction on Avail & Unified Bridge can take 30 to 75 minutes for the tokens to arrive at the destination network, depending on the bridge's status. Transfer at your own risk!
{% endhint %}

**Step 4**: Check your transaction details, then click "**Approve**" to proceed.&#x20;

<figure><img src="../../../.gitbook/assets/image (2425).png" alt=""><figcaption></figcaption></figure>

**Step 5**: Your transaction request has been submitted!

<figure><img src="../../../.gitbook/assets/image (2426).png" alt=""><figcaption></figcaption></figure>

You can either click "**Back to home**" to return to the homepage or "**View transaction**" to see transaction details in the History tab.

{% hint style="info" %}
If you click "**View transaction**", SubWallet will display the latest transaction record in your transaction history, along with the extrinsic hash of the transfer.&#x20;

![](<../../../.gitbook/assets/image (2427).png>)
{% endhint %}

{% hint style="warning" %}
Please note that although the transaction status indicates "Completed", this simply means that the tokens are being transferred to the destination network. To complete this transaction, you must manually claim the funds on that network.
{% endhint %}

### Claim tokens on the destination network

{% hint style="info" %}
If you transfer ETH from Ethereum to Polygon zkEVM, you won't need to follow the steps below, as the tokens will be credited to the destination network after the bridging time ends.
{% endhint %}

**Step 6**: On the SubWallet homepage, click on the <img src="../../../.gitbook/assets/Screenshot_287 (1).png" alt="" data-size="line"> button at the top right of the screen.

<figure><img src="../../../.gitbook/assets/image (2409).png" alt=""><figcaption></figcaption></figure>

In the Notifications screen, look for the notification related to claiming bridged tokens, and then click on it.

<figure><img src="../../../.gitbook/assets/image (2410).png" alt=""><figcaption></figcaption></figure>

**Step 7**: A popup screen will appear on the right side. Click "**Continue**" to proceed.

<figure><img src="../../../.gitbook/assets/image (2416).png" alt=""><figcaption></figcaption></figure>

**Step 8**: Check your transaction details, then click "**Approve**" to proceed.

**Step 9**: Your transaction has been submitted!

<figure><img src="../../../.gitbook/assets/Screenshot_29 (2).png" alt="" width="363"><figcaption></figcaption></figure>

You can either click "**Back to home**" to return to the homepage or "**View transaction**" to see transaction details in the History tab.

{% hint style="info" %}
If you click "**View transaction**", SubWallet will display the latest transaction record in your transaction history, along with the extrinsic hash of the transfer.&#x20;

<img src="../../../.gitbook/assets/Screenshot_296.png" alt="" data-size="original">
{% endhint %}
