---
description: Sign & approve transactions from dApp on SubWallet.
---

# Sign transactions from dApp

{% hint style="info" %}
The user interface (UI) and buttons you encounter will vary based on the specific designs of each dApp/website.
{% endhint %}

### **Sign transactions on Polkadot/Ethereum dApps**

**Step 1:** Open the dApp and connect your account(s) to it from either one of these options:&#x20;

* Connect by selecting [the SubWallet option](https://app.gitbook.com/o/CyPU0v2iA12ILmupTKub/s/x2bpnbQM0WCkMm0eOyd6/)
* Connect by selecting [the WalletConnect option](https://app.gitbook.com/o/CyPU0v2iA12ILmupTKub/s/-Lh39Kwxa1xxZM9WX_Bs/~/changes/702/extension-user-guide/connect-dapps-and-manage-website-access/connect-disconnect-dapp-via-walletconnect#connect-dapp-with-walletconnect)

_We are connecting to Uniswap in this instance. Once you've connected your account(s) to Uniswap, it will display as follows:_

<figure><img src="../../.gitbook/assets/Screenshot_141 (3).png" alt=""><figcaption></figcaption></figure>

**Step 2:** Fill in the necessary information for the transaction.&#x20;

_In this example, we will swap ETH for WETH on the Ethereum Sepolia network. This transaction is also referred to as wrapping ETH. Once completed, click "**Wrap**"._

<figure><img src="../../.gitbook/assets/Screenshot_145 (2).png" alt=""><figcaption></figcaption></figure>

**Step 3**: The SubWallet popup window will appear. Check the transaction details, then click "**Approve**" to proceed.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot_146 (2).png" alt=""><figcaption></figcaption></figure>

**Step 4**: You've successfully signed a transaction on a dApp! If the transaction is successful, you'll see the change in the balance of each token.

<figure><img src="../../.gitbook/assets/Screenshot_147 (2).png" alt=""><figcaption></figcaption></figure>

### Sign transactions on Cardano dApps

**Step 1:** Open the dApp and connect your account(s) to it from either one of these options:&#x20;

* Connect by selecting [the SubWallet option](https://app.gitbook.com/o/CyPU0v2iA12ILmupTKub/s/x2bpnbQM0WCkMm0eOyd6/)
* Connect by selecting [the WalletConnect option](https://app.gitbook.com/o/CyPU0v2iA12ILmupTKub/s/-Lh39Kwxa1xxZM9WX_Bs/~/changes/702/extension-user-guide/connect-dapps-and-manage-website-access/connect-disconnect-dapp-via-walletconnect#connect-dapp-with-walletconnect)

_We are connecting to Minswap in this instance. Once you've connected your account(s) to Minswap, it will display as follows:_

<figure><img src="../../.gitbook/assets/Screenshot_152 (3).png" alt=""><figcaption></figcaption></figure>

**Step 2:** Fill in the necessary information for the transaction. Once done, hit "**Trade now**".

<figure><img src="../../.gitbook/assets/Screenshot_153 (3).png" alt=""><figcaption></figcaption></figure>

**Step 3**: The SubWallet popup window will appear.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot_154 (2).png" alt=""><figcaption></figcaption></figure>

You will notice the difference between the amount you typed and the amount displayed in the popup. This is because Cardano is an _Unspent Transaction Output (UTXO)-based_ blockchain, which utilizes a different accounting model for its ledger from other account-based blockchains like Ethereum & Polkadot.

The amount displayed in the popup is the summary of the amount you want to swap + the minimum UTXO ADA for this transaction (it will be returned when your swaps are processed or cancelled) + the network fee.

{% hint style="info" %}
If you click on the "**View details**" option, you will see the transaction details. In Cardano, each transaction includes inputs and outputs, where the input represents the address that is sending ADA or the native asset, and the outputs represent the addresses that are receiving ADA or the native asset.

<img src="../../.gitbook/assets/Screenshot_155 (2).png" alt="" data-size="original">
{% endhint %}

Check the transaction details, then click "**Approve**" to proceed.&#x20;

**Step 4**: You've successfully signed a transaction on a dApp! If the transaction is successful, you'll see the change in the balance of each token.

<figure><img src="../../.gitbook/assets/Screenshot_156 (2).png" alt=""><figcaption></figcaption></figure>
