### Tx transaction link
```
https://explorer.solana.com/tx/5fHMhhnD4zFYW5j7UxkwYNs9T3Fpkts2YZiJkVzdPeWMtXTsbFAEddCLAuNovqTSY4Rp23umoavx3LcovcsaSa4z?cluster=devnet
```

### Final submission - how to run
```bash
yarn install
yarn enroll
```

### files overview

- `keygen.ts` - to generate new address run `yarn keygen`, result can be saved to `dev-wallet.json` to be re-used later
- `airdrop.ts` - to top a balance for address specified in this script (from running keygen.ts) - `yarn airdrop`
- `transfer.ts` - to transfer SOL from address specified in `dev-wallet.json` to new address, generated via prev script
- `enroll.ts` - add a transaction to dev blockchain with specific github id, to run `yarn enroll`