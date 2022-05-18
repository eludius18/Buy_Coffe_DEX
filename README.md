# Buy me a Coffe DEX

## Install Dependencies

```shell
yarn install
```

## Create .env and add the info

```shell
GOERLI_URL=""
GOERLI_API_KEY=""
PRIVATE_KEY=""
```

## Install .env

```shell
yarn add dotenv
```

## Compile

```shell
npx hardhat compile
```

## Test

```shell
npx hardhat run scripts/buy-coffee.js
```

## Deploy on Goerli

```shell
px hardhat run --network goerli scripts/deploy.js
```

## Deployed contracts

https://goerli.etherscan.io/address/0xeB5aDe3F3d7a58C16E5979B96cff225a1395662e#code

## Frontend

https://buymeacoffee-solidity-defi-tipping-app.eladiorobles.repl.co/
