# 0001-LongLiveTheODAO

- Status: Proposed
- Authors: Optim Labs

## Introduction

The time has come to initiate Optim’s transition to a fully decentralized protocol. 

We’ve released and supported our first product, climbed to the top ranks of Cardano DeFi protocols, and are ready to kick off the next phase of Optim with renewed resolve and at the direction of our ever-growing community of supporters. ODAO, OPTIM token, new products

To this end, we must kickstart the Optim DAO (ODAO) and vote on a few key matters.

## ODAO Process Overview  

ODAO proposals and voting can be divided into 2 steps:

1) Temperature Check on Optim’s Github Governance Forum

2) Formal On-Chain Governance Vote on 

The Temperature Check on Optim’s Github Governance Forum allows community members to share a proposed idea and gather early community responses. Based on community brainstorming and discussions, the proposers refine their ideas until the point at which they are confident in their proposal’s ability to successfully pass a formal governance vote. [Detailed information on how to submit a proposal for temp check on Optim’s Github Governance Forum optim-finance](gitbook.io/optim-finance/governance/governance-overview/proposal-temp-check)
Official ODAO Governance Voting via the Formal Governance Forum are binding proposals voted on by the community and executed on their behalf by the Optim Foundation via Optim Labs. Proposal creators must deposit $1,000 worth of OPTIM tokens (market price at submission) to create a formal on-chain governance proposal, upon which the tokens are held under Optim’s custody. In case the proposal isn't successful, the deposited OPTIM is then burnt and removed from the circulating supply rather than returned to the proposer as is the case of a successful proposal. [Detailed information on Formal Governance proposals and voting](optim-finance.gitbook.io/optim-finance/governance/governance-overview/governance-proposal)


## ODAO First Proposal 

The ODAO’s first vote will be on a number of matters related to the OPTIM token as well as future Optim governance structure. These are combined into a single proposal to expedite decisions on closely related matters and to facilitate the advance of the ODAO final structure. 

The four matters up for temp check then formal governance vote:

- OPTIM token Initial Liquidity Event
- VC vesting schedules 
- Bond LP token airdrop 
- ODAO Constitution 

## OPTIM token Initial Liquidity Event

### Overview

Optim’s Initial Liquidity Event (ILE) will distribute the OPTM and OPTMiz tokens to participants.

It is planned to take place within a 24hour window beginning between October 28th and November 8th.

Optim proposes to allocate 11% of total supply ~ 11,000,000 OPTIM tokens ~ to its ILE
Another 4% of potential supply, in the form of 4,000,000 OPTIMiz tokens, will also be distributed

More detail on OPTIMiz will be released, but when paired with OPTIM/ADA LP tokens OPTIMiz will convert to OPTIM. OPTIMiz tokens are a bonus automatically received with each OPTIM 

11,000,000 OPTIM
- 8,000,000 OPTIM tokens will be available for ILE participants in an exchange 
- 3,000,000 OPTIM tokens will be paired with ADA for initial POL on TBD DEX 
  (protocol owned liquidity)

4,000,000 OPTIMiz 
Distributed pro rata, with each 1 OPTIM token receiving a bonus of 0.5 OPTIMiz 

*OPTIM to be paired with ADA for POL is dynamic and adjusted pro-rata to meet exchange rate

*OPTIM and OPTIMiz tokens received by the community will not be in the form of LP tokens.  
It is up to individuals to decide what to do with the OPTIM tokens received via the exchange. The LP tokens on TBD DEX will be created by pairing the amount of ADA allocated to the  ADA/OPTIM pool with the 3% of OPTIM supply reserved for this purpose. 

### Process

Before the start of the ILE, the OPTIM and OPTIMiz tokens will be sent to the ODAO treasury owned wallet for distribution. The ODAO treasury will then push these tokens to the distribution system contracted out to and built by Optim Labs for the ILE. 

The Initial Liquidity Event will begin X/X/2023 at 14:00 UTC and end in 24 hours

The ILE consists of 3 phases: First Swap Phase, Second Swap Phase, and Settlement Phase

1. First Swap Phase - an allotment of OPTIM is available in exchange for ADA 
2. Second Swap Phase -an allotment of OPTIM is available in exchange for Optim Bond Tokens
3. Settlement Phase - all orders are settled, demand between phases is balanced, and participants' OPTIM and any excess funds are sent. 

Any available unclaimed OPTIM from the second swap phase will be allocated to the pool of available OPTIM for first swap phase participants. 
If the first swap phase is oversubscribed, any excess second phase OPTIM will be automatically added to fulfill orders placed during the first phase. It will be distributed on the same pro-rata basis as a participant’s percentage of the total order pool

### First Swap Phase 

The first swap phase allows participants to exchange ADA for OPTIM tokens 

5M OPTIM are available in exchange for 2.5M ADA during this swap phase 

Participants will submit orders, all ADA will be pooled, and distributions will be calculated on a pro-rata basis with each order settling as the amount calculated as percentage of all orders submitted during this phase.. This is not first come, first serve as the intention is to prevent frontrunning bots and disorder during the ILE.

Once an order is submitted it can’t be reversed or adjusted in any way. 

In the case that more ADA is sent than OPTIM available, participants will be refunded all excess ADA beyond their final pro-rata allotment. The ADA will be sent back along with their OPTIM tokens after the Settlement phase. 

### Second Swap Phase

The second swap phase allows participants to exchange Optim Bond Tokens for OPTIM

3M OPTIM are available in exchange for 15,000 Optim Bond Tokens (1.5M ADA Face Value)  

Participants will submit orders, all Optim Bond tokens will be pooled, and distributions will be calculated on a pro-rata basis with each order settling as the amount calculated as percentage of all orders submitted during this phase.

In the case that more Optim Bond tokens are sent than OPTIM available in the second phase, participants will be refunded all excess Bond Tokens beyond their pro-rata allotment. The Bond tokens will be sent back along with all OPTIM tokens during the Settlement phase. The algorithm chooses, after rounding down the total ADA value of bonds sent, the oldest issued bonds that can be added to the user's contribution before going over their alloted cap. 
Meaning if the bond round is 3x oversubscribed, and the user has submitted 2102 ADA worth of bond tokens, their contribution will be equal to however many bond tokens, taking them from oldest to newest will be able to be taken before their value exceeds 700.666666 ada.
The remaining ada rounding error is added to the allocation of the ADA round, and, assuming that it also has overflown, it will influence its allication. Otherwise it will simply be unallocated. 

Any available unclaimed OPTIM from the second swap phase will be allocated to the pool of available OPTIM for first swap phase participants. If the first swap phase is oversubscribed, any excess second phase OPTIM will be automatically added to fulfill orders placed during the first phase. It will be distributed on the same pro-rata basis as a participant’s percentage of the total order pool.  

### Settlement Phase

The Settlement phase is a brief period during which order allocations are finalized and tokens are sent to ILE participants. Operations such as excess second phase tokens being pushed to the first phase and adjusted pro-rata calculations are executed. 

### Terms

1 ADA sent to the ILE contract will be exchanged for 2 OPTIM and 1 OPTIMiz

Exchange Rate: 
.50 ADA = 1 OPTIM  |  1 ADA = 2 OPTIM + 1 OPTIMiz (bonus)

ADA can only be exchanged for OPTIM (+OPTIMiz) in 1 ADA increments 

OPTIM and OPTIMiz tokens will be received at end of ILE duration 

The available supply and exchange rate are fixed. If less than 4MM ADA is exchanged, not all OPTIM will be distributed. 

The exchange of ADA for OPTIM is one way and final. There is no pool withdrawal or adjustment period once orders have been submitted. 

### Optim Bonds 

Optim Bonds values will be calculated at their full maturity value 
This equals 100 ADA face value + all potential accrued interest 
It assumes a bonds interest is paid to its maximum duration 

Example: 

A 6 month (36 epoch) Bond was issued at 7% APY to lenders 
At ILE the Bond is 3 months (18 epochs) into its duration

At this point, the Bond is technically worth 102.33 ADA 
(1.75 ADA interest accrued + .58 ADA interest buffer)

If the Bond reached maximum duration of 6 months the redemption value would be 103.5 ADA
Optim’s ILE system would value this bond at 103.5 ADA in calculating the amount of OPTIM a participant receives in exchange for the bond described in the above example.  

*Bonds issued after 10/17/2023 are not eligible for ILE exchange, but bonds purchased on second hand markets (that were issued before the cutoff, are)

### Liquidity Allocations

8,000,000 OPTIM (+ 4,000,000 OPTIMiz)
swapped for 4,000,000 ADA of POL

Allocation of all Optim POL: 

- DEX TBD  1,500,000 ADA < > 3,000,000 OPTIM
- DEX TBD 1,250,000 ADA < > 1,250,000 OADA  (minted from ADA) 

*The amounts above are dynamic but remain in the same percentages if less than 4M ADA is raised

## VC Vesting Schedules 

As detailed in Optim’s seed round funding Medium article Optim exchanged 10.88 % (10,880,000 OPTIM) for $3.92M. The vesting schedule is proposed as follows:

### VC Tokens - 8,689,524 OPTIM (8.69% Total Supply)

2 Month Cliff from Initial Liquidity Event (i.e no tokens to VCs for 2 months)

Months 3, 4, 5, 6  – 1,000,000 OPTIM (1%) per month 

Months 7 through 27 –  223,311 OPTIM (.22%) per month 

### Alameda Research Tokens - 2,190,476 OPTIM (2.19% Total Supply) 

2 Month Cliff from Initial Liquidity Event

10 year linear vesting after cliff

Months 3 through 123 – 18,253 OPTIM (.018%) per month   

*If owner does not come forward in timely manner to claim tokens, and if an expiry date on claims can be established by legal counsel, all 2.19% of Alameda supply will be burned 

## Optim Bond LP Airdrop 

Begin OPTIM claims for all liquidity providers who have participated in Optim Bonds no later than 1 month after ILE but likely around 2 weeks after token launch. 

Total OPTIM emissions from Bonds thus far is as follows and can be broken down into currently claimable from closed bonds and earned future claims from active bonds.

Currently Claimable: 

Catalyst Bond LPs: 16,589 OPTIM  
SPO Bond Issuers: 76,000 OPTIM
Optim Bond LPs: 20,430 OPTIM 

Earned Future Claims:

Optim Bond LPs: 500,000 OPTIM 

*Optim Bond LPs emissions, both current and future, are an estimate but within a 10% margin of error due to pro-rata LP rewards and the unknown closing dates of bonds. However, all potential Bond LP emissions to date comprise less than .75% of total supply.  

*Optim Bond LPs amount is calculated as of 17/10/2023, and should only be used as a reference. It will be updated and dropped periodically as loans close post the initial airdrop

## Team Vesting Schedule

Team earning and vesting will occur in a continuous series of tranches. Each tranche is a period of time during which the team earns tokens. The tokens from the previous tranche vest during the following earning period. Each earning and vesting period is 20 months in duration. 

*There was an earning period freeze during September & October 2023 due to TGE delay. The second earning period/ first vesting period thus begins November 2023

### Team Earning Period 1 –  January 2022 through August 2023 (20 months) 

Tokens Earned – 10.5% 

Vesting – 3 month cliff (i.e vesting begins February 2024) 
17 month linear (Feb 2024 through July 2025)
	   
### Team Earning Period 2 – November 2023 through July 2025  (20 months) 
(First Vesting Period) 

Tokens Earned – 6% 

Vesting – 20 month linear (August 2025 through May 2026)

### Team Earning Period 3 – August 2025 through May 2026 (20 months)
(Second Vesting Period) 

Tokens Earned – 4% 

Vesting – 20 month linear (June 2026 through February 2027)

## Future ODAO Structure 

The ODAO if all interests represent the future direction of the Optim DAO. It advances us towards a more comprehensive and capable DAO as Optim grows as a protocol.

Below is a brief summary outlining the general structure as well as some of its future workings. The full ODAO Constitution that outlines the future structure can be found here. 

Summary: 

We divide the DAO into three branches representing various interests. 

The Core, α, represents the interests of the token holders and has power over the protocols. The group that can execute a proposal to change the behavior of things on-chain. 

The Council, ∆, represents the self-interest of themselves and has power to manage the treasury. The group that can look and objectively evaluate what is the best strategy to grow the treasury and finance the maintenance and growth of the ODAO. 

The Court, ω, represents the ecosystem at large and evaluates the impact of the protocols on it. The group that governs legitimacy of contracts and resolves disputes. 

### META GOVERNANCE 

Distinction between governance and meta governance as used to refer to two separate layers of governance. The meta layer refers to the power of branches to restructure other branches, in a circular power structure dynamic, Core checking Council checking Court checking Core. Whereas governance is the branch-internal decision making and responsibility delegation system that may be tailored and idiosyncratic to best represent the interests of the branch. 

Meta Governace is used as a framework to keep balance of power in check, with a very simple system of decision making. It is designed to be largely optimistic in a way that each branch self governs to the best of its ability and a meta vote is only used to keep this behavior ’in check’, to be able to step in in case of a problem. The meta governance proposal may be put forward by, for example, Core to change Council. Then, the third branch, Court, has three options. Accept, Deny, and Chain Proposal, the last of which makes the execution of the original proposal conditional on, here in this example, the proposal of Court to change Core, which prompts the decision of Council on that one. 
