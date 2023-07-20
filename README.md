# Token Contract Project

Try running some of the following tasks:

Create a ENV file with =>
API_URL = "https://sepolia.infura.io/v3/{YOUR INFURA ID}"
PRIVATE_KEY={YOURS PRIVATE KEY}
ETHERSCANKEY={YOURS ETHERECAN ID}

```shell
npm install
npx hardhat compile
npx hardhat run scripts/deploy.js --network sepolia
npx hardhat verify --network sepolia {Deployed address} {constructor arguments}
```
DEployed address => 0x29d0e44De63b1AE367B10f80188c02A4657048B6
Verify and published => https://sepolia.etherscan.io/address/0x29d0e44De63b1AE367B10f80188c02A4657048B6#readContract
