# Launchpad
Launchpad is a no-code solution for algorithmic artwork generation, smart contract deployment and distribution of NFTs. 

##### Live Website: https://goofy-neumann-fd67a4.netlify.app/

### Problems faced by artists / Inspiration
#### 1. Lack of technical knowledge
- Artists have ready-designed artworks and wish to enter the NFT scene, however, existing marketplaces do not support mass uploading
- Lack technical expertise to customize and deploy their own smart contract
- As such, they miss out on opportunity to monetize and promote their creations
#### 2. Cost & risk associated with outsourcing
- Creators may not have the resources to hire dedicated developers to work on their project
- Not every developers are good actors (counterparty risk), outsourcing work fundamentally relies on trust
#### 3. Time consuming & inefficient process
- Hello world

## Video Demo 


## Core Functionality
#### 1. Artwork Generation
- Import layers of images
- Configure rarity of each images and merge them
- Generate merged images and metadata 

#### 2. Collection Dispenser
- Deploy custom IRC-31 contract
- Upload images and metadata to IPFS via Pinata Cloud
- Generate minting dApp and configure launch time / minting whitelist

## Solution Architecture


## Local Deployment
#### Pre-requisites
1. ICONex Wallet (https://chrome.google.com/webstore/detail/iconex/flpiciilemghbmfalicajoolhkkenfel?hl=en)
2. NodeJS

#### Test Guide
1. Clone and unzip repository to a folder
2. Open CLI and ```cd``` to package directory
3. Run ```npm install``` to install dependencies 
4. Run ```npm start``` to start local server

## Limitations
- Artwork generation only supports static images
- Unable to link multiple collections under one parent contract
- 

## Roadmap
- Migrating to Java SCORE
- Integration with Craft Marketplace for secondary sales
- Supporting different types of NFTs (e.g., Music, Event Tickets, In-game assets)

## Resources
##### Medium - (https://medium.com/@justin.mok.2020/launchpad-the-go-to-nft-minting-solution-e5b0b686ad02)

##### Slides - (https://docs.google.com/presentation/d/1is7rN8gtYgGrecR8nc653bLBN8FT0caA5buM4SZBkRE/edit#slide=id.p1)

##### Testnet Faucet - (https://faucet.ibriz.ai/)


## Team
Hey there! We're a group of students from Singapore Management University!

BY - bytan.2021@scis.smu.edu.sg

JR - jinrui.seah.2021@economics.smu.edu.sg

Justin - justin.mok.2020@business.smu.edu.sg

Yong Jiun - yjlew.2020@scis.smu.edu.

Sebastian - cpong.2021@scis.smu.edu.sg
