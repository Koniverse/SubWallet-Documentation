# FAQs

## Can I use the SubWallet mobile app on iOS 17?

Yes, but due to iOS 17’s instability, you may run into some problems. SubWallet has recorded several cases where users reported losing app data after updating to iOS 17.1, so we recommend either not updating yet or **backing up your data** before updating to iOS 17 (see instructions below). We are working hard to resolve this problem. For updated information, please join our [Telegram](https://t.me/subwallet) or [Discord](https://discord.gg/vPCN4vdB8v).

{% content-ref url="account-management/export-and-backup-accounts.md" %}
[export-and-backup-accounts.md](account-management/export-and-backup-accounts.md)
{% endcontent-ref %}

<mark style="color:yellow;">**Nov 28, 2023 update**</mark>: For user security and app performance, SubWallet, like many iOS apps, has been using the Apple webkit to store app data locally on the device. Therefore, app data loss can happen due to the iOS 17 webkit's instability. This problem has been reported by multiple applications running on iOS and using Apple webkit for local data storage. \
We have implemented hotfixes in v1.1.11 (241) to lower the risk of losing app data, and we will continue to work on a drastic solution in the coming days.

<mark style="color:yellow;">**Nov 30, 2023 update**</mark>: The issue has been fixed in v1.1.12 (242). All users are recommended to update to the latest version.

## I can't sign transactions via Polkadot Vault on EVM networks.

This is due to the latest update of the Polkadot Vault app, in which Polkadot Vault no longer supports signing transactions for the EVM networks (Moonbeam, Moonriver, Moonbase).

If you have assets on these networks on Polkadot Vault, please follow the steps below to transfer them out of your Polkadot Vault account:

{% hint style="info" %}
In this example, we want to transfer GLMR on Moonbeam out of the account using an iPhone.
{% endhint %}

**Step 1**: On the homepage, click on the Moonbeam Key Set.

<figure><img src="../.gitbook/assets/Screenshot_33.png" alt="" width="376"><figcaption></figcaption></figure>

**Step 2**: Click on the 3-dot icon at the top right of the screen and click the "**Share Private Key**" option.

<figure><img src="../.gitbook/assets/Screenshot_34.png" alt="" width="374"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot_41.png" alt="" width="374"><figcaption></figcaption></figure>

**Step 3**: Enter your passcode to authorize the action, then choose the "**Export Private Key**" button.

<figure><img src="../.gitbook/assets/image (1967).png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Screenshot_35.png" alt="" width="377"><figcaption></figcaption></figure>

The "**Export Private Key**" screen will pop up with the QR code of your private key. Screenshot and keep it in a safe place.

<figure><img src="../.gitbook/assets/image (1968).png" alt="" width="375"><figcaption></figcaption></figure>

**Step 4**: Open the SubWallet extension. On the SubWallet homepage, click on the account name at the top left of the screen to get to the account list.

<figure><img src="../.gitbook/assets/image (1969).png" alt="" width="374"><figcaption></figcaption></figure>

**Step 5**: Click the "**Import**" icon at the bottom of the account list.

<figure><img src="../.gitbook/assets/image (1970).png" alt="" width="374"><figcaption></figcaption></figure>

**Step 6**: Choose the "**Import by QR code**" option.

<figure><img src="../.gitbook/assets/image (1971).png" alt="" width="374"><figcaption></figcaption></figure>

**Step 7**: Click the "**Scan the QR code**" button.

<figure><img src="../.gitbook/assets/image (1972).png" alt="" width="374"><figcaption></figcaption></figure>

**Step 8**: If you have not previously granted camera access to SubWallet, please click "**OK**" to allow.

Then, choose the "**Upload from photos**" option and select the screenshot you have taken in **Step 3**.

<figure><img src="../.gitbook/assets/image (1973).png" alt="" width="374"><figcaption></figcaption></figure>

**Step 9**: After successfully importing the account, you will be directed to the homepage. You can now transfer your GLMR to another account using the guide [here](https://docs.subwallet.app/main/mobile-app-user-guide/receive-and-transfer-assets/transfer-tokens).

### How do I sync my account on the mobile app to the extension using the QR code?

You can easily sync your account on mobile to the extension by exporting your account's QR code. If you have multiple accounts, repeat the instructions below for each account.

**Step 1:** Export your account's QR code by following this [guide](https://docs.subwallet.app/main/mobile-app-user-guide/account-management/export-and-backup-accounts). Please note that in Step 4 of the guide, select "**Export QR code**" only.

You can either screenshot it or keep your mobile on the export screen.

![](https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-Lh39Kwxa1xxZM9WX\_Bs%2Fuploads%2FCE5om6nO1QjKqx3LqEYt%2Fphoto\_2024-06-24\_17-50-05%20\(3\).jpg?alt=media\&token=88f8fd2a-682d-47bb-92b9-7d4974a9f8a8)

**Step 2**: Import your newly exported account onto the extension by following this [guide](https://docs.subwallet.app/main/extension-user-guide/account-management/import-and-restore-an-account#import-by-qr-code).

{% hint style="info" %}
If you have not yet installed the SubWallet extension, you can do so by clicking on the relevant link for your browser:&#x20;

* For Google Chrome, Brave & MS Edge users, click [here](https://chrome.google.com/webstore/detail/subwallet-polkadot-extens/onhogfjeacnfoofkfgppdlbmlmnplgbn).&#x20;
* For Firefox users, click [here](https://mzl.la/3AoAMmd).
{% endhint %}
