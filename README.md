LAPO Core Stable repository
=====================================

[![Build Status](https://travis-ci.org/LAPO-Project/LAPO.svg?branch=master)](https://travis-ci.org/LAPO-Project/LAPO) [![GitHub version](https://badge.fury.io/gh/LAPO-Project%2FLAPO.svg)](https://badge.fury.io/gh/LAPO-Project%2FLAPO)

LAPO (LAX) is the native token of the LAPO Network Protocol, all the transactions running on the network are expressed in LAX and the cost of the transaction is paid directly in LAX. The services offered in the LAPO ecosystem (ePlatform and eFinance) have a cost expressed in LAX and might require a locked minimal amount of LAX in order to work.

### 2 TIER BLOCKCHAIN MODEL

The classic Bitcoin approach is essentially a way to synchronize a distributed system through common transaction logs. It requires that each network node store the full copy of the transaction history. Obviously, this does not scale well, since eventually not every node will be able to store the full history.

LAPO Network Protocol works in a “2 Tier” Model where each tier has a specific function

The First Tier is used by the miner to secure the Blockchain using Lyra2zz Proof-of-Work algorithm until the Q2 2019. After that date the First Tier will work only on Proof-of-Stake mode inherited from PIVX.

The Second Tier is the “Masternode” level: Masternodes are used to process the transactions and the Blockchain. This approach produces the best performance possible using a robust and highly serviceable network in the most critical part of the Blockchain. The Masternode process all the Proof-of-Service algorithm.

### MASTERNODE

Unlike Bitcoin's single-tier network, where all jobs on the network are performed by miners, LAPO Network Protocol utilizes a two-tier network. Certain network functions, such as creating new blocks, are handled by the miners. The second tier of the network consists of "Masternodes" which perform more critical tasks like: Lightning Payment Confirmation and governance functions. Masternodes require 1’000’000 LAX as collateral to prevent sybil attacks. That collateral can be spent or removed at any time, but doing so removes the associated Masternode from the network.

For running a Masternode we recommend: 2GB of RAM, 2GHZ of Processor, 40GB of HD, Ubuntu 18.04 and a dedicated IP.

More information at [lapo.io](http://lapo.io)

### Coin Specs
<table>
<tr><td>Algo</td><td>Lyra2z</td></tr>
<tr><td>Block Time PoW</td><td>30 Seconds</td></tr>
<tr><td>Block Time PoS</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Max Coin Supply (PoW Phase)</td><td>12'628'000'000 LAX</td></tr>
<tr><td>Max Coin Supply (PoS Phase)</td><td>87'372'000'000 LAX</td></tr>
<tr><td>Premine</td><td>10'000'000'000 LAX</td></tr>
</table>

### Reward Distribution

<table>
<th colspan=4>Genesis Block</th>
<tr><th>Block Height</th><th>Reward Amount</th><th>Notes</th></tr>
<tr><td>1</td><td>10'000'000'000 LAX</td><td></td></tr>
</table>

### PoW Rewards Breakdown

<table>
<th>Block Height</th><th>Masternodes</th><th>Miner</th><th>Budget</th>
<tr><td>2-1051200</td><td>30% (750 LAX)</td><td>60% (1'500 LAX)</td><td>10% (250 LAX)</td></tr>
</table>

### PoS Rewards Breakdown

<table>
<th>Phase</th><th>Block Height</th><th>Reward</th><th>Masternodes & Stakers</th><th>Budget</th>
<tr><td>Phase 1</td><td>1051201-4204800	</td><td>2'500 LAX</td><td>90% (2250 LAX)</td><td>10% (250 LAX)</td></tr>
<tr><td>Phase 2</td><td>4204801-7358400</td><td>2'000 LAX</td><td>90% (1800 LAX)</td><td>10% (200 LAX)</td></tr>
<tr><td>Phase 3</td><td>7358401-10512000</td><td>1'800 LAX</td><td>90% (1620 LAX)</td><td>10% (180 LAX)</td></tr>
<tr><td>Phase 4</td><td>10512001-15768000</td><td>1'600 LAX</td><td>90% (1440 LAX)</td><td>10% (160 LAX)</td></tr>
<tr><td>Phase 5</td><td>15768001-26280000</td><td>1'400 LAX</td><td>90% (1260 LAX)</td><td>10% (140 LAX)</td></tr>
<tr><td>Phase 6</td><td>26280001-36792000</td><td>1'200 LAX</td><td>90% (1080 LAX)</td><td>10% (120 LAX)</td></tr>
<tr><td>Phase 7</td><td>36792001-47304000</td><td>1'000 LAX</td><td>90% (900 LAX)</td><td>10% (100 LAX)</td></tr>
<tr><td>Phase 8</td><td>47304001-63072000</td><td>750 LAX</td><td>90% (675 LAX)</td><td>10% (75 LAX)</td></tr>
<tr><td>Phase 9</td><td>63072001-84096000</td><td>350 LAX</td><td>90% (315 LAX)</td><td>10% (35 LAX)</td></tr>
<tr><td>Phase X</td><td>84096001-Infinite</td><td>HALVING</td><td>90%</td><td>10%</td></tr>
</table>
