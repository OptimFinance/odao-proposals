# 0018-OADAADALendingAddition

- Status: Proposed
- Authors: Optim Labs

## Context

With the initial success of the OADA System we seek furthher avenues for opportunity in the ecosystem to grow the base for its yield. 

As initially outlined, the first step in that direction was adding the avenue to lend out the system reserves in Liqwid, and this proposal adds such capacity. 

Thanks to our proposal in the Liqwid DAO, lending ADA has become more attractive. Thus, with our developement of ADA the Lending Strategy, we propose the structure under which it will operate.

## Proposal

### Addition of the Liqwid ADA Lending Strategy

We whitelist the following script `5416303af5dd8d47818f4c19141d7f122c955ecc1eb1047509be68f1` as the Liqwid ADA Lending Strategy, to be also whitelisted into the Stake Auction Whitelist.

### Operation of OADA System with Liqwid ADA Lending Strategy

The Liqwid ADA Lending Strategy introduces an offchain controller guidance parameter under control of the ODAO Council, namely, the LiqwidADALendingCapacity. It is meant to serve as a maximum amount of ADA allocated to be lent out during the epoch to allow smooth deposits and withdrawals of the reserves to and from the Lending Market. We initialize the parameter to 15M ADA, corresponding to 20% of the total deposits into the Liqwid ADA market.

We augument the operations of the system, to the following:

At the beginning of every epoch, gather reserves. 
- Use sufficient reserves to buy back OADA to restore price to 0.999. 
- Find the pot of reserves allocated to the Liqwid ADA Ledning Strategy: 
    - Set the amount of ADA used to deposit into Liqwid as = min(LiqwidADALendingCapacity, 0.8 * TotalADAReserves)
- Find the pot of reserves allocated to the DEX AMO:
    - Set the amount of ADA used to deposit into Splash as 90% of the remaining funds
    - Use the remaining funds idle for first capital for mid-epoch buybacks 

During the epoch operations: 
- ADA auctioned off in the stake auction comes first from the ADA Lending Strategy until empty, then from the DEX AMO
- In case of a need for capital to buy back OADA, the ADA will be moved from the Liqwid deposit into the DEX AMO and used for it
    - Currently such buybacks only occur when the price drops under 0.99 and bring it back up to 0.99 ADA per OADA

In case of inability to withdraw from Liqwid, the system can do nothing but wait until it is made possible. 