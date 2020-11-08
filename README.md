## PoC of OpenSea Cloud Sale for Bazaaar project

### Deployment

export following env values
```
export INFURA_KEY=""
export MNEMONIC=""
```

Deploy Contract to rinkeby testnet.
```
DEPLOY_CREATURES_SALE=1 yarn truffle deploy --network rinkeby --reset
```

Deployed contract address will be used in next process.

### Start Sale

export following env values
```
export OWNER_ADDRESS="0xf410F9F3fC9ed3378D6119BBa3F4102159dE16CB"
export NFT_CONTRACT_ADDRESS="0x1f0080683721b6111F40BD8e2536125Cee889876"
export FACTORY_CONTRACT_ADDRESS="0x9f7F06c71b95dd241C13132C947C13d13a71c40a"
export NETWORK="rinkeby"
```

Specify token id to sale
```
export TOKEN_ID=1
```