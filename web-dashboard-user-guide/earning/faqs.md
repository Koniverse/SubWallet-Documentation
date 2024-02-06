---
description: Frequently asked questions about SubWallet Earning feature.
---

# FAQs

### Polkadot crowdloan FAQs

1.  **What are Polkadot crowdloans?**

    Polkadot enables parachains to source tokens for their parachain bids in a crowdloan. When a parachain wins an auction, users who contribute to the crowdloan will have their DOT locked for the lease duration in exchange for rewards in the parachain’s native token. Parachains can choose to host their crowdloans natively on Polkadot or via third-party platforms like DeFi protocols or cryptocurrency exchanges.

    Learn more about crowdloans and auctions [here](https://www.polkadot.network/features/auctions/).
2.  **What happens when the crowdloan funds are unlocked?**

    If you contribute natively on Polkadot, your DOT will automatically be unlocked and distributed to your wallet. If you contribute via third-party platforms, make sure you visit these platforms for instructions on how to redeem your DOT.
3.  **Which projects have their crowdloans unlocked in the first batch?**

    The first batch of crowdloan unlocks include Moonbeam, Acala, Astar, Parallel and Clover Finance.
4.  **Do I need to claim my unlocked DOT?**

    If you contribute natively on Polkadot, your DOT will automatically be unlocked and distributed to your wallet. If you contribute via third-party platforms like DeFi protocols or cryptocurrency exchanges, make sure you visit these platforms for instructions on how to redeem your DOT.
5.  **Where can I check my crowdloan contributions?**

    You can check via SubWallet's crowdloan checking portal [here](https://web.subwallet.app/crowdloan-unlock-campaign/check-contributions).
6. **Why can't I see my crowdloan contributions in SubWallet's crowdloan checking portal?**\
   If you contributed through cryptocurrency exchanges like Binance, Kraken, Gate.io, etc... we won't be able to check your contributions.

### General FAQs

1.  **What is SubWallet Earning?**

    Earning is a feature within the SubWallet web dashboard and mobile app where you can see earning possibilities open for you and the assets you hold in the Polkadot & Ethereum ecosystem. At the moment, you can explore earning options for DOT token. Other tokens will follow shortly.
2.  **How does SubWallet Earning work?**

    While each network and each protocol works differently, SubWallet generally uses API from partner protocols to calculate and display data for each earning option. We don’t deploy smart contracts for yield optimization but rather assemble data from existing protocols to give you a panoramic picture.
3.  **Why SubWallet Earning?**

    We aggregate the best earning options from our partner protocols so that you can easily compare, make informed decisions, and participate directly on a single interface.
4.  **What are the risks of using SubWallet Earning?**

    Even though we try our best to select and display reliable earning options, as well as provide sufficient information with an error-tolerant UX, these protocols contain inherent risks that are out of our control. You should always do your own research before participating in any risk-bearing activities. SubWallet is not responsible for any loss of assets.
5.  **Can I use MetaMask?** \
    Yes, but the use of MetaMask and other EVM wallets is protocol-specific. If a protocol is EVM-compatible, there will be an option for you to connect to EVM wallets. If a protocol is Substrate-based only, you will need to use a Substrate wallet.

    We recommend using SubWallet web dashboard and mobile app, a non-custodial wallet compatible with both EVM and Substrate protocols. You can easily create or import an account and sign all transactions.
6.  **Can I use hardware wallets?**

    Yes, but the use of hardware wallets depends on each wallet’s support for specific actions. For example, Ledger already supports staking on Polkadot but hasn’t supported Bifrost yet, so you can use Ledger for Polkadot staking but not Bifrost liquid staking.
7.  **What does APY mean?**

    APY stands for annual percentage yield, which shows you the projected reward rate you will receive over a year and takes into account compound interest. Note that the projected values provided by our Earning calculator are not guaranteed and actual results may vary.
8.  **Are there fees incurred during my transactions？**

    Gas fees are incurred in each transaction that requires you to sign. Other than that, SubWallet doesn’t collect any fees from you.

### Polkadot Nomination Pool

1.  **What are Polkadot nomination pools?**

    Nomination pools are run on-chain, allowing stakers with as little as 1 DOT to pool their funds together and share rewards. Nomination pools act as single nominator accounts, where the pool owners select and manage validators on behalf of pool members, yet can’t withdraw or use members’ funds for other purposes.

    One account can only contribute to one pool. Rewards from nomination pool staking are not automatically compounded and need to be claimed or compounded manually.
2.  **When should I claim my rewards?**

    Unlike direct nomination where you can select your own payout schedule, the payout schedule for nomination pools is determined by the pool. Once the payout has been triggered, you should be able to see your rewards on the dashboard where you can choose to withdraw to your account or compound. Make sure your rewards are higher than the gas fee.
3.  **Is there a minimum active stake for nomination pools?**

    For nomination pools, the minimum active stake is equal to the minimum amount needed to participate, which is 1 DOT.
4.  **Can I unstake immediately?**

    No. Polkadot native staking requires a waiting time of 28 days before you can withdraw your stake. If you prefer dynamic withdrawal, take a look at liquid staking options.
5.  **What risks do I have when staking natively on Polkadot?**

    If a validator misbehaves and gets slashed, both validators, nominators, and pool members could lose assets. Another risk is that you may not receive staking rewards if your staked amount is lower than the minimum active stake. In both cases, choose reliable validators and constantly manage your nominations, or consider joining a trustworthy nomination pool where the pool owner manages your nominations on your behalf.

### Acala

1.  **What is liquid staking on Acala?**

    Acala establishes a decentralized and non-custodial trustless staking protocol where you can stake your DOT and receive LDOT that represents the staked DOT plus the staking yield continuously accruing.
2.  **What are LDOT and lcDOT?**

    LDOT stands for Liquid DOT, a yield-bearing token that represents the staked DOT plus the staking yield continuously accruing. lcDOT stands for Liquid Crowdloan DOT, a 1:1 representation of DOT locked in the Acala crowdloan.
3.  **How long does it take to unstake my DOT?**

    Currently, you can withdraw your DOT instantly using fast unstake or wait 28 days to withdraw with a lower fee.
4.  **Why doesn’t my LDOT balance increase over time?**

    The amount of LDOT doesn’t increase over time, only its value in DOT does. This means that by the time you decide to redeem DOT from LDOT, your LDOT should be worth more than your originally staked DOT.
5.  **Can I stake LDOT for extra rewards?**

    Yes. You can either hold LDOT to accrue staking rewards or use it in other DeFi protocols to boost your earnings.
6.  **Why can’t I unstake instantly all my LDOT?**

    If your unstaked amount is higher than the staking queue, choosing to unstake instantly will mean selling your LDOT into the pool. You can always check the amount able to be withdrawn instantly in the pool information.
7.  **I only have DOT in my wallet, can I pay transaction fees on Acala?**

    Your DOT will be automatically swapped to ACA to pay staking fees, but for unstaking transactions you need ACA.
8.  **What are the risks of LDOT?**

    The liquid staking protocol by Acala selects validators on your behalf. If a validator misbehaves and gets slashed, you face the risk of losing assets. The risk is also present when you stake natively on Polkadot.
9.  **What is the current validator set?**

    You can find the list of selected validators [here](https://polkadot.subscan.io/account/15sr8Dvq3AT3Z2Z1y8FnQ4VipekAHhmQnrkgzegUr1tNgbcn?tab=vote).

### Bifrost

1.  **What is liquid staking on Bifrost?**

    Bifrost offers an efficient form of staking referred to as liquid staking, where you can stake DOT to receive vDOT as a representative of the staked DOT plus the staking yield continuously accruing.
2.  **What are vDOT and vsDOT?**

    vDOT stands for voucher DOT, a yield-bearing token that represents the staked DOT plus the staking yield continuously accruing. vsDOT is a 1:1 representation of DOT locked in the Bifrost liquid crowdloan solution.
3.  **How long does it take to unstake my DOT?**

    Currently, you can withdraw your DOT instantly using fast unstake or wait 28 days to withdraw with a lower fee.
4.  **Why doesn’t my vDOT balance increase over time?**

    The amount of vDOT doesn’t increase over time, only its value in DOT does. This means that by the time you decide to redeem DOT from vDOT, your vDOT should be worth more than your originally staked DOT.
5.  **Can I stake vDOT for extra rewards?**

    Yes. You can either hold vDOT to accrue staking rewards or use it in other DeFi protocols to boost your earnings.
6.  **I only have DOT in my wallet, can I pay transaction fees on Bifrost?**

    Your DOT will be automatically swapped to BNC to pay staking fees, but for unstaking transactions you need BNC.
7.  **What are the risks of vDOT?**

    The liquid staking protocol by Bifrost selects validators on your behalf. If a validator misbehaves and gets slashed, you face the risk of losing assets. The risk is also present when you stake natively on Polkadot.

    However, Bifrost provides insurance for vDOT. More details can be found [here](https://docs.bifrost.finance/quick-start/faq#regarding-security).
8.  **What is the current validator set?**

    You can find the list of selected validators [here](https://bifrost.app/vstaking/vDOT?tab=validators).

### StellaSwap

1.  **What is liquid staking on StellaSwap?**

    Taking the baton from Lido, StellaSwap launches DOT liquid staking where you can stake DOT to receive stDOT as a representative of the staked DOT plus the staking yield continuously accruing.
2.  **How long does it take to unstake my DOT?**

    Currently, you can unstake your DOT immediately on SubWallet web dashboard and mobile app.
3.  **Why doesn’t my stDOT balance increase over time?**

    The amount of stDOT doesn’t increase over time, only its value in DOT does. This means that by the time you decide to withdraw DOT from stDOT, your stDOT should be worth more than your originally staked DOT.
4.  **Can I stake stDOT for extra rewards?**

    Yes. You can either hold stDOT to accrue staking rewards or use it in stDOT pools to boost your earnings.
5.  **I only have DOT in my wallet, can I pay transaction fees on StellaSwap?**

    No, you need GLMR in your EVM account to pay transaction fees on StellaSwap.
6.  **I only have DOT in my Polkadot account, how can I join liquid staking on StellaSwap?**

    You need to first transfer your DOT from Polkadot to Moonbeam. Check out the instructions here.
7.  **What are the risks of stDOT?**

    The liquid staking protocol by StellaSwap selects validators on your behalf. If a validator misbehaves and gets slashed, you face the risk of losing assets. The risk is also present when you stake natively on Polkadot.

### Parallel

1.  **What is liquid staking on Parallel?**

    Parallel offers an efficient form of staking referred to as liquid staking, where you can stake DOT to receive sDOT as a representative of the staked DOT plus the staking yield continuously accruing.
2.  **What is sDOT?**

    sDOT is a yield-bearing token that represents the staked DOT plus the staking yield continuously accruing.
3.  **How long does it take to unstake my DOT?**

    Currently, you can withdraw your DOT instantly using fast unstake or wait 28 days to withdraw with a lower fee.
4.  **Why doesn’t my sDOT balance increase over time?**

    The amount of sDOT doesn’t increase over time, only its value in DOT does. This means that by the time you decide to redeem DOT from sDOT, your sDOT should be worth more than your originally staked DOT.
5.  **Can I stake sDOT for extra rewards?**

    Yes. You can either hold sDOT to accrue staking rewards or use it in [Parallel Money Market](https://app.parallel.fi/lendAndBorrow).
6.  **I only have DOT in my wallet, can I pay transaction fees on Parallel?**

    No. You need PARA to pay transaction fees.
7.  **What are the risks of sDOT?**

    The liquid staking protocol by Parallel selects validators on your behalf. If a validator misbehaves and gets slashed, you face the risk of losing assets. The risk is also present when you stake natively on Polkadot.

    However, if this happens, Parallel will pay for the loss.
8.  **What is the current validator set?**

    You can find the list of selected validators [here](https://analytics.parallel.fi/polkadot/staking).

### Interlay

1.  **What is DOT lending on Interlay?**

    Interlay allows you to trustlessly lend and borrow wherein supplied assets can start earning interest immediately. By supplying DOT, you receive qDOT as a representative of your lent DOT plus the interest continuously accruing.
2.  **What is qDOT?**

    qDOT is a representative of your lent DOT plus the interest continuously accruing.
3.  **What is the minimum amount needed to lend DOT on Interlay?**

    There is no minimum amount required to start lending your DOT on Interlay.
4.  **Can I stake qDOT for extra rewards?**

    You can use qDOT as Vault collateral in the BTC bridge on the Interlay dApp, thus boosting your earnings.
5.  **I only have DOT in my wallet, can I pay transaction fees on Interlay?**

    Yes. Your DOT will be automatically swapped to INTR to pay transaction fees.

### vMANTA on Bifrost

1.  **What is liquid staking on Bifrost?**

    Bifrost offers an efficient form of staking referred to as liquid staking, where you can stake MANTA to receive vMANTA as a representative of the staked MANTA plus the staking yield continuously accruing.
2.  **What is vMANTA?**

    vMANTA stands for voucher MANTA, a yield-bearing token that represents the staked MANTA plus the staking yield continuously accruing.&#x20;
3.  **How long does it take to unstake my MANTA?**

    Currently, you can withdraw your DOT instantly using fast unstake or wait up to 7 days to withdraw with a lower fee.
4.  **Why doesn’t my vMANTA balance increase over time?**

    The amount of vMANTA doesn’t increase over time, only its value in MANTA does. This means that by the time you decide to redeem MANTA from vMANTA, your vMANTA should be worth more than your originally staked MANTA.
5.  **Can I stake vMANTA for extra rewards?**

    Yes. You can either hold vMANTA to accrue staking rewards or use it in other DeFi protocols to boost your earnings.
6.  **I only have MANTA in my wallet, can I pay transaction fees on Bifrost?**

    Your MANTA will be automatically swapped to BNC to pay staking fees, but for unstaking transactions you need BNC.
7.  **What are the risks of vMANTA?**

    The liquid staking protocol by Bifrost selects collators on your behalf. If a collator misbehaves and gets slashed, you face the risk of losing assets. The risk is also present when you stake natively on Manta.
