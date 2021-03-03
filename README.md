# hardhat-tutorial

## Quick start - Creating a new Hardhat project 

npm init --yes 
npm install --save-dev hardhat 
npx hardhat

## ehters.js + waffle :

npm install --save-dev @nomiclabs/hardhat-ethers ethers @nomiclabs/hardhat-waffle ethereum-waffle chai

## Compile : 

npx hardhat compile

## Test : 

npx hardhat test

## Deploy live : 

npx hardhat run scripts/deploy.js --network <network-name>