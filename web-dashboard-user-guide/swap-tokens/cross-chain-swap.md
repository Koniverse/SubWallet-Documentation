---
description: Easily swap tokens across different networks directly on SubWallet in 1 click.
---

# Cross-chain swap

## Supported swap pairs & swap providers

### Cross-chain swap on the Polkadot ecosystems

<table><thead><tr><th>Swap provider</th><th width="412">Supported swap pair</th></tr></thead><tbody><tr><td><ul><li>SimpleSwap</li></ul></td><td><ul><li>DOT (Polkadot) &#x3C;> TAO (Bittensor)</li></ul></td></tr><tr><td><ul><li>ChainFlip</li></ul></td><td><ul><li>DOT (Polkadot) &#x3C;> USDT (Polkadot Asset Hub)</li><li>DOT (Polkadot) &#x3C;> USDC (Polkadot Asset Hub)</li></ul></td></tr></tbody></table>

### Cross-chain swap on the Ethereum ecosystems

<table><thead><tr><th>Swap provider</th><th width="413">Supported swap pair</th></tr></thead><tbody><tr><td><ul><li>ChainFlip</li></ul></td><td><ul><li>ETH (Ethereum) &#x3C;> USDC (Arbitrum One)</li><li>USDT (Ethereum) &#x3C;> USDC (Arbitrum One)</li><li>ETH (Arbitrum One) &#x3C;> USDC (Ethereum)</li><li>ETH (Arbitrum One) &#x3C;> USDT (Ethereum)</li><li>FLIP (Ethereum) &#x3C;> ETH (Arbitrum One)</li><li>FLIP (Ethereum) &#x3C;> USDC (Arbitrum One)</li></ul></td></tr><tr><td><ul><li>KyberSwap</li></ul></td><td><ul><li>1000+ swap pairs across 10+ EVM networks, combine with token bridging to find the best route</li></ul></td></tr><tr><td><ul><li>Uniswap</li></ul></td><td><ul><li>1000+ swap pairs across 13 EVM networks, combine with token bridging to find the best route</li></ul></td></tr></tbody></table>

### Cross-chain swap between Polkadot & Ethereum ecosystems

<table><thead><tr><th>Swap provider</th><th width="413">Supported swap pair</th></tr></thead><tbody><tr><td><ul><li>ChainFlip</li><li>SimpleSwap</li></ul></td><td><ul><li>DOT (Polkadot) &#x3C;> ETH (Ethereum)</li><li>DOT (Polkadot) &#x3C;> USDC (Ethereum)</li><li>DOT (Polkadot) &#x3C;> USDT (Ethereum)</li></ul></td></tr><tr><td><ul><li>ChainFlip</li></ul></td><td><ul><li>DOT (Polkadot) &#x3C;> FLIP (Ethereum)</li><li>DOT (Polkadot) &#x3C;> USDC/ETH (Arbitrum One)</li></ul><ul><li>USDT, USDC, WETH (Polkadot Asset Hub) &#x3C;>  ETH/USDT/USDC (Ethereum)</li><li>USDT, USDC, WETH (Polkadot Asset Hub) &#x3C;>  ETH/USDT/USDC (Arbitrum One)</li></ul></td></tr><tr><td><ul><li>SimpleSwap</li></ul></td><td><ul><li>TAO (Bittensor) &#x3C;> ETH (Ethereum)</li><li>TAO (Bittensor) &#x3C;> USDC (Ethereum)</li><li>TAO (Bittensor) &#x3C;> USDT (Ethereum)</li></ul></td></tr></tbody></table>

{% hint style="info" %}
With this type of swap, you can choose to swap your tokens to another account.
{% endhint %}

### Cross-chain swap between Polkadot & Bitcoin ecosystems

<table><thead><tr><th>Swap provider</th><th width="413">Supported swap pair</th></tr></thead><tbody><tr><td><ul><li>ChainFlip</li></ul></td><td><ul><li>DOT (Polkadot) &#x3C;> BTC (Bitcoin)</li><li>USDC (Polkadot Asset Hub) &#x3C;> BTC (Bitcoin)</li><li>USDT (Polkadot Asset Hub) &#x3C;> BTC (Bitcoin)</li></ul></td></tr></tbody></table>

{% hint style="info" %}
* With this type of swap, you can choose to swap your tokens to another account.
* BTC swap is supported on all 3 Bitcoin address types (Native SegWit, Legacy & Taproot).
{% endhint %}

## Swap tokens

**Step 1**: On the SubWallet homepage, select the "**Swap**" tab on the sidebar.

<figure><img src="../../.gitbook/assets/image (2159).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If this is the first time you click the button, the Terms of service popup will appear. Read carefully, then select "**I understand the associated risk and will act under caution**". After that, click "**Confirm and continue swapping**".

<p align="center"><img src="../../.gitbook/assets/image (2160).png" alt="">  <img src="../../.gitbook/assets/image (2163).png" alt=""></p>
{% endhint %}

**Step 2**: On the Swap screen, enter the required information. This includes:

* The token you want to swap
* The token you wish to receive
* The amount of tokens to swap

{% hint style="info" %}
You will also need to enter the recipient address for some specific swap pairs.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (2189).png" alt=""><figcaption></figcaption></figure>

_In this example, we want to swap USDC on Base Mainnet for ETH on the Ethereum network._&#x20;

<details>

<summary>If you're in the "All accounts" mode</summary>

In this case, you will need to select the swapping account.

<figure><img src="../../.gitbook/assets/image (2211).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (2212).png" alt=""><figcaption></figcaption></figure>

</details>

{% stepper %}
{% step %}
### Select the token you want to swap

Select "**USDC (Base Mainnet)**" in this example.

<figure><img src="../../.gitbook/assets/image (2201).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Select the token you wish to receive

Select "**ETH (Ethereum)**" in this example.

{% hint style="info" %}
Ensure the token you want to swap and the token you wish to receive are on the same network; otherwise, check out this [guide](<../../extension-user-guide/swap-tokens/single-chain-swap (1).md>).
{% endhint %}

<figure><img src="../../.gitbook/assets/image (2202).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Enter the amount you want to swap

Enter the amount of the token you want to swap. Once done, the swap quote (with the related information) will appear.

<figure><img src="../../.gitbook/assets/image (2203).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

<details>

<summary>If you want to change the slippage tolerance</summary>

To change the slippage tolerance, hit the <img src="../../.gitbook/assets/Screenshot_67 (9).png" alt="" data-size="line"> button in the Slippage field.&#x20;

<figure><img src="../../.gitbook/assets/image (2184).png" alt=""><figcaption></figcaption></figure>

A popup screen will appear on the right side. In the Slippage setting screen, select or enter your desired slippage tolerance and click "**Apply**".

<figure><img src="../../.gitbook/assets/image (2185).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (2186).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
You cannot change the slippage tolerance if the swap provider is ChainFlip or SimpleSwap:

* With ChainFlip, every swap has a fixed slippage tolerance of 2%.
* With SimpleSwap, the slippage tolerance can't be predicted as it varies based on market conditions, but it will never exceed 5%.
{% endhint %}

</details>

<details>

<summary>If you want to change the swap provider (ChainFlip/Uniswap/KyberSwap)</summary>

{% hint style="info" %}
_This feature is available for swap pairs on the Ethereum network._
{% endhint %}

To do that, hit the "**<**" button on the Quote rate field.

<figure><img src="../../.gitbook/assets/image (2176).png" alt=""><figcaption></figcaption></figure>

A popup screen will appear on the right side. Select the provider you want to perform the swap, then click "**Confirm**".

<figure><img src="../../.gitbook/assets/image (2177).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (2178).png" alt=""><figcaption></figcaption></figure>

You will see the newly updated quote.

<figure><img src="../../.gitbook/assets/image (2179).png" alt=""><figcaption></figcaption></figure>

</details>

A completed swapping request would look like the following image. Click "**Swap**" to proceed.

<figure><img src="../../.gitbook/assets/image (2204).png" alt=""><figcaption></figcaption></figure>

**Step 3**: Check your transaction details, then click "**Approve**" to proceed.

<figure><img src="../../.gitbook/assets/image (2205).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If Uniswap is chosen to be your transaction's swap provider, then on the Confirmation screen, you will see that this transaction has the "Process" field. Click the button to view the details of the swapping process.

![](<../../.gitbook/assets/image (2206).png>) ![](<../../.gitbook/assets/image (2207).png>)
{% endhint %}

**Step 4**: Your swapping request has been submitted!

You'll be directed to the new screen. From there, either click "**View progress**" to view the transaction progress in the Notifications screen or "**Back to home**" to return to the homepage.

<figure><img src="../../.gitbook/assets/image (2208).png" alt=""><figcaption></figcaption></figure>

If you select "**View progress**", you'll be directed to the Notifications screen. Click the swap-related notification to view progress.

<figure><img src="../../.gitbook/assets/image (2209).png" alt=""><figcaption></figcaption></figure>
