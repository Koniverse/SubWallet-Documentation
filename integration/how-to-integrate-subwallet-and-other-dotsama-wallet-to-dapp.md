# How to integrate SubWallet and other Dotsama Wallet to DApp

## Overview

SubWallet, Polkadot{.js} and Talisman extension allow DApp to connect with them by public their interaction in object `injectedWeb3` of window browser.

* SubWallet (public with properties `subwallet-js`)
* Polkadot{.js} (public with properties `polkadot-js`)
* Talisman (public with properties `talisman`)

![](../.gitbook/assets/SubConnect.png)

You can open `injectedWeb3` object in chrome devtools

![](../.gitbook/assets/InjectWeb3DevTools.png)

## How to integrate wallet with DApp

{% hint style="info" %}
Please refer to our example:&#x20;

* Github Repository [**https://github.com/Koniverse/SubConnect**](https://github.com/Koniverse/SubConnect)****
* Demo App: **** [**https://connect.subwallet.app/**](https://connect.subwallet.app)****
* Video Demo**:** [**https://bit.ly/38QhmfI**](https://bit.ly/38QhmfI)****
{% endhint %}

* Check the activation of extension:
  * When a wallet extension is active in browser it will modify `window.injectedWeb3` by add its interaction with specify name.
  * Example check SubWallet extension by these code: `window.injectedWeb3 && window.injectedWeb3['subwallet-js']`
*   Enable intergate with DApp by method `enable()` of extension interaction object

    ```
    const SubWalletExtension = window.injectedWeb3['subwallet-js']
    const extension = await SubWalletExtension.enable()
    ```

    After run these code extension will show popup confirmation popup to confirm integrate with DApp
* After enable, `extension` variable can contains these object
  * `accounts`: Allow get accounts data with 2 methods `get` `subscribe`.
  * `signer`: Allow to sign data with 2 methods: `signPayload`, `signRaw`.
  * `metadata`: Allow to get additional metadata list with method `get` and add/update with method `provide`.

## Use with typescript

If DApp is writen with typescript you need to add package `@polkadot/extension-inject` to your package.json to get extensions interfaces
