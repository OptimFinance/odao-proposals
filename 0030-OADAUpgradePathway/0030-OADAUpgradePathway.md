# 0030 - OADA Upgrade Pathway

- Status: Proposed
- Authors: Optim Labs

## Context

OADA V2 has brought, in practice a need for an internalized lending market through a complete rebuild of the system which unfortunately has not provided us with any data on the demand for it. Furthermore due to the size of the system drastically contracting we believe there is a need for a yet undisclosed upgrade that will allow us to attempt to reach a yet more conservative holder segment in a push for getting liquidity. 

In order to allow such a future to pass an upgrade path that is not yet implemented via a module that authorizes the move of liquidity through a bespoke, temporarily custodying controller. The execution of such a liquidity move is to be authorized by another proposal, while the upgrade remains live after this proposal is accepted.

## Proposal

### Add Manual Upgrade Module

The Manual Upgrade Module allows us to fully abandon the OADA V2 shell and upgrade to the latest version of Plutus, add a new Direct Withdrawal AMO (replacing the old Staking AMO), and enable more direct Leviathan coverage.
