---
description: Effortlessly send tokens across networks on SubWallet.
---

# Cross-chain transfer

{% hint style="info" %}
"**Cross-chain transfer**" refers to the process of transferring tokens between different networks for enhanced collaboration and decentralized exchange.
{% endhint %}

**Step 1**: On the SubWallet homepage, click the "**Send**" button at the upper right corner of the screen.

<figure><img src="../../../.gitbook/assets/image (2374).png" alt=""><figcaption></figcaption></figure>

The Transfer screen will popup on the right side.

<figure><img src="../../../.gitbook/assets/image (2375).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
If you are in Single-account mode, make sure the account you initially chose is not watch-only.
{% endhint %}

**Step 2:** Enter the required information in the corresponding fields.

<figure><img src="../../../.gitbook/assets/image (2393).png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
First, you will need to select the token you want to transfer and the destination network to which you want your tokens transferred.

<figure><img src="../../../.gitbook/assets/image (2394).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (2395).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Next, select the recipient address and the amount you want to transfer.

<figure><img src="../../../.gitbook/assets/image (2396).png" alt=""><figcaption></figcaption></figure>

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

<figure><img src="../../../.gitbook/assets/image (2397).png" alt=""><figcaption></figcaption></figure>

**Step 3**: Check your transaction details, then click "**Approve**" to proceed.&#x20;

<figure><img src="../../../.gitbook/assets/image (2398).png" alt=""><figcaption></figcaption></figure>

**Step 4**: Your transaction request has been submitted!

<figure><img src="../../../.gitbook/assets/image (2399).png" alt=""><figcaption></figcaption></figure>

You can either click "**Back to home**" to return to the homepage or "**View transaction**" to see transaction details in the History tab.

{% hint style="info" %}
If you click "**View transaction**", SubWallet will show you the latest transaction record in your transaction history along with the extrinsic hash of the transfer.&#x20;

![](<../../../.gitbook/assets/image (2400).png>)
{% endhint %}
