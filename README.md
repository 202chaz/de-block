# Block Exchange


##### 1. Docker Desktop
1. Download Docker Desktop from the following [link](https://desktop.docker.com/mac/stable/Docker.dmg) (Mac)
2. Follow installation instructions to setup Docker Desktop

#### 2. Truffle (Smart Contracts) commands
  [Truffle](https://trufflesuite.com)

  A world class development environment, testing framework and asset pipeline for blockchains using the Ethereum Virtual Machine (EVM), aiming to make life as a developer easier.

##### Create a bare Truffle project with no smart contracts included
```docker-compose run smart-contracts truffle init```
##### Create a Truffle project and use the MetaCoin box, which creates a token that can be transferred between accounts
```docker-compose run smart-contracts truffle unbox metacoin```

##### Compile and migrate the smart contracts
```docker-compose run smart-contracts truffle complile```
```docker-compose run smart-contracts truffle migrate```

#### 4. Ganache (ONE CLICK BLOCKCHAIN)
  [Ganache](https://trufflesuite.com/ganache/)

  Quickly fire up a personal Ethereum blockchain which you can use to run tests, execute commands, and inspect state while controlling how the chain operates.

#### 5. IPFS (Interplanetary File System)
  [IPFS](https://ipfs.io/)

  IPFS, or the InterPlanetary File System, is a peer-to-peer (P2P) networking protocol used to share data on the distributed web. As its full name suggests, you can think of IPFS as a file system, and it has some unique characteristics that make it ideal for safe, decentralized sharing.

#### 3. Prod build command
```docker-compose -f docker-compose.prod.yml build```
```docker-compose -f docker-compose.prod.yml up```


