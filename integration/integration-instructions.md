---
description: >-
  Or how to integrate SubWallet and other Polkadot and Kusama wallets into your
  DApps
---

# Integration Instructions

## Overview

SubWallet, Polkadot{.js} and Talisman extensions allow DApp to connect with them by publicizing their interaction in object `injectedWeb3` of window browser.

* SubWallet (public with properties `subwallet-js`)
* Polkadot{.js} (public with properties `polkadot-js`)
* Talisman (public with properties `talisman`)

![](../.gitbook/assets/SubConnect.png)

You can open `injectedWeb3` object in Chrome devtools.

![](../.gitbook/assets/InjectWeb3DevTools.png)

## How to integrate wallets into DApps

{% hint style="info" %}
Please refer to our examples below:&#x20;

* Github Repository: [**https://github.com/Koniverse/SubConnect**](https://github.com/Koniverse/SubConnect)****
* Demo App: **** [**https://connect.subwallet.app/**](https://connect.subwallet.app/)****
* Demo Video: **** [**https://bit.ly/38QhmfI**](https://bit.ly/38QhmfI)****
{% endhint %}

* Check extension's activation:
  * When a wallet extension is active in browser it will modify `window.injectedWeb3` by adding its interaction with a specific name.
  * For example, check SubWallet extension by these code: `window.injectedWeb3 && window.injectedWeb3['subwallet-js']`
*   Enable intergation into your DApp by method `enable()` of extension interaction object.

    ```
    const SubWalletExtension = window.injectedWeb3['subwallet-js']
    const extension = await SubWalletExtension.enable()
    ```

    * After running, these code extension will show popup confirmation to confirm integration into your DApp
* After enabling, `extension` variable can contain these objects:
  * `accounts`: Allow getting accounts' data with 2 methods, `get` and `subscribe`.
  * `signer`: Allow signing data with 2 methods, `signPayload` and `signRaw`.
  * `metadata`: Allow getting additional metadata list with method `get` and adding/updating with method `provide`.

{% hint style="info" %}
If your DApp is writen in typescript, you need to add package `@polkadot/extension-inject` to your package.json to get extensions interfaces.
{% endhint %}
