---
description: This document will show you how to transfer NFT with SubWallet.
---

# Transfer NFT

**Step 1**: Open SubWallet homepage and scroll with your mouse/touchpad to see your NFT collections.

![](<../../.gitbook/assets/image (62) (1) (1) (1).png>)



**Step 2**: Choose a collection.

![](<../../.gitbook/assets/image (11) (1) (2).png>)



**Step 3**: Choose NFT in the collection, scroll to see the details, and click "Send".

![](<../../.gitbook/assets/image (146) (1) (1).png>) ![](<../../.gitbook/assets/image (25) (2).png>)

{% hint style="info" %}
Please notice the chain in which you have the NFT, because you could only send an NFT to an account that is of the same type as the chain. In this example, the NFT is on the Kusama chain - a Substrate chain, so you know that the receiving account must be a Substrate account.&#x20;
{% endhint %}



**Step 4**: Enter the receiving account address. Since we are sending an NFT that exists on Kusama, you would need to enter a Substrate account. Then click "Next".

![](<../../.gitbook/assets/image (40) (2).png>)

{% hint style="info" %}
In this new version of SubWallet, we introduced a new feature: Address book.&#x20;

This feature would save you a lot of time when entering the address for a transaction.&#x20;

By clicking the book icon on the right-hand side of the address field, you will be directed to a list of addresses including the addresses of your accounts and other addresses (contacts) you have manually saved before.&#x20;

![](<../../.gitbook/assets/image (144) (1) (1) (1).png>) ![](<../../.gitbook/assets/image (7) (3).png>)

In this case, "Eugene" is my manually saved contact. I might want to save this contact because I have to transfer to them frequently and I do not want to manually enter the address every time I make the transfer.&#x20;



To manage your address book, please follow this [guide](../manage-address-book.md).
{% endhint %}

The image below is an example of a complete input:

![](<../../.gitbook/assets/image (145) (1) (1).png>)

In this case, we are sending an NFT that exists on Kusama network to an account named "Stove". Whether you are in "All accounts" mode or single account mode, SubWallet automatically detects your sender account so you do not have to manually input that information when making a transaction request.&#x20;

{% hint style="info" %}
Guess how? Since NFT is non-fungible and unique, a particular NFT can only be held by a particular account. This is very different from fungible tokens, say, DOT, which can be held by many accounts. Due to this non-fungible attribute of the asset, we can detect the sending account automatically.&#x20;
{% endhint %}



**Step 5**: Check the transaction details and click "Approve" if you want to proceed.

![](<../../.gitbook/assets/image (3) (3) (1) (1) (1).png>)



**Step 6**: Transaction result is in!

You can either go back to the homepage or view the "receipt" of your transaction in the transaction history.&#x20;

![](<../../.gitbook/assets/image (161) (1) (1).png>)

{% hint style="info" %}
If you click "view transaction", the wallet will show you the latest transaction record in your transaction history which corresponds with the extrinsic hash of this action.&#x20;
{% endhint %}

In this case, as we are sending to an account also managed by SubWallet, there would be two (2) records corresponding with this action: one is a send record from "Arrange" to "Stove" and the other is a receive record of "Stove" from "Arrange".&#x20;

If you click the "View transaction" button, SubWallet will display the receive record, because it was recorded after the send record.

![](<../../.gitbook/assets/image (2) (3) (1) (1).png>)

However, in the History tab, you would see both records and their extrinsic hash should be identical. To get to the transaction history tab, please follow this [guide](broken-reference).

![](<../../.gitbook/assets/image (1) (4) (1).png>)
