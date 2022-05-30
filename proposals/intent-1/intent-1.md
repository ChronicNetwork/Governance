# Gov Proposal 03: intent-1

## Description: 
- Governance proposal 03 labeled 'intent-1' is a proposal to agree on a block height to halt consensus & upgrade the Chronic Network to v1.1.0.

Upgraded Features Include:
- Upgrade to Cosmos SDK v0.45.4 which includes some bug fixes & additional features.
- Upgrades to Cosmwasm v1.0.0
- Upgrades to ibc-go v3


### Details:
- Param: v1.1.0
- Block Height of upgrade: 754525

This proposal suggests block #754525 for the upgrade, which is estimated to be at Thursday 12:30 UTC using avg block time of 6.0 secs https://go.dev/play/p/npQ9vt8cIaZ. When the network reaches the halt height, the state machine of the blockchain will be halted. Validators will then switch the binary used to v1.1.0, and then the chain will continue to make progress. 
In the event of an issue at upgrade time, we will coordinate via the verified-validators channel in discord.