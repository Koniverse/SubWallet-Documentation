# Transfer tokens

**Step 1**: Open SubWallet and click the Send button

![](<../../.gitbook/assets/image (48) (2).png>)

You would be directed to a transaction request screen.

{% hint style="info" %}
In this new version of SubWallet, we introduced a new feature: Address book.&#x20;

This feature would save you a lot of time when entering address for transaction.&#x20;

By clicking the book icon on the right hand side of the address field, you would be directed to a list of addresses including: the addresses of your accounts and other addresses (contacts) you have manually saved before.&#x20;

![](<../../.gitbook/assets/image (150).png>) ![](<../../.gitbook/assets/image (149).png>)\


In this case, "Eugene" is my manually saved contact. I might want to save this contact because I have to transfer to them frequently and I do not want to manually enter the address everytime I make transfer.&#x20;



To manage your address book, please follow this [guide](broken-reference).
{% endhint %}

## **If you are in "All accounts" mode**

**Step 2**: Enter the information for the transaction and click the "Transfer" button. In this example, we are sending ACA.&#x20;

Please note that the destination account and the destination chain must be of the same type.&#x20;

For example, if you choose Acala as your destination chain, the destination account must be a Substrate account.

![](<../../.gitbook/assets/image (45) (2).png>)

{% hint style="info" %}
SubWallet support both single-chain transfer and cross-chain transfer (also known as teleporting or XCM).&#x20;

In this example, user can send ACA to either Acala (single-chain) or Moonbeam (cross-chain).

To specify the type of transfer, you would only need to choose the destination chain.

![](<../../.gitbook/assets/image (148).png>) ![](<../../.gitbook/assets/image (5) (1).png>)


{% endhint %}

A completed transfer request would look like the following image:

![](<../../.gitbook/assets/image (30) (3).png>)

Here we are doing a transfer of 0.0001 ACA from an account named "Arrange" to an account named "Stove - EVM". The transfer would be cross-chain, from Acala to Moonbeam.\
Click "Transfer".

## **If you are in Single-account mode**

**Step 2:** Enter the information for the transaction and click the "Transfer" button. In this example, we are sending ACA.

The only difference from the "All accounts" mode is that you would not have to choose a sender account.&#x20;

{% hint style="info" %}
In this new version of SubWallet, we introduced a new feature: Address book.&#x20;

This feature would save you a lot of time when entering address for transaction.&#x20;

By clicking the book icon on the right hand side of the address field, you would be directed to a list of addresses including: the addresses of your accounts and other addresses (contacts) you have manually saved before.\
In this new version of SubWallet, we introduced a new feature: Address book.&#x20;

This feature would save you a lot of time when entering address for transaction.&#x20;

By clicking the book icon on the right hand side of the address field, you would be directed to a list of addresses including: the addresses of your accounts and other addresses (contacts) you have manually saved before.&#x20;

![](<../../.gitbook/assets/image (46) (2).png>) ![](<../../.gitbook/assets/image (143) (1).png>)\


In this case, "Eugene" is my manually saved contact. I might want to save this contact because I have to transfer to them frequently and I do not want to manually enter the address everytime I make transfer.&#x20;

To manage your address book, please follow this [guide](broken-reference)
{% endhint %}

Here we are doing a transfer of 0.0001 ACA from an account named "Arrange" to an account named "Stove - EVM". The transfer would be cross-chain, from Acala to Moonbeam.\
Click "Transfer".

{% hint style="info" %}
"All accounts" mode and "Single-account" mode share the same confirmation proccess. So in this guide, the differences are in Step 1 and Step 2 only. &#x20;
{% endhint %}

**Step 3**: Check your transaction details, then click "Approve" if you want to proceed.&#x20;

![](<../../.gitbook/assets/image (24) (1).png>)

**Step 4**: Transaction result is in.

You can either go back to homepage or view the "receipt" of your transaction in the transaction history.&#x20;

![](<../../.gitbook/assets/image (8) (2).png>)

{% hint style="info" %}
If you click "view transaction", the wallet would show you the latest transaction record in your transaction history which corresponds with the extrinsic hash of this action.&#x20;
{% endhint %}

In this case, as we are sending to an account also managed by SubWallet, there would be two (2) records correspond with this action: one is a send record from "Arrange" to "Stove - EVM" and the other is a receive record of "Stove - EVM" from "Arrange".&#x20;

If you click the "View transaction" button, SubWallet would display the receive record, because it was recorded after the send record.&#x20;

![](<../../.gitbook/assets/image (152).png>)

However, in the History tab, you would see both records and their extrinsic hash should be identical. To get to the transaction history tab, please follow this [guide](broken-reference).

![](<../../.gitbook/assets/image (44) (2).png>)

![](<../../.gitbook/assets/image (19) (1).png>) ![](<../../.gitbook/assets/image (6) (1).png>)
