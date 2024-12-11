Hello, this is a token swap application on the Core blockchain

1- create a file: secret.json (and paste the line below)
{‘PrivateKey’: ‘your private key, do not leak this file, do keep it absolutely safe’}

2- navigate to the directory: cd \Backend
3- install the hardhat modules: npm install --save-dev hardhat
4- compile the smart contracts (Swap.sol and Token.sol) : npx hardhat compile

5- Deploy the smart contracts (Swap.sol and Token.sol): npx hardhat run .\scripts\deploy.js
the result will look like the line below:
Deploying contracts with the account: 0x5720ec329B00EAd34D2FBAf97c852231222efb0A
Contracts deployed:
Swap Contract: 0xb35580F3F76d50D8DfF385017bd5Da6336E56C85
usdt Token: 0x2061c8427c1B3cCF1fdf5F12B0EBbDE782EeD2dB
usdc Token: 0x65216B13a69AC7b5D8e6477906EfcE33e59C2BD7

6- navigate to the Frontend directory: cd Frontend
7- install the modules (e.g. node.js) by typing: npm install
8- test the application locally with the command: npm run start
