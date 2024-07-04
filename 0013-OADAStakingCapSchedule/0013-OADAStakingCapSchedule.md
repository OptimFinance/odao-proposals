# 0013-OADAStakingCapSchedule

- Status: Proposed
- Authors: Optim Labs

## Context

As OADA incrementally scales post-launch there must be continuous evaluation and consideration of the sOADA vault capacity. The vault enables users to stake OADA and receive yield-bearing sOADA.

The development and deployment of additional AMOs post-launch will increase the capacity of the system to provide stakers yield that is meaningfully above Cardano’s base staking rate. In the interim, the staking vault is capped with its capacity continuously expanded to match the growth of the system. Over time we expect there to be no cap and for a market equilibrium to be reached system wide.

Until such a time is found, the cap mmust be carefully raised as to not induce large swings and unexpected weight brought into the system. We propose a mix of schedule and dynamic based approach to serve as a baseline for the vault capacity. 

## Proposal

### Proposed sOADA Capacity

The target schedule for increasing the staking cap (which is denominated in the amount of outstanding sOADA) is 1M sOADA per epoch, starting from and inclusive of 495. 

The amount may be decreased or increased by the ODAO Council, but the epoch to epoch delta on sOADA cap is not to be less than zero.

### Optim Labs Perspective

This paragraph is to serve as a guideline, but not a strict one. The ODAO Council is free to choose any path forward, within the proposed boundaries.

Staking Vault capacity must be increased slowly but surely for the system to work. 

If the demand is shown to be substantially above schedule and it would not negatively impact the stakers in an outsized way, the number should be increased higher. 

If the cap is to be raised simply to be raised, then it shouldn't be allowed to increase into infinity. Some meanigful demand should be present in advance in order to proceed. 
