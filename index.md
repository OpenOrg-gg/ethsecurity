---
title: "Is Ethereum a Security?"
keywords: ethereum, security, SEC, regulation, law, Howey Test
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html
summary: This site is dedicated to review the technical and legal status of securities law related to Ethereum - we believe most of the views of Ethereum being a security can be resolved through a nuanced technical understanding of the protocol.
---

{% include note.html content="This site is maintained by OpenOrg and <a href='https://twitter.com/adamscochran'>@adamscochran</a>. You can contribute to the Github repo <a href='(https://github.com/OpenOrg-gg/ethsecurity)'>here</a>. This site should be deemed as research and opinion. It does not reflect legal advice or guidance." %}

# Is Ethereum a Security?
<br />
The question of if Ethereum is a security has been a topic of hot debate, especially as Ethereum transitioned to "Proof-of-Stake" a model in which users stake their Ether on a validator and take part in rewards for validating the network.
<br />
In order to answer if Ethereum is a security, at least in the eyes of US regulators, we must view it through the lens of a test known as the "*Howey Test*" which is a **three-pronged**[^1] that determines if Ethereum is a security.
<br />
It should be noted that *all* three prongs of the test must be met for something to be deemed a security.
<br />
We can review the elements of the test individually:
<br />
## 1. An investment of money:<br />

Prong #1 is simple and does not require debate. Ethereum **does** meet this criteria in a Proof-of-Stake model and requires a user buying or acquiring Ethereum to take part in staking.

The word "*money*" does not negate or by-pass this prong.

The case "*State V Gopher Tire and Rubber Co*"[^2] the court notes that "*laying out of capital in a way intended to secure income or employement*" is sufficient to meet this prong.

It is also noted in "*Uselton v. Commercial Lovelace Motor Freight*"[^3] the court expressly found that the "*investment of money*" can take the forms of "*goods or services*" or another "*exchange of value*."

Lastly, in "*SEC v. Shavers*"[^4] the court expressly found that Bitcoin and other digital currencies could meet the standard of "an investment of *money*."

<br />
{% include callout.html content="**Status:** <span style='color:red'>Meets this Prong</span>" type="danger" %} 
<br />

## 2. In a common entperise: <br />

In order to review this prong one needs to understand:

- <a href='./CommonEnterprise.html'>Common Enterprise</a>
- <a href='./EthereumValidation.html'>Ethereum Validation</a>
- <a href='./EthereumRewardsAndPenalties.html'>Ethereum Rewards & Penalties</a>

<br />

The short summary of the Ethereum Validation system is:<br />

- Your funds are not pooled with other stakers.
- If your validator is <a href="#" data-toggle="tooltip" data-original-title="{{site.data.glossary.slashed}}">slashed</a> only you receive a penalty.
- Penalties take place if are offline too long (failed technical effort) or if you are malicious.
- You are only rewarded based on the role of your validator.
- Validators are rewarded for reporting slashable offenses, making them adversarial and not communal.
- Individual block proposers profit from extended effort such as MEV that is not shared by others.
<br />
In line which each framing of common enterprise:<br />

### **Horizontal Commonality:**
<br />
As outlined in "*Revak v SEC Realty Corp*"[^5] the court looks for "*the pro-rata distribution of profits*" and the "*tying together of investors assets, via the pooling of funds*."

In "*Hart v. Pulte Homes of Michigan Corp*"[^6] and "*Salcer v. Merrill Lync, Pierce, Fenner & Smith Inc*"[^7] the courts expressly suggest that the "*investment **must** be part of a pooled group of funds*."

And in "*Milnarik v M-S Commodities*"[^8] it is noted that "*the success or failure of other contracts must have a direct impact on the profitability of plantiffs contracts*."

Since our Ethereum is not pooled and a validators profit or penalty is derived solely from their performance and does not impact other validators, we can conclude there is not "*Horizontal Commonality*."
<br /><br />
### **Vertical Commonality:**
<br />
As outlined in "*SEC v. Glenn W Turner Enters Inc*"[^9] vertical commonality requires the investors profits are "*tied inextricably to the efficacy of the promoter*"

In "*Villeneuve v. Advanced Bus Concepts Corp*"[^10] its noted that "*the fortunes of investors need be linked only to the efforts of the promoter*" and in "*Long v. Shultz Cattle Co*"[^11] expanded to note that it requires only that the "*fortunes of invesntors be tied to the fortunes of the promoters*."

First there is the challenge that it is not likely that there is grounds to find that there is an "Ethereum Promoter" any more under the definition of this role. Yet, that is novel legal precedent that would need to be tested.

Instead, if we assume the Ethereum creators were found to be "*Promoters*" for sake of the arguement, then the question is if their fortune is directly tied to the fortunes of the "investors."

By contributing to Ethereum, developers do not expressly own part of the network unless they themselves purchased Ether. As such, they cannot be deemed to be a promoter.
<br /><br />
**Commonality**
<br /><br />
The only commonality arguement that exists is that there is some sort of "common enterprise" among validators running the network, and a cooperative mechanic between validators validating a transaction. However, as those are distinct and post facto to the development of the networks code, these validators cannot sufficiently be found to be "promoters" in any established sense of the term.
<br /><br />
{% include callout.html content="**Status:** <span style='color:green'>Does not this Prong</span>" type="success" %} 
<br />
## 3. An expectation of profit, derived from the efforts of others:
<br />
The final prong of the Howey Test is if the investor can have "*an expectation of profit, **derived from** the efforts of others*."

As outlined in "<a href='./ProngsOfHoweyTest.html'>How Many Prongs Are In The Howey Test?</a>" it is important to note that this clause is a compound because:
<br />

- Users are allowed to expect profit, and,
- The common enterprise may have efforts of others.
- But, the **profit** must not be derived from the efforts of others.

<br />
In "*United Housing Foundation v. Forman*"[^12] the courts expressly noted that the core of this is based "*on a reasonable expectation of profits to be derived from the entrepreneurial or mangerial efforts of others*."

This requires that we must not only expect profit, but the profit we expect must be from the efforts of others and not be from our own efforts or goods.

In "*US v. Holtzclaw*"[^13] a church bought into a program to resell gold certificates from the "Sell America" program, the courts found that a multi-level marketing program was not a security for the aggreved party, as they only earned from sales resulting from their own efforts.

While the "*efforts of others*" were absolutely needed in order for their to be profit (Sell America had to acquire gold, issue certificates, create a system to sell and register those and redeem them) the profit expected did not stem from those efforts and **required** the efforts of the investor party to be selling.

As mentioned in the summary of <a href='./EthereumValidation.html'>Ethereum Validation</a> and <a href='./EthereumRewardsAndPenalties.html'>Ethereum Rewards & Penalties</a>, we know that:


- Validators must use their own technical expertise to maintain adequate technology and uptime.
- Their validator is *only* rewarded when it takes part in validation.
- Their validator only earns a reward or penalty, for itself, based on its own actions.
- A validtor can increase their earnings, and only their earnings through implementing MEV strategies.
- Validators can increase their earnings by reporting bad validators in the set, making clear that the validator "committee" is not a common enterprise with profits tied to each other, but instead an seperate and adverseral set of vendors.
- In theory a single validator could be rewarded if no other validator took part in the process, showing there is not a dependence on actions of others.
<br /><br />

Ultimately this prong of the Howey Test posits the question "*What are you being rewarded for?*."

In the Ethereum network, you as a validator are not rewarded on the basis that the Ethereum developers continue to develop.

Validators are selling "*reliable participation*", they are rewarded for being available and accurate. We know this because a validator is <a href="#" data-toggle="tooltip" data-original-title="{{site.data.glossary.slashed}}">slashed</a> when it has excessive downtime, or its trust becomes deficient and it is slashed on an individual level.

If we are rewarded for "*reliable participation*" and slashed when and only when we have either downtime or lose trust, then this must be what is for sale.

The question then becomes is the effort of maintaining that "*reliable participation*" by maintaining a validator sufficient that we are being clearly rewarded for our own individual actions rather than the efforts of others?

We believe the SEC has indirectly answered that for us already in "*SEC v. Homero Joshua Garza*"[^14] in which Garza was charged with violating section 5a of the Securities Law Act of 1933.

In this case, the SEC viewed that owning and managing Bitcoin mining rigs/servers *was* a managerial effort, and that selling access to their future earnings was therefore a matter of expectation of profit at the efforts of others and thus a security.

Therefore we believe it is undeniable that the maintaining of an Ethereum validator which has the additional burden and complexity of uptime and accuracy requirements, should also be viewed as the key managerial effort, and therefore does not meet this prong.
<br /><br />
{% include callout.html content="**Status:** <span style='color:green'>Does not this Prong</span>" type="success" %} 
<br />
## Summary:
<br />

**Prong #2:**<br />
- Hard to suggest there is an "*issuer*" or "*promoter*" at this point in Ethereum.
- Staking does not have horizontal commonality in relation to profits.
- Staking does have some horizontal commonality in relation to other validators, but they are not an issuer/promoter.
- Horziontal commonality in efforts is negated by the factor that the profits and loses are solely based on your own validators performance and actions.
- Your validator can be taken to another network is not locked in to any type of commonality.
- Staking does not have strong vertical commonality with the issuer.
- There is only broad vertical commonality, if you believe what is being sold is blockspace, and that the blockspace is owned by developers who publish code, but do not run the network.

<br />
**Prong #3:**<br />
- There is an expectation of profits.
- Those profits are only derived from your own ability to maintain a reliable validator.
- The maintenance of a machine performing network validation has been shown to be a key managerial effort in the past.
- You are selling uptime and validation, and not blockspace, as your validator could connect to another PoS network, or fork, with other validators and do the same action.

This would mean finding Ethereum Proof-of-Stake to not be a security.
<br /><br /><br />

## Common Arguements Debunked:

<br /><br /><br />


{% include links.html %}

<br /><br /><br /><br /><br /><br />

[^1]: <a href='./ProngsOfHoweyTest.html'>How Many Prongs Are In The Howey Test?</a>
[^2]: *Seeking non-secondary link to case*
[^3]: <a href='https://casetext.com/case/uselton-v-commercial-lovelace-motor-freight'>Uselton v. Commercial Lovelace Motor Freight</a>
[^4]: <a href='https://casetext.com/case/sec-exch-commn-v-shavers-1'>SEC v. Shavers</a>
[^5]: <a href='https://casetext.com/case/revak-v-sec-realty-corp'>Revak v. SEC Realty Corp</a>
[^6]: <a href='https://casetext.com/case/hart-v-pulte-homes-of-mich-corp'>Hart v. Pulte Homes of Michigan Corp</a>
[^7]: <a href='https://casetext.com/case/salcer-v-merrill-lynch-pierce-fenner'>Salcer v. Merrill Lynch, Pierce, Fenner</a>
[^8]: <a href='https://casetext.com/case/milnarik-v-m-s-commodities-inc'>Milnarik v. M-S Commodities, Inc.</a>
[^9]: <a href='https://www.lexisnexis.com/community/casebrief/p/casebrief-sec-v-glenn-w-turner-enters-inc'>SEC v. Glenn W. Turner Enters., Inc</a>
[^10]: <a href='https://casetext.com/case/villeneuve-v-advanced-bus-concepts-corp'>Villeneuve v. Advanced Bus. Concepts Corp.</a>
[^11]: <a href='https://casetext.com/case/long-v-shultz-cattle-co-inc-2'>Long v. Shultz Cattle Co, inc.</a>
[^12]: <a href="https://supreme.justia.com/cases/federal/us/421/837/">United Housing Foundation, Inc V. Forman</a>
[^13]: <a href="https://casetext.com/case/us-v-holtzclaw-4">US v. Holtzclaw</a>
[^14]: <a href="https://www.sec.gov/litigation/litreleases/2017/lr23960.htm">SEC v. Homero Joshua Garza"</a>
