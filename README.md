# 20200401supplychain
# Building Blockchain apps with JavaScript part 2 

# URL to this repo: https://bit.ly/2QbPB5m
 
 <img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

#### Lennart Frantzell, IBM Devloper Advocate San Francisco alf@us.ibm.com

#### David Nugent, IBM Developer Advocate, San Francisco

#### Taiji Hagino, Senior IBM Developer Advocate, Tokyo

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

# Blockchain sources

## Satoshi Nakamoto's paper: Bitcoin: A Peer-to-Peer Electronic Cash System https://bitcoin.org/bitcoin.pdf from 2008.

## https://nakamotoinstitute.org/static/docs/bitcoin-jp.pdf

## Hyperledger Fabric – from The Linux Foundation – is the open source modular blockchain framework that has become the de facto standard for enterprise blockchain platforms. 

### FYI: [Hyperledger Fabric documentation](https://hyperledger-fabric.readthedocs.io/en/release-2.0/)

### FYI: [Hyperledger Fabric code](https://www.hyperledger.org/projects/fabric)

### Hyperledger Projects: https://www.hyperledger.org/projects

<p>
 <img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">
 

# Introduction to the Blockchain

<img src="/img/BlockChain1.png">

The Blockchain is a shared, replicated ledger 台帳 with consensus, provenance, <br>
immutability and finality and maintained by each peer in a business network.
<p>
 A blockchain network is comprised primarily of a set of peer nodes (or, simply, peers). Peers are a fundamental element of the network because they host ledgers and smart contracts.
<p>
 
Peers nodes leverage the gossip protocol to broadcast ledger and channel data in a scalable fashion. Gossip messaging is continuous, and each peer on a channel is constantly receiving current and consistent ledger data from multiple peers 
 
 <img src="/img/peers.png">
 
<p>
Transaction are permanently stored in the Blockchain and also stored in the World state that contains the current value of all objects.
 
## Transaction <br>
Txn = buy<br>
Issuer = MagnetoCorp<br>
Paper = 00001<br>
Current owner = MagnetoCorp<br>
New owner = DigiBank<br>
Purchase time = 31 May 2020 10:00:00 EST<br>
Price = 4.94M USD<br>
<p>

## like stored procedures in the database world


<a href="https://www.hyperledger.org/blog/2018/10/26/hyperledger-fabric-now-supports-ethereum">EVM integration: Hyperledger Fabric Now Supports Ethereum</a>

<p>

<img src="/img/Blockchain.png">
<p>
<img src="/img/Ledger.png">
<p>

## Blockchain concepts

### On-Chain and Off-Chain

Blockchain is not meant for large datasets. Instead it is better to use traditional data bases for large datasets and then create a hash of the large datasets that is stored on the Blockchain. And that allows the large datasets to be accessed through the hash. 

### Public, private

### Permissioned, permission-less

### Oracles

### Tokens and incentive mechanisms

### Identity and Zero Knowledge

### Consensus mechanisms

## Smart Contracts to program the Internet 

<img src="/img/SmartContract2.png">

## Food industry and Blockchain

<table style="width:100%">
  <tr>
    <th colspan="2"></th>
  </tr>
  <tr>
    <td><img src="/img/FoodIndustry1.png"></td>
    <td><img src="/img/FoodIndustry2.png"></td>   
  </tr>
</table>

# Some Supply Chain Apps written in Blockchain

<img src="/img/Food.Trust1.png">

https://github.com/LennartFr/20200401supplychain

## TradeLens

<img src="/img/TradeLens5.png">

<a href="tradelens.com">TradeLens</a>

https://github.com/LennartFr/20200401supplychain/blob/master/TradeLens.md

<img src="/img/Bean2.png">

## FYI: <a href="https://www.ibm.com/thought-leadership/blockchainbean/">Blockchain Bean</a>

## FYI: <a href="https://www.ibm.com/blockchain/industries/supply-chain">IBM Blockchain for Supply Chain </a>

## IBM Blockchain World Wire and blockchainm performance

https://www.ibm.com/blogs/blockchain/2019/04/does-hyperledger-fabric-perform-at-scale/ 
 
<img src="/img/IBM.World.Wire.png"> 

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

# Blockchain in the news

<img src="/img/Mipasa.png">

<img src="/img/IBP.GS.png">

<img src="/img/Supplychain.png">

https://youtu.be/mMHmxoNrWKo

<img src="/img/BC.2.1.3.png">

## FYI: <A HREF="https://developer.ibm.com/technologies/blockchain/patterns/run-smart-contract-on-blockchain-network-with-raft-ordering-service/">Run a smart contract on a blockchain network with the Raft ordering service</a>

## FYI: <a href="https://hyperledger-fabric.readthedocs.io/en/release-1.4/orderer/ordering_service.html">The Ordering Service</a>

## Orderers and the transaction flow
### Kafka (deprecated in v2.0)
### Raft (recommended)
### New as of v1.4.1, Raft is a crash fault tolerant (CFT) ordering service based on 
### an implementation of Raft protocol in etcd

https://hyperledger-fabric.readthedocs.io/en/release-2.0/orderer/ordering_service.html


<img src="/img/Honeywell.png">

<img src="/img/Oracle.png">

<img src="/img/Amsterdam.png">                            

<img src="/img/Credentials.png">

<img src="/img/bmw.png">

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

## We'll start here: [Sign up to a free IBM Cloud Account](https://ibm.biz/BdqXCj)

<img src="/img/Signup.png">            


## In addition to the Open Source Hyperledger Fabric there is the cloud-based IBM Blockchain Platform:

<img src="/img/BP1.png">
<p>
<img src="/img/BP2.png">

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

## IBM Blockchain Platform Console. https://www.ibm.com/cloud/blockchain-platform/pricing

### https://cloud.ibm.com/docs/services/blockchain?topic=blockchain-ibp-saas-pricing#ibp-saas-pricing-free-howto

<img src="/img/BCConsole1.png">

### FYI: [IBM Blockchain Platform Component Overview](https://cloud.ibm.com/docs/services/blockchain?topic=blockchain-blockchain-component-overview)

### FYI: [Getting started with the IBM Blockchain Platform](https://cloud.ibm.com/docs/services/blockchain?topic=blockchain-get-started-ibp)

### FYI: <a href="https://cloud.ibm.com/docs/services/blockchain?topic=blockchain-ibp-v2-faq#ibp-v2-faq-vscode-tutorials">IBM Blockchain Platform FAQs</a>

### FYI: [Blockchain Garage can help you get started with Blockchain](https://www.ibm.com/blockchain/garage)

### FYI: Blockchain Code Patterns https://developer.ibm.com/technologies/blockchain/patterns/

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

# Developing Supply Chain Apps, prerequisites and downloads

 1. [Check Pre-requisites 2.0](https://hyperledger-fabric.readthedocs.io/en/release-2.0/prereqs.html)
 2. Download Visual Studio Code: https://code.visualstudio.com/updates/v1_39. Sept 2019 version 1.39.x Be sure to change Setttings/Update:Mode to manual  
 3. Download the IBM Blockchain Platform Extension for VS Code: https://bit.ly/2RS2R02 
 4. Trouble-shoot installation: https://github.com/IBMDeveloperNYC/coffee-supply-chain-blockchain/blob/master/TROUBLE-SHOOTING.md 
 
 # Create your first Blockchain MVP
 
# Event URL: <a href="http://ibm.biz/OlgaBlockChain">http://ibm.biz/OlgaBlockChain</a>

# Contact:  Linkedin.com/in/lennartfrantzell/
 
[Whitelisting](https://cloud.ibm.com/registration/whitelist) 

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

# Blockchain development methodology

# Step 1: Start with: <a href="https://www.ibm.com/blockchain/use-cases/">Blockchain Use Cases</a>
      
# Step 2: Existing architecture, systems, domain knowledge and data, regulations
  
  ## 2.2: Move selected Off-chain data On-Chain
  
# Step 3: Smart Contracts
  
# Step 4: dev team
  ### 1 Architect
  ### 1 domain expert, marketing expert
  ### 1 operator
  ### 2 devs

### Step 5: Blockchain Architecture

   ### Orderer (Solo, Kafka Raft, SBFT)
   ### MSP, Peers, Channel, World State, Ledger
  
  

# Hands-on Blockchain

Follow tutorials

### Tutorial 1 Local Smart Contract Development

<img src="/img/VSCode.png">

Follow the typical workflow from generating a new default smart contract project, deploying code to the Local Fabric environment, and testing out your transactions via an application gateway.

### Tutorial 2

Create a cloud blockchain deployment

After developing a smart contract against the local runtime, you'll need somewhere more permanent to deploy for further dev, proof of concept, or production use. IBM Blockchain Platform includes an offering on IBM Cloud for creating and operating a suitable runtime environment for such purposes. Its full name is "IBM Blockchain Platform on IBM Cloud", but for the sake of brevity we'll refer to it from here on out as "the cloud service". In this tutorial you will learn how to get a cloud environment set up using the cloud service.

### Tutorial 3

Deploying and transacting with IBM Cloud

Important: You will need a smart contract package and a suitable cloud environment to follow this tutorial. Follow parts 1 and 2 of this series first for instructions.


<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">
     
# Appendix

### 1.1 <a href="https://github.com/IBMDeveloperNYC/coffee-supply-chain-blockchain"> Installing Visual Studio Code </a>

### 1.2 <a href="https://cloud.ibm.com/docs/services/blockchain/howto?topic=blockchain-develop-vscode">Developing smart contracts with Visual Studio Code extension </a>

### 1.3 IBM Blockchain 101: https://ibm.co/36U1QZM
 
### 1.4 Blockchain code patterns: https://ibm.co/2GROsL0
  
### 1.5 https://github.com/Grant-Steinfeld/coffee-supply-chain-blockchain

### 1.6 Youtube Video: <a href="https://youtu.be/5b7awLi93-E">Create a simple Coffee Bean Supply Chain Blockchain on Hyperledger Fabric</a>

### 1.7 <a href="https://developer.ibm.com/patterns/coffee-supply-chain-network-hyperledger-fabric-blockchain-2/">Create a fair trade supply chain network Use Hyperledger Fabric and IBM Blockchain Platform to increase efficiency in the supply chain of a coffee retailer</a>
