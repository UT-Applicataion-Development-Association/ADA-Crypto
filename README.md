# ADA-Crypto
## Overview
This project includes a lottery system using a self-made ERC20 token. Have fun!

## Contributing

```sh
# Clone the repo from github
git clone <URL>
```
### Front End
```sh
# Switch to front end folder
cd web

# Install web3 dependency if you do not have it in your computer
npm install web3

# Install dependencies
npm install

# Run the app
npm start

# Modify code...
```

### Back End
```sh
# Switch to the contract folder
cd contract
# Modify the code in contracts/Lottery.sol

# Change the provider variable into your own seed phrase and end point in deploy.js
node deploy.js

# Copy the returned ABI and contract address to web/src/lottery.js
```

### Commit
```sh
git add .
git commit -m 'message'
```