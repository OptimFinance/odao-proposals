# 0016-OADACatalystPartnerProgram

- Status: Judged
- Authors: Optim Labs

## Context

This proposal defines the intended behavior of the Controller at times of Catalyst rounds, assuming the vote-counting method stays the same (if not, it needs to be amended), and the intended voting method for Catalyst Votes for any vote power captured by the ODAO.

With this proposal we define a framework for projects to acquire a say in the ODAO Process of utilizing the captured ADA vote power thru provided OADA utility. This is primarilty thought of as easily quantifiable things (OADA/project token LP) but can be expanded later to other means via another vote. 

In essence, this is a juvenile version of a dual-token (or rather, multi-token) governance framework for OADA's captured vote power. We intend to further explore this, especially as times of Voltiare come.

## Proposal

### Catalyst OADA Staking Auction Behavior 

To speak of the ODAO Staking Auction behavior, we assume the snapshot of the vote power is conducted the same way as in previous funds. 
One-slot, full-power. Any adjustment to the formula will necessitate the change in the structure of the behavior in a future proposal.

We assert that the fair price of ADA stake during the Catalyst snapshot should imply an APY of 100% (approximately speaking, acquiring 10M vote power for 136k ADA) As such, the stake auction formula (which normally can be adjusted by ODAO Council, here we choose to be explicit and forbid overrides of this decision by ODAO Council), is to be conducted with a BASE of 100%, and if no bids exist at epoch end, capture ALL stake power for the ODAO and stake it normally, passing the staking yield in later.

The Vote power captured by the ODAO is utilized for the Partner Program, and also to be voted directly for 10 proposals filtered by the ODAO Council (again, interim prior to ODAO Court).

### Partner Program Definition

We define and give the ODAO Council (interim, until ODAO Court is brought into existence) the ability to recognize a project as participating in the program with the guideline that it has to be 'real enough', leaving that to the interpretation of each individual member. 

Only after the recognition by ODAO Council consensus, can the projects qualify for the Ranking Points system, and their points accrue retroactively from the start of the Ranking period.

#### Ranking Points for Fund13

This system will be evaluated at the end of the Fund period and revisited to adjust for any shortcomings and 

We define a ranking of projects by the quantititive measure of their contribution, for the purpose of giving them a fair measure.
- Total Time Weighted TVL in OADA/project token (counting OADA TVL in LP, i.e. total OADA provided)

The TOP 2 projects that qualify, will each get to direct vote of ODAO to any 2 proposals
And the remaining projects, making up the rest of the TOP 5 (3 following projects in the ranking) will each get to direct vote of ODAO to any 1 proposal

As well as choosing ANY DEX qualitying via the following measure:
- Total Time Weighted TVL in OADA/ADA pool (counting OADA TVL in LP, i.e. total OADA provided)
    (Disqualifying Splash, given DEX AMO involvement) EXCEEDED 2.5M OADA in TVL
    (Note: It is in the DEXes own best interest to make the pool in question a stableswap, but it is not necessary)
Furthermore, per each 2 pools of OADA/token (any token) that exceed Time Weighted TVL of 250k OADA in TVL, earns the DEX 1 additional vote. This is capped at 2 additional votes. The DEX NEEDS to qualify for the 2.5M OADA/ADA category first. 

Note: The Time-Weighing (for both categories) starts in epoch 500 and lasts until the Catalyst Voting begins. 

#### Rationale 

Projects at a local level have to directly strike deals with DEXes, and major ADA stakeholders to get their proposals passed, in a very nonmeritocratic and cabalistic way. We see this as a major improvement over that, a simple transparent way for them to boost their proposals while providing alignment with the Cardano DeFi 2.0 vision. 

Smaller DEXes will also benefit from this, as they themselves can only show so much ADA vote power, and by having OADA be the cross-layer of ADA Vote power, they will get a substantial boost to their ability to pass proposals. 

In the future, as more projects buy into the protocol, we will see to it that the layer of OADA is able to provide higher and higher assurance of getting proposals passed, as well as updating our pricing on the Catalyst epoch stake pricing. 