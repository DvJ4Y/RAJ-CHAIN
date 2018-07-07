# RAJ-CHAIN

# Problem
Under Bhamashah Scheme rajasthan government is providing financial benefits to  the targeted beneficiaries in a transparent manner but  When funds are allocated directly to the entity, there may be a possibility of the funds to be misused by the individual or other family member for other things, that doesn't serve the purpose of the allocated funds.

# Solution
"RAJCHAIN" is private blockchain demonstrating Direct Social Benefits provided by Rajasthan government under Bhamashan Scheme, made using HyperLedger Composer and HyperLedger Composer PlayGround.The Admin in our case the Government can issue cryptocurrency to any registered organization, individual. It can be used to add specific constraints on the asset issued, which allows it to be spent only when those constraint matches.Blockchain Technology helps in this problem by ensuring that the purpose of those funds are served, and when it happens it naturally resonates.

"RAJCHAIN" helps in all such instances where fraud, corruption and misuse of alloted funds take place. It helps in resisting corruption by self-managing ledger on the private blockchain ('Raj-Chain') that cannot be altered by the third party. Also, different government entities can allow an individual for allowance benefit. Thus, different entities can function independently and funds are allocated and spent as planned.Funds allocated with careful planning should reflect in the progress.

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
1. Open https://composer-playground.mybluemix.net/

2. Import Network Business Card

3. Deploy a New Business Network, with raj-chain.bna file

4. Start Playing!!

