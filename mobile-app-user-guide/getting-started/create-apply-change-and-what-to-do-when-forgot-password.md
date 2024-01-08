---
description: >-
  This document will show you some features you need to know when you use
  SubWallet for the first time.
---

# Create, apply, change and what to do when forgot password

At the start of your journey with us, we always ask you to create a password (such as when you [create a new account](../account-management/create-a-new-account-with-new-seed-phrase.md) or [import and restore an existing account](../account-management/import-restore-an-account.md)).&#x20;

If you have been using the current version of SubWallet extension wallet, when updating to the new official version, SubWallet will ask you to create and apply a master password to your existing accounts.&#x20;

<div align="left">

<figure><img src="../../.gitbook/assets/image (175).png" alt="" width="266"><figcaption></figcaption></figure>

</div>

If you have already used SubWallet before and are migrating to the new version, we would ask you to create and apply a password to your existing accounts. Please read the corresponding guide to see if it correctly describes your situation.

Once applied, you can also [change your master password](create-apply-change-and-what-to-do-when-forgot-password.md#change-master-password) if you so wish. Please note that you would need your current master password to confirm the change.&#x20;

{% hint style="warning" %}
In order to change your password, you would need to remember your old password. This function cannot help you if you forget your password and want to restore it.&#x20;

If you lose your password, you would need to [import the account](../account-management/import-restore-an-account.md) again with a seedphrase, private key, or QR code, and then set up a new password.&#x20;
{% endhint %}

## Apply master password

After creating the master password, we would ask you to apply the newly created master password to all your accounts.&#x20;

{% hint style="info" %}
You would need your old password for each account to confirm the change.&#x20;
{% endhint %}

**Step 1**: Click **Apply master password** to continue.

![](<../../.gitbook/assets/image (1088).png>)

**Step 2**: Enter your old password for each and every account you are managing with SubWallet and click **Next**.

In this example, we are managing 04 accounts with SubWallet.

![](<../../.gitbook/assets/image (1091).png>) ![](<../../.gitbook/assets/image (954).png>) ![](<../../.gitbook/assets/image (938).png>) ![](<../../.gitbook/assets/image (1364).png>)

**Step 3**: Your master password has been successfully applied! Click **Finish** to go to the Home screen.&#x20;

![](<../../.gitbook/assets/image (1438).png>)



## Change master password

{% hint style="warning" %}
Please note that SubWallet is non-custodial, so you would be the only person who knows your password; we cannot help you restore your password once it is lost.&#x20;

Please make sure that your password is well-kept. \
In order to change your password, you would need to remember your old password. This function cannot help you if you forget your password and want to restore it.&#x20;
{% endhint %}

**Step 1**: Open SubWallet and choose the list item on the top left corner to get to the Settings section.

![](<../../.gitbook/assets/image (985).png>)

**Step 2**: Choose **Security settings**, then click **Change password**.

![](<../../.gitbook/assets/image (934).png>) ![](<../../.gitbook/assets/image (1230).png>)

**Step 3**: Enter your password and click **Finish**.&#x20;

You would need your old password to confirm the change.&#x20;

![](<../../.gitbook/assets/image (1235).png>)\


### Forgot password

{% hint style="info" %}
If you forgot your account password, don't worry! You can continue the process by re-importing your account to the app. Simply ensure you have your seed phrase/JS backup file/private key/QR backup key, and you can easily regain access to your account.
{% endhint %}

**Step 1**: At the welcome page, click **Forgot password?**.

![](<../../.gitbook/assets/image (174).png>)

**Step 2:** Here, there will be 2 options provided:

* Reset account
* Erase all

Choose the option you want to apply:

![](<../../.gitbook/assets/image (172).png>)

{% hint style="info" %}
With the option to Reset account:

This action will reset **some** information associated with the account, including:&#x20;

* Balance&#x20;
* NFTs&#x20;
* Staking
* Crowdloans
* Transactions (History)
* Auth URLs (Manage website access)
{% endhint %}

{% hint style="info" %}
With the option to Erase all:

This action will reset **all** the information in the wallet. Besides the information mentioned in the Reset account option, it also resets the following information:

* List custom network
* List custom token
* Chain state&#x20;
* Asset tate&#x20;
* Setting: Pin code, Theme, Language...
* Manage address book
{% endhint %}

**Step 3:** In this step, you will re-import your forgotten account using your seed phrase/JS backup file/private key/QR backup key. For instructions on how to import an account, click [here](../account-management/import-restore-an-account.md).

{% hint style="info" %}
Please note that SubWallet will lock automatically after 15 minutes of inactive or if you exit the app.&#x20;
{% endhint %}
