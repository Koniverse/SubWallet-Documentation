---
description: Stake alpha tokens to validator on subnets via SubWallet to earn rewards
---

# Subnet staking (dTAO staking)

## Subnet staking (dTAO staking) overview

{% hint style="success" %}
Learn more about dTAO staking [here](https://docs.taostats.io/docs/dtao).
{% endhint %}

### 1. What is dTAO staking?

At its core, Dynamic TAO (dTAO) is an upgrade to&#x20;the Bittensor network that replaces the previous emission logic with an intelligent, market-driven mechanism that&#x20;can be used to determine token emissions.

Bittensor incentivizes the production and distribution&#x20;of digital commodities by emitting newly minted TAO in&#x20;each block to a set of **subnets**. Each subnet has its own token (_Alpha_ for subnet 1, _Beta_ for subnet 2, etc.).&#x20;

The key mechanism introduced with Dynamic TAO is that each subnet operates as its own automated market maker (AMM). Each subnet has two liquidity reserves: one containing TAO (ττ)—the currency of the Bittensor network—and the other containing a subnet-specific "dynamic" currency, known as the subnet's alpha (α) token.

For simplicity, all subnet tokens will be referred to as _**alpha tokens**_.

{% hint style="info" %}
Each _**alpha**_ has a hard cap of 21 million, identical to the cap for TAO tokens.
{% endhint %}

### 2. Difference between Dynamic TAO staking & traditional TAO staking (via direct nomination)

Instead of staking TAO to a validator, in Dynamic TAO, you stake to a validator on a specific subnet. This can be either a mining subnet (most subnets) or the unique root subnet called _Subnet Zero._

* When you stake on a mining subnet, you swap TAO for a dynamic token representing the subnet's alpha where the validator operates (_**alpha tokens**_). Then, you stake that into the validator's hotkey.
* When you stake on the root subnet, you stake TAO for TAO.

{% hint style="info" %}
Any TAO staked before the launch of dTAO staking is now staked to root (Root staking).

If you prefer to stake TAO via the traditional staking method, refer to this [guide](../../manage-staking/direct-nomination/).
{% endhint %}

### 3. Alpha tokens&#x20;

in dTao staking, all subnets will have a token for staking. The subnet tokens are given a letter from an alphabet (greek, hebrew, arabic, etc.) but are generically defined as "_**Alpha**_". (Alpha is also the token of Subnet 1, as it is the first letter in the Greek alphabet).

Alpha tokens can only be purchased with TAO tokens (i.e., swap TAO for alpha).

{% hint style="info" %}
**SubWallet currently supports 70+ alpha tokens on the Bittensor network.**
{% endhint %}

### **4. dTAO staking information & parameters**

<table><thead><tr><th width="249">Parameter</th><th>Information</th></tr></thead><tbody><tr><td>Minimum stake</td><td>0.1 TAO</td></tr><tr><td>Existential deposit (ED)</td><td>0.0000005 TAO</td></tr><tr><td>Unstaking period</td><td>Up to 1.2 hours (your funds will be instantly withdrawn to your account)</td></tr><tr><td>Rewards payout</td><td><p>At the end of each era ( 1 era ~ 24 hours). </p><p>Rewards will be <strong>automatically compounded</strong>.</p></td></tr><tr><td>Nominating mechanism</td><td>Stake TAO in subnets to receive derivative alpha tokens</td></tr></tbody></table>

## Here are the articles in this section:

{% content-ref url="start-staking.md" %}
[start-staking.md](start-staking.md)
{% endcontent-ref %}

{% content-ref url="stake-more.md" %}
[stake-more.md](stake-more.md)
{% endcontent-ref %}

{% content-ref url="unstake-and-redeem-tao.md" %}
[unstake-and-redeem-tao.md](unstake-and-redeem-tao.md)
{% endcontent-ref %}
