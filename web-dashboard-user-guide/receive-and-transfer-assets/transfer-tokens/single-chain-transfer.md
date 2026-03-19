---
description: >-
  Single-chain token transfer keeps it simple—move your tokens between accounts
  in the same network.
---

# Single-chain transfer

{% hint style="info" %}
"**Single-chain transfer**" refers to the process of transferring tokens within the same network.
{% endhint %}

**Step 1**: On the SubWallet homepage, click the "**Send**" button at the upper right corner of the screen.

<figure><img src="../../../.gitbook/assets/image (2374).png" alt=""><figcaption></figcaption></figure>

The Transfer screen will popup on the right side.

<figure><img src="../../../.gitbook/assets/image (2375).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
If you are in Single-account mode, make sure the account you initially chose is not watch-only.
{% endhint %}

**Step 2:** Enter the required information in the corresponding fields. That includes:

* The token you want to transfer
* The recipient address
* The amount you want to transfer

In the "**To**" field, you can select one account from the account list or paste a valid address.

<figure><img src="../../../.gitbook/assets/image (2376).png" alt=""><figcaption></figcaption></figure>

<details>

<summary>If you are in the "All accounts" mode</summary>

In this case, in addition to the above information, you will also need to choose the sender's address.

<figure><img src="../../../.gitbook/assets/image (2378).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (2379).png" alt=""><figcaption></figcaption></figure>

</details>

{% hint style="info" %}
From version v1.3.3 onwards, we have introduced a new feature: **Advanced address detection**.

This feature, when enabled, will allow you to enter any Substrate-based address for transactions. This means you are no longer restricted to using only the fixed addresses from your account list; for example, you can input an Acala address as the recipient address when transferring VARA tokens rather than just using the VARA address.

{% hint style="warning" %}
However, we strongly recommend not using this feature if you aren't an expert in transactions on the Polkadot ecosystem, as transferring to the wrong address will result in loss of funds.
{% endhint %}

![](<../../../.gitbook/assets/image (2381).png>) ![](<../../../.gitbook/assets/image (2382).png>)
{% endhint %}

<details>

<summary>Customize gas fee for EVM transactions</summary>

{% hint style="info" %}
With EVM networks, high traffic can result in slower transaction processing times. As a result, the optimal transaction fee required to incentivize miners to validate transactions may fluctuate based on changes in network usage and conditions.
{% endhint %}

From version v1.3.24, SubWallet allows you to customize the transaction fee for transactions performed on any EVM network. This means you can set the fee amount to whatever you desire rather than being limited to a fixed fee, as in previous versions.

To customize the fee, once you input the needed information, click the <img src="../../../.gitbook/assets/Screenshot_67.png" alt="" data-size="line"> in the "**Estimated fee**" field. In the Edit fee popup, you can select between 3 fee options: "**Low**", "**Medium**", and "**High**". These options are dynamic and offer suggestions based on network congestion during transactions.

Choose the option you prefer.

<figure><img src="../../../.gitbook/assets/image (2383).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (2384).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You can also set your custom fee by selecting the "**Custom**" tab, entering the Max & Priority fees you prefer, and then clicking "**Apply fee**".

<mark style="color:red;">Please note that the Priority fee cannot be higher than the Max fee.</mark>

![](<../../../.gitbook/assets/image (2385).png>) ![](<../../../.gitbook/assets/image (2386).png>)
{% endhint %}

</details>

<details>

<summary>Select a non-native token to pay gas fees for transactions on some Substrate (Polkadot) networks</summary>

{% hint style="success" %}
Currently, SubWallet supports customizing payment tokens for single-chain transactions on these networks:

* **Polkadot Asset Hub** (starting from version 1.3.18)
* **Kusama Asset Hub** (starting from version 1.3.18)
* **Hydration** (starting from version 1.3.24)

Instead of requiring native tokens to cover gas fees, you now have a variety of tokens to choose from for this fee.
{% endhint %}

To customize the payment token, once you input the required information, click the <img src="../../../.gitbook/assets/Screenshot_67.png" alt="" data-size="line"> in the "**Estimated fee**" field. Select any tokens you have balances to pay the gas fee.

<figure><img src="../../../.gitbook/assets/image (2387).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (2388).png" alt=""><figcaption></figcaption></figure>

</details>

Below is the complete transfer request. Once done, click "**Transfer**".

<figure><img src="../../../.gitbook/assets/image (2389).png" alt=""><figcaption></figcaption></figure>

**Step 3**: Check your transaction details, then click "**Approve**" to proceed.&#x20;

<figure><img src="../../../.gitbook/assets/image (2390).png" alt=""><figcaption></figcaption></figure>

**Step 4**: Your transaction request has been submitted!

<figure><img src="../../../.gitbook/assets/image (2391).png" alt=""><figcaption></figcaption></figure>

You can either click "**Back to home**" to return to the homepage or "**View transaction**" to see transaction details in the History tab.

{% hint style="info" %}
If you click "**View transaction**", SubWallet will show you the latest transaction record in your transaction history along with the extrinsic hash of the transfer.&#x20;

![](<../../../.gitbook/assets/image (2392).png>)
{% endhint %}
