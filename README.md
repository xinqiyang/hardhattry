# hardhattry
https://hardhat.org/getting-started/



https://vittominacori.github.io/solidity-starter-kit/#usage-using-truffle


# Command

```bash
npm init 
npm install --save-dev hardhat

npx hardhat

npx hardhat accounts
npx hardhat compile
npx hardhat test
npx hardhat run scripts/sample-script.js

# select other networks 
npx hardhat run scripts/sample-script.js --network localhost

npx hardhat node


npm install --save-dev mocha


npm i -g hardhat-shorthand


```

## DEPLOY
https://hardhat.org/guides/deploying.html

```bash

npx hardhat flatten --remove-licenses
npx hardhat flatten --license MIT
# flatten to a file 
npx hardhat flatten contracts/Greeter.sol > flatten/Greeter.sol

npx hardhat node
npx hardhat run --network localhost scripts/deploy.js
npx hardhat run --network <your-network> scripts/deploy.js

```
