### Prerequisites

- Have Docker installed

### Getting started

1. Go to user directory

2. Clone repo

```
// https
git clone https://github.com/programmer1718/ergo-node-docker-setup.git

// or

// ssh
git clone git@github.com:programmer1718/ergo-node-docker-setup.git
```

3. Rename repo folder to `ergo`

### For testnet
1. Go to testnet dir
2. Create `data` dir
3. Run `docker-compose up -d`

### For mainnet
1. Go to mainnet dir
2. Create `data` dir
3. Run `docker-compose up -d`

### Configuring the node and setting up a wallet

Refer to [this wiki](https://github.com/ergoplatform/ergo/wiki/Set-up-a-full-node#compute-the-hash-of-your-secret) for instructions on how to create an API key to interact with the node, and on how to setup a node wallet.