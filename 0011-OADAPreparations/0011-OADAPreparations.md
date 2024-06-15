# 0011 - OADA Preparations

- Status: Proposed
- Authors: Optim Labs

## Context

With OADA launch fast approaching we need to line up the plans for both the treasury support of its launch, and set parameters of the protocol. 

We propose to define "The OADA System" with an initial parameter set as shown in the outlined document, and mobilize 1.5M ADA liquidity from ODAO treasury to support liquidity in the redemption pair on the Splash stableswap. 

Furthermore we mobilize 4M OPTIM, earmarked for conversion of OPTIMiz, to support the launch of an OADA vault that allows the conversion of OPTIMiz to OPTIM. 

Yet furthermore, we adjust the prior 80/20 OPTIM/ADA and OPTIM/OADA plans, given the timelines to a gradual rollout, at the discretion of ODAO Council. The intended fee structure of 1.5% can be adjusted down to 1% total on OPTIM/OADA to give it preferred capital flow. 

## Proposal

We define "OADA", "The OADA System" as a system deployment with equivalent parameter set and behavior to that outlined in [This Document](https://github.com/OptimFinance/public-documents/commit/ccbd4c5ac3803873202a8f605d641044f7a001c0), concretely chosen by the Optim Labs, with the current candidate already on mainnet. Provided that there will be no bugs found in the bug bounty program, Optim Labs will proceed with using that deployment. 

### OPTIMiz Conversion

Release 4M OPTIM into a contract managing the conversion, introducing it as a modular system for unlocking the OPTIMiz conversion

#### Proposed method of conversion

1 year lockup of X OADA, allowing Y OPTIMiz to be converted with it into Y OPTIM.

At any point in time T the user can unlock the OADA, releasing with it `(T/2)/1 year * Y` OPTIM, and burning the rest of OPTIMiz, returning the OPTIM into the treasury. In effect, if unlocked early, unlocks half of the 'vested' OPTIM. 

The Y parameter is dependent on X, and is a *maximum* that can be locked with X OADA, but not a minimum. 
Y is given by the following equation: `Y = X/5`, allowing a lock of maximum of 1 OPTIMiz for every 5 OADA.

#### Cost/benefit analysis of method of conversion

The following is a cost/benefit analysis for the method of conversion. Methodology strongly relying on a 'baseline reasonable' market behavior and performance. 

Above formula is allowing 20M OADA to be locked for a year, which we step forward projecting with the nummbers of 20% ODAO fee and 4% performance on reserves (achievable, not unrealistic but can be worse can be better, no data to support it either way. Assume <2.7% ADA baseline rate, the rest made up by strategy performance. Not guaranteed, pure projection.) 

This would support, assuming the clearing rate on ADA to be anything >5%, which roughly translates to a leverage factor of 100/63, with a little rounding this supports 32M sOADA in TVL alone getting >5% yield. We have seen this clearing rate in action with our liquidity bonds platform, and anything above it has been historically eaten up by lenders like hot cakes.

Total fees on that 52M ADA would be ~420k ADA. 

For a cost of ~4M OPTIM, i.e. at ILE prices, 2M ADA, on fees alone it would make a bit over 20% of the cost back in fees.

It's always going to be a negative carry trade to bootstrap a system, and such issuance, but under these assumptions we can model the actual cost and incentives for LPs in a reasonable way. 
In its own right if we get this to get us a total of 52M ADA in TVL alone for a year we have already won, and the cost of that is pretty much a bargain given a ~20-25% of the cost comes back as fees -- which is regarded as a pretty good margin across all of DeFi historically. 

Another important factor, from the perspective of the OADA locker, is if the APY is good enough for them. Assuming full duration lockup, with 0 cost basis for OPTIMiz, we arrive at 10% APY for OPTIM at 0.5 ADA, assuming price risk and valuing it at current market price close to ILE. 

With a cost basis of 0.25ADA on OPTIMiz historical 'rounded up average' we get ~5% APY which is exactly where we want to be. Despite a different risk profile (less principal risk, more interest risk), we should assume a similar clearing rate. 

This is all subject to price action of OPTIM and OPTIMiz and performance of reserves and liquidity and volumes so as far as modelling this goes I think it's roughly where we want to be.

Ultimately, if the goal is successful bootstrapping of the OADA protocol, this in our opinion is a bargain price to pay. 

### Mobilization of Treasury Liquidity

The proposal puts a total of 1.5M ADA of sidelined liquidity for the purposes of providing semi-permanent pool for redemption and confidence in the asset, as well as moving the yield to the LPs of the protocol. 

1.5M ADA is divided into 750k ADA used to be converted into OADA, and 750k ADA used to pair with it in the Splash stableswap.

ODAO treasury is also going to farm emissions given to the pool, once enabled and if voted on, reinforcing the ownership position of Splash. The management of these emissions is delegated to the ODAO Council.

### Adjustment to OPTIM POL

The OPTIM/ADA liquidity was set to move to an 80/20 pool, with 1.5% fees, including an issuance line to allow *all* of the ADA present in pool to be matched without price adjustments. 

Given a delicate situation on the leveage side, with OPTIM bieng used as collateral in loans, Optim Labs is in touch with the leverage providers to get a smooth transition of liquidity without affecting the market.

As such, the liquidity plans are adjusted in the following ways, all authorized by ODAO Council:
- Instead of an 80/20 OPTIM/ADA pool, an 80/20 OPTIM/OADA pool with 1% total lp fees.
- Movement of liquidity will not be a single event, but rather partial and in a few batches. 