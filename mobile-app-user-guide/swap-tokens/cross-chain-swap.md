---
description: Easily swap tokens across different networks directly on SubWallet in 1 click.
---

# Cross-chain swap

## Supported swap pairs & swap providers

### Cross-chain swap within the Polkadot ecosystem

<table><thead><tr><th>Swap provider</th><th width="412">Supported swap pair</th></tr></thead><tbody><tr><td><ul><li>SimpleSwap</li></ul></td><td><ul><li>DOT (Polkadot) &#x3C;> TAO (Bittensor)</li></ul></td></tr></tbody></table>

### Cross-chain swap within the Ethereum ecosystem

<table><thead><tr><th>Swap provider</th><th width="413">Supported swap pair</th></tr></thead><tbody><tr><td><ul><li>ChainFlip</li></ul></td><td><ul><li>ETH (Ethereum) &#x3C;> USDC (Arbitrum One)</li><li>USDT (Ethereum) &#x3C;> USDC (Arbitrum One)</li><li>ETH (Arbitrum One) &#x3C;> USDC (Ethereum)</li><li>ETH (Arbitrum One) &#x3C;> USDT (Ethereum)</li><li>FLIP (Ethereum) &#x3C;> ETH (Arbitrum One)</li><li>FLIP (Ethereum) &#x3C;> USDC (Arbitrum One)</li></ul></td></tr></tbody></table>

### Cross-chain swap between Polkadot & Ethereum ecosystem

<table><thead><tr><th>Swap provider</th><th width="413">Supported swap pair</th></tr></thead><tbody><tr><td><ul><li>ChainFlip</li><li>SimpleSwap</li></ul></td><td><ul><li>DOT (Polkadot) &#x3C;> ETH (Ethereum)</li><li>DOT (Polkadot) &#x3C;> USDC (Ethereum)</li><li>DOT (Polkadot) &#x3C;> USDT (Ethereum)</li></ul></td></tr><tr><td><ul><li>ChainFlip</li></ul></td><td><ul><li>DOT (Polkadot) &#x3C;> FLIP (Ethereum)</li><li>DOT (Polkadot) &#x3C;> USDC (Arbitrum One)</li><li>DOT (Polkadot) &#x3C;> ETH (Arbitrum One)</li></ul></td></tr><tr><td><ul><li>SimpleSwap</li></ul></td><td><ul><li>TAO (Bittensor) &#x3C;> ETH (Ethereum)</li><li>TAO (Bittensor) &#x3C;> USDC (Ethereum)</li><li>TAO (Bittensor) &#x3C;> USDT (Ethereum)</li></ul></td></tr></tbody></table>

{% hint style="info" %}
With this type of swap, you can choose to swap your tokens to another account.
{% endhint %}

## Swap tokens

**Step 1**: On the SubWallet app, hit the "**Swap**" button on the homepage.

<figure><img src="../../.gitbook/assets/Screenshot_15 (5).png" alt="" width="267"><figcaption></figcaption></figure>

{% hint style="info" %}
If this is the first time you use this feature, the Terms of service popup will appear. Read carefully, then select "**I understand the associated risk and will act under caution**". After that, click "**Confirm and continue swapping**".

<img src="../../.gitbook/assets/Screenshot_2 (6).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_3 (9).png" alt="" data-size="original">
{% endhint %}

**Step 2**: On the Swap screen, select the token you want to swap and the token you wish to receive.

_In this example, we want to swap DOT (Polkadot) for ETH (Ethereum)._

Select "**DOT (Polkadot)**" as the token you want to swap.

<div><figure><img src="../../.gitbook/assets/Screenshot_16 (6).png" alt="" width="267"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_17 (3).png" alt="" width="268"><figcaption></figcaption></figure></div>

Select "**ETH (Ethereum)**" as the token you wish to receive.

<div><figure><img src="../../.gitbook/assets/Screenshot_18 (4) (1).png" alt="" width="267"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_19 (4).png" alt="" width="267"><figcaption></figcaption></figure></div>

<details>

<summary>If you're in the "All accounts" mode</summary>

In this case, you will need to select the swapping account.

<img src="../../.gitbook/assets/Screenshot_25 (4).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_26 (5).png" alt="" data-size="original">

</details>

Enter the amount you want to swap. Once done, the swap quote (with the related information) will appear. Hit "**Swap**" to proceed.

<figure><img src="../../.gitbook/assets/Screenshot_34 (6).png" alt="" width="267"><figcaption></figcaption></figure>

<details>

<summary>If you want to change the swap provider</summary>

:information\_source: _This feature is available for swap pairs on the Ethereum network._

To do that, hit the "**View swap quote**" button, then continue clicking on the "**View quote**" button.

<img src="../../.gitbook/assets/Screenshot_20 (8).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_21 (10).png" alt="" data-size="original">

In the Swap quotes popup, choose the provider you want for the swap.

<img src="../../.gitbook/assets/Screenshot_22 (3).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_23 (6).png" alt="" data-size="original">

</details>

{% hint style="warning" %}
You cannot change the slippage tolerance with this swap type:

* With ChainFlip, every swap has a fixed slippage tolerance of 2%.
* With SimpleSwap, the slippage tolerance can't be predicted as it varies based on market conditions, but it will never exceed 5%.
{% endhint %}

**Step 3**: Check your transaction details, then click "**Approve**" to proceed.

<figure><img src="../../.gitbook/assets/Screenshot_24 (3).png" alt="" width="267"><figcaption></figcaption></figure>

{% hint style="warning" %}
Swapping via SimpleSwap can take 5 to 60 minutes, depending on the market conditions.
{% endhint %}

**Step 4**: Your swapping request has been submitted!

<figure><img src="../../.gitbook/assets/Screenshot_14 (6).png" alt="" width="267"><figcaption></figcaption></figure>

You can either click "**Back to home**" to return to the homepage or "**View transaction**" to see transaction details in the History tab.

{% hint style="info" %}
If you click "**View transaction**", SubWallet will show you the latest transaction record in your transaction history along with the extrinsic hash of the transfer.
{% endhint %}
