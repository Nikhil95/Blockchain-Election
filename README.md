# Blockchain-Election

# Objective:
Implementing elections on blockchain using the Ethereum blockchain platform.
Note: Indian elections are organized and conducted around smaller units called Constituencies.

# Architecture:
1.My idea is to create an Election SmartContract that holds a list of SmartContract addresses that represent Election Constituencies.

2.Every Election constituency is represented using a SmartContract that consists of Voters and Contestants and methods to enable adding Voters and Contestants and casting the vote.

3.Voters are issued an Ethereum address upon reviewing their eligibility to vote by the Election Commission and are added to the appropriate Contituency's list of Voters through a function call (can be made only by the regulatory authority, here the Election Commission).

4.The person this address corresponds to is only known to the Election Commission and the person himself.

5.A mapping (address to uint, representing Voter and the Contestant he casted his vote for) is used to represent the votes cast by the Voters.
