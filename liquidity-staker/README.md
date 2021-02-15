# @uniswap/liquidity-staker

Forked from 
[https://github.com/Synthetixio/synthetix/tree/v2.27.2/](https://github.com/Synthetixio/synthetix/tree/v2.27.2/)

===================

Morpheus Labs cloned this the source code (provided with MIT license) for Liquidity Staker related contracts for the Uniswap protocol. Users can explore, modify and test the protocol on Morpheus Labs SEED platform.

===================

# Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`

The test suite includes testing the following smart contracts

1. StakingRewards

Test cases include

- rewardsDuration
- notifyRewardAmount
- stakeWithPermit
- some others

2. StakingRewardsFactory

Test cases include verification of the `StakingRewards` deployment
