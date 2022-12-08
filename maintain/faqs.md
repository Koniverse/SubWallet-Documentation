# FAQs

## Why does SubWallet show nothing when I use the extension on Brave?

If the extension keeps on loading and does not show balances on all networks like this, try the following steps.

![](<../.gitbook/assets/Screen Shot 2022-04-20 at 11.56.48.png>)

**Step 1**: Go to [brave://flags/](brave://flags/) and type "websockets" on the Search bar. In the drop-down menu, select **Disabled**.&#x20;

![1.1](<../.gitbook/assets/Screen Shot 2022-04-20 at 12.01.28.png>) ![1.2](<../.gitbook/assets/Screen Shot 2022-04-20 at 12.02.29.png>)

**Step 2**: Brave will ask you to relaunch the browser so that the change can take effect. Click **Relaunch** and open SubWallet extension again. Your balances should all show up now.

![](<../.gitbook/assets/Screen Shot 2022-04-20 at 12.04.56.png>) ![](<../.gitbook/assets/Screen Shot 2022-04-20 at 12.07.41.png>)

## Why do some of my nodes keep on showing nothing?

This might result from a broken link to the nodes. Follow these steps:&#x20;

**Step 1**: Reload the network using the **Reload** icon next to the network's account. If the network continues to load, move on to step 2.

![](<../.gitbook/assets/Screen\_Shot\_2022-06-09\_at\_11.00.51 (3).png>) ![](<../.gitbook/assets/Screen Shot 2022-06-09 at 15.44.13.png>)

**Step 2:** Click on the **Edit** icon to edit the network endpoints. Under Provider URL, click on the drop-down menu and choose a different link. Hit **Save**, then hit **Done**.

![](<../.gitbook/assets/Screen Shot 2022-06-09 at 15.49.04.png>) ![](<../.gitbook/assets/Screen Shot 2022-06-09 at 15.49.59.png>)

## I want to log off my wallet when I’m not at my computer. Can I do this with SubWallet?

For now, SubWallet extension doesn't have the automatic lock feature, but to keep the security of your assets, the wallet requires password everytime you submit a transaction, so no one will be able to transfer your assets without a password.

Our developers are working on the master password and locking mechanism.



## Where can I get my account address?

Your account address should be visible under your account name. If you cannot see the address, it is likely that you are in the All Accounts mode. Since an address must go with a specific account, you would need to choose the exact account you want to get the address for.

To choose an account, click on the round item on the upper right corner of the wallet, scroll and choose the specific account you want, and the address would be visible

![](../.gitbook/assets/photo\_2022-07-12\_19-42-59.jpg)



## I cannot see my assets. What’s the problem?

Make sure to active the network you have assets on

In case you have your network activated but still cannot see the asset, you might want to restart the wallet or check again later. Some networks have slow processing speed and sometimes nodes can be unstable. If you need extra support, you can always visit us on Discord and Telegram.



## I imported an account from other wallet and now I cannot see my assets. What is the problem?

Please make sure that you have activated the network on which you have the assets

In some case, if you import account by seedphrase, problems can arise if the seedphrase of your original wallet is not compatible with SubWallet. If you need further information, feel free to reach out to us via Discord and Telegram



## How do I add my USDT/USDC to SubWallet?

You can transfer USDC/USDT to SubWallet using the Moonbeam network



## I cannot unstake. What might be the problem?

The unstake feature can be unavailabe if you haven’t yet withdraw the amount you have unstaked earlier. Please claim/withdraw the assets you had unstaked before and you can continue unstaking.



## Some of the buttons on my screen are inactive

If some buttons on your homescreen such as Send funds, Receive, etc… are inactive, it is likely that you are in the All Accounts mode. Please click the round item on the upper right corner of your wallet, scroll to see your accounts and choose the account you want to use. Once a specific account has been chosen, the buttons would be enabled.



## I cannot see my staking rewards

For some networks, there has not been any data indexers to track real-time information about your staking rewards. However, you can observe your balance to know whether or not your staking is paying off. A slight increase in your total balance would be a sign of staking rewards



## Would my staking reward be restaked automatically?

If you stake on a parachain, your staking reward would not be staked automatically.

If you stake on a relaychain or solochain, then your staking reward would be restaked automatically.



## Problems connecting with Astar portal

Due to some problems with Astar portal, you might have to refresh the webpage, or if you have connected Astar with SubWallet before, forget site in SubWallet before you can access Astar.



