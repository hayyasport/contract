# Hayya

Development for Hayya tokenomics

## Development

#### Setup

Make sure these tools are installed with the correct version

- `nodejs` LST `v16.13.0`
- `npm` `8.1.0`
- `solc` `0.8.4`

#### Build and Tests
Install dependencies
```console
cmd$> npm install
```

Run local network
```console
cmd$> npx hardhat node
```

Compile contracts
```console
cmd$> npx hardhat compile
```

Deploy contracts (default is local network `hardhat`)
```console
cmd$> npx hardhat run scripts/deploy.js --network <your-network>
```

-----------