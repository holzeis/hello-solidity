# hello-solidity

A hello world dapp

## Configure environment

1. Create .env in the root directory
1. Set API_URL and PRIVATE_KEY like this

    ```
    API_URL = <e.g. your HTTP Alchemy API URL>
    PRIVATE_KEY = <e.g. your meta mask private key>
    ```

## Compile smart contract

```bash
npx hardhat compile
```

## Deploy smart contract to ropsten

```bash
npx hardhat run scripts/deploy.js --network ropsten
```
