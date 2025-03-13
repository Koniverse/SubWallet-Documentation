---
description: >-
  Effortlessly swap tokens within the same network directly on SubWallet in 1
  click.
---

# Single-chain swap

## Supported swap pairs & swap providers

SubWallet supports single-chain token swaps on the following networks:

<table><thead><tr><th width="198">Network name</th><th>Swap provider</th><th width="340">Supported swap pair</th></tr></thead><tbody><tr><td>Hydration</td><td>Hydration</td><td>200+ swap pairs from 23+ tokens (including DOT, KSM, GLMR, HDX, etc.)</td></tr><tr><td>Polkadot Asset Hub</td><td>Polkadot Asset Hub</td><td><ul><li>DOT &#x3C;> USDC</li><li>DOT &#x3C;> USDT</li><li>USDC &#x3C;> USDT</li></ul></td></tr><tr><td>Ethereum</td><td><ul><li>ChainFlip</li><li>SimpleSwap*</li></ul></td><td><ul><li>ETH &#x3C;> USDC</li><li>ETH &#x3C;> USDT</li><li>USDC &#x3C;> USDT</li><li>ETH &#x3C;> FLIP</li><li>USDC &#x3C;> FLIP</li><li>USDT &#x3C;> FLIP</li></ul></td></tr><tr><td>Arbitrum One</td><td>ChainFlip</td><td><ul><li>ETH &#x3C;> USDC</li></ul></td></tr></tbody></table>

_(\*): SimpleSwap doesn't support swap pairs involving the FLIP token._

{% hint style="info" %}
With single-chain swap, you can only swap tokens within the account you want to swap (i.e., tokens can't be swapped from one account to another).
{% endhint %}

## Swap tokens

**Step 1**: On the SubWallet app, hit the "**Swap**" button on the homepage.

<figure><img src="../../.gitbook/assets/Screenshot_1 (5).png" alt="" width="267"><figcaption></figcaption></figure>

{% hint style="info" %}
If this is the first time you use this feature, the Terms of service popup will appear. Read carefully, then select "**I understand the associated risk and will act under caution**". After that, hit "**Confirm and continue swapping**".

<img src="../../.gitbook/assets/Screenshot_2 (5).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_3 (8).png" alt="" data-size="original">
{% endhint %}

**Step 2**: On the Swap screen, select the token you want to swap and the token you wish to receive.

_In this example, we want to swap DOT for MYTH on the Hydration network._&#x20;

Select "**DOT (Hydration)**" as the token you want to swap.

<div><figure><img src="../../.gitbook/assets/Screenshot_5 (5).png" alt="" width="267"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_6 (5).png" alt="" width="267"><figcaption></figcaption></figure></div>

Select "**MYTH (Hydration)**" as the token you wish to receive.

<div><figure><img src="../../.gitbook/assets/Screenshot_7 (4).png" alt="" width="267"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_8 (4).png" alt="" width="267"><figcaption></figcaption></figure></div>

{% hint style="info" %}
Ensure the token you want to swap and the token you wish to receive are on the same network; otherwise, check out this [guide](https://app.gitbook.com/o/CyPU0v2iA12ILmupTKub/s/-Lh39Kwxa1xxZM9WX_Bs/~/changes/705/extension-user-guide/swap-tokens/cross-chain-swap#swap-tokens).
{% endhint %}

<details>

<summary>If you're in the "All accounts" mode</summary>

In this case, you will need to select the swapping account:

<img src="../../.gitbook/assets/Screenshot_27 (5).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_28 (6).png" alt="" data-size="original">

</details>

Enter the amount you want to swap. Once done, the swap quote (with the related information) will appear.

<figure><img src="../../.gitbook/assets/Screenshot_29 (4).png" alt="" width="267"><figcaption></figcaption></figure>

<details>

<summary>If you want to change the slippage tolerance</summary>

To change the slippage tolerance, hit the "**View swap quote**" button.&#x20;

<img src="../../.gitbook/assets/Screenshot_20 (7).png" alt="" data-size="original">

In the Swap quote detail screen, tap on the green-colored "**Slippage**" field, then select or enter your desired slippage tolerance and hit "**Apply**".

<img src="../../.gitbook/assets/Screenshot_10 (5).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_11 (15).png" alt="" data-size="original">

:warning: <mark style="color:orange;">You cannot change the slippage tolerance if the swap provider is ChainFlip or SimpleSwap:</mark>

* With ChainFlip, every swap has a fixed slippage tolerance of 2%.
* With SimpleSwap, the slippage tolerance can't be predicted as it varies based on market conditions, but it will never exceed 5%.

</details>

<details>

<summary>If you want to change the swap provider (ChainFlip/SimpleSwap)</summary>

:information\_source: _<mark style="color:blue;">This feature is available for swap pairs on the Ethereum network.</mark>_

To do that, hit the "**View swap quote**" button, then continue clicking on the "**View quote**" button.

<img src="../../.gitbook/assets/Screenshot_30 (5).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_31 (5).png" alt="" data-size="original">

In the Swap quotes popup, choose the provider you want for the swap.

<img src="../../.gitbook/assets/Screenshot_32 (5).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_33 (6).png" alt="" data-size="original">

</details>

A completed swapping request would look like the following image. Click "**Swap**" to proceed.

<figure><img src="../../.gitbook/assets/Screenshot_12 (6).png" alt="" width="267"><figcaption></figcaption></figure>

**Step 3**: Check your transaction details, then click "**Approve**" to proceed.

<figure><img src="../../.gitbook/assets/Screenshot_13 (9).png" alt="" width="267"><figcaption></figcaption></figure>

**Step 4**: Your swapping request has been submitted!

<figure><img src="../../.gitbook/assets/Screenshot_14 (5).png" alt="" width="267"><figcaption></figcaption></figure>

You can either click "**Back to home**" to return to the homepage or "**View transaction**" to see transaction details in the History tab.

{% hint style="info" %}
If you click "**View transaction**", SubWallet will show you the latest transaction record in your transaction history along with the extrinsic hash of the transfer.
{% endhint %}
