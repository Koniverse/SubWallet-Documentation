---
description: >-
  Effortlessly swap tokens within the same network directly on SubWallet in 1
  click.
---

# Single-chain swap

## Supported swap pairs & swap providers

SubWallet supports single-chain token swaps on the following networks:

<table><thead><tr><th width="198">Network name</th><th>Swap provider</th><th width="340">Supported swap pair</th></tr></thead><tbody><tr><td>Hydration</td><td>Hydration</td><td>200+ swap pairs from 23+ tokens (including DOT, GLMR, HDX, etc.)</td></tr><tr><td>Polkadot Asset Hub</td><td>Polkadot Asset Hub</td><td><ul><li>DOT &#x3C;> USDC</li><li>DOT &#x3C;> USDT</li><li>USDC &#x3C;> USDT</li></ul></td></tr><tr><td>Ethereum</td><td><ul><li>ChainFlip</li><li>SimpleSwap*</li><li>Uniswap*</li></ul></td><td><ul><li>ETH &#x3C;> USDC</li><li>ETH &#x3C;> USDT</li><li>USDC &#x3C;> USDT</li><li>ETH &#x3C;> FLIP</li><li>USDC &#x3C;> FLIP</li><li>USDT &#x3C;> FLIP</li><li>WBTC &#x3C;> ETH**</li></ul></td></tr><tr><td>Arbitrum One</td><td><ul><li>ChainFlip</li><li>Uniswap</li></ul></td><td><ul><li>ETH &#x3C;> USDC</li><li>ETH &#x3C;> USDT**</li><li>ETH &#x3C;> ARB**</li><li>ETH &#x3C;> WBTC**</li></ul></td></tr><tr><td>13 networks</td><td>Uniswap Labs Trading API</td><td>1000+ swap pairs across 13 networks</td></tr></tbody></table>

_(\*): SimpleSwap doesn't support swap pairs involving the FLIP token._

_(\*\*): Available **only** for swapping via Uniswap Trading Labs API._

{% hint style="info" %}
With single-chain swap, you can only swap tokens within the account you want to swap (i.e., tokens can't be swapped from one account to another).
{% endhint %}

## Swap tokens via Hydration, Polkadot Asset Hub, ChainFlip & SimpleSwap

**Step 1**: Open the SubWallet extension and click the "**Swap**" button on the homepage.

<div><figure><img src="../../.gitbook/assets/Screenshot_348.png" alt="" width="363"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_349.png" alt="" width="363"><figcaption></figcaption></figure></div>

{% hint style="info" %}
If this is the first time you click the button, the Terms of service popup will appear. Read carefully, then select "**I understand the associated risk and will act under caution**". After that, click "**Confirm and continue swapping**".

<img src="../../.gitbook/assets/Screenshot_382 (1).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_383 (1).png" alt="" data-size="original">
{% endhint %}

**Step 2**: On the Swap screen, select the token you want to swap and the token you wish to receive.

_In this example, we want to swap DOT for MYTH on the Hydration network._&#x20;

Select "**DOT (Hydration)**" as the token you want to swap.

<div><figure><img src="../../.gitbook/assets/Screenshot_350.png" alt="" width="363"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_351.png" alt="" width="363"><figcaption></figcaption></figure></div>

Select "**MYTH (Hydration)**" as the token you wish to receive.

<div><figure><img src="../../.gitbook/assets/Screenshot_352.png" alt="" width="363"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_353.png" alt="" width="363"><figcaption></figcaption></figure></div>

{% hint style="info" %}
Ensure the token you want to swap and the token you wish to receive are on the same network; otherwise, check out this [guide](https://app.gitbook.com/o/CyPU0v2iA12ILmupTKub/s/-Lh39Kwxa1xxZM9WX_Bs/~/changes/705/extension-user-guide/swap-tokens/cross-chain-swap#swap-tokens).
{% endhint %}

<details>

<summary>If you're in the "All accounts" mode</summary>

In this case, you will need to select the swapping account.

<img src="../../.gitbook/assets/Screenshot_362 (1).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_363 (1).png" alt="" data-size="original">

</details>

Enter the amount you want to swap. Once done, the swap quote (with the related information) will appear.

<figure><img src="../../.gitbook/assets/Screenshot_354.png" alt="" width="363"><figcaption></figcaption></figure>

<details>

<summary>If you want to change the slippage tolerance</summary>

To change the slippage tolerance, hit the "**View swap quote**" button.&#x20;

<img src="../../.gitbook/assets/Screenshot_355.png" alt="" data-size="original">

In the Swap quote detail screen, click on the green-colored "**Slippage**" field, then select or enter your desired slippage tolerance and click "**Apply**".

<img src="../../.gitbook/assets/Screenshot_356 (1).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_357 (1).png" alt="" data-size="original">

{% hint style="warning" %}
You cannot change the slippage tolerance if the swap provider is ChainFlip or SimpleSwap:

* With ChainFlip, every swap has a fixed slippage tolerance of 2%.
* With SimpleSwap, the slippage tolerance can't be predicted as it varies based on market conditions, but it will never exceed 5%.
{% endhint %}

</details>

<details>

<summary>If you want to change the swap provider (ChainFlip/SimpleSwap/Uniswap)</summary>

{% hint style="info" %}
_This feature is available for swap pairs on the Ethereum network._
{% endhint %}

To do that, hit the "**View swap quote**" button, then continue clicking on the "**View quote**" button.

<img src="../../.gitbook/assets/Screenshot_368.png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_369.png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_370 (1).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_371 (1).png" alt="" data-size="original">

</details>

A completed swapping request would look like the following image. Click "**Swap**" to proceed.

<figure><img src="../../.gitbook/assets/Screenshot_364.png" alt="" width="363"><figcaption></figcaption></figure>

**Step 3**: Check your transaction details, then click "**Approve**" to proceed.

<figure><img src="../../.gitbook/assets/Screenshot_365.png" alt="" width="363"><figcaption></figcaption></figure>

{% hint style="warning" %}
Swapping via SimpleSwap can take 5 to 60 minutes, depending on the market conditions.
{% endhint %}

**Step 4**: Your swapping request has been submitted!

<figure><img src="../../.gitbook/assets/image (1986).png" alt="" width="363"><figcaption></figcaption></figure>

You can either click "**Back to home**" to return to the homepage or "**View transaction**" to see transaction details in the History tab.

{% hint style="info" %}
If you click "**View transaction**", SubWallet will show you the latest transaction record in your transaction history along with the extrinsic hash of the transfer.

<img src="../../.gitbook/assets/Screenshot_367.png" alt="" data-size="original">
{% endhint %}

## Swap tokens via Uniswap

{% hint style="info" %}
If you want to swap ETH on the Ethereum or the Arbitrum One network for other tokens, the swap process will be the same as swapping via other providers.

If you want to swap from other tokens on these 2 networks via Uniswap, follow the instructions below.
{% endhint %}

**Step 1**: Open the SubWallet extension and click the "**Swap**" button on the homepage.

<div><figure><img src="../../.gitbook/assets/Screenshot_10 (4).png" alt="" width="362"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_25 (3).png" alt="" width="362"><figcaption></figcaption></figure></div>

{% hint style="info" %}
If this is the first time you click the button, the Terms of service popup will appear. Read carefully, then select "**I understand the associated risk and will act under caution**". After that, click "**Confirm and continue swapping**".

<img src="../../.gitbook/assets/Screenshot_382 (1).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_383 (1).png" alt="" data-size="original">
{% endhint %}

**Step 2**: On the Swap screen, select the token you want to swap and the token you wish to receive.

_In this example, we want to swap ARB for ETH on the Arbitrum One network._&#x20;

Select "ARB **(Arbitrum One)**" as the token you want to swap.

<div><figure><img src="../../.gitbook/assets/Screenshot_26 (4).png" alt="" width="362"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_27 (3).png" alt="" width="362"><figcaption></figcaption></figure></div>

Select "**ETH (Arbitrum One)**" as the token you wish to receive.

<div><figure><img src="../../.gitbook/assets/Screenshot_28 (4) (1).png" alt="" width="362"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_29 (3) (1).png" alt="" width="362"><figcaption></figcaption></figure></div>

{% hint style="info" %}
Ensure the token you want to swap and the token you wish to receive are on the same network; otherwise, check out this [guide](https://app.gitbook.com/o/CyPU0v2iA12ILmupTKub/s/-Lh39Kwxa1xxZM9WX_Bs/~/changes/705/extension-user-guide/swap-tokens/cross-chain-swap#swap-tokens).
{% endhint %}

<details>

<summary>If you're in the "All accounts" mode</summary>

In this case, you will need to select the swapping account.

<img src="../../.gitbook/assets/Screenshot_30 (3).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_16 (5) (1).png" alt="" data-size="original">

</details>

Enter the amount you want to swap. Once done, the swap quote (with the related information) will appear.

<figure><img src="../../.gitbook/assets/Screenshot_31 (2) (1).png" alt="" width="362"><figcaption></figcaption></figure>

<details>

<summary>If you want to change the slippage tolerance</summary>

To change the slippage tolerance, hit the "**View swap quote**" button.&#x20;

<img src="../../.gitbook/assets/Screenshot_31 (3).png" alt="" data-size="original">

In the Swap quote detail screen, click on the green-colored "**Slippage**" field, then select or enter your desired slippage tolerance and click "**Apply**".

<img src="../../.gitbook/assets/Screenshot_32 (3) (1).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_34 (5).png" alt="" data-size="original">

Once applied, you can see the new quote with the applied slippage tolerance.&#x20;

<img src="../../.gitbook/assets/Screenshot_35 (3).png" alt="" data-size="original">

</details>

A completed swapping request would look like the following image. Click "**Swap**" to proceed.

<figure><img src="../../.gitbook/assets/Screenshot_36 (3).png" alt="" width="362"><figcaption></figcaption></figure>

**Step 3**: On the Confirmation screen, you will see that this transaction has 3 steps. Click the button to view the details of the swapping process.

<div><figure><img src="../../.gitbook/assets/Screenshot_37 (3).png" alt="" width="362"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_38 (3).png" alt="" width="362"><figcaption></figcaption></figure></div>

Once checked, close the view and click "**Approve**" to swap.

<figure><img src="../../.gitbook/assets/Screenshot_39 (2) (1).png" alt="" width="362"><figcaption></figcaption></figure>

**Step 4**: Your swapping request has been submitted!

You'll be directed to the Expand view of the SubWallet extension. You can either click "**View progress**" to view the transaction progress in the Notifications screen or "**Back to home**" to return to the homepage.

{% hint style="warning" %}
DO NOT close this view until the swap is complete. Closing it before completion will result in the swap failing.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (1998).png" alt=""><figcaption></figcaption></figure>

If you select "**View progress**", you'll be directed to the Notifications screen. Click the swap-related notification to view progress.

<figure><img src="../../.gitbook/assets/Screenshot_43 (2) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot_41 (3) (1).png" alt=""><figcaption></figcaption></figure>
