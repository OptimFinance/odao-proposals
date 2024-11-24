# 0020-NewWorldOrder

- Status: Accepted
- Authors: Optim Labs

## Context

We designed this proposal for a multitude of reasons - better align incentives, improve sustainability of protocol governance, increase potential OPTIM utility, and usher in cutting-edge capabilities for the OPTIM token as the protocol matures and staking becomes a consideration.

By shifting all unissued token supply into the hands of the public, through the issuance of a new token and deprecation of the old one, this operation will reduce market cap and fully diluted valuation without affecting the per-token price post-migration.

Furthermore, *all* VC distributions will be on a 7 year linear vesting schedule. This aligns with traditional VC fund time horizons and corrects the failed industry standard from 2021/2022 of tokens with rapid vesting, low float, and high fdv. Both current and future distributions held by VCs shall be re-vested. Maintaining fair and undisturbed markets during the potential token migration necessitate the execution of steps by the ODAO and Council as follows - ODAO Council pulling all available liquidity on OPTIM from the dexes then submitting this proposal for vote. 

Any ADA collateral damage at the time of the snapshot
, to both users utilizing lending protocols and providing liquidity on dexes, shall be compensated for by Optim Labs

By the time this proposal is submitted for voting the snapshot for the potential new token distribution will have already been taken. Airdropping of the new token will be done after potential acceptance of this proposal.

The strategy put forward in this proposal stands to benefit the Optim protocol in multitude of ways, despite being merely a decisive step forward in order to lay the groundwork for positioning Optim Finance as a  leader of Cardano DeFi.

Highlighting the key parts of the proposal:
- Governance power handoff to a new token
- Airdrop of the new token to existing public holders
- Massive Tokenomic overhaul
   - 75% supply reduction
   - VCs put on a 7 year vesting schedule

## Proposal

### The Transition of Power

In broad strokes, we first describe the process that has been undertaken prior to the submission of this proposal, that which is ongoing during the voting of it, and what takes place after the completion of voting.

#### Prior to Proposal Submission

The ODAO Council has achieved consensus and pledged support for the execution of the migration.
Including, and in order to make it possible, pulling 100% of the OPTIM/ADA and OPTIM/OADA liquidity from dexes that is owned by the ODAO.

We refer to the proposed new token (asset1syldtrz2qfl280fxkz3cxq4xmrsqg75jvr2k88) as "O" and to the current/old token as "OPTIM" (asset1fdcq0j9quw9arn6zf8rzzzuqhcpl08vdwy63ym) in this proposal moving forward to disambiguate.

The O token was created through the use of the Open Sourced OTOKEN Smart Contract, and like OADA, is governance-owned. It was minted in the supply of 25 Million, and was registered to the token registry under the same clandestine moniker of "O".

Once and if the proposal is accepted, the O token shall be renamed to "OPTIM" via the registry to fully replace the old OPTIM as the governance token of ODAO.

#### During the Proposal Voting

We fully expect the community to be in overwhelming support of the proposal, however in the transitionary period we also expect turbulence, including the open market price of OPTIM to be trading at near or close to zero, for the full duration of the proposal up until resolution of it, given that if the proposal is accepted, the OPTIM token becomes effectively meaningless, migrated to O.

#### After the Voting concludes

If the proposal doesn't pass, the ODAO Council has pledged to return liquidity into the dex in the same state it was pulled out prior to the submission of this proposal, and we continue with no changes.

If, however, the proposal passes, we shall execute it immediately and henceforth not return in consideration to the case that it doesn't.
The ODAO Council will provide O/ADA and O/OADA liquidity into the dexes at the same per-token price as the old token at the moment of the removal of liquidity, which coincides with the snapshot for the O distribution.

We shall distribute the new token soon after the vote passes, and after liquidity is provided on the dexes.

### New Token, New Tokenomics

This section is dedicated to more detail of the new distribution and exact mechanics of it.

We preface it, by mentioning, again, that the snapshot was already taken, and it includes tokens held in smart contracts and divided by public, team and vc groups.

#### Public:Holder Tokens

We define publicly held as not having received tokens as part of the team distribution or through the saft acquired by venture capital firms. In other words, everything but VC and Team.

OPTIM tokens held in pubkey addresses shall be airdropped to automatically in the first distribution wave, and will be dropped 1:1, meaning, for each OPTIM token held, an O token is airdropped.

The tokens held in smart contracts (dex, lending) shall not be distributed automatically and will require manual distribution by creating a ticket on the discord server to accelerate the process, or, it shall be airdropped later.

Of note, as well, the "bonds airdrop" OPTIM allocation is fdv-scaled down and and airdropped as though it was part of the public distribution already.

We allocate 7.75M O tokens to this distribution, and once the distribution is finalized, the remainder is allocated to the ODAO Treasury.

#### Team Tokens

The vesting schedule of team allocation is changed to only include period 1 and 2.

Team Earning Period 1 — January 2022 through August 2023 (20 months)
Tokens Earned — 4M
Vesting — 3 month cliff (i.e vesting begins February 2024)
17 month linear (Feb 2024 through June 2025)

Team Earning Period 2 — November 2023 through June 2025 (20 months)
Tokens Earned — 2M
Vesting — 20 month linear (July 2025 through February 2027)

This change is done to simplify the distribution and allocations of the asset, removing unnecessary tail emissions.

We allocate 6M O tokens to this distribution.

#### VC Tokens

Unilaterally the VC firms are moved to a 7 year vesting schedule, from January 2025 through January 2032.

There is one VC firm, split into two sub-funds and wallets, that will have its vesting scheudle remain unchanged due to terms in their original SAFTs that don’t allow for such changes. These tokens comprise 9.5% of the total VC allocation if proposal passes.

These are current wallets:
* addr1q8ef4vvdsrk3egzqwlswlfxcfwyawa3t0mn287x3z2ce9maj5dtkw4v27dr74nvhulfs0f8qdd2gc00x4rh6yz2l2aqsnw0ywa
* addr1q9ndyd4n4fcqfmuy49p5d3skcrz3t5yqppvzk7yj6fqx7evvl4lfqrsr892yw3kxt750dlln50t3mcfpx9323klhyvmsgmxvpx

We allocate 2.7M O tokens to this distribution.

#### Public:OPTIMiz Conversion

Given the radical changes to OPTIM, while the existing OADA Locks will be respected and receive the exact amount of O that they would OPTIM through manual distribution.

We, however, drop support for further locks to be created until another proposal addresses the matter and we assess the situation once the new order is in play for sufficiently long.

Otherwise the plan for OPTIMiz remains the same as promised and plan to support conversions in a similar fashion as before.

Conversions are to be live for 1 year once they are started again, and afterwards any unconverted or unconverting $O will be moved into the ODAO Treasury.

We allocate 4M O tokens to this distribution.

#### Listings

Previously called Market Making, this is a portion explicitly carved out to allow Centralized Exchange listings. It is controlled by Optim Labs to enable sufficient confidentiality.

We allocate 0.5M O tokens to this distribution.

#### Treasury

This category is initially assigned to be in control of the ODAO Council for the purposes of Liquidity Provision on DEXes in a dynamic way.

Once that is carried out, the ODAO Treasury may utilize it for other purposes as well through a vote.

We allocate 4.05M tokens to this distribution.