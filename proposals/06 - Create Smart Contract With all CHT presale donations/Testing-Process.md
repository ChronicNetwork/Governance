# DAO TESTING PROCESS

This document goes over the sequence taking place for testing the functionality of instantiating & utilizing a DAO smart contract, on Chronic Chain.

### The steps are as follows:

1. Upload & Instantiate Audited DA0-DA0 smart contracts
2. Test Executing Message Proposal & Voting for DAO
3. Deploy IBC Channels (Cosmos Hub, Juno Network, Osmosis Zone, Secret Network)
4. Test Functionality of IBC channels + DAO Treasury
5. Mock Trial of intended action for DAO.

## 1. Upload & Instantiate Audited DA0-DA0 smart contracts

Attached are two links, one being the v1.0.0 release of DAO-DAO's smart contracts, & the other is a cvs sheet representing the current code id's of the smart contracts on Chronic Chain.

- [DAO DAO v1 official release](https://github.com/DA0-DA0/dao-contracts/releases/tag/v1.0.0) 
- [Chronic Network Code ID Log](https://github.com/ChronicNetwork/documentation/blob/main/smart-contracts/Code-ID%20Log.csv) 

With this information, one is able to accurately verify that the smart contracts that are being used have been audited and are identical to the ones built by the DA0-DA0 team.

This wiki describes the process on [how to verify smart contracts](https://github.com/DA0-DA0/dao-contracts/wiki/Verifying-DAO-DAO-v1-contracts). 

## 2. Test Executing Message Proposal & Voting for DAO 

This step will include testing out the basic functionalities of a DAO. The following actions will be tested:

- Sending funds to a DAO treasury
- Voting to send funds out of the DAO treasury
- Attempt to vote with a non DAO member address.

These three test can gives us confidence that functions perform as expected, & unwanted functions are not functional.

## 3. IBC Channel Deployements

With a fully functioning DAO, in order for cross chain interaction, IBC channels are needed so both protocols 
can recieve and validate cross-chain messages like token transfers, smart contract calls, & much more as the multichain vision expands.

IBC Channels are able to connect any protocol using Tendermint & CosmosSDK. In this [github repository](https://github.com/ChronicNetwork/documentation/tree/main/relayers) there is a spreadsheet to help keep organize the specific channels port numbers & IBC denoms. 

All conversations regarding relayer operations are encouraged in the [validator discord chat!](https://discord.gg/yzYbbtWbwq) 

## 4. Testing of IBC Channel Integrations

Testing of IBC channel functions will take place to be able to have confidence that things are working as intended. The following will be tested: 

- Sending a protocol native token (such as OSMO,ATOM,SCRT,JUNO) via ibc channel.
- Sending a protocol native token from one chronic address to another.
- Sending a cw20 token via ibc channel (such as CanLab, & a CW20 created on [junotools](https://juno.tools/) )
- Sending CHT & CGAS tokens via ibc channel message (Osmosis, Cosmos-Hub, Secret Network, Juno Network)

This will help confirm the functionality is expected! 

## 5. Mock Trail With JunoMint Tokens

A mock trial of instantiating a DAO that has: 
- 1 voting power per participant
- 50% consensus for voting on messages
- 50 % quorum for voting on messages
- a set voting period
- permissions to change vote before the voting period ends
- A treasury that holds non native tokens (in this case will be newly minted junomint tokens, which only serve for this testing purposes).

Once the mock trial DAO is instantiated & non-native cw-20 tokens are in the DAO's treasury:
- A proposal will be executed to send tokens to a multisig wallet address
- A voting period will undergo (this will be minutes to speed up testing)
- confrimation that funds were sent to the proper destination will complete.


This testing sequence is a way to ensure the quality of the actions benefiting the whole community. 
