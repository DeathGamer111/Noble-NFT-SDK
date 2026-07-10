# Noble NFT SDK

TypeScript SDK for building peer-to-peer token and NFT swap experiences on EVM-compatible networks. It is based on the Trader.xyz NFT Swap SDK and is retained here as the Noble marketplace integration reference.

## Install and develop

```bash
yarn install
yarn build
yarn test
```

Use `yarn lint` and `yarn typecheck` to validate changes. The `src/` directory contains the SDK implementation, while `test/` includes its test coverage and `example*.ts` provides integration examples.

## Compatibility

Verify protocol, dependency, and target-network compatibility before integrating the SDK into a production application. Configure network-specific behavior in the consuming application rather than hard-coding environment values here.

