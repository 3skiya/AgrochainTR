# Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain
## Problem statement:
- In the recent past, we have read many incidents regarding farmer suicides due to debts and poor yield from farming. For a country like India, with the rise in - - population, dependency over the land for building houses and industrial areas is increasing rapidly. The fertile land for farming is dwindling and more yields have to be produced to satisfy the needs of the country. 

- Even though the demand increases, the farmers are suffering from some major issues like **raising initial investments, fetching reasonable prices, analysing market trends,disputes with middlemen and finally issues in transportation and storage.**

## Objective:

- The main aim/objective behind choosing such a project is because the agricultural industry is one of the industries which faces a lot of criticism and too many Farmer deaths are reported every day. According to the latest National Crime Records Bureau (NCRB) data on accidental deaths and suicides, **10,281 farmers** committed suicide in 2019. The main reasons for these suicides being unable to pay hefty interest rates on loans. **Now what if we directly establish a link between the product consumers and the Farmers, this is what is the focus of our project i.e to help farmers raise the amount required for their cultivation using the concept of crowd funding from the consumers.**

- One more important objective the project focuses on is that of eradicating a broker or a middleman which not only reduces the final product MRP, but also helps to reduce the adulteration and other intermediary offences. Here only the customers and farmers are there to monitor the entire process in a blockchain, this creates an even more transparent and trustful environment.

## Introduction:

- **Agrosahakar** is a blockchain based transparent marketplace where the farmers and consumers could implement a co-operative farming method. Here, the farmers can list the potential crops and the expected yield on his farm on the distributed public ledger. The consumers can view the details and check for the farmer's credibility based on the previous cultivation and supply. 

- This creates a transparent and tamper-proof digital market platform for farm products. Thus an agreement (consensus) can be formed between farmer and consumer, such that the consumer can fund individual crops or a field and can acquire the yield from the farm or the profit percentage of its market value. There will be a rating mechanism to build the credibility of farmer and consumer based on the previous experiences in the agromarket.

## Methodology:

![Flowchart](https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/screenshots/AgriChain.jpg)

## These are the features or methodologies implemented for the project:
### 1. Registration form for Farmers:
- The details we ask while registration are:Farmer id, Farmer name, location, Crop name, phone number, quantity and expected price.
- The entered details are directly stored onto the blockchain.
<p align="center"> <img src="https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/screenshots/b1.png" width="700" height="400"> </p>
 
### 2. Quality testing: 
- Here we get the farmers details mentioned above by entering the Farmer id.
- Once the quality testing is done the block number is assigned and approved details will provide the details of the farmer.
- Approved details button will redirect to the product details page where we enter the lot number, grade, price, test date, expiry date and store these details into the ledger as a set of transaction details.
<p align="center"> <img src="https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/screenshots/b2.png" width="700" height="400"> </p>

### 3. Customer: 
- In this page the customer has to enter the Farmer id and lot number to see the status of quality testing of his agricultural produce.
<p align="center"> <img src="https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/screenshots/b3.png" width="700" height="400"> </p>

### 4. Micro-finance: 
- This form enables any user to fund the farmer.
- The funding is done by providing the farmer’s public id, lot number of the product and the amount.
<p align="center"> <img src="https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/screenshots/b4.png" width="700" height="400"> </p>

## Technology stacks used :

  <img src="https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/Techstack/geth.png" width="100" height="100">  &nbsp; <img src="https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/Techstack/lb.png" width="200" height="100"> &nbsp; <img src="https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/Techstack/nodejs.png" width="100" height="100"> &nbsp; <img src="https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/Techstack/solidity.png" width="100" height="100"> &nbsp; <img src="https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/Techstack/web3js.png" width="100" height="100"> &nbsp; <img src="https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/Techstack/wtg.png" width="300" height="100">

## Smart contract and business logic :

- The smart contract is basically a script or many lines of code deployed in our blockchain to bring the business logic into consideration.
- The main components of the smart contract are that of the different entities that we had used in the Agromarket. These entities are that of the lot(The lot is    assigned by the tester for testing the specific commodity), StructStorage(is used to map the various addresses to the respective balances of the customers. 
- Initially we assume that the customer has around 2000 $ as the balance in his account). Another main entity used are that of Farmers entity to store the Farmer ID, name, location he is residing in, crop he is going to grow, his contact address, quantity and the expected price that he would like to raise. This idea was inspired from the concept of crowdfunding.
- The various functions such as the sendcoin, produce, getproduce, quality and getquality are also used so that the proper details are extracted and displayed to the farmers as and when the need arises. An important point to be noted is that of why we used the memory variable for farmer id. It was done because the farmer id is used as a mapping to extract the farmer details.
- **Links to screenshots:**
    - [scr1](https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/screenshots/b5.png)
    - [scr2](https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/screenshots/b6.png)

## Steps to use this repo:

 1. Start ganache! Should work with ganache or geth!

 2. Go to AgroChain Directory and do 'npm install'
       update the node_modules folder when you run locally(npm install)

 3. truffle migrate

 4. Important Note:

     - In  src directory --> app.js

     - Line number 43820 --->

     - change the variable conaddress = "0x733fa0cfc10adee89e2e426b133f7b40706d5ea3"; 

     - The above value of contract address should be changed to the result you get when you do truffle migrate.

     - When you do truffle migrate you get a contract address !!!
      Put that value to conaddress!!!


 5. 'npm run dev' to start lite-server

 6. Goto localhost:3000

**Eureka!**

## Project Video Demonstration:
[![Watch the demo](https://github.com/kuluruvineeth/Agrochain-A-Blockchain-Based-Agricultural-Supply-Chain/blob/main/screenshots/b1.png)](https://drive.google.com/file/d/1d8BpBcgeXOoPOJm9A57ZgmjCnCsiA9Q1/view?resourcekeyct+https://drive.google.com/file/d/1d8BpBcgeXOoPOJm9A57ZgmjCnCsiA9Q1/view?resourcekeydemo)





