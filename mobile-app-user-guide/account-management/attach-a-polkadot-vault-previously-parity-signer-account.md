---
description: >-
  Learn how to attach a Polkadot Vault account (formerly Parity-Signer) to
  SubWallet.
---

# Attach a Polkadot Vault (previously Parity-Signer) account

Polkadot Vault is a cold storage solution that turns your iOS or Android device into a dedicated hardware wallet for Substrate-based networks. Your keys are kept secure (i.e., offline) at all times, and transactions are signed in an air-gapped way via QR codes.

{% hint style="warning" %}
We advise you to create a backup of your recovery phrase and update to the latest version of Polkadot Vault if you are utilizing Parity Signer (an older version of the app before its rebranding).
{% endhint %}

### Add networks to your Polkadot Vault account <a href="#add-networks-to-your-polkadot-vault-account" id="add-networks-to-your-polkadot-vault-account"></a>

Polkadot Vault supports 3 networks by default: **Polkadot, Kusama, and Westend.**

To add more networks, you can scan a **trusted** spec QR code and metadata QR fountain. Below are the detailed instructions:

**Step 1**: Navigate to the [Novasama Metadata Portal](https://metadata.novasama.io/#/polkadot). The interface should be like the image below.

This should be done on a device that is **not** your Polkadot Vault device (PC recommended).

<figure><img src="../../.gitbook/assets/image (2009).png" alt=""><figcaption></figcaption></figure>

**Step 2**: Choose the network you want to add in the **Network** tab on the sidebar.

<figure><img src="../../.gitbook/assets/image (2010).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
To make it easier, type the network you want to update in the **Search** bar.

_In this case, we want to add the Avail network._

![](https://docs.subwallet.app/~gitbook/image?url=https%3A%2F%2F631687399-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lh39Kwxa1xxZM9WX_Bs%252Fuploads%252FRwaRPv03X8VV0wWJXHXu%252Fimage.png%3Falt%3Dmedia%26token%3D7e3aca7e-c0fe-4eed-b483-af1e2dbf4834\&width=300\&dpr=4\&quality=100\&sign=eafa51e0\&sv=2)
{% endhint %}

You will see a QR code, which will be used to add the corresponding network to your account.

<figure><img src="../../.gitbook/assets/image (2011).png" alt=""><figcaption></figcaption></figure>

**Step 3**: Open the Polkadot Vault app and click on the "**Scan QR code**" button at the bottom of the screen.

<figure><img src="../../.gitbook/assets/image (2012).png" alt="" width="332"><figcaption></figcaption></figure>

**Step 4**: Scan the QR code in Step 2 to add the network. Once you've completed it, review the verifier certificate and select "**Approve**".

<figure><img src="../../.gitbook/assets/image (2013).png" alt="" width="331"><figcaption></figcaption></figure>

**Step 5**: After approving the addition of the new network, you'll be prompted to create a new key (account) for that network. It will be added to the main tab under the selected key set.

<div><figure><img src="../../.gitbook/assets/image (2) (4).png" alt="" width="333"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (1) (4).png" alt="" width="332"><figcaption></figcaption></figure></div>

**Step 6**: You have successfully added the network!

<figure><img src="../../.gitbook/assets/image (2014).png" alt="" width="332"><figcaption></figcaption></figure>

### Update network metadata <a href="#update-network-metadata-in-polkadot-vault" id="update-network-metadata-in-polkadot-vault"></a>

Given that your Polkadot Vault device is always offline and separated from any networks (air-gapped), you'll need to engage in a specific process to ensure your transactions remain valid by updating the chain metadata.

This can be done through the use of QR codes found on the [Novasama Metadata Portal](https://metadata.novasama.io/#/polkadot), which will provide your device with the information required to update the chain metadata.

To update the chain metadata, please follow the instructions below:

{% hint style="info" %}
Please look at the following example for your perusal. Here, we are updating the metadata of the Avail network.
{% endhint %}

**Step 1**: Navigate to the [Novasama Metadata Portal](https://metadata.novasama.io/#/polkadot). The interface should be like the image below.

{% hint style="info" %}
This should be done on a device that is **not** your Polkadot Vault device (PC recommended).
{% endhint %}

_In this example, we are using a PC._

<figure><img src="../../.gitbook/assets/image (2015).png" alt=""><figcaption></figcaption></figure>

**Step 2**: Choose the network you need to update in the "**Network**" tab on the sidebar.

<figure><img src="../../.gitbook/assets/image (2016).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
To make it easier, type the network you want to update in the "**Search**" bar.

![](https://docs.subwallet.app/~gitbook/image?url=https%3A%2F%2F631687399-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lh39Kwxa1xxZM9WX_Bs%252Fuploads%252FRwaRPv03X8VV0wWJXHXu%252Fimage.png%3Falt%3Dmedia%26token%3D7e3aca7e-c0fe-4eed-b483-af1e2dbf4834\&width=300\&dpr=4\&quality=100\&sign=eafa51e0\&sv=2)
{% endhint %}

**Step 3**: Go to the "**Metadata**" tab.

<figure><img src="../../.gitbook/assets/image (2017).png" alt=""><figcaption></figcaption></figure>

**Step 4**: Scan the Metadata Animated QR code using your Polkadot Vault device.

<figure><img src="../../.gitbook/assets/image (2018).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Make sure your device remains stationary while the scanning process is in progress. This may take a few minutes to complete.

![](https://docs.subwallet.app/~gitbook/image?url=https%3A%2F%2F631687399-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lh39Kwxa1xxZM9WX_Bs%252Fuploads%252FFxGKSMfCVjIcm3HpYa6m%252Fimage.png%3Falt%3Dmedia%26token%3D849952ae-7929-4a39-aba2-62817b7c2364\&width=300\&dpr=4\&quality=100\&sign=8b3410c7\&sv=2)
{% endhint %}

**Step 5**: Once you've completed, review the verifier certificate and select **"Approve**".

<figure><img src="../../.gitbook/assets/image (2019).png" alt="" width="332"><figcaption></figcaption></figure>

Now, you have successfully updated the network's metadata!

### Attach your Polkadot Vault account <a href="#attach-a-polkadot-vault-account" id="attach-a-polkadot-vault-account"></a>

**Step 1**: Open the Polkadot Vault app and have the QR code ready.

**Step 2:** On the SubWallet homepage, hit the account name at the top of the screen to access the account selection tab.

<figure><img src="../../.gitbook/assets/Screenshot_16 (7).png" alt="" width="270"><figcaption></figcaption></figure>

**Step 3**: In the account selection tab, hit the <img src="https://docs.subwallet.app/~gitbook/image?url=https%3A%2F%2F631687399-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Lh39Kwxa1xxZM9WX_Bs%252Fuploads%252FFiGMDTOg9S8t9pK5Ty8A%252FScreenshot_191.png%3Falt%3Dmedia%26token%3D0a583318-92e6-4dcc-a747-c92f918addcb&#x26;width=40&#x26;dpr=4&#x26;quality=100&#x26;sign=c2666f64&#x26;sv=2" alt="" data-size="line"> button at the bottom right corner of the screen.

<figure><img src="../../.gitbook/assets/Screenshot_1 (6).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 4**: Choose "**Connect a Polkadot Vault account**".

<figure><img src="../../.gitbook/assets/Screenshot_2 (8).png" alt="" width="272"><figcaption></figcaption></figure>

{% hint style="info" %}
If you are on the SubWallet welcome page, select the "**Attach an account**" option, then hit "**Connect a Polkadot Vault account**".
{% endhint %}

**Step 5**: Press the "**Scan QR code**" button.

<figure><img src="../../.gitbook/assets/Screenshot_3 (13).png" alt="" width="272"><figcaption></figcaption></figure>

<details>

<summary>If you haven't granted camera access to SubWallet yet</summary>

In this case, once you hit the button, your device will show the following message:

<img src="../../.gitbook/assets/Screenshot_5 (9).png" alt="" data-size="original">

Click "**Go to Settings**" to open your phone's settings.&#x20;

On the settings screen, switch the toggle next to "**Camera**" to allow the camera access to the app.

<img src="../../.gitbook/assets/Screenshot_4 (5).png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_5 (7).png" alt="" data-size="original">

</details>



**Step 6**: Scan the QR code provided in the Polkadot Vault app, or upload an image containing this QR code using the "**Upload from photos**" option.

<figure><img src="../../.gitbook/assets/Screenshot_4 (7).png" alt="" width="272"><figcaption></figcaption></figure>

**Step 7**: Once the app recognizes the QR code, a popup will appear, asking you to enter the name of your account. Once done, click "**Confirm**".

<figure><img src="../../.gitbook/assets/Screenshot_6 (1) (2).png" alt="" width="271"><figcaption></figcaption></figure>

You've successfully attached a Polkadot Vault account! If you repeat the action in **Step 2**, you will see your Polkadot Vault account displayed in the "**QR signer account**" section.

<div><figure><img src="../../.gitbook/assets/Screenshot_7 (8).png" alt="" width="272"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_8 (7).png" alt="" width="272"><figcaption></figcaption></figure></div>
