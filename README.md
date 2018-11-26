# Basic Command of Truffle
#### Compile:              truffle compile
#### Migrate:              truffle migrate
#### Test contracts:       truffle test
#### Test dapp:            cd client && npm test
#### Run dev server:       cd client && npm run start
#### Build for production: cd client && npm run build

# how to run
1. metamask account reset (confer trouble shooting)
1. ganache-cli -m "mnemonics you saved before"
2. /app root/truffle compile
3. /app root/truffle migrate
4. cd client
5. npm install
6. npm run start

# Trouble Shooting
1. MetaMask - RPC Error: Internal JSON-RPC error. {code: -32603, message: "Internal JSON-RPC error."}
    1. Change MetaMask networks to some testnet
    2. Change back to "Localhost 8545"
    3. Go to MetaMask "Custom RPC", and press "Reset Account"
    4. this is metamask bug
    5. error remains, but this works.