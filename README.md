# RAJ-CHAIN
A Blockchain implementation on "Bhamashah Scheme" of Rajasthan Govt. demonstrating allocation of funds and spent as planned,made for Rajasthan Hackathon 2018




































# Technical Specifications
Framework used - HyperLedger Fabric, Composer and PlayGround

After Deploying the chain-code(.bna file) on the HyperLedger Fabric, Composer PlayGround is used to access the data on the blockchain

BNA file is Business Network Archive

## Models
   Access Rules
   Transaction Rules
## Participants
   Government
   Individual
   Organizations
## Assets
  Lakshmi
  LakshmiType
## Transactions
  sendTransaction

When we make a transaction of money transfer by an individual to an organization, it matches the assetTypes of both the entities involved, if they match the transaction goes through, else it fails.

## Steps to Deploy
< 1. Open https://composer-playground.mybluemix.net/

2. Import Network Business Card, given in the repository with name networkadmin.card

3. Deploy a New Business Network, with bharat-chain.bna file

4. Start Playing!!
/>
