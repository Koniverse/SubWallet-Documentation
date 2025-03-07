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

Polkadot Vault supports 3 networks by default: **Polkadot, Kusama, and Westend.**&#x20;

To add more networks, you can scan a **trusted** spec QR code and metadata QR fountain. Below are the detailed instructions:

**Step 1**: Navigate to the [Novasama Metadata Portal](https://metadata.novasama.io/#/polkadot). The interface should be like the image below.

This should be done on a device that is **not** your Polkadot Vault device (PC recommended).

<figure><img src="../../.gitbook/assets/image (5) (3).png" alt=""><figcaption></figcaption></figure>

**Step 2**: Choose the network you want to add in the **Network** tab on the sidebar.&#x20;

<figure><img src="../../.gitbook/assets/image (6) (3).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
To make it easier, type the network you want to update in the **Search** bar.

_In this case, we want to add the Avail network._

![](<../../.gitbook/assets/image (7) (3).png>)
{% endhint %}

You will see a QR code, which will be used to add the corresponding network to your account.

<figure><img src="../../.gitbook/assets/image (8) (3).png" alt=""><figcaption></figcaption></figure>

**Step 3**: Open the Polkadot Vault app and click on the "**Scan QR code**" button at the bottom of the screen.

<figure><img src="../../.gitbook/assets/image (9).png" alt="" width="332"><figcaption></figcaption></figure>

**Step 4**: Scan the QR code in Step 2 to add the network. Once you've completed, review the verifier certificate and select **"Approve**".

<figure><img src="../../.gitbook/assets/image (10).png" alt="" width="331"><figcaption></figcaption></figure>

**Step 5**: After approving the addition of the new network, you'll be prompted to create a new key (account) for that network. It will be added to the main tab under the selected key set.

<div><figure><img src="../../.gitbook/assets/image (11).png" alt="" width="333"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/images.png" alt="" width="332"><figcaption></figcaption></figure></div>

**Step 6**: You have successfully added the network!

<figure><img src="../../.gitbook/assets/image (12).png" alt="" width="332"><figcaption></figcaption></figure>

### Update Network metadata in Polkadot Vault <a href="#update-network-metadata-in-polkadot-vault" id="update-network-metadata-in-polkadot-vault"></a>

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

In this case, we are using a PC.

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

**Step 2**: Choose the network you need to update in the "**Network**" tab on the sidebar.

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
To make it easier, type the network you want to update in the "**Search**" bar.

![](<../../.gitbook/assets/image (7) (3).png>)
{% endhint %}

**Step 3**: Go to the "**Metadata**" tab.

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

**Step 4**: Scan the Metadata Animated QR code using your Polkadot Vault device.

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Make sure your device remains stationary while the scanning process is in progress. This may take a few minutes to complete.

![](<../../.gitbook/assets/image (17).png>)
{% endhint %}

**Step 5**: Once you've completed, review the verifier certificate and select **"Approve**".

<figure><img src="../../.gitbook/assets/image (18).png" alt="" width="332"><figcaption></figcaption></figure>

Now, you have successfully updated the network's metadata!

### Attach a Polkadot Vault account

#### **Enable/disable your permission for camera access**

You will need to grant the SubWallet extension permission to use your camera in order to import via this method.

To enable this permission, please follow these steps:

**Step 1**: Open the SubWallet extension and click on the list item at the top left of the screen to get to the Settings section.

<figure><img src="../../.gitbook/assets/Screenshot_13 (6).png" alt="" width="362"><figcaption></figcaption></figure>

**Step 2**: In the Settings screen, choose "**Security settings**".

<figure><img src="../../.gitbook/assets/Screenshot_66.png" alt="" width="362"><figcaption></figcaption></figure>

**Step 3**: In the Security settings, switch the toggle next to "**Camera access for QR**" and approve the browser's popup to enable camera access.

<div><figure><img src="../../.gitbook/assets/Screenshot_72.png" alt="" width="362"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot_177.png" alt="" width="293"><figcaption></figcaption></figure></div>

{% hint style="info" %}
If you use the Brave browser, there will be multiple options that allow you to access the camera for different durations. You can choose the time option that best fits your personal preferences.&#x20;

![](<../../.gitbook/assets/image (2) (3).png>)
{% endhint %}

{% hint style="info" %}
If you want to disable this permission, you can switch the toggle back.

<img src="../../.gitbook/assets/Screenshot_70.png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_71.png" alt="" data-size="original">
{% endhint %}

#### **Attach your account**

**Step 1**: Open your Polkadot Vault app and have the QR code ready.

**Step 2:** On the SubWallet homepage, click on the account name at the top of the screen to access the account selection tab.

<figure><img src="../../.gitbook/assets/Screenshot_23 (3).png" alt="" width="362"><figcaption></figcaption></figure>

**Step 3**: In the account selection tab, click the <img src="../../.gitbook/assets/Screenshot_191.png" alt="" data-size="line"> button at the bottom left corner of the screen.

<figure><img src="../../.gitbook/assets/Screenshot_55.png" alt="" width="362"><figcaption></figcaption></figure>

**Step 4**: Choose "**Connect a Polkadot Vault account**".

<figure><img src="../../.gitbook/assets/Screenshot_57.png" alt="" width="362"><figcaption></figcaption></figure>

{% hint style="info" %}
If you are on the SubWallet welcome page, select the "**Attach an account**" option, then click  "**Connect a Polkadot Vault account**".

<img src="../../.gitbook/assets/Screenshot_197.png" alt="" data-size="original"><img src="../../.gitbook/assets/Screenshot_200.png" alt="" data-size="original">
{% endhint %}

**Step 5**: Click the "**Scan QR code**" button.

<figure><img src="../../.gitbook/assets/Screenshot_203.png" alt="" width="363"><figcaption></figcaption></figure>

**Step 6**: Put the Polkadot Vault app (with the QR code displayed) in front of your computer and scan it with the computer's camera, or upload an image containing this QR code using the "**Upload from photos**" option.

<figure><img src="../../.gitbook/assets/Screenshot_204.png" alt="" width="363"><figcaption></figcaption></figure>

**Step 7**: Once your computer recognizes the QR code, a popup will appear, asking you to enter the name of your account. Once done, click "**Confirm**".

<figure><img src="../../.gitbook/assets/Screenshot_205.png" alt="" width="363"><figcaption></figcaption></figure>

You've successfully attached a Polkadot Vault account! If you repeat the action in **Step 2**, you will see your Polkadot Vault account displayed in the "**QR signer account**" section.

<figure><img src="../../.gitbook/assets/Screenshot_65.png" alt="" width="362"><figcaption></figcaption></figure>
