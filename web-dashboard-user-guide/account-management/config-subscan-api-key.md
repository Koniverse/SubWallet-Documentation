---
description: >-
  Generate & use Subscan API key to enable authenticated access to Subscan’s
  data services on SubWallet.
---

# Config Subscan API key

## Why do you need Subscan API key

To provide a more stable and secure experience for the Polkadot & Kusama ecosystems, Subscan (the primary block explorer used to track your transactions) has updated its access policies (check out [this announcement](https://x.com/subscan_io/status/2027688499684810931?s=20) for detailed information).

Previously, some data could be retrieved anonymously. However, Subscan now requires an official API Key to prevent service abuse and ensure high-speed data delivery. Without this key configured in SubWallet, certain advanced operations—such as detailed transaction histories or specific on-chain data visualizations—may fail to load or appear restricted.

{% hint style="info" icon="key" %}
## Key changes to note:

* Mandatory authentication: As of March 9, Subscan has restricted all unauthenticated access (requests without a key).
* Enhanced stability: Using your own API key ensures your data requests are prioritized and unaffected by general network traffic or public limits.
* Privacy & security: Registering for a key allows Subscan to provide a more secure environment for ecosystem partners and developers.
{% endhint %}

To continue viewing full transaction details and a seamless operational history within SubWallet, you must generate a free API key on the Subscan dashboard and enter it in your wallet settings.

{% hint style="success" icon="lightbulb" %}
**Pro Tip**: Subscan offers a Free Plan specifically designed for individual developers and ecosystem enthusiasts so that you can maintain full visibility of your assets at no cost.
{% endhint %}

## Generate & config Subscan API key on SubWallet

### Generate your Subscan API key on Subscan

Before configuring the API key on SubWallet, you must obtain it from the Subscan developer portal.

**Step 1**: Go to [pro.subscan.io](https://pro.subscan.io/) and sign up for a new account or login.

<figure><img src="../../.gitbook/assets/image (2333).png" alt=""><figcaption></figcaption></figure>

Depending on whether you have an account, select the tab that best suits your needs.

{% tabs %}
{% tab title="Sign up" %}
**Step 2**: Click the "**Sign up**" button if you don't have an account.

<figure><img src="../../.gitbook/assets/image (2334).png" alt=""><figcaption></figcaption></figure>

You'll be redirected to the Sign up screen.

**Step 3**: In the Sign up screen, you can choose to register using your email or your Substrate (Polkadot) address.&#x20;

{% hint style="info" %}
If you don't use the SubWallet browser extension, **registering via email is recommended**.
{% endhint %}

_**3.1. If you want to register using your email**_

Provide the required information as listed upon signing up via email.&#x20;

<figure><img src="../../.gitbook/assets/image (2335).png" alt=""><figcaption></figcaption></figure>

Once done, tick the "**I have agree to the terms of the** [**Subscan user agreement**](https://www.subscan.io/term)" checkbox, then click "**Sign Up**".

<figure><img src="../../.gitbook/assets/Screenshot_6 (1) (3).png" alt=""><figcaption></figcaption></figure>

_**3.2. If you want to register using your wallet address**_

Select the "**Sign with Web 3.0 Address**" option.



<figure><img src="../../.gitbook/assets/image (2336).png" alt=""><figcaption></figcaption></figure>

You'll be redirected to a wallet signing screen. Choose the wallet-connect option (Polkadot or EVM) you'd like to connect with, then click "**Connect wallet**".

<figure><img src="../../.gitbook/assets/image (2337).png" alt=""><figcaption></figcaption></figure>

The SubWallet browser extension will appear. Select the account you'd want to connect, then click "**Connect**".

<figure><img src="../../.gitbook/assets/image (2338).png" alt=""><figcaption></figcaption></figure>

Once connected, tick the "**I have agree to the terms of the** [**Subscan user agreement**](https://www.subscan.io/term)" checkbox, then click "**Sign Up**".

<figure><img src="../../.gitbook/assets/image (2339).png" alt=""><figcaption></figcaption></figure>

A signature request popup from SubWallet will appear, asking you to sign to prove you're the owner of the selected account. Click "**Approve**" to proceed.

<figure><img src="../../.gitbook/assets/image (2340).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Login" %}
**Step 2**: Click the "**Login**" button if you already have a Subscan account.

<figure><img src="../../.gitbook/assets/image (2341).png" alt=""><figcaption></figcaption></figure>

**Step 3**: You'll be redirected to the Login screen. From there, depending on the signing method you've used to create your account, choose the appropriate option.

{% hint style="info" %}
If you don't use the SubWallet browser extension, **logging in via email is recommended**.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (2342).png" alt=""><figcaption></figcaption></figure>

_**3.1. If you want to login using your email address**_

Provide your email address & password, then click "**Login**".

<figure><img src="../../.gitbook/assets/image (2343).png" alt=""><figcaption></figcaption></figure>

_**3.2. If you want to login using your wallet address**_

Select the "**Sign with Web 3.0 Address**" option.

<figure><img src="../../.gitbook/assets/image (2344).png" alt=""><figcaption></figcaption></figure>

You'll be redirected to a wallet signing screen. Choose the wallet-connect option (Polkadot or EVM) you'd like to connect with, then click "**Login**".

<figure><img src="../../.gitbook/assets/image (2345).png" alt=""><figcaption></figcaption></figure>

A signature request popup from SubWallet will appear, asking you to sign to prove you're the owner of the selected account. Click "**Approve**" to proceed.

<figure><img src="../../.gitbook/assets/image (2346).png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

**Step 4**: Once you've logged in/signed up, you'll be redirected to the Subscan homepage. Click the Profile button at the top right of the screen, then choose "**Manage**" to access the account profile.

<figure><img src="../../.gitbook/assets/image (2347).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot_7.png" alt=""><figcaption></figcaption></figure>

**Step 5**: In the Account profile screen, hover over the Dashboard section and then select the "**Manage**" button under the API key card.

<figure><img src="../../.gitbook/assets/Screenshot_8.png" alt=""><figcaption></figcaption></figure>

**Step 6**: In the API services screen, click the "**Add**" button to create your API key. Skip this step if you've already created it.

<figure><img src="../../.gitbook/assets/Screenshot_9.png" alt=""><figcaption></figcaption></figure>

**Step 7**: Enter a name for your API key. Once done, click "**Create New API Key**".

<figure><img src="../../.gitbook/assets/Screenshot_10.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot_11.png" alt=""><figcaption></figcaption></figure>

**Step 8**: Your Subscan API Key has been created! You can now get the key by clicking the Copy button. This action is needed so that you can paste it on SubWallet later.

<figure><img src="../../.gitbook/assets/Screenshot_12.png" alt=""><figcaption></figcaption></figure>

### Config API Key on SubWallet

**Step 9**: On the SubWallet homepage, click the "**Settings**" tab on the sidebar.

<figure><img src="../../.gitbook/assets/image (2578).png" alt=""><figcaption></figcaption></figure>

**Step 10**: In the Settings screen, select "**Account settings**".

<figure><img src="../../.gitbook/assets/image (2579).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You can also open the Settings screen by clicking on the account name to access the account selection tab. Then click the <img src="../../.gitbook/assets/Screenshot_25 (1).png" alt="" data-size="line"> icon to access the Settings section.

![](<../../.gitbook/assets/image (2581).png>)

![](<../../.gitbook/assets/image (2582).png>)
{% endhint %}

**Step 11**: In the Account settings screen, choose "**Config Subscan API key**".

<figure><img src="../../.gitbook/assets/image (2583).png" alt=""><figcaption></figcaption></figure>

**Step 12**: Enter the key obtained in **Step 8**, then click "**Save**" to save it in SubWallet. Once saved, the key will then be used to retrieve Subscan data for transactions on Subscan-supported networks.

<figure><img src="../../.gitbook/assets/image (2584).png" alt=""><figcaption></figcaption></figure>

That’s it—you’re all set! You can now track your real-time balance, transaction history, and more directly in the wallet using your free Subscan API key.
