EAZY Core integration/staging repository
=====================================

[![Build Status](https://travis-ci.org/EAZY-Project/EAZY.svg?branch=master)](https://travis-ci.org/EAZY-Project/EAZY) [![GitHub version](https://badge.fury.io/gh/EAZY-Project%2FEAZY.svg)](https://badge.fury.io/gh/EAZY-Project%2FEAZY)

EAZY is an open source crypto-currency focused on fast private transactions with low transaction fees & environmental footprint.  It utilizes a custom Proof of Stake protocol for securing its network and uses an innovative variable seesaw reward mechanism that dynamically balances 90% of its block reward size between masternodes and staking nodes and 10% dedicated for budget proposals. The goal of EAZY is to achieve a decentralized sustainable crypto currency with near instant full-time private transactions, fair governance and community intelligence.
- Anonymized transactions using the [_Zerocoin Protocol_](http://www.eazy.org/zpiv).
- Fast transactions featuring guaranteed zero confirmation transactions, we call it _SwiftX_.
- Decentralized blockchain voting utilizing Masternode technology to form a DAO. The blockchain will distribute monthly treasury funds based on successful proposals submitted by the community and voted on by the DAO.

More information at [eazy.org](http://www.eazy.org) Visit our ANN thread at [BitcoinTalk](http://www.bitcointalk.org/index.php?topic=1262920)

### Coin Specs
<table>
<tr><td>Algo</td><td>Quark</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Max Coin Supply (PoW Phase)</td><td>43,199,500 PIV</td></tr>
<tr><td>Max Coin Supply (PoS Phase)</td><td>Infinite</td></tr>
<tr><td>Premine</td><td>60,000 PIV*</td></tr>
</table>

*60,000 PIV Premine was burned in block [279917](http://www.presstab.pw/phpexplorer/EAZY/block.php?blockhash=206d9cfe859798a0b0898ab00d7300be94de0f5469bb446cecb41c3e173a57e0)

### Reward Distribution

<table>
<th colspan=4>Genesis Block</th>
<tr><th>Block Height</th><th>Reward Amount</th><th>Notes</th></tr>
<tr><td>1</td><td>60,000 PIV</td><td>Initial Pre-mine to be distributed to community </td></tr>
</table>

### PoW Rewards Breakdown
Only premine

<table>
<th>Block Height</th><th>Masternodes</th><th>Miner</th><th>Budget</th>
<tr><td>2-43200</td><td>20% (50 EZY)</td><td>80% (200 EZY)</td><td>N/A</td></tr>
<tr><td>43201-151200</td><td>20% (50 EZY)</td><td>70% (200 EZY)</td><td>10% (25 EZY)</td></tr>
<tr><td>151201-259200</td><td>45% (22.5 EZY)</td><td>45% (22.5 EZY)</td><td>10% (5 EZY)</td></tr>
</table>
### PoS Rewards Breakdown
     
This is preliminary, needs to be changed to what is in code
<table>
<th>Phase</th><th>Block Height</th><th>Reward</th><th>Masternodes & Stakers</th><th>Budget</th>
<tr><td>Phase 1</td><td></td><td>50</td><td>90% (45)</td><td>10% (5)</td></tr>
<tr><td>Phase 2</td><td></td><td>45</td><td>90% (40.5)</td><td>10% (4.5)</td></tr>
<tr><td>Phase 3</td><td></td><td>40</td><td>90% (36)</td><td>10% (4)</td></tr>
<tr><td>Phase 4</td><td></td><td>35</td><td>90% (31.5)</td><td>10% (3.5)</td></tr>
<tr><td>Phase 5</td><td></td><td>30</td><td>90% (27)</td><td>10% (3)</td></tr>
<tr><td>Phase 6</td><td></td><td>25</td><td>90% (22.5)</td><td>10% (2.5)</td></tr>
<tr><td>Phase 7</td><td></td><td>20</td><td>90% (18)</td><td>10% (2)</td></tr>
<tr><td>Phase 8</td><td></td><td>15</td><td>90% (13.5)</td><td>10% (1.5)</td></tr>
<tr><td>Phase 9</td><td></td><td>10</td><td>90% (9)</td><td>10% (1)</td></tr>
<tr><td>Phase X</td><td></td><td>5</td><td>90% (4.5)</td><td>10% (0.5)</td></tr>
</table>
