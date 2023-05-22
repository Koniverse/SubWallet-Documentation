---
description: >-
  This document will show you How to Start Staking (Also known as Bonding)
  Tokens on SubWallet.
---

# Start staking

For now, SubWallet has already supported 2 staking methods in-app including joining pools and nominating.\
By joining pools, you can stake on Polkadot (DOT), Kusama (KSM) & Aleph Zero (AZERO).\
By nomination, SubWallet has supported 14 networks containing Polkadot (DOT), Kusama (KSM), Aleph Zero (AZERO), Polkadex (PDEX), Ternoa (CAPS), Moonbeam (GLMR), Moonrive (MOVR), Turing (TUR), Calamari (KMA), Bifrost Kusama (BNC), Amplitude (AMPE), Kilt Spiritnet (KILT), Astar (ASTR), Shiden (SDN).

## If you want to directly stake to a validator (become a Nominator)

**Step 1**: Open SubWallet and choose the Staking tab. Then click the "+" icon on the upper right corner to start staking.&#x20;

![](<../../.gitbook/assets/image (175).png>)



**Step 2**: Choose the "Nominate" type of staking and enter staking information.&#x20;

![](<../../.gitbook/assets/image (173) (1).png>)

{% hint style="info" %}
If you are in all-accounts mode like the current example, you would need to choose the staking account.&#x20;

If you have already been in a single account, you would not have to select account. Your Step 2 would be as the following image:

![](<../../.gitbook/assets/image (182).png>)
{% endhint %}

We suggest you pay close attention to the validator you are choosing. When selecting validator, SubWallet support you with the latest record of validator details. Please click the three-dot icon on the right hand side of each validator to see the validator details.

![](<../../.gitbook/assets/image (163) (1).png>) ![](<../../.gitbook/assets/image (181) (1).png>)

{% hint style="info" %}
You could use the sort function to find the most suitable validator according to your need. Please click the sort icon on the upper right corner and choose your sorting criteria.&#x20;

![](<../../.gitbook/assets/image (169) (2).png>) ![](<../../.gitbook/assets/image (166) (1).png>)
{% endhint %}

After choosing the validator, please make sure that the amount you want to stake is at least equal or higher than the validator's minimum staking required.&#x20;

An example of a complete staking request would be as the following:

![](<../../.gitbook/assets/image (161).png>)

In this case we are staking 100 TZERO with an account named "Apology". APY is expected to be 217.02% per annum.&#x20;

The "Minimum active" stake of 100 TZERO means that once staked, you would always need to keep your active stake above 100 TZERO, which means you would not be able to unstake if your estimated active stake after such unstaking falls below 100 TZERO. This is an important information to keep in mind.&#x20;

If you wish to proceed with the staking request, click the "Stake" button.&#x20;



**Step 3**: Confirm staking and click "Approve"

![](<../../.gitbook/assets/image (157).png>)



**Step 4**: Result is in!

You could see your staking transaction in the History tab.

![](<../../.gitbook/assets/image (158).png>)

{% hint style="info" %}
If you click "view transaction", the wallet would show you the latest transaction record in your transaction history which corresponds with the extrinsic hash of this action.&#x20;
{% endhint %}

To get to the transaction history tab, please follow this [guide](broken-reference).

![](<../../.gitbook/assets/image (177) (1).png>) ![](<../../.gitbook/assets/image (180) (1).png>)

##

## If you want to stake in a nomination pool (Pooled staking)

{% hint style="info" %}
SubWallet is currently supporting pooled staking for Substrate blockchains.&#x20;
{% endhint %}

**Step 1**: Open SubWallet and choose the Staking tab. Then click the "+" icon on the upper right corner to start staking.&#x20;

![](<../../.gitbook/assets/image (3) (3).png>)



**Step 2**: Choose the "Pool" tab in the "Add to Bond" screen and enter the staking information.&#x20;

![](<../../.gitbook/assets/image (159) (2).png>)

{% hint style="info" %}
If you are in all-accounts mode like the current example, you would need to choose the staking account.&#x20;

If you have already been in a single account, you would not have to select account. Your Step 2 would be as the following image:

![](<../../.gitbook/assets/image (155) (1).png>)
{% endhint %}

We suggest you pay close attention to the pool you are choosing. When selecting pool, SubWallet support you with the latest record of pool details. Please click the three-dot icon on the right hand side of each pool to see the pool details.

![](<../../.gitbook/assets/image (171) (2).png>) ![](<../../.gitbook/assets/image (162) (2).png>)

{% hint style="info" %}
You could use the sort function to find the most suitable validator according to your need. Please click the sort icon on the upper right corner and choose your sorting criteria.&#x20;

![](<../../.gitbook/assets/image (184).png>) ![](<../../.gitbook/assets/image (156).png>)
{% endhint %}

{% hint style="info" %}
We also identify destroyed/ inactive pool. **We suggest that you always choose an active pool to stake with**.&#x20;

To filter out active pool, click the fader icon on the right hand side of the search validator bar. Then click the checkbox "Active validator".&#x20;

![](<../../.gitbook/assets/image (179) (1).png>) ![](<../../.gitbook/assets/image (178).png>)
{% endhint %}

An example of a complete input for pooled staking would be like the following image:

![](<../../.gitbook/assets/image (154) (2).png>)

The minimum active stake of 1 AZERO means that once staked, you would always need to keep your active stake above 1 AZERO, which means you would not be able to unstake if your estimated active stake after such unstaking falls below 1 AZERO. This is an important information to keep in mind.

Click "Stake" to continue.



**Step 3**: Check the information and confirm your staking request by clicking "Approve".&#x20;

![](<../../.gitbook/assets/image (164) (1).png>)



Step 4: Result is in!

You could see your staking transaction in the History tab.

![](<../../.gitbook/assets/image (172) (2).png>)

{% hint style="info" %}
If you click "view transaction", the wallet would show you the latest transaction record in your transaction history which corresponds with the extrinsic hash of this action.&#x20;

In this example, the staking request was a failed transaction because we did not stake enough AZERO to also cover the fee.&#x20;

Network fee could be extra small (so it would appear zero in the confirmation screen). Best practice to keep in mind is to always stake slightly above minimum active stake.&#x20;

![](<../../.gitbook/assets/image (160).png>)
{% endhint %}

To get to the transaction history tab, please follow this [guide](broken-reference).

![](<../../.gitbook/assets/image (165) (1).png>)

