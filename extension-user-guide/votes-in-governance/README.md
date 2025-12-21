---
description: >-
  Participate in Polkadot OpenGov and make your voice heard on key proposals
  that shape the network's future.
---

# Votes in Governance

{% hint style="warning" %}
For now, SubWallet only supports referendum voting. OpenGov delegation will be available in upcoming releases.
{% endhint %}

## What is Governance (Polkadot OpenGov)?

Polkadot OpenGov is Polkadot's on-chain governance system, which enables token holders to collectively manage network upgrades, treasury spending, and other key protocol changes directly on-chain, without relying on centralized decision-makers.&#x20;

In OpenGov, anyone can submit a proposal, which becomes a public referendum that the community votes on using stake-weighted and conviction voting.

## **Key features of Governance** <a href="#key-features-of-polkadot-opengov" id="key-features-of-polkadot-opengov"></a>

### **Referendum**

The referenda are the key piece of Polkadot OpenGov on which all other parts rely. All referenda are proposed and submitted by members of the community.

<div data-with-frame="true"><figure><img src="../../.gitbook/assets/image.png" alt="Lifecycle of a Polkadot OpenGov Referendum. Source: Polkadot"><figcaption><p>Lifecycle of a Polkadot OpenGov Referendum. <em>Source: Polkadot</em></p></figcaption></figure></div>

Each proposal must be accompanied by a "Decision deposit." After the "Lead-in period", the votes of token holders begin to contribute to the "Support" and "Approval" of the referendum.

The "Approval" represents the current percentage of voting power (balance multiplied by conviction) in favor (**Ayes**) of that referendum. "Support" is defined by the % of "Ayes" plus abstentions out of the total possible number of votes that can be made within the system (excluding conviction adjustments).

For a referendum to be approved, it must be "Passing" by keeping both approval and support values over the track's own minimum curves during the entire "Confirmation period."

Once a referendum is approved, a typically short "Enactment period" must pass before the referendum content is enacted on-chain.

### **Tracks**

In Polkadot OpenGov, proposals are handled in different "Tracks", each with its own set of rules. When you submit a referendum, you choose a track, which determines factors such as the type of change it can make, the required deposit amount, the number of votes needed, and the duration of each phase.

Each track has specific restrictions regarding the type of referendum, submission requirements (i.e., deposit), minimum approval and support values, and the duration of each phase. For example, a track that can execute extrinsics that can make drastic changes on network parameters must be executed in the "Root" track, which has much more conservative parameters and confirmation times than the "Small Tipper" track.

### **Voters and voting power**

In Governance, token holders decide whether a referendum will be approved or rejected by voting with their tokens. Polkadot OpenGov has also inherited the ability to amplify this voting power by locking the voting balance for extended periods. With the flexibility added to the system for multiple referenda running in parallel, you can simultaneously vote with different conviction locking periods on each one.

### **Multi-role delegation**

If you want to participate in Polkadot's democracy but can't do it as often as you would like, Polkadot OpenGov allows you to delegate your voting power to delegates you trust. But that's not all; you can also delegate to different delegates for various tracks.&#x20;

For example, you can delegate your vote to someone with a more technical profile on technical tracks (e.g., "Root") while delegating the same voting power to a delegate with an economic background on tracks related to the treasury (e.g., "Small Spender" or "Big Tipper").

***

## Here are the articles in this section

{% content-ref url="view-and-manage-referendums.md" %}
[view-and-manage-referendums.md](view-and-manage-referendums.md)
{% endcontent-ref %}

{% content-ref url="cast-vote-for-a-referendum.md" %}
[cast-vote-for-a-referendum.md](cast-vote-for-a-referendum.md)
{% endcontent-ref %}

{% content-ref url="revote-for-a-referendum.md" %}
[revote-for-a-referendum.md](revote-for-a-referendum.md)
{% endcontent-ref %}

{% content-ref url="unlock-expired-votes.md" %}
[unlock-expired-votes.md](unlock-expired-votes.md)
{% endcontent-ref %}
