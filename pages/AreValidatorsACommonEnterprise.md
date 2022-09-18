---
title: "Are Validators a Common Enterprise?"
keywords: ethereum, validator, proof of stake, legal
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: AreValidatorsACommonEnterprise.html
summary: This page reviews how Ethereum validators operate through a legal lens, for a technical lens please see <a href='https://eth2book.info/altair/part2/incentives'>Ethereum Incentives</a>
---

# How Ethereum Validation Works:

When a user sets up an Ethereum Validator, they are required to stake 32 Ether to become part of the consensus process.

Each block, a "committe" of 128 validators is chosen from all eligible validators in the system.

One validator is the "proposer" of the block and the remainder of the commitee are responsible for attesting to the accuracy of the block. If a majority of the nodes attest to the correctness of the block, the block is finalized and members of the committee are rewarded.

## Rewards:

The rewards are established based on:

- Being a proposer
- Attesting to part of the chain
- Committee signing

Each validator does not get an equal reward, nor are they gaurenteed a reward for mere participation.

Instead the reward is based on their individual action and overall performance as a validator.

![image](https://user-images.githubusercontent.com/95639994/190914623-583f382e-0a43-43d2-8312-22990d582f53.png)

## Expertise Expanding Rewards:

By having greater uptime, and responsiveness, through improved technical deployments and redundancy a node can increase there overall participation and thus rewards.

But, through implementations like MEV searching, a validator can also be more likely to be the first to propose a block, securing them a higher reward for being the proposer.

MEV searching is a complicated but lucrative process, the site <a href='https://www.mevboost.org/'>MevBoost</a> shows stats of the top MEV searches and relays they've used to implement their process.

![image](https://user-images.githubusercontent.com/95639994/190914928-6a723d05-4442-4a5f-8025-87ec93c289f7.png)

In the image above from September 18th, 2022, we can see that address ending in `27fc` is highly profficient at building blocks that have a higher reward and proposing them quickly. They've managed to propose 2210 blocks and earned an additional 412.26 Ether ($587,355 USD) compared to others.

By comparison the second best MEV searcher has earned only an additional 70 ETH, showing the drastic difference individual expertise can make.


## Penalties:

Penalties are small fees taken from the staking balance that are different than "slashing" which is reserved for severe penalties.

A validator can recieve a small penalty in two senarios:

- When their uptime is below a safe threshold
- When they attest to incorrect information

In both of these cases, a validator is likely experiencing a technical malfunction due to poor setup or maintenece.

These penalties are individualized and do not impact others on the committee.

## Slashing

Slashing is a punishment for when validators have taken a clear malicious action that has been caught by the other members of the committee.

In this case, a validator will recieve a large penalty of their staked Ether being removed from their balance, and in turn, a portion of it is rewarded to the whistleblower validator who first identified the malicious action.


# The Legal Summary:

- Validators rely on their own individual technical expertise to set up and maintain their validator.
- The profits of a validator are individual to their own performance, participation and uptime.
- Deep technical expertise can be used to expand an individual's earning income via MEV.
- The competition to become the block proposer is adverserial and can dramatically influence individual income.
- Penalties are only applied to an individual validator based on their own performance.
- Whistle blower rewards create an adversarial committee looking for and reporting poor performance of an individual.

Proof of Stake validators derive profit from their own actions. Their fortunes, profits and punishments are derived from their own performance and rely solely on their own actively used technical expertise.

