---
description: >-
  This document will show you how to transfer tokens on cross-chain with
  SubWallet.
---

# Cross-chain transfer

{% hint style="info" %}
willCross-chain transfer refers to the process of transferring assets between different blockchains for enhanced collaboration and decentralized exchange.
{% endhint %}

**Step 1**: Open SubWallet homepage and click the "Send" button.

![](<../../../.gitbook/assets/image (706).png>)

You will be directed to a transaction request screen.

## **If you are in Single-account mode**

**Step 2:** Enter the information for the transaction.

To make a **cross-chain transfer**, click on "Select destination chain".

![](<../../../.gitbook/assets/image (802).png>)

Next, choose the chain you want to transfer tokens to.

![](<../../../.gitbook/assets/image (805).png>)

Enter the amount and the recipient's address, then click on "Transfer."

![](<../../../.gitbook/assets/image (806).png>)

{% hint style="info" %}
In this new version of SubWallet, we introduced a new feature: Address book.&#x20;

This feature would save you a lot of time when entering address for transaction.&#x20;

By clicking the book icon on the right-hand side of the address field, you will be directed to a list of addresses including: the addresses of your accounts and other addresses (contacts) you have manually saved before.

![](<../../../.gitbook/assets/image (850).png>)![](<../../../.gitbook/assets/image (707).png>)

To manage your address book, please follow this [guide](../../manage-address-book.md)
{% endhint %}



**Step 3**: Check your transaction details carefully, then click "Approve" if you want to proceed.&#x20;

![](<../../../.gitbook/assets/image (808).png>)

**Step 4**: Transaction result is in.

You can either go back to the homepage or view the "receipt" of your transaction in the transaction history.&#x20;

![](<../../../.gitbook/assets/image (1278).png>)

{% hint style="info" %}
If you click "view transaction", the wallet will show you the latest transaction record in your transaction history which corresponds with the extrinsic hash of this action.&#x20;
{% endhint %}

In this case, as we are sending to an account also managed by SubWallet, there would be two (2) records corresponding with this action: one is a send record from "SubWallet Demo" to "SubWallet-EVM Demo" and the other is a receive record of "SubWallet-EVM Demo" from "SubWallet Demo".&#x20;

![](<../../../.gitbook/assets/image (810).png>)

{% hint style="info" %}
If you click the "View transaction" button, SubWallet will display the receive record, because it was recorded after the send record.&#x20;
{% endhint %}

However, in the History tab, you would see both records and their extrinsic hash should be identical. To get to the transaction history tab, please follow this [guide](../../view-transaction-history.md).

![](<../../../.gitbook/assets/image (811).png>)![](<../../../.gitbook/assets/image (812).png>)

## **If you are in "All accounts" mode**

{% hint style="info" %}
In "All accounts" mode, most transaction steps are identical to the "Single-account mode". The only additional step that users need to perform is selecting the "Sender".

![](<../../../.gitbook/assets/image (815).png>)
{% endhint %}
