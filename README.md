# Decentralized Voting Application



## Installation

After you cloned the repository, you want to install the packages using

```shell
npm install
```

You first need to compile the contract and upload it to the blockchain network. Run the following commands to compile and upload the contract.

```shell
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js
```

Once the contract is uploaded to the blockchain, copy the contract address and copy it in the .env file. You can also use another blockchain by writing the blockchain's endpoint in hardhat-config.

Once you have pasted your private key and contract address in the .env file, simply run command

```shell
npm start
```

 ## This Dapp is using Volta test network 
 To add this network in meta mask simply go to add new network  

 Network name = volta ,

 RPC URL = [RPC URL](https://73799.rpc.thirdweb.com) ,

 Chain ID =  73799 ,

 Currency symbol = VT , 

And save 

To get volta test tokans for voting go to [voltafaucet](https://voltafaucet.energyweb.org/) and paste the wallet id and recive the tokans 
