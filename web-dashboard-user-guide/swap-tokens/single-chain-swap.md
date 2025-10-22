---
description: >-
  Effortlessly swap tokens within the same network directly on SubWallet in 1
  click.
---

# Single-chain swap

## Supported swap pairs & swap providers

SubWallet supports single-chain token swaps on the following networks:

<table><thead><tr><th width="198">Network name</th><th>Swap provider</th><th width="340">Supported swap pair</th></tr></thead><tbody><tr><td>Hydration</td><td>Hydration</td><td>300+ swap pairs from 30+ tokens (DOT, GLMR, HDX, etc.)</td></tr><tr><td>Polkadot Asset Hub</td><td>Polkadot Asset Hub</td><td><ul><li>DOT &#x3C;> USDC</li><li>DOT &#x3C;> USDT</li><li>USDC &#x3C;> USDT</li></ul></td></tr><tr><td>Ethereum</td><td><ul><li>ChainFlip</li><li>SimpleSwap*</li><li>Uniswap*</li><li>KyberSwap*</li></ul></td><td><ul><li>ETH &#x3C;> USDC</li><li>ETH &#x3C;> USDT</li><li>USDC &#x3C;> USDT</li><li>ETH &#x3C;> FLIP</li><li>USDC &#x3C;> FLIP</li><li>USDT &#x3C;> FLIP</li><li>WBTC &#x3C;> ETH**</li></ul></td></tr><tr><td>Arbitrum One</td><td><ul><li>ChainFlip</li><li>Uniswap</li></ul></td><td><ul><li>ETH &#x3C;> USDC</li><li>ETH &#x3C;> USDT**</li><li>ETH &#x3C;> ARB**</li><li>ETH &#x3C;> WBTC**</li></ul></td></tr><tr><td>13 EVM networks</td><td>Uniswap Labs Trading API</td><td>1000+ swap pairs across 13 networks</td></tr><tr><td>10+ EVM networks</td><td>KyberSwap</td><td>1000+ swap pairs across 10+ networks</td></tr></tbody></table>

_(\*): SimpleSwap doesn't support swap pairs involving the FLIP token._

_(\*\*): Available **only** for swapping via Uniswap Trading Labs API._

{% hint style="info" %}
With single-chain swap, you can only swap tokens within the account you want to swap (i.e., tokens can't be swapped from one account to another).
{% endhint %}

## Swap tokens via Hydration, Polkadot Asset Hub, ChainFlip, SimpleSwap & KyberSwap

**Step 1**: On the SubWallet homepage, select the "**Swap**" tab on the sidebar.

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If this is the first time you click the button, the Terms of service popup will appear. Read carefully, then select "**I understand the associated risk and will act under caution**". After that, click "**Confirm and continue swapping**".

<p align="center"><img src="../../.gitbook/assets/image (1).png" alt="">  <img src="../../.gitbook/assets/image (4).png" alt=""></p>
{% endhint %}

**Step 2**: On the Swap screen, enter the required information. This includes:

* The token you want to swap
* The token you wish to receive
* The amount of tokens to swap

<figure><img src="../../.gitbook/assets/image (2159).png" alt=""><figcaption></figcaption></figure>

_In this example, we want to swap HDX for MYTH on the Hydration network._&#x20;

<details>

<summary>If you're in the "All accounts" mode</summary>

In this case, you will need to select the swapping account.

<figure><img src="../../.gitbook/assets/image (2181).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (2182).png" alt=""><figcaption></figcaption></figure>

</details>

{% stepper %}
{% step %}
### Select the token you want to swap

Select "**HDX (Hydration)**" in this example.

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Select the token you wish to receive

Select "**MYTH (Hydration)**" in this example.

{% hint style="info" %}
Ensure the token you want to swap and the token you wish to receive are on the same network; otherwise, check out this [guide](https://app.gitbook.com/o/CyPU0v2iA12ILmupTKub/s/-Lh39Kwxa1xxZM9WX_Bs/~/changes/705/extension-user-guide/swap-tokens/cross-chain-swap#swap-tokens).
{% endhint %}

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Enter the amount you want to swap

Enter the amount of the token you want to swap. Once done, the swap quote (with the related information) will appear.

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

<details>

<summary>If you want to change the slippage tolerance</summary>

To change the slippage tolerance, hit the <img src="../../.gitbook/assets/Screenshot_67.png" alt="" data-size="line"> button in the Slippage field.&#x20;

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

A popup screen will appear on the right side. In the Slippage setting screen, select or enter your desired slippage tolerance and click "**Apply**".

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
You cannot change the slippage tolerance if the swap provider is ChainFlip or SimpleSwap:

* With ChainFlip, every swap has a fixed slippage tolerance of 2%.
* With SimpleSwap, the slippage tolerance can't be predicted as it varies based on market conditions, but it will never exceed 5%.
{% endhint %}

</details>

<details>

<summary>If you want to change the swap provider (ChainFlip/SimpleSwap/Uniswap/KyberSwap)</summary>

{% hint style="info" %}
_This feature is available for swap pairs on the Ethereum network._
{% endhint %}

To do that, hit the "**<**" button on the Quote rate field.

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

A popup screen will appear on the right side. Select the provider you want to perform the swap, then click "**Confirm**".

<figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

You will see the newly updated quote.

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

</details>

A completed swapping request would look like the following image. Click "**Swap**" to proceed.

<figure><img src="../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

**Step 3**: Check your transaction details, then click "**Approve**" to proceed.

<figure><img src="../../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Swapping via SimpleSwap can take 5 to 60 minutes, depending on the market conditions.
{% endhint %}

**Step 4**: Your swapping request has been submitted!

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

You can either click "**Back to home**" to return to the homepage or "**View transaction**" to see transaction details in the History tab.

{% hint style="info" %}
If you click "**View transaction**", SubWallet will show you the latest transaction record in your transaction history along with the extrinsic hash of the transfer.

![](<../../.gitbook/assets/image (24).png>)
{% endhint %}

## Swap tokens via Uniswap

{% hint style="info" %}
If you want to swap ETH on the Ethereum or the Arbitrum One network for other tokens, the swap process will be the same as swapping via other providers.

If you want to swap from other tokens on these 2 networks via Uniswap, follow the instructions below.
{% endhint %}

**Step 1**: On the SubWallet homepage, select the "**Swap**" tab on the sidebar.

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If this is the first time you click the button, the Terms of service popup will appear. Read carefully, then select "**I understand the associated risk and will act under caution**". After that, click "**Confirm and continue swapping**".

<p align="center"><img src="../../.gitbook/assets/image (1).png" alt="">  <img src="../../.gitbook/assets/image (4).png" alt=""></p>
{% endhint %}

**Step 2**: On the Swap screen, enter the required information. This includes:

* The token you want to swap
* The token you wish to receive
* The amount of tokens to swap

<figure><img src="../../.gitbook/assets/image (2183).png" alt=""><figcaption></figcaption></figure>

**Step 1**: On the SubWallet homepage, select the "**Swap**" tab on the sidebar.

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If this is the first time you click the button, the Terms of service popup will appear. Read carefully, then select "**I understand the associated risk and will act under caution**". After that, click "**Confirm and continue swapping**".

<p align="center"><img src="../../.gitbook/assets/image (1).png" alt="">  <img src="../../.gitbook/assets/image (4).png" alt=""></p>
{% endhint %}

**Step 2**: On the Swap screen, enter the required information. This includes:

* The token you want to swap
* The token you wish to receive
* The amount of tokens to swap

<figure><img src="../../.gitbook/assets/image (2159).png" alt=""><figcaption></figcaption></figure>

_In this example, we want to swap USDC for ETH on the Base Mainnet network via Uniswap._&#x20;

<details>

<summary>If you're in the "All accounts" mode</summary>

In this case, you will need to select the swapping account.

<figure><img src="../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

</details>

{% stepper %}
{% step %}
### Select the token you want to swap

Select "**USDC (Base Mainnet)**" in this example.

<figure><img src="../../.gitbook/assets/image (2161).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Select the token you wish to receive

Select "**ETH (Base Mainnet)**" in this example.

{% hint style="info" %}
Ensure the token you want to swap and the token you wish to receive are on the same network; otherwise, check out this [guide](https://app.gitbook.com/o/CyPU0v2iA12ILmupTKub/s/-Lh39Kwxa1xxZM9WX_Bs/~/changes/705/extension-user-guide/swap-tokens/cross-chain-swap#swap-tokens).
{% endhint %}

<figure><img src="../../.gitbook/assets/image (2162).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Enter the amount you want to swap

Enter the amount of the token you want to swap. Once done, the swap quote (with the related information) will appear.
{% endstep %}
{% endstepper %}

<details>

<summary>If you want to change the slippage tolerance</summary>

To change the slippage tolerance, hit the <img src="../../.gitbook/assets/Screenshot_67.png" alt="" data-size="line"> button in the Slippage field.&#x20;

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

A popup screen will appear on the right side. In the Slippage setting screen, select or enter your desired slippage tolerance and click "**Apply**".

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
You cannot change the slippage tolerance if the swap provider is ChainFlip or SimpleSwap:

* With ChainFlip, every swap has a fixed slippage tolerance of 2%.
* With SimpleSwap, the slippage tolerance can't be predicted as it varies based on market conditions, but it will never exceed 5%.
{% endhint %}

</details>

<details>

<summary>If you want to change the swap provider (ChainFlip/SimpleSwap/Uniswap/KyberSwap)</summary>

{% hint style="info" %}
_This feature is available for swap pairs on the Ethereum network._
{% endhint %}

To do that, hit the "**<**" button on the Quote rate field.

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

A popup screen will appear on the right side. Select the provider you want to perform the swap, then click "**Confirm**".

<figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

You will see the newly updated quote.

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

</details>

A completed swapping request would look like the following image. Click "**Swap**" to proceed.

<figure><img src="../../.gitbook/assets/image (2164).png" alt=""><figcaption></figcaption></figure>

**Step 3**: On the Confirmation screen, you will see that this transaction has the "Process" field. Click the button to view the details of the swapping process.

<figure><img src="../../.gitbook/assets/image (2166).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (2167).png" alt=""><figcaption></figcaption></figure>

Click the "**X**" button to get out, then check your transaction details, then click "**Approve**" to proceed.

<figure><img src="../../.gitbook/assets/image (2168).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Swapping via SimpleSwap can take 5 to 60 minutes, depending on the market conditions.
{% endhint %}

**Step 4**: Your swapping request has been submitted!

You'll be directed to the new screen. From there, either click "**View progress**" to view the transaction progress in the Notifications screen or "**Back to home**" to return to the homepage.

<figure><img src="../../.gitbook/assets/Screenshot_117 (3).png" alt=""><figcaption></figcaption></figure>

If you select "**View progress**", you'll be directed to the Notifications screen. Click the swap-related notification to view progress.

<figure><img src="../../.gitbook/assets/image (2170).png" alt=""><figcaption></figcaption></figure>
