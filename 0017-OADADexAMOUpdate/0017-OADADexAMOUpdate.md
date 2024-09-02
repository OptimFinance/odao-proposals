# 0017-OADADexAMOUpdate

- Status: Judged
- Authors: Optim Labs

## Context

In the initial OADA Deployment the DEX AMO has been set up with a deposit guard too restrictive in order to safeguard the reserves from unforeseen circumstances.

Now that we have acquired a significantly expanded confidence in the performance of the strategy as well as confidence in the ability to timely execute the epochly routine. 

To that end we wish to push the deposit guard parameter of the DEX AMO to the limit of its efficiency, as well as update the splash stableswap deployment in preparation for the activation of their DAO.

Furthermore, the proposal makes a migration from the old stableswap pool to the new one, as well as a new Wingriders OADA/ADA stableswap.

## Proposal

### OADA DEX AMO Update

Update the "DEX AMO" (as currently understood, incliuding the strategy, the amo rule, and the auction whitelist) to be derived from the new strategy script of 3ae44baefa4d14f672d1dd9d13445cf93efbc367c08dc392e183edad

This script is parameterized by the new splash stableswap pool, and a new 'guard' parameter that allows deposits into the stable pool in a certain bounded range to prevent system reserve loss (in simple terms, don't sell OADA at under 1 ADA), initially set higher than ideal for added sanity levels of security. 

Furthermore, we change the stablepool for a new deployment to allow the epoch-crossing ADA to be staked, which was previously not happening due to an oversight.

### OADA/ADA Liquidity move

From the ~1.5M ADA TVL (at 1 OADA = 0.999362 ADA), i.e. 657,435.134585 ADA and 843,821.217589 OADA, 
Move maxium of 400k TVL into Wingriders Stableswap (with ODAO Council having the authority on how much exactly, and authority to move that sum at will between the Splash and Wingriders on) and the remaining sum of ~1.1M ADA TVL, into the new Splash Stablepool