# ND1309 C2 Ethereum Smart Contracts, Tokens and Dapps - Project Starter 
**PROJECT: Decentralized Star Notary Service Project** 

### Rinkeby Details

- Token Name: Udacity Star Token
- Token Symbol: UST
- Token address: 0x980C4a0fB782b582DBB817AC36A784DF38707D4A (view it on EtherScan https://rinkeby.etherscan.io/address/0x980C4a0fB782b582DBB817AC36A784DF38707D4A)

### Dependencies
For this project, following versions have been used (see also package.json):
```
Truffle v5.4.24 (core: 5.4.24)
Solidity v0.5.16 (solc-js)
Node v10.16.0
Web3.js v1.5.3
openzeppelin-solidity v2.5.1
```

### How to run the application locally
1. Clean the frontend 
```bash
cd app
# Remove the node_modules  
# remove packages
rm -rf node_modules
# clean cache
npm cache clean
rm package-lock.json
# install all modules listed as dependencies in package.json
npm install
```


2. Start Truffle by running
```bash
# For starting the development console
truffle develop
# truffle console

# For compiling the contract, inside the development console, run:
compile

# For migrating the contract to the locally running Ethereum network, inside the development console
migrate --reset

# For running unit tests the contract, inside the development console, run:
test
```

3. Frontend - Once you are ready to start your frontend, run the following from the app folder:
```bash
cd app
npm run dev
```

---

### Important
When you will add a new Rinkeyby Test Network in your Metamask client, you will have to provide:

| Network Name | New RPC URL | Chain ID |
|---|---|---|
|Private Network 1|`http://127.0.0.1:9545/`|1337 |

The chain ID above can be fetched by:
```bash
cd app
node index.js
```